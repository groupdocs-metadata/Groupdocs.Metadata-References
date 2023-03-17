---
title: ExifGpsPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные GPS в пакете метаданных EXIF.
type: docs
weight: 2770
url: /ru/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Представляет метаданные GPS в пакете метаданных EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Инициализирует новый экземпляр[`ExifGpsPackage`](../exifgpspackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Получает или задает высоту на основе ссылки в[`AltitudeRef`](./altituderef) . Единицей отсчета являются метры. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Получает или задает высоту, используемую в качестве эталонной высоты. Если эталоном является уровень моря и высота над уровнем моря, задается 0. Если высота ниже уровня моря, задается значение 1, а высота указывается как абсолютное значение в[`Altitude`](./altitude) тег. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Получает или задает строку символов, записывающую название области GPS. Первый байт указывает используемый код символа, за ним следует название области GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Получает или задает DOP GPS (степень точности данных). Значение HDOP записывается при двумерном измерении, а PDOP — при трехмерном измерении. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Получает или задает информацию о дате и времени записи строки символов относительно UTC (Всемирное координированное время). Формат ГГГГ:ММ:ДД. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Получает или задает направление GPS на точку назначения. Диапазон значений: от 0,00 до 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Получает или задает опорную точку GPS, используемую для указания пеленга на точку назначения. «T» обозначает истинное направление, а «M» — магнитное направление. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Получает или задает расстояние GPS до точки назначения. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Получает или задает единицу измерения GPS, используемую для выражения расстояния до точки назначения. 'K', 'M' и 'N' обозначают километры, мили и узлы. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Получает или задает широту GPS точки назначения. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Получает или задает значение GPS, указывающее, является ли широта точки назначения северной или южной широтой. Значение ASCII «N» указывает северную широту, а «S» — южную широту. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Получает или задает долготу GPS точки назначения. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Получает или задает значение GPS, указывающее, является ли долгота точки назначения восточной или западной долготой. Символ ASCII «E» указывает восточную долготу, а «W» — западную долготу. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к приемнику GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Получает или задает направление движения приемника GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Получает или задает GPS-направление изображения при его захвате. Диапазон значений: от 0,00 до 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Получает или задает ссылку GPS для указания направления изображения при его захвате. «T» обозначает истинное направление, а «M» — магнитное направление. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Получает тег TIFF с указанным идентификатором. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Получает или устанавливает широту GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Получает или задает значение GPS, указывающее, является ли широта северной или южной широтой. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Получает или задает долготу GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Получает или задает значение GPS, указывающее, является ли долгота восточной или западной долготой. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Получает или задает данные геодезической съемки, используемые приемником GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Получает или задает режим измерения GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Получает или задает строку символов, записывающую имя метода, используемого для определения местоположения. Первый байт указывает используемый код символа, за которым следует имя метода. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Получает или устанавливает спутники GPS, используемые для измерений. Этот тег может использоваться для описания количества спутников, их идентификационного номера, угла места, азимута, SNR и другой информации в нотации ASCII. Формат не указан. Если приемник GPS не может выполнять измерения, значение тега должно быть установлено в NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Получает или задает скорость движения приемника GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Получает или задает единицу измерения, используемую для выражения скорости движения приемника GPS. 'K', 'M' и 'N' представляют километры в час, мили в час и узлы. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Получает или задает состояние приемника GPS при записи изображения. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Получает или задает время в формате UTC (Всемирное координированное время). TimeStamp выражается тремя РАЦИОНАЛЬНЫМИ значениями, представляющими час, минуту и секунду. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Получает или задает ссылку для указания направления движения приемника GPS. «T» обозначает истинное направление, а «M» — магнитное направление. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Получает или задает версию GPS IFD. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Удаляет все теги TIFF, хранящиеся в пакете. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Удаляет свойство с указанным идентификатором. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Добавляет или заменяет указанный тег. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Создает список из пакета. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Узнать больше**

* [Работа с метаданными EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Смотрите также

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* пространство имен [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
