---
title: DigitalSignaturePackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Λαμβάνει το πακέτο μεταδεδομένων ψηφιακής υπογραφής.
type: docs
weight: 10
url: /el/net/groupdocs.metadata.formats.font/opentyperootpackage/digitalsignaturepackage/
---
## OpenTypeRootPackage.DigitalSignaturePackage property

Λαμβάνει το πακέτο μεταδεδομένων ψηφιακής υπογραφής.

```csharp
public CmsPackage DigitalSignaturePackage { get; }
```

### Αξία περιουσίας

Το πακέτο μεταδεδομένων ψηφιακής υπογραφής.

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με γραμματοσειρές OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Παραδείγματα

Αυτό το απόσπασμα κώδικα δείχνει πώς να εξαγάγετε ψηφιακές υπογραφές που σχετίζονται με μια γραμματοσειρά OpenType.

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
    // Εμφάνιση του ονόματος ιδιότητας και της τιμής του OID
    if (oid != null)
    {
        Console.WriteLine(oid.FriendlyName);
        Console.WriteLine(oid.Value);
    }
}

private static void PrintAttributes(CmsAttribute[] attributes)
{
    //Εμφάνιση των CmsAttributes ενός OID
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

### Δείτε επίσης

* class [CmsPackage](../../../groupdocs.metadata.standards.pkcs/cmspackage)
* class [OpenTypeRootPackage](../../opentyperootpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Font](../../opentyperootpackage)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
