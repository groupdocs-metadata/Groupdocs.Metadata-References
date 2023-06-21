---
title: ProjectManagementRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package intended to work with metadata in a project management format.
type: docs
weight: 206
url: /java/com.groupdocs.metadata.core/projectmanagementrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage
```
public class ProjectManagementRootPackage extends DocumentRootPackage<ProjectManagementPackage>
```

Represents the root package intended to work with metadata in a project management format.

**Learn more**

 *  [Working with metadata in ProjectManagement formats][]

This code sample demonstrates how to extract built-in properties of a ProjectManagement document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputMpp)) {
>      ProjectManagementRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getAuthor());
>      System.out.println(root.getDocumentProperties().getCreationDate());
>      System.out.println(root.getDocumentProperties().getCompany());
>      System.out.println(root.getDocumentProperties().getCategory());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      System.out.println(root.getDocumentProperties().getRevision());
>      System.out.println(root.getDocumentProperties().getSubject());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in ProjectManagement formats]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+ProjectManagement+formats
