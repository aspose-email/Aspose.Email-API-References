---
title: "Aspose::Email::Mapi::MapiJournal class"
linktitle: "MapiJournal"
articleTitle: "MapiJournal"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI journal item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapijournal/
---

## MapiJournal class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI journal item.

This class serves as a wrapper for MapiMessage to simplify the process of handling journal information from MAPI properties. It provides a more intuitive interface for accessing and manipulating journal data within the MAPI message.

The following example demonstrates how to get a MapiJournal object from a MapiMessage .

```csharp
var msg = MapiMessage.Load("journal.msg");
 
// Check if the loaded message is a supported journal type
if (msg.SupportedType == MapiItemType.Journal)
{
 // Convert the MAPI message to a MapiJournal object
    var mapiJournal = (MapiJournal)msg.ToMapiMessageItem();
 
 // Display some journal info
    Console.WriteLine(mapiJournal.StartTime);
    Console.WriteLine(mapiJournal.Description);
}
```

```vb
Dim msg = MapiMessage.Load("journal.msg")
 
' Check if the loaded message is a supported journal type
If msg.SupportedType = MapiItemType.Journal Then
    ' Convert the MAPI message to a MapiJournal object
    Dim mapiJournal = DirectCast(msg.ToMapiMessageItem(), MapiJournal)
 
 ' Display some journal info
    Console.WriteLine(mapiJournal.StartTime)
    Console.WriteLine(mapiJournal.Description)
End If
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiJournal (3 overloads)](./mapijournal/) | Initializes a new instance of the MapiJournal class. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts journal object to mapi message |
| [get_BriefDescription](./get_briefdescription/) | Gets the brief description of activity that is being recorded. |
| [get_Description](./get_description/) | Gets the description of activity that is being recorded. |
| [get_DocumentStatus](./get_documentstatus/) | Gets the status of document. |
| [get_Duration](./get_duration/) | Gets the duration of the activity. |
| [get_EndTime](./get_endtime/) | Gets the time at which the activity ended. |
| [get_Flags](./get_flags/) | Gets a flags that contains metadata about the Journal object. |
| [get_StartTime](./get_starttime/) | Gets the time at which the activity began. |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (2 overloads)](./save/) | Saves the specified stream. |
| [set_BriefDescription](./set_briefdescription/) | Sets the brief description of activity that is being recorded. |
| [set_Description](./set_description/) | Sets the description of activity that is being recorded. |
| [set_DocumentStatus](./set_documentstatus/) | Sets the status of document. |
| [set_EndTime](./set_endtime/) | Sets the time at which the activity ended. |
| [set_Flags](./set_flags/) | Sets a flags that contains metadata about the Journal object. |
| [set_StartTime](./set_starttime/) | Sets the time at which the activity began. |

