---
title: TiffTagID
second_title: GroupDocs.Metadata لمرجع .NET API
description: يحدد معرفات علامات TIFF .
type: docs
weight: 2100
url: /ar/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

يحدد معرفات علامات TIFF .

```csharp
public enum TiffTagID : ushort
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| GpsVersionID | `0` | يشير إلى إصدار GPSInfoIFD. |
| GpsLatitudeRef | `1` | يشير إلى ما إذا كان خط العرض هو خط العرض الشمالي أو الجنوبي . |
| GpsLatitude | `2` | تشير إلى خط العرض . |
| GpsLongitudeRef | `3` | يشير إلى ما إذا كان خط الطول شرقًا أم غربًا. |
| GpsLongitude | `4` | يشير إلى خط الطول . |
| GpsAltitudeRef | `5` | يشير إلى الارتفاع المستخدم كارتفاع مرجعي . |
| GpsAltitude | `6` | يشير إلى الارتفاع بناءً على المرجع في GPSAltitudeRef. |
| GpsTimeStamp | `7` | يشير إلى الوقت كـ UTC (التوقيت العالمي المنسق). |
| GpsSatellites | `8` | يحدد أقمار GPS الصناعية المستخدمة للقياسات. |
| GpsStatus | `9` | يشير إلى حالة مستقبل GPS عند تسجيل الصورة. |
| GpsMeasureMode | `10` | يشير إلى وضع قياس GPS . |
| GpsDop | `11` | يشير إلى DOP GPS (درجة دقة البيانات). |
| GpsSpeedRef | `12` | يشير إلى الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS |
| GpsSpeed | `13` | يشير إلى سرعة حركة مستقبل GPS. |
| GpsTrackRef | `14` | يشير إلى المرجع لإعطاء اتجاه حركة مستقبل GPS. |
| GpsTrack | `15` | يشير إلى اتجاه حركة مستقبل GPS . |
| GpsImgDirectionRef | `16` | يشير إلى المرجع لإعطاء اتجاه الصورة عند التقاطها. |
| GpsImgDirection | `17` | يشير إلى اتجاه الصورة عند التقاطها. |
| GpsMapDatum | `18` | يشير إلى بيانات المسح الجيوديسي التي يستخدمها مستقبل GPS. |
| GpsDestLatitudeRef | `19` | يشير إلى ما إذا كان خط عرض نقطة الوجهة هو خط العرض الشمالي أو الجنوبي. |
| GpsDestLatitude | `20` | يشير إلى خط عرض نقطة الوجهة . |
| GpsDestLongitudeRef | `21` | يشير إلى ما إذا كان خط طول نقطة الوجهة هو خط الطول الشرقي أو الغربي. |
| GpsDestLongitude | `22` | يشير إلى خط طول نقطة الوجهة . |
| GpsDestBearingRef | `23` | يشير إلى المرجع المستخدم لإعطاء الاتجاه إلى نقطة الوجهة . |
| GpsDestBearing | `24` | يشير إلى الاتجاه إلى نقطة الوجهة . |
| GpsDestDistanceRef | `25` | يشير إلى الوحدة المستخدمة للتعبير عن المسافة إلى نقطة الوجهة . |
| GpsDestDistance | `26` | تشير إلى المسافة إلى نقطة الوجهة. |
| GpsProcessingMethod | `27` | سلسلة أحرف تسجل اسم الطريقة المستخدمة للعثور على الموقع. |
| GpsAreaInformation | `28` | سلسلة أحرف تسجل اسم منطقة GPS . |
| GpsDateStamp | `29` | معلومات تاريخ ووقت تسجيل سلسلة الأحرف المتعلقة بالتوقيت العالمي المنسق (UTC). |
| GpsDifferential | `30` | يشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل GPS. |
| GpsHPositioningError | `31` | تشير هذه العلامة إلى أخطاء تحديد الموضع الأفقي بالأمتار. |
| NewSubfileType | `254` | إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| SubfileType | `255` | إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. تم إهمال هذا الحقل. يجب استخدام حقل NewSubfileType بدلاً من ذلك |
| ImageWidth | `256` | عدد الأعمدة في الصورة ، أي عدد البكسل لكل خط مسح. |
| ImageLength | `257` | عدد الصفوف (التي توصف أحيانًا بخطوط المسح) في الصورة. |
| BitsPerSample | `258` | عدد وحدات البت لكل مكون. |
| Compression | `259` | مخطط الضغط المستخدم في بيانات الصورة . |
| PhotometricInterpretation | `262` | مساحة اللون لبيانات الصورة . |
| Threshholding | `263` | بالنسبة لملفات TIFF بالأبيض والأسود التي تمثل ظلال اللون الرمادي ، فإن التقنية المستخدمة للتحويل من البكسل الرمادي إلى الأسود والأبيض. |
| CellWidth | `264` | عرض مصفوفة التدرج أو الألوان النصفية المستخدمة لإنشاء ملف ثنائي المستوى متذبذب أو نصف نغمة . |
| CellLength | `265` | طول مصفوفة التدرج أو الألوان النصفية المستخدمة لإنشاء ملف ثنائي المستوى متذبذب أو نصف نغمة. |
| FillOrder | `266` | الترتيب المنطقي للبتات داخل بايت. |
| DocumentName | `269` | اسم المستند الذي تم مسح الصورة ضوئيًا منه. |
| ImageDescription | `270` | سلسلة تصف موضوع الصورة. |
| Make | `271` | الشركة المصنعة للماسح الضوئي. |
| Model | `272` | اسم أو رقم طراز الماسح الضوئي . |
| StripOffsets | `273` | لكل شريط ، إزاحة البايت لهذا الشريط. |
| Orientation | `274` | اتجاه الصورة بالنسبة للصفوف والأعمدة. |
| SamplesPerPixel | `277` | عدد المكونات لكل بكسل . |
| RowsPerStrip | `278` | عدد الصفوف في كل قطاع . |
| StripByteCounts | `279` | لكل شريط ، عدد البايتات في الشريط بعد الضغط. |
| MinSampleValue | `280` | الحد الأدنى لقيمة المكون المستخدمة . |
| MaxSampleValue | `281` | الحد الأقصى لقيمة المكون المستخدمة . |
| XResolution | `282` | عدد البكسل لكل وحدة دقة في اتجاه ImageWidth . |
| YResolution | `283` | عدد البكسل لكل وحدة دقة في اتجاه طول الصورة. |
| PlanarConfiguration | `284` | كيف يتم تخزين مكونات كل بكسل. |
| PageName | `285` | اسم الصفحة التي تم مسح هذه الصورة منها. |
| XPosition | `286` | موضع X للصورة . |
| YPosition | `287` | موضع Y للصورة . |
| FreeOffsets | `288` | لكل سلسلة من وحدات البايت المتجاورة غير المستخدمة في ملف TIFF ، إزاحة البايت للسلسلة. |
| FreeByteCounts | `289` | لكل سلسلة من وحدات البايت المتجاورة غير المستخدمة في ملف TIFF ، عدد البايت في السلسلة. |
| GrayResponseUnit | `290` | دقة المعلومات الواردة في GrayResponseCurve. |
| GrayResponseCurve | `291` | بالنسبة إلى بيانات التدرج الرمادي ، الكثافة الضوئية لكل قيمة بكسل ممكنة . |
| T4Options | `292` | خيارات ترميز T4 . |
| T6Options | `293` | خيارات ترميز T6 . |
| ResolutionUnit | `296` | وحدة قياس XResolution و YResolution. |
| PageNumber | `297` | رقم الصفحة للصفحة التي تم مسح هذه الصورة منها. |
| TransferFunction | `301` | يصف وظيفة نقل للصورة بنمط جدولي. يمكن أن تكون مكونات البكسل معوضة بأشعة غاما ، أو مركبة ، أو مكمية بشكل غير منتظم ، أو مشفرة بطريقة أخرى. تقوم وظيفة النقل بتعيين مكونات البكسل من نموذج غير خطي BitsPerSample (على سبيل المثال 8 بت) إلى شكل خطي 16 بت بدون خسارة ملحوظة للدقة. |
| Software | `305` | الاسم ورقم إصدار حزمة (حزم) البرامج المستخدمة لإنشاء الصورة. |
| DateTime | `306` | تاريخ ووقت إنشاء الصورة . |
| Artist | `315` | الشخص الذي قام بإنشاء الصورة . |
| HostComputer | `316` | الكمبيوتر و / أو نظام التشغيل المستخدم وقت إنشاء الصورة. |
| Predictor | `317` | يحدد هذا القسم متنبئًا يعمل على تحسين نسب الضغط لبعض الصور بشكل كبير. |
| WhitePoint | `318` | لونية النقطة البيضاء للصورة. |
| PrimaryChromaticities | `319` | اللونية في الانتخابات التمهيدية للصورة. |
| ColorMap | `320` | خريطة ألوان للصور الملونة بالألوان . |
| HalftoneHints | `321` | الغرض من حقل HalftoneHints هو نقل نطاق من المستويات الرمادية إلى دالة الألوان النصفية داخل صورة محددة بشكل قياسي يجب أن تحتفظ بتفاصيل الدرجة اللونية . |
| TileWidth | `322` | عرض التجانب بالبكسل. هذا هو عدد الأعمدة في كل مربع. |
| TileLength | `323` | طول البلاط (الارتفاع) بالبكسل. هذا هو عدد الصفوف في كل مربع. |
| TileOffsets | `324` | لكل بلاطة ، إزاحة البايت لتلك القطعة ، مضغوطة ومخزنة على القرص. يتم تحديد الإزاحة بالنسبة لبداية ملف TIFF. لاحظ أن هذا يعني أن كل بلاطة لها موقع مستقل عن مواقع المربعات الأخرى. |
| TileByteCounts | `325` | لكل بلاطة ، عدد البايتات (المضغوطة) في هذا المربع. |
| InkSet | `332` | مجموعة الأحبار المستخدمة في صورة منفصلة (PhotometricInterpretation = 5). |
| InkNames | `333` | اسم كل حبر مستخدم في صورة منفصلة (PhotometricInterpretation = 5) ، مكتوبة كقائمة من سلاسل ASCII المتسلسلة المنتهية بـ NUL. |
| NumberOfInks | `334` | عدد الأحبار. عادةً ما تساوي SamplesPerPixel ، ما لم تكن هناك عينات إضافية. |
| DotRange | `336` | قيم المكون التي تتوافق مع 0٪ نقطة و 100٪ نقطة. DotRange [0] يتوافق مع 0٪ نقطة ، و DotRange [1] يتوافق مع 100٪ dot. |
| ExtraSamples | `338` | وصف المكونات الإضافية . |
| SampleFormat | `339` | يحدد هذا الحقل كيفية تفسير كل عينة بيانات بالبكسل. |
| SMinSampleValue | `340` | يحدد هذا الحقل الحد الأدنى لقيمة العينة. |
| SMaxSampleValue | `341` | يحدد هذا الحقل الجديد الحد الأقصى لقيمة العينة. |
| TransferRange | `342` | يوسع نطاق دالة النقل. |
| JpegProc | `512` | يشير هذا الحقل إلى عملية JPEG المستخدمة لإنتاج البيانات المضغوطة. |
| JpegInterchangeFormat | `513` | يشير هذا الحقل إلى ما إذا كان تنسيق نقل البيانات بتنسيق JPEG موجودًا في ملف TIFF. |
| JpegInterchangeFormatLength | `514` | يشير هذا الحقل إلى الطول بالبايت لتنسيق تبادل JPEG bitstream |
| JpegRestartInterval | `515` | يشير هذا الحقل إلى طول فترة إعادة التشغيل المستخدمة في بيانات الصورة المضغوطة. |
| JpegLosslessPredictors | `517` | يشير هذا الحقل إلى قائمة بقيم متنبئ التحديد بدون فقدان ، قيمة واحدة لكل مكون . |
| JpegPointTransforms | `518` | يشير هذا الحقل إلى قائمة قيم تحويل النقاط ، قيمة واحدة لكل مكون. |
| JpegQTables | `519` | يشير هذا الحقل إلى قائمة تعويضات جداول التقسيم ، واحد لكل مكون. |
| JpegDCTables | `520` | يشير هذا الحقل إلى قائمة الإزاحات إلى جداول DC Huffman أو جداول Lossless Huffman ، واحد لكل مكون. |
| JpegACTables | `521` | يشير هذا الحقل إلى قائمة الإزاحات لجداول Huffman AC ، واحد لكل مكون. |
| YCbCrCoefficients | `529` | مكونات المصفوفة للتحول من بيانات صورة RGB إلى YCbCr . |
| YCbCrSubSampling | `530` | نسبة أخذ العينات لمكونات التلون بالنسبة لمكون النصوع. |
| YCbCrPositioning | `531` | يحدد موضع مكونات التلون المستندة إلى عينات فرعية بالنسبة إلى عينات النصوع. |
| ReferenceBlackWhite | `532` | يحدد زوجًا من قيم (رموز) بيانات صورة مساحة الرأس والقدم لكل مكون من مكونات البكسل. |
| Copyright | `33432` | حقوق النشر. |
| UserComment | `37510` | كلمات رئيسية أو تعليقات على الصورة ؛ يكمل ImageDescription. |
| Xmp | `700` | مؤشر إلى بيانات تعريف XMP . |
| ImageID | `32781` | ذات الصلة بـ OPI . |
| Iptc | `33723` | بيانات تعريف IPTC (المجلس الدولي للاتصالات السلكية واللاسلكية) . في كثير من الأحيان ، يتم تحديد نوع البيانات بشكل غير صحيح على أنه LONG. |
| Photoshop | `34377` | مجموعة من "كتل موارد الصور" في Photoshop . |
| ImageLayer | `34732` | طبقة الصورة . |
| IccProfile | `34675` | بيانات ملف تعريف اللون . |
| ExifIfd | `34665` | مؤشر لتجميع كافة بيانات EXIF الوصفية. يستخدم EXIF أسماء الحقول بدلاً من العلامات للإشارة إلى محتوى الحقل. |
| GpsIfd | `34853` | مؤشر إلى بيانات GPS . |
| Makernotes | `37500` | مؤشر إلى بيانات العلامات . |
| InteroperabilityIfd | `40965` | IFD المتعلقة بقابلية التشغيل البيني ذات الصلة بـ Exif . |
| CameraOwnerName | `42032` | اسم مالك الكاميرا كسلسلة ASCII . |
| BodySerialNumber | `42033` | الرقم التسلسلي لجسم الكاميرا كسلسلة ASCII . |
| CfaPattern | `41730` | يحدد النمط الهندسي لصفيف مرشح الألوان (CFA) لمستشعر الصورة عند استخدام مستشعر منطقة اللون أحادي الرقاقة. لا تنطبق على جميع طرق الاستشعار. |
| ExifVersion | `36864` | دعم إصدار معيار EXIF . |
| ComponentsConfiguration | `37121` | معلومات خاصة بالبيانات المضغوطة. يتم ترتيب قنوات كل مكون بالترتيب من المكون الأول إلى المكون الرابع. |
| FlashpixVersion | `40960` | إصدار تنسيق Flashpix الذي يدعمه ملف FPXR. إذا كانت وظيفة FPXR تدعم تنسيق Flashpix Ver. 1.0 ، يشار إلى هذا بشكل مشابه لـ ExifVersion بتسجيل "0100" كـ 4 بايت ASCII. |
| ColorSpace | `40961` | يتم دائمًا تسجيل علامة معلومات مساحة اللون (ColorSpace) كمحدد مساحة اللون. عادةً ما يتم استخدام sRGB (= 1) لتحديد مساحة اللون بناءً على ظروف وبيئة شاشة الكمبيوتر. إذا تم استخدام فراغ لوني غير sRGB ، فسيتم تعيين Uncalibrated (= FFFF.H). |
| PixelXDimension | `40962` | معلومات خاصة بالبيانات المضغوطة. عند تسجيل ملف مضغوط ، يجب تسجيل العرض الصالح للصورة ذات المعنى في هذه العلامة ، سواء كانت هناك بيانات حشو أو علامة إعادة تشغيل أم لا. |
| PixelYDimension | `40963` | معلومات خاصة بالبيانات المضغوطة. عند تسجيل ملف مضغوط ، يجب تسجيل الارتفاع الصالح للصورة ذات المعنى في هذه العلامة ، سواء كانت هناك بيانات حشو أو علامة إعادة تشغيل أم لا. |
| SceneCaptureType | `41990` | تشير هذه العلامة إلى نوع المشهد الذي تم تصويره. يمكن استخدامه أيضًا لتسجيل الوضع الذي تم فيه التقاط الصورة. |
| Gamma | `42240` | تشير إلى قيمة معامل جاما. |
| CompressedBitsPerPixel | `37122` | معلومات خاصة بالبيانات المضغوطة. يشار إلى وضع الضغط المستخدم للصورة المضغوطة بوحدات بت لكل بكسل. |
| RelatedSoundFile | `40964` | تُستخدم هذه العلامة لتسجيل اسم ملف صوتي متعلق ببيانات الصورة. المعلومات العلائقية الوحيدة المسجلة هنا هي اسم ملف Exif الصوتي وامتداده (سلسلة ASCII تتكون من 8 أحرف + '.' + 3 أحرف). |
| DateTimeOriginal | `36867` | تاريخ ووقت إنشاء بيانات الصورة الأصلية. بالنسبة إلى DSC ، يتم تسجيل تاريخ ووقت التقاط الصورة. التنسيق هو "YYYY: MM: DD HH: MM: SS" مع عرض الوقت بتنسيق 24 ساعة ، والتاريخ والوقت مفصولان بحرف واحد فارغ . |
| DateTimeDigitized | `36868` | تاريخ ووقت تخزين الصورة كبيانات رقمية. على سبيل المثال ، إذا تم التقاط صورة بواسطة DSC وفي نفس الوقت الذي تم فيه تسجيل الملف ، فإن DateTimeOriginal و DateTimeDigitized سيكون لهما نفس المحتويات. التنسيق هو "YYYY: MM: DD HH: MM: SS" مع عرض الوقت بتنسيق 24 ساعة ، والتاريخ والوقت مفصولان بحرف واحد فارغ . |
| OffsetTime | `36880` | علامة تستخدم لتسجيل الإزاحة من التوقيت العالمي المنسق (فرق التوقيت من منسق التوقيت العالمي بما في ذلك التوقيت الصيفي) لعلامة التاريخ والوقت. التنسيق عند تسجيل الإزاحة هو "± HH: MM". يتم تسجيل جزء "±" كـ "+" أو "-" . |
| OffsetTimeOriginal | `36881` | علامة مستخدمة لتسجيل الإزاحة من التوقيت العالمي المنسق (فرق التوقيت من منسق التوقيت العالمي بما في ذلك التوقيت الصيفي) لوقت علامة DateTimeOriginal . التنسيق عند تسجيل الإزاحة هو "± HH: MM". يتم تسجيل جزء "±" كـ "+" أو "-" . |
| OffsetTimeDigitized | `36882` | علامة مستخدمة لتسجيل الإزاحة من UTC (فرق التوقيت من منسق التوقيت العالمي بما في ذلك التوقيت الصيفي) لوقت علامة DateTimeDigitized. التنسيق عند تسجيل الإزاحة هو "± HH: MM". يتم تسجيل جزء "±" كـ "+" أو "-" . |
| SubsecTime | `37520` | علامة تستخدم لتسجيل أجزاء من الثواني لعلامة DateTime . |
| SubsecTimeOriginal | `37521` | علامة تستخدم لتسجيل أجزاء من الثواني للعلامة DateTimeOriginal . |
| SubsecTimeDigitized | `37522` | علامة تستخدم لتسجيل أجزاء من الثواني للعلامة DateTimeDigitized . |
| ExposureTime | `33434` | وقت التعرض ، بالثواني (ثانية) . |
| FNumber | `33437` | الرقم F . |
| ExposureProgram | `34850` | فئة البرنامج التي تستخدمها الكاميرا لضبط التعريض الضوئي عند التقاط الصورة . |
| SpectralSensitivity | `34852` | يشير إلى الحساسية الطيفية لكل قناة من قنوات الكاميرا المستخدمة. قيمة العلامة هي سلسلة ASCII متوافقة مع المعيار الذي طورته اللجنة الفنية ASTM . |
| PhotographicSensitivity | `34855` | تشير هذه العلامة إلى حساسية الكاميرا أو جهاز الإدخال عند التقاط الصورة. |
| Oecf | `34856` | تشير إلى وظيفة التحويل البصري الكهربائي (OECF) المحددة في ISO 14524. OECF هي العلاقة بين الإدخال البصري للكاميرا وقيم الصورة. |
| SensitivityType | `34864` | تشير علامة SensitivityType إلى أي من معلمات ISO12232 هي علامة PhotographicSensitivity. على الرغم من أنها علامة اختيارية ، إلا أنه يجب تسجيلها عند تسجيل علامة PhotographicSensitivity . |
| StandardOutputSensitivity | `34865` | تشير هذه العلامة إلى قيمة حساسية الإخراج القياسية للكاميرا أو جهاز الإدخال المحدد في ISO 12232. عند تسجيل هذه العلامة ، يجب أيضًا تسجيل علامتي PhotographicSensitivity و SensitivityType. |
| RecommendedExposureIndex | `34866` | تشير هذه العلامة إلى قيمة مؤشر التعريض الموصى بها للكاميرا أو جهاز الإدخال المحدد في ISO 12232. عند تسجيل هذه العلامة ، يجب أيضًا تسجيل علامتي PhotographicSensitivity و SensitivityType. |
| IsoSpeed | `34867` | تشير هذه العلامة إلى قيمة سرعة ISO للكاميرا أو جهاز الإدخال المحدد في ISO 12232. عند تسجيل هذه العلامة ، يجب أيضًا تسجيل علامتي PhotographicSensitivity و SensitivityType . |
| ISOSpeedLatitudeYyy | `34868` | تشير هذه العلامة إلى قيمة سرعة ISO yyy لخط العرض للكاميرا أو جهاز الإدخال المحدد في ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | تشير هذه العلامة إلى قيمة zzz لخط العرض لسرعة ISO للكاميرا أو جهاز الإدخال المحدد في ISO 12232. |
| ShutterSpeedValue | `37377` | سرعة الغالق. الوحدة هي إعداد APEX (النظام الإضافي للتعرض الضوئي). |
| ApertureValue | `37378` | فتحة العدسة. الوحدة هي قيمة APEX. |
| BrightnessValue | `37379` | قيمة السطوع. الوحدة هي قيمة APEX. |
| ExposureBiasValue | `37380` | انحياز التعريض. الوحدة هي قيمة APEX. |
| MaxApertureValue | `37381` | أصغر رقم F للعدسة. الوحدة هي قيمة APEX. |
| SubjectDistance | `37382` | المسافة إلى الموضوع معطاة بالأمتار . |
| MeteringMode | `37383` | وضع القياس . |
| LightSource | `37384` | نوع مصدر الضوء . |
| Flash | `37385` | تشير هذه العلامة إلى حالة الفلاش عند التقاط الصورة. تشير البتة 0 إلى حالة إطلاق الفلاش ، وتشير البتتان 1 و 2 إلى حالة عودة الفلاش ، وتشير بت 3 و 4 إلى وضع الفلاش ، وتشير البتة 5 إلى ما إذا كانت وظيفة الفلاش موجودة ، وتشير البتة 6 إلى وضع "العين الحمراء". |
| SubjectArea | `37396` | تشير هذه العلامة إلى موقع ومساحة الموضوع الرئيسي في المشهد العام. |
| FocalLength | `37386` | الطول البؤري الفعلي للعدسة ، بالملم. لم يتم التحويل إلى الطول البؤري لكاميرا فيلم مقاس 35 مم. |
| FlashEnergy | `41483` | يشير إلى الطاقة القوية في وقت التقاط الصورة ، كما تم قياسها في قوة الشعاع ثانية (BCPS) . |
| SpatialFrequencyResponse | `41484` | هذه العلامة تسجل الكاميرا أو جدول التردد المكاني لجهاز الإدخال وقيم SFR في اتجاه عرض الصورة ، ارتفاع الصورة ، والاتجاه القطري ، كما هو محدد في ISO 12233. |
| FocalPlaneXResolution | `41486` | يشير إلى عدد البكسل في اتجاه عرض الصورة (X) لكل FocalPlaneResolutionUnit على المستوى البؤري للكاميرا. |
| FocalPlaneYResolution | `41487` | تشير إلى عدد البكسل في اتجاه ارتفاع الصورة (Y) لكل FocalPlaneResolutionUnit على المستوى البؤري للكاميرا. |
| FocalPlaneResolutionUnit | `41488` | يشير إلى وحدة قياس دقة FocalPlaneX و FocalPlaneYResolution. هذه القيمة هي نفسها وحدة الدقة. |
| SubjectLocation | `41492` | يشير إلى موقع الهدف الرئيسي في المشهد. تمثل قيمة هذه العلامة البكسل الموجود في مركز الموضوع الرئيسي بالنسبة للحافة اليسرى ، قبل معالجة التدوير وفقًا لعلامة التدوير. تشير القيمة الأولى إلى رقم العمود X وتشير القيمة الثانية إلى رقم الصف Y. |
| ExposureIndex | `41493` | يشير إلى فهرس التعريض المحدد على الكاميرا أو جهاز الإدخال في وقت التقاط الصورة. |
| SensingMethod | `41495` | يشير إلى نوع مستشعر الصورة على الكاميرا أو جهاز الإدخال. |
| FileSource | `41728` | يشير إلى مصدر الصورة. إذا قام DSC بتسجيل الصورة ، فيجب دائمًا تعيين قيمة العلامة هذه على 3. |
| SceneType | `41729` | يشير إلى نوع المشهد. إذا قام DSC بتسجيل الصورة ، فيجب دائمًا تعيين قيمة العلامة هذه على 1 ، للإشارة إلى أن الصورة تم تصويرها بشكل مباشر. |
| CustomRendered | `41985` | تشير هذه العلامة إلى استخدام معالجة خاصة لبيانات الصورة ، مثل العرض الموجه للإخراج . |
| ExposureMode | `41986` | تشير هذه العلامة إلى وضع التعريض الضوئي الذي تم ضبطه عند التقاط الصورة. في وضع التصحيح التلقائي ، تقوم الكاميرا بتصوير سلسلة من الإطارات لنفس المشهد بإعدادات تعريض مختلفة. |
| WhiteBalance | `41987` | تشير هذه العلامة إلى وضع توازن اللون الأبيض الذي تم ضبطه عند التقاط الصورة. |
| DigitalZoomRatio | `41988` | تشير هذه العلامة إلى نسبة الزوم الرقمي عند التقاط الصورة. إذا كان بسط القيمة المسجلة 0 ، فهذا يشير إلى عدم استخدام الزوم الرقمي. |
| FocalLengthIn35mmFilm | `41989` | تشير هذه العلامة إلى الطول البؤري المكافئ بافتراض وجود كاميرا فيلم مقاس 35 مم ، بالملم. تعني القيمة 0 أن الطول البؤري غير معروف. لاحظ أن هذه العلامة تختلف عن علامة FocalLength . |
| GainControl | `41991` | تشير هذه العلامة إلى درجة الضبط الكلي لكسب الصورة . |
| Contrast | `41992` | تشير هذه العلامة إلى اتجاه معالجة التباين المطبق بواسطة الكاميرا عند التقاط الصورة. |
| Saturation | `41993` | تشير هذه العلامة إلى اتجاه معالجة التشبع المطبق بواسطة الكاميرا عند التقاط الصورة. |
| Sharpness | `41994` | تشير هذه العلامة إلى اتجاه معالجة الحدة الذي تطبقه الكاميرا عند التقاط الصورة . |
| DeviceSettingDescription | `41995` | تشير هذه العلامة إلى معلومات حول ظروف التقاط الصور لطراز كاميرا معين. |
| SubjectDistanceRange | `41996` | تشير هذه العلامة إلى المسافة إلى الموضوع . |
| CompositeImage | `42080` | تشير هذه العلامة إلى ما إذا كانت الصورة المسجلة هي صورة مركبة * أم لا. |
| SourceImageNumberOfCompositeImage | `42081` | تشير هذه العلامة إلى عدد الصور المصدر (الصور المسجلة مبدئيًا) الملتقطة لصورة مركبة. |
| SourceExposureTimesOfCompositeImage | `42082` | بالنسبة للصورة المركبة ، تسجل هذه العلامة المعلمات المتعلقة بوقت التعرض للتعريضات لتوليد الصورة المركبة المذكورة ، مثل أوقات التعريض الخاصة بصور المصدر الملتقطة (الصور المسجلة مبدئيًا) . |
| Temperature | `37888` | درجة الحرارة مثل الوضع المحيط عند اللقطة ، على سبيل المثال درجة حرارة الغرفة حيث كان المصور يحمل الكاميرا. الوحدة درجة مئوية. |
| Humidity | `37889` | الرطوبة مثل الوضع المحيط عند اللقطة ، على سبيل المثال رطوبة الغرفة حيث كان المصور يحمل الكاميرا. الوحدة٪. |
| Pressure | `37890` | الضغط حسب الوضع المحيط عند اللقطة ، على سبيل المثال ، الغلاف الجوي للغرفة حيث كان المصور يحمل الكاميرا أو ضغط الماء تحت سطح البحر. الوحدة hPa. |
| WaterDepth | `37891` | عمق الماء هو الوضع المحيط عند اللقطة ، على سبيل المثال عمق الماء في الكاميرا عند التصوير تحت الماء. الوحدة m. |
| Acceleration | `37892` | التسارع (عددي بغض النظر عن الاتجاه) مثل الوضع المحيط عند اللقطة ، على سبيل المثال تسارع قيادة السيارة التي ركبها المصور عند اللقطة. الوحدة mGal (10-5 م / ث 2) . |
| CameraElevationAngle | `37893` | الارتفاع / الانخفاض. زاوية اتجاه الكاميرا (تصوير المحور البصري) مثل الوضع المحيط عند اللقطة. الوحدة درجة (°) . |
| ImageUniqueID | `42016` | تشير هذه العلامة إلى معرف مخصص بشكل فريد لكل صورة. |
| LensSpecification | `42034` | تشير هذه العلامة إلى الحد الأدنى للبعد البؤري ، والحد الأقصى للبعد البؤري ، والحد الأدنى لرقم F في الحد الأدنى للبعد البؤري ، و والحد الأدنى لرقم F في أقصى طول بؤري ، وهي معلومات مواصفات للعدسة التي تم استخدامها في التصوير الفوتوغرافي. |
| LensMake | `42035` | تسجل هذه العلامة الشركة المصنعة للعدسة كسلسلة ASCII. |
| LensModel | `42036` | تسجل هذه العلامة اسم طراز العدسة ورقم الطراز كسلسلة ASCII. |
| LensSerialNumber | `42037` | تسجل هذه العلامة الرقم التسلسلي للعدسة القابلة للتبديل التي تم استخدامها في التصوير الفوتوغرافي كسلسلة ASCII. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
