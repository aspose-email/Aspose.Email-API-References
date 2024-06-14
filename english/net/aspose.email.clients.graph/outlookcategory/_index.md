---
title: Class OutlookCategory
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.OutlookCategory class. Represents a category by which a user can group Outlook items such as messages and events. The user defines categories in a master list and can apply one or more of these userdefined categories to an item. https//docs.microsoft.com/enus/graph/api/resources/outlookcategoryviewgraphrest1.0
type: docs
weight: 16100
url: /net/aspose.email.clients.graph/outlookcategory/
---
## OutlookCategory class

Represents a category by which a user can group Outlook items such as messages and events. The user defines categories in a master list, and can apply one or more of these user-defined categories to an item. https://docs.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0

```csharp
public class OutlookCategory
```

## Constructors

| Name | Description |
| --- | --- |
| [OutlookCategory](outlookcategory/#constructor)() | Initializes a new instance of the `OutlookCategory` class. |
| [OutlookCategory](outlookcategory/#constructor_1)(string, CategoryPreset) | Initializes a new instance of the `OutlookCategory` class. |
| [OutlookCategory](outlookcategory/#constructor_2)(string, string, CategoryPreset) | Initializes a new instance of the `OutlookCategory` class. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.email.clients.graph/outlookcategory/color/) { get; set; } | String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. The possible values for color are pre-set constants such as None, preset0 and preset1. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in. |
| [DisplayName](../../aspose.email.clients.graph/outlookcategory/displayname/) { get; set; } | A unique name that identifies a category in the user's mailbox. After a category is created, the name cannot be changed. |
| [Id](../../aspose.email.clients.graph/outlookcategory/id/) { get; set; } | Category identifier |
| [Preset](../../aspose.email.clients.graph/outlookcategory/preset/) { get; set; } | A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email.clients.graph/outlookcategory/tostring/)() | Returns a string that represents the current object. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


