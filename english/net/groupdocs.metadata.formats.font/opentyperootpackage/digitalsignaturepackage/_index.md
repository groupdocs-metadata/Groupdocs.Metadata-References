---
title: DigitalSignaturePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets the digital signature metadata package.
type: docs
weight: 10
url: /net/groupdocs.metadata.formats.font/opentyperootpackage/digitalsignaturepackage/
---
## OpenTypeRootPackage.DigitalSignaturePackage property

Gets the digital signature metadata package.

```csharp
public CmsPackage DigitalSignaturePackage { get; }
```

### Property Value

The digital signature metadata package.

### Remarks

**Learn more**

* [Working with OpenType fonts](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Examples

This code snippet demonstrates how to extract digital signatures associated with an OpenType font.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputTtf))
    {
        var root = metadata.GetRootPackage<OpenTypeRootPackage>();

        if (root.DigitalSignaturePackage != null)
        {
            Console.WriteLine(root.DigitalSignaturePackage.Flags);
            foreach (var signature in root.DigitalSignaturePackage.Signatures)
            {
                Console.WriteLine(signature.SignTime);
                if (signature.DigestAlgorithms != null)
                {
                    foreach (var signatureDigestAlgorithm in signature.DigestAlgorithms)
                    {
                        PrintOid(signatureDigestAlgorithm);
                    }
                }
                if (signature.EncapsulatedContent != null)
                {
                    PrintOid(signature.EncapsulatedContent.ContentType);
                    Console.WriteLine(signature.EncapsulatedContent.ContentRawData.Length);
                }
                if (signature.Certificates != null)
                {
                    foreach (var certificate in signature.Certificates)
                    {
                        Console.WriteLine(certificate.NotAfter);
                        Console.WriteLine(certificate.NotBefore);
                        Console.WriteLine(certificate.RawData.Length);
                    }
                }
                if (signature.Signers != null)
                {
                    foreach (var signerInfoEntry in signature.Signers)
                    {
                        Console.WriteLine(signerInfoEntry.SignatureValue);
                        PrintOid(signerInfoEntry.DigestAlgorithm);
                        PrintOid(signerInfoEntry.SignatureAlgorithm);
                        Console.WriteLine(signerInfoEntry.SigningTime);
                        PrintAttributes(signerInfoEntry.SignedAttributes);
                        PrintAttributes(signerInfoEntry.UnsignedAttributes);
                    }
                }
            }
        }
    }
}

private static void PrintOid(Oid oid)
{
    // Display the property name and value of OID
    if (oid != null)
    {
        Console.WriteLine(oid.FriendlyName);
        Console.WriteLine(oid.Value);
    }
}

private static void PrintAttributes(CmsAttribute[] attributes)
{
    //Display the CmsAttributes of an OID
    if (attributes != null)
    {
        foreach (CmsAttribute attribute in attributes)
        {
            PrintOid(attribute.Oid);
            Console.WriteLine(attribute.Value);
        }
    }
}
```

### See Also

* class [CmsPackage](../../../groupdocs.metadata.standards.pkcs/cmspackage)
* class [OpenTypeRootPackage](../../opentyperootpackage)
* namespace [GroupDocs.Metadata.Formats.Font](../../../groupdocs.metadata.formats.font)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
