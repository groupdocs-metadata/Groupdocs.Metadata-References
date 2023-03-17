---
title: ExifGpsPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: EXIF मेटडेट पैकेज में GPS मेटडेट क प्रतनधत्व करत है
type: docs
weight: 2770
url: /hi/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

EXIF मेटाडेटा पैकेज में GPS मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | का एक नया उदाहरण प्रारंभ करता है[`ExifGpsPackage`](../exifgpspackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | में संदर्भ के आधार पर ऊंचाई प्राप्त या सेट करता है[`AltitudeRef`](./altituderef) . संदर्भ इकाई मीटर है। |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | संदर्भ ऊंचाई के रूप में उपयोग की जाने वाली ऊंचाई प्राप्त या सेट करता है। यदि संदर्भ समुद्र स्तर है और ऊंचाई समुद्र स्तर से ऊपर है, तो 0 दिया जाता है।[`Altitude`](./altitude) टैग. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | जीपीएस क्षेत्र के नाम की रिकॉर्डिंग करने वाली कैरेक्टर स्ट्रिंग को प्राप्त या सेट करता है। पहली बाइट उपयोग किए गए वर्ण कोड को इंगित करती है, और इसके बाद GPS क्षेत्र का नाम आता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | जीपीएस डीओपी (परिशुद्धता की डेटा डिग्री) प्राप्त या सेट करता है। |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | यूटीसी (समन्वित सार्वभौमिक समय) के सापेक्ष वर्ण स्ट्रिंग रिकॉर्डिंग तिथि और समय की जानकारी प्राप्त या सेट करता है। प्रारूप YYYY:MM:DD. है |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | जीपीएस असर को गंतव्य बिंदु पर ले जाता है या सेट करता है। मानों की सीमा 0.00 से 359.99. है |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | गंतव्य बिंदु पर असर देने के लिए उपयोग किए जाने वाले GPS संदर्भ को प्राप्त या सेट करता है। 'T' सही दिशा को दर्शाता है और 'M' चुंबकीय दिशा है। |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | जीपीएस दूरी को गंतव्य बिंदु पर सेट या सेट करता है। |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | गंतव्य बिंदु तक दूरी को व्यक्त करने के लिए उपयोग की जाने वाली जीपीएस इकाई को प्राप्त या सेट करता है। 'के', 'एम' और 'एन' किलोमीटर, मील और समुद्री मील का प्रतिनिधित्व करते हैं। |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | गंतव्य बिंदु का जीपीएस अक्षांश प्राप्त या सेट करता है। |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | GPS मान प्राप्त या सेट करता है जो इंगित करता है कि गंतव्य बिंदु का अक्षांश उत्तर या दक्षिण अक्षांश है या नहीं। ASCII मान 'N' उत्तर अक्षांश को इंगित करता है, और 'S' दक्षिण अक्षांश है। |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | गंतव्य बिंदु के GPS देशांतर को प्राप्त या सेट करता है। |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | GPS मान प्राप्त या सेट करता है जो इंगित करता है कि गंतव्य बिंदु का देशांतर पूर्व या पश्चिम देशांतर है। ASCII 'E' पूर्व देशांतर इंगित करता है, और 'W' पश्चिम देशांतर है। |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | एक GPS मान प्राप्त या सेट करता है जो इंगित करता है कि क्या अंतर सुधार GPS रिसीवर पर लागू किया गया है। |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | जीपीएस रिसीवर आंदोलन की दिशा प्राप्त या सेट करता है। |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | छवि को कैप्चर किए जाने पर जीपीएस दिशा प्राप्त या सेट करता है। मानों की सीमा 0.00 से 359.99. तक है |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | छवि को कैप्चर किए जाने पर दिशा देने के लिए GPS संदर्भ प्राप्त या सेट करता है। 'T' वास्तविक दिशा को दर्शाता है और 'M' चुंबकीय दिशा है। |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | निर्दिष्ट आईडी के साथ TIFF टैग प्राप्त करता है। (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | GPS अक्षांश प्राप्त या सेट करता है। |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | एक जीपीएस मान प्राप्त या सेट करता है जो दर्शाता है कि अक्षांश उत्तर या दक्षिण अक्षांश है। |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | GPS देशांतर प्राप्त या सेट करता है। |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | एक GPS मान प्राप्त या सेट करता है जो दर्शाता है कि देशांतर पूर्व या पश्चिम देशांतर है। |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | GPS रिसीवर द्वारा उपयोग किए जाने वाले जियोडेटिक सर्वेक्षण डेटा को प्राप्त या सेट करता है। |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | GPS माप मोड प्राप्त या सेट करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | स्थान खोजने के लिए उपयोग की जाने वाली विधि का नाम रिकॉर्ड करने वाली वर्ण स्ट्रिंग प्राप्त या सेट करता है। पहला बाइट उपयोग किए गए वर्ण कोड को इंगित करता है, और इसके बाद विधि का नाम आता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | माप के लिए उपयोग किए जाने वाले जीपीएस उपग्रहों को प्राप्त या सेट करता है। इस टैग का उपयोग उपग्रहों की संख्या, उनकी आईडी संख्या, ऊंचाई के कोण, दिगंश, एसएनआर और एएससीआईआई संकेतन में अन्य जानकारी का वर्णन करने के लिए किया जा सकता है। प्रारूप not निर्दिष्ट नहीं है। यदि GPS रिसीवर माप लेने में अक्षम है, तो टैग का मान NULL. पर सेट किया जाएगा |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | जीपीएस रिसीवर की गति को प्राप्त या सेट करता है। |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | जीपीएस रिसीवर गति की गति को व्यक्त करने के लिए उपयोग की जाने वाली इकाई को प्राप्त या सेट करता है। 'के' 'एम' और 'एन' किलोमीटर प्रति घंटे, मील प्रति घंटे और समुद्री मील का प्रतिनिधित्व करता है। |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | छवि रिकॉर्ड होने पर GPS रिसीवर की स्थिति प्राप्त या सेट करता है। |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | यूटीसी (समन्वित सार्वभौमिक समय) के रूप में समय प्राप्त या सेट करता है। |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | जीपीएस रिसीवर आंदोलन की दिशा देने के लिए संदर्भ प्राप्त या सेट करता है। 'टी' सही दिशा को दर्शाता है और 'एम' चुंबकीय दिशा है। |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | GPS IFD. का संस्करण प्राप्त या सेट करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | पैकेज में संग्रहीत सभी टीआईएफएफ टैग हटा देता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | निर्दिष्ट आईडी के साथ संपत्ति को हटाता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | निर्दिष्ट टैग जोड़ता या प्रतिस्थापित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | पैकेज से एक सूची बनाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [EXIF मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### यह सभी देखें

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
