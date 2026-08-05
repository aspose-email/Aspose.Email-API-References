---
title: "Aspose::Email::Mapi::MapiDistributionList class"
linktitle: "MapiDistributionList"
articleTitle: "MapiDistributionList"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI distribution list item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapidistributionlist/
---

## MapiDistributionList class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI distribution list item.

This class serves as a wrapper for MapiMessage to simplify the process of handling distribution list information from MAPI properties. It provides a more intuitive interface for accessing and manipulating distribution list data within the MAPI message.

The following example demonstrates how to get a MapiDistributionList object from a MapiMessage .

```csharp
var msg = MapiMessage.Load("distributionList.msg");
 
// Check if the loaded message is a supported distribution list type
if (msg.SupportedType == MapiItemType.DistList)
{
 // Convert the MAPI message to a MapiDistributionList object
    var mapiDistributionList = (MapiDistributionList)msg.ToMapiMessageItem();
 
 // Display some distribution list info
    Console.WriteLine(mapiDistributionList.DisplayName);
    Console.WriteLine(mapiDistributionList.Members.Count);
}
```

```vb
Dim msg = MapiMessage.Load("distributionList.msg")
 
' Check if the loaded message is a supported distribution list type
If msg.SupportedType = MapiItemType.DistList Then
    ' Convert the MAPI message to a MapiDistributionList object
    Dim mapiDistributionList = DirectCast(msg.ToMapiMessageItem(), MapiDistributionList)
 
 ' Display some distribution list info
    Console.WriteLine(mapiDistributionList.DisplayName)
    Console.WriteLine(mapiDistributionList.Members.Count)
End If
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiDistributionList (3 overloads)](./mapidistributionlist/) | Initializes a new instance of the MapiDistributionList class. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts contact object to mapi message |
| [FromVCF (2 overloads)](./fromvcf/) | Loads MapiDistributionList from VCF stream. |
| [get_DisplayName](./get_displayname/) | Gets the user-visible name of the personal distribution list. |
| [get_Members](./get_members/) | Gets the list of the members of the personal distribution list. |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (4 overloads)](./save/) | Saves the specified stream. |
| [set_DisplayName](./set_displayname/) | Sets the user-visible name of the personal distribution list. |

