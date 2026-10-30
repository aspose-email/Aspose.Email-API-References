---
title: Class ItemMovedEventArgs
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.ItemMovedEventArgs class. Provides data for the ItemMoved event
type: docs
weight: 19150
url: /net/aspose.email.storage.pst/itemmovedeventargs/
---
## ItemMovedEventArgs class

Provides data for the [`ItemMoved`](../folderinfo/itemmoved/) event.

```csharp
public class ItemMovedEventArgs : EventArgs
```

## Constructors

| Name | Description |
| --- | --- |
| [ItemMovedEventArgs](itemmovedeventargs/#constructor)(FolderInfo) | Initializes a new instance of the `ItemMovedEventArgs` class for a moved folder. |
| [ItemMovedEventArgs](itemmovedeventargs/#constructor_1)(MessageInfo) | Initializes a new instance of the `ItemMovedEventArgs` class for a moved message. |
| [ItemMovedEventArgs](itemmovedeventargs/#constructor_2)(string, MapiPropertyCollection) | Initializes a new instance of the `ItemMovedEventArgs` class for an item given by its entry ID and properties. |

## Properties

| Name | Description |
| --- | --- |
| [DestinationFolder](../../aspose.email.storage.pst/itemmovedeventargs/destinationfolder/) { get; } | Gets the folder the item was moved to. |
| [EntryId](../../aspose.email.storage.pst/itemmovedeventargs/entryid/) { get; } | Gets the entry ID of the moved item. |
| [IsFolder](../../aspose.email.storage.pst/itemmovedeventargs/isfolder/) { get; } | Gets a value indicating whether the moved item is a folder. |
| [IsMessage](../../aspose.email.storage.pst/itemmovedeventargs/ismessage/) { get; } | Gets a value indicating whether the moved item is a message. |
| [ItemProperties](../../aspose.email.storage.pst/itemmovedeventargs/itemproperties/) { get; } | Gets the properties of the moved item. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


