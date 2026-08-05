---
title: "Aspose::Email::Mapi::MapiNote class"
linktitle: "MapiNote"
articleTitle: "MapiNote"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI note (\"sticky note\") item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapinote/
---

## MapiNote class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI note ("sticky note") item.

This class serves as a wrapper for MapiMessage to simplify the process of handling note information from MAPI properties. It provides a more intuitive interface for accessing and manipulating note data within the MAPI message.

The following example demonstrates how to get a MapiNote object from a MapiMessage .

```csharp
var msg = MapiMessage.Load("note.msg");
 
// Check if the loaded message is a supported note type
if (msg.SupportedType == MapiItemType.Note)
{
 // Convert the MAPI message to a MapiNote object
    var mapiNote = (MapiNote)msg.ToMapiMessageItem();
 
 // Display some note info
    Console.WriteLine(mapiNote.Color);
    Console.WriteLine(mapiNote.Body);
}
```

```vb
Dim msg = MapiMessage.Load("note.msg")
 
' Check if the loaded message is a supported note type
If msg.SupportedType = MapiItemType.Note Then
    ' Convert the MAPI message to a MapiNote object
    Dim mapiNote = DirectCast(msg.ToMapiMessageItem(), MapiNote)
 
 ' Display some note info
    Console.WriteLine(mapiNote.Color)
    Console.WriteLine(mapiNote.Body)
End If
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiNote (3 overloads)](./mapinote/) | Initializes a new instance of the MapiNote class. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts note object to mapi message |
| [get_Color](./get_color/) | Gets the suggested background color of the Note object |
| [get_CreationDate](./get_creationdate/) | Gets the creation date of note |
| [get_Height](./get_height/) | Gets height of the visible message window in pixels |
| [get_Width](./get_width/) | Gets width of the visible message window in pixels |
| [get_XPosition](./get_xposition/) | Gets the distance, in pixels, from the left edge of the screen that a user interface displays a Note object |
| [get_YPosition](./get_yposition/) | Gets the distance, in pixels, from the top edge of the screen that a user interface displays a Note object |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (2 overloads)](./save/) | Saves this MapiNote to the given stream using specified format. |
| [set_Color](./set_color/) | Sets the suggested background color of the Note object |
| [set_CreationDate](./set_creationdate/) | Sets the creation date of note |
| [set_Height](./set_height/) | Sets height of the visible message window in pixels |
| [set_Width](./set_width/) | Sets width of the visible message window in pixels |
| [set_XPosition](./set_xposition/) | Sets the distance, in pixels, from the left edge of the screen that a user interface displays a Note object |
| [set_YPosition](./set_yposition/) | Sets the distance, in pixels, from the top edge of the screen that a user interface displays a Note object |

