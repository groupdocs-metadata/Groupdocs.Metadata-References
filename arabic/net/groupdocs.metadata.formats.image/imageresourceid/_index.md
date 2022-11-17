---
title: ImageResourceID
second_title: GroupDocs.Metadata لمرجع .NET API
description: أرقام التعريف القياسية لموارد الصور. لا تستخدم جميع تنسيقات الملفات جميع المعرفات. قد يتم تخزين بعض المعلومات في أقسام أخرى من الملف.
type: docs
weight: 1750
url: /ar/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

أرقام التعريف القياسية لموارد الصور. لا تستخدم جميع تنسيقات الملفات جميع المعرفات. قد يتم تخزين بعض المعلومات في أقسام أخرى من الملف.

```csharp
public enum ImageResourceID
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| ResolutionInfo | `1005` | هيكل ResolutionInfo. راجع الملحق أ في وثيقة دليل Photoshop API بتنسيق PDF . |
| NamesOfAlphaChannels | `1006` | أسماء قنوات ألفا كسلسلة من سلاسل باسكال. |
| Caption | `1008` | التسمية التوضيحية كسلسلة باسكال. |
| BorderInformation | `1009` | معلومات الحدود. يحتوي على رقم ثابت (2 بايت حقيقي ، 2 بايت كسر) لعرض الحدود ، و 2 بايت لوحدات الحدود (1 = بوصة ، 2 = سم ، 3 = نقاط ، 4 = بيكا ، 5 = أعمدة) . |
| BackgroundColor | `1010` | لون الخلفية. [شاهد المزيد.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | طباعة الأعلام. سلسلة من القيم المنطقية أحادية البايت (انظر مربع حوار إعداد الصفحة): تسميات ، وعلامات اقتصاص ، وأشرطة ملونة ، وعلامات تسجيل ، وسالب ، وقلب ، وإقحام ، وتسمية توضيحية ، وأعلام الطباعة. |
| Grayscale | `1012` | معلومات الألوان النصفية بتدرج الرمادي ومتعدد القنوات. |
| ColorHalftoning | `1013` | معلومات الألوان النصفية . |
| DuotoneHalftoning | `1014` | معلومات الدرجات اللونية النصفية. |
| GrayscaleFunction | `1015` | وظيفة النقل بتدرج الرمادي ومتعدد القنوات. |
| ColorTransferFunctions | `1016` | وظائف نقل اللون. |
| DuotoneTransferFunctions | `1017` | وظائف نقل Duotone . |
| DuotoneImageInformation | `1018` | معلومات الصورة المزدوجة . |
| EPSOptions | `1021` | خيارات EPS . |
| QuickMaskInformation | `1022` | معلومات القناع السريع. 2 بايت تحتوي على معرّف قناة Quick Mask ؛ 1- بايت منطقي يشير إلى ما إذا كان القناع فارغًا في البداية. |
| LayerStateInformation | `1024` | معلومات حالة الطبقة. 2 بايت تحتوي على فهرس الطبقة المستهدفة (0 = الطبقة السفلية) . |
| WorkingPath | `1025` | مسار العمل (غير محفوظ). راجع تنسيق مورد المسار. |
| LayersGroupInformation | `1026` | معلومات مجموعة الطبقات. 2 بايت لكل طبقة تحتوي على معرف مجموعة لمجموعات السحب. الطبقات في المجموعة لها نفس معرف المجموعة. |
| Iptc | `1028` | سجل IPTC-NAA. يحتوي على معلومات الملف ... المعلومات. راجع الوثائق في مجلد IPTC لمجلد الوثائق. |
| ImageModeForRawFormat | `1029` | وضع الصورة لملفات التنسيق الخام. |
| JpegQuality | `1030` | جودة JPEG. خاص . |
| GridAndGuidesInfoPhotoshop4 | `1032` | معلومات الشبكة والأدلة . |
| ThumbnailResourcePhotoshop4 | `1033` | مورد الصور المصغرة لبرنامج Photoshop 4.0 فقط. |
| CopyrightFlagPhotoshop4 | `1034` | علامة حقوق النشر. قيمة منطقية تشير إلى ما إذا كانت الصورة محمية بحقوق الطبع والنشر. يمكن تعيينها عبر مجموعة الخصائص أو بواسطة المستخدم في File Info ... |
| UrlPhotoshop4 | `1035` | URL. التعامل مع سلسلة نصية مع محدد موقع الموارد المنتظم. يمكن تعيينها عبر مجموعة الخصائص أو بواسطة المستخدم في File Info ... |
| ThumbnailResourcePhotoshop5 | `1036` | مورد الصورة المصغرة (يحل محل المورد 1033). راجع تنسيق مورد الصورة المصغرة. |
| GlobalAnglePhotoshop5 | `1037` | زاوية عالمية. 4 بايت تحتوي على عدد صحيح بين 0 و 359 ، وهي زاوية الإضاءة العامة لطبقة التأثيرات. إذا لم يكن موجودًا ، يفترض أنه 30 . |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ملف تعريف ICC. وحدات البايت الأولية لملف تعريف تنسيق ICC (اتحاد الألوان الدولي). راجع ICC1v42_2006-05.pdf في مجلد الوثائق و icProfileHeader.h في نموذج التعليمات البرمجية \ Common \ Includes. |
| WatermarkPhotoshop5 | `1040` | علامة مائية. بايت واحد. |
| IccUntaggedProfilePhotoshop5 | `1041` | ملف تعريف ICC غير مميز. 1 بايت الذي يعطل أي معالجة ملف تعريف مفترض عند فتح الملف. 1 = بدون علامة عن قصد . |
| TransparencyIndexPhotoshop6 | `1047` | مؤشر الشفافية. 2 بايت لمؤشر اللون الشفاف ، إن وجد. |
| GlobalAltitudePhotoshop6 | `1049` | الارتفاع العالمي. إدخال 4 بايت للارتفاع . |
| SlicesPhotoshop6 | `1050` | شرائح (فوتوشوب 6) . |
| WorkflowUrlPhotoshop6 | `1051` | عنوان URL لسير العمل. سلسلة Unicode. فوتوشوب 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | معرفات ألفا. 4 بايت من الطول ، متبوعًا بـ 4 بايت لكل معرف ألفا. |
| UrlListPhotoshop6 | `1054` | قائمة URL الداخلية. عدد 4 بايت لعناوين URL ، متبوعًا بـ 4 بايت طويل ، ومعرف 4 بايت ، وسلسلة Unicode لكل عدد. |
| VersionInfoPhotoshop6 | `1057` | معلومات الإصدار. إصدار 4 بايت ، 1 بايت hasRealMergedData ، سلسلة Unicode: اسم الكاتب ، سلسلة Unicode: اسم القارئ ، إصدار ملف 4 بايت. |
| ExifData1Photoshop7 | `1058` | بيانات EXIF 1 ،[شاهد المزيد](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ بيانات EXIF 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | بيانات تعريف XMP. معلومات الملف كوصف XML ،[شاهد المزيد](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | ملخص التسمية التوضيحية. 16 بايت: أمان بيانات RSA ، خوارزمية ملخص الرسالة MD5. |
| PrintScalePhotoshop7 | `1062` | مقياس الطباعة. نمط 2 بايت (0 = توسيط ، 1 = حجم مناسب ، 2 = محدد من قِبل المستخدم). 4 بايت × الموقع (النقطة العائمة). موقع y 4 بايت (النقطة العائمة). مقياس 4 بايت (النقطة العائمة). |
| PixelAspectRatio | `1064` | نسبة العرض إلى الارتفاع بالبكسل. 4 بايت (الإصدار = 1 أو 2) ، 8 بايت مزدوج ، x / y من البكسل. الإصدار 2 ، يحاول تصحيح قيم NTSC و PAL ، التي كانت متوقفة مسبقًا عن عامل تقريبًا. 5٪ . |
| LayerComps | `1065` | تركيبات طبقة. 4 بايت (إصدار الواصف = 16) ، الواصف . |
| LayerSelectionIds | `1069` | معرف (معرفات) تحديد الطبقة. عدد 2 بايت ، يتم تكرار ما يلي لكل عدد: معرف طبقة 4 بايت. |
| PrintInfoCS2 | `1071` | معلومات الطباعة (Photoshop CS2) . |
| LayerGroupEnabledIdCS2 | `1072` | معرف تمكين مجموعة (مجموعات) الطبقة. 1 بايت لكل طبقة في المستند ، مكررًا بطول المورد. ملاحظة: مجموعات الطبقات لها علامات بداية ونهاية (Photoshop CS2) . |
| ColorSamplersResourceCS3 | `1073` | مورد عينات الألوان. راجع أيضًا المعرف 1038 للتنسيق القديم. |
| MeasurementScaleCS3 | `1074` | مقياس القياس. 4 بايت (إصدار الواصف = 16) ، الواصف . |
| TimelineInformationCS3 | `1075` | معلومات الخط الزمني. 4 بايت (إصدار الواصف = 16) ، الواصف . |
| SheetDisclosureCS3 | `1076` | كشف الورقة. 4 بايت (إصدار الواصف = 16) ، الواصف . |
| PrintInformationCS5 | `1082` | معلومات الطباعة (Photoshop CS5) . |
| PrintStyleCS5 | `1083` | نمط الطباعة (Photoshop CS5) . |
| MacintoshNSPrintInfoCS5 | `1084` | ماكنتوش NSPrintInfo. معلومات خاصة بنظام التشغيل المتغير لنظام التشغيل Macintosh. NSPrintInfo. يوصى بعدم تفسير هذه البيانات أو استخدامها. (فوتوشوب CS5) . |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. معلومات خاصة بنظام التشغيل المتغير لنظام التشغيل Windows. DEVMODE. يوصى بعدم تفسير هذه البيانات أو استخدامها. (فوتوشوب CS5) . |
| AutoSaveFilePathCS6 | `1086` | مسار ملف الحفظ التلقائي. سلسلة Unicode. (فوتوشوب CS6) . |
| AutoSaveFormatCS6 | `1087` | تنسيق الحفظ التلقائي. سلسلة Unicode. (فوتوشوب CS6) . |
| PathSelectionStateCC | `1088` | حالة تحديد المسار. (فوتوشوب CC) . |
| ImageReadyVariables | `7000` | متغيرات الصورة الجاهزة. تمثيل XML لتعريف المتغيرات. |
| ImageReadyDatasets | `7001` | مجموعات البيانات الجاهزة للصور . |
| PrintFlagsInformation | `10000` | طباعة معلومات الأعلام. إصدار 2 بايت (= 1) ، علامات اقتصاص مركز 1 بايت ، 1 بايت (= 0) ، قيمة عرض تسييل 4 بايت ، مقياس عرض تجاوز 2 بايت. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
