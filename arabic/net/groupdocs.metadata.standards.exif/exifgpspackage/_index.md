---
title: ExifGpsPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل البيانات الوصفية لنظام تحديد المواقع العالمي GPS في حزمة بيانات تعريف EXIF .
type: docs
weight: 2770
url: /ar/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

يمثل البيانات الوصفية لنظام تحديد المواقع العالمي (GPS) في حزمة بيانات تعريف EXIF .

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | يقوم بتهيئة مثيل جديد لملف[`ExifGpsPackage`](../exifgpspackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | الحصول على الارتفاع أو تحديده بناءً على المرجع بتنسيق[`AltitudeRef`](./altituderef) . الوحدة المرجعية متر . |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | الحصول على الارتفاع المستخدم كارتفاع مرجعي أو تعيينه. إذا كان المرجع هو مستوى سطح البحر والارتفاع فوق مستوى سطح البحر ، فيعطى 0. إذا كان الارتفاع تحت مستوى سطح البحر ، يتم إعطاء قيمة 1 ويشار إلى الارتفاع كقيمة مطلقة في[`Altitude`](./altitude) العلامة . |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | الحصول على سلسلة الأحرف أو تعيينها لتسجيل اسم منطقة GPS. يشير البايت الأول إلى رمز الحرف المستخدم ، ويتبعه اسم منطقة GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | الحصول على أو تعيين DOP GPS (درجة دقة البيانات) . يتم كتابة قيمة HDOP أثناء القياس ثنائي الأبعاد ، و PDOP أثناء القياس ثلاثي الأبعاد . |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | الحصول على أو تعيين معلومات تاريخ ووقت تسجيل سلسلة الأحرف المتعلقة بالتوقيت العالمي المنسق (UTC). التنسيق هو YYYY: MM: DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | الحصول على أو تعيين اتجاه GPS إلى نقطة الوجهة. يتراوح نطاق القيم من 0.00 إلى 359.99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | الحصول على مرجع GPS المستخدم لإعطاء الاتجاه لنقطة الوجهة أو تعيينه. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | الحصول على أو تحديد مسافة GPS لنقطة الوجهة. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | الحصول على أو تعيين وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. تمثل "K" و "M" و "N" الكيلومترات والأميال والعقد . |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | الحصول على أو تحديد خط عرض GPS لنقطة الوجهة. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | الحصول على أو تعيين قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة هو خط العرض الشمالي أو الجنوبي . تشير قيمة ASCII "N" إلى خط العرض الشمالي ، و "S" هي خط العرض الجنوبي . |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | الحصول على أو تعيين خط طول GPS لنقطة الوجهة. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | الحصول على أو تعيين قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة هو خط الطول الشرقي أو الغربي. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | الحصول على أو تعيين قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | الحصول على أو تحديد اتجاه حركة مستقبل GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | الحصول على أو تحديد اتجاه GPS للصورة عند التقاطها. يتراوح نطاق القيم من 0.00 إلى 359.99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | الحصول على مرجع GPS أو تعيينه لإعطاء اتجاه الصورة عند التقاطها. يشير الحرف "T" إلى الاتجاه الحقيقي بينما يشير الحرف "M" إلى الاتجاه المغناطيسي . |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | يحصل على علامة TIFF بالمعرف المحدد. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | الحصول على خط عرض GPS أو تعيينه. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | الحصول على أو تعيين قيمة GPS تشير إلى ما إذا كان خط العرض شمالًا أم جنوبًا. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | الحصول على أو تعيين خط طول GPS . |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | الحصول على أو تعيين قيمة GPS تشير إلى ما إذا كان خط الطول شرقًا أم غربًا. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | الحصول على أو تعيين بيانات المسح الجيوديسي التي يستخدمها مستقبل GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | الحصول على أو تعيين وضع قياس GPS . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | الحصول على أو تعيين سلسلة أحرف تسجل اسم الطريقة المستخدمة للعثور على الموقع . يشير البايت الأول إلى رمز الحرف المستخدم ، ويتبع ذلك اسم الطريقة. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | الحصول على أو تعيين الأقمار الصناعية لنظام تحديد المواقع العالمي (GPS) المستخدمة للقياسات . يمكن استخدام هذه العلامة لوصف عدد الأقمار الصناعية ، رقم معرفها ، وزاوية الارتفاع ، والسمت ، ونسبة الإشارة إلى الضوضاء (SNR) وغيرها من المعلومات في تدوين ASCII. لم يتم تحديد التنسيق . إذا كان جهاز استقبال GPS غير قادر على أخذ القياسات ، فيجب ضبط قيمة العلامة على NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | الحصول على أو تحديد سرعة حركة مستقبل GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | الحصول على الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS أو تعيينها. تمثل "K" و "N" كيلومترات في الساعة ، وأميال في الساعة ، وعقدة . |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | الحصول على أو تعيين حالة مستقبل GPS عند تسجيل الصورة. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | الحصول على الوقت أو تعيينه كـ UTC (التوقيت العالمي المنسق) . يتم التعبير عن الطابع الزمني بثلاث قيم RATIONAL تعطي الساعة والدقيقة والثانية . |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | الحصول على المرجع لإعطاء اتجاه حركة مستقبل GPS أو تعيينه. يشير الحرف "T" إلى الاتجاه الصحيح بينما يشير الحرف "M" إلى الاتجاه المغناطيسي. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | الحصول على أو تحديد إصدار GPS IFD . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | يزيل كل علامات TIFF المخزنة في الحزمة. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | يزيل الخاصية بالمعرف المحدد. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | إضافة أو استبدال العلامة المحددة. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | إنشاء قائمة من الحزمة . |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع بيانات EXIF الوصفية](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### أنظر أيضا

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
