---
title: IIptc
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents base operations intended to work with IPTC metadata.
type: docs
weight: 358
url: /nodejs-java/com.groupdocs.metadata.core/iiptc/
---```
public interface IIptc
```

Represents base operations intended to work with IPTC metadata. Please find more information at  [http://en.wikipedia.org/wiki/International\_Press\_Telecommunications\_Council][http_en.wikipedia.org_wiki_International_Press_Telecommunications_Council] .

**Learn more**

 *  [Working with IPTC IIM metadata][]

This example shows how to read basic IPTC metadata properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.JpegWithIptc)) {
>      IIptc root = (IIptc) metadata.getRootPackage();
>      if (root.getIptcPackage() != null) {
>          if (root.getIptcPackage().getEnvelopeRecord() != null) {
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getDateSent());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getDestination());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getFileFormat());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getFileFormatVersion());
>              // ...
>          }
>          if (root.getIptcPackage().getApplicationRecord() != null) {
>              System.out.println(root.getIptcPackage().getApplicationRecord().getHeadline());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getByLine());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getByLineTitle());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getCaptionAbstract());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getCity());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getDateCreated());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getReleaseDate());
>              // ...
>          }
>      }
>  }
>  
> ```
> ```


[http_en.wikipedia.org_wiki_International_Press_Telecommunications_Council]: http://en.wikipedia.org/wiki/International_Press_Telecommunications_Council
[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Methods

| Method | Description |
| --- | --- |
| [getIptcPackage()](#getIptcPackage--) | Gets the IPTC metadata package associated with the file. |
| [setIptcPackage(IptcRecordSet value)](#setIptcPackage-com.groupdocs.metadata.core.IptcRecordSet-) | Sets the IPTC metadata package associated with the file. |
### getIptcPackage() {#getIptcPackage--}
```
public abstract IptcRecordSet getIptcPackage()
```


Gets the IPTC metadata package associated with the file.

**Returns:**
[IptcRecordSet](../../com.groupdocs.metadata.core/iptcrecordset) - The IPTC metadata package associated with the file.
### setIptcPackage(IptcRecordSet value) {#setIptcPackage-com.groupdocs.metadata.core.IptcRecordSet-}
```
public abstract void setIptcPackage(IptcRecordSet value)
```


Sets the IPTC metadata package associated with the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IptcRecordSet](../../com.groupdocs.metadata.core/iptcrecordset) | The IPTC metadata package associated with the file. |

