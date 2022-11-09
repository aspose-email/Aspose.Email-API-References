---
title: OutlookCategory
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 190
url: /python-net/aspose.email.clients.graph/outlookcategory/
---

## OutlookCategory class

Represents a category by which a user can group Outlook items such as messages and events. <br/>            The user defines categories in a master list, and can apply one or more of these user-defined categories to an item.<br/>            https://docs.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0

The OutlookCategory type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|OutlookCategory()|Initializes a new instance of the [OutlookCategory](/python-net/aspose.email.clients.graph/outlookcategory/) class.|
|OutlookCategory(display_name, preset)|Initializes a new instance of the OutlookCategory class|
|OutlookCategory(item_id, display_name, preset)|Initializes a new instance of the OutlookCategory class|
## Properties
| Name | Description |
| :- | :- |
|id|Category identifier|
|display_name|A unique name that identifies a category in the user's mailbox. <br/>            After a category is created, the name cannot be changed.|
|color|String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors.<br/>            The possible values for color are pre-set constants such as None, preset0 and preset1. <br/>            Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.|
|preset|A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. <br/>            Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.|

### See Also

* namespace [aspose.email.clients.graph](/python-net/aspose.email.clients.graph/)
* assembly [Aspose.Email](/python-net/)

