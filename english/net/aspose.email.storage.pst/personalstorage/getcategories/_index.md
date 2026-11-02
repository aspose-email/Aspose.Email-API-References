---
title: PersonalStorage.GetCategories
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Gets the categories used in the PST each with its name and color
type: docs
weight: 280
url: /net/aspose.email.storage.pst/personalstorage/getcategories/
---
## PersonalStorage.GetCategories method

Gets the categories used in the PST, each with its name and color.

```csharp
public List<PstItemCategory> GetCategories()
```

### Return Value

The categories. The list is empty if no categories are found.

## Examples

This example lists the categories of a PST with their colors.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    foreach (var category in pst.GetCategories())
    {
        Console.WriteLine($"{category.Name}: {category.Color}");
    }
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    For Each category As PstItemCategory In pst.GetCategories()
        Console.WriteLine($"{category.Name}: {category.Color}")
    Next
End Using
```

### See Also

* class [PstItemCategory](../../pstitemcategory/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


