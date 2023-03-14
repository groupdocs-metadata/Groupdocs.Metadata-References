---
title: DigitalSignaturePackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package de métadonnées de signature numérique.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata.formats.font/opentyperootpackage/digitalsignaturepackage/
---
## OpenTypeRootPackage.DigitalSignaturePackage property

Obtient le package de métadonnées de signature numérique.

```csharp
public CmsPackage DigitalSignaturePackage { get; }
```

### Valeur de la propriété

Le package de métadonnées de signature numérique.

### Remarques

**Apprendre encore plus**

* [Utilisation des polices OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Exemples

Cet extrait de code montre comment extraire les signatures numériques associées à une police OpenType.

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
    // Affiche le nom de la propriété et la valeur de l'OID
    if (oid != null)
    {
        Console.WriteLine(oid.FriendlyName);
        Console.WriteLine(oid.Value);
    }
}

private static void PrintAttributes(CmsAttribute[] attributes)
{
    //Affiche les CmsAttributes d'un OID
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

### Voir également

* class [CmsPackage](../../../groupdocs.metadata.standards.pkcs/cmspackage)
* class [OpenTypeRootPackage](../../opentyperootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Font](../../opentyperootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->