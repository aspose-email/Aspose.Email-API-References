---
title: Class MapiNote
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiNote class. Represents a MAPI note sticky note item
type: docs
weight: 18690
url: /net/aspose.email.mapi/mapinote/
---
## MapiNote class

Represents a MAPI note ("sticky note") item.

```csharp
public sealed class MapiNote : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiNote](mapinote/#constructor)() | Initializes a new instance of the `MapiNote` class. |
| [MapiNote](mapinote/#constructor_1)(string, string) | Initializes a new instance of the `MapiNote` class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments/) { get; } | Gets the attachments in the message. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf/) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the type of the body. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Contains keywords or categories for the message object. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page. |
| [Color](../../aspose.email.mapi/mapinote/color/) { get; set; } | Gets or sets the suggested background color of the Note object |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Contains the names of the companies that are associated with an item. |
| [CreationDate](../../aspose.email.mapi/mapinote/creationdate/) { get; set; } | Gets or sets the creation date of note |
| [Height](../../aspose.email.mapi/mapinote/height/) { get; set; } | Gets or sets height of the visible message window in pixels |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | The item id, uses with a server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Contains the mileage information that is associated with an item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the named property mapping. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets the recipients of the message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets the Sensitivity. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the supported item type. |
| [Width](../../aspose.email.mapi/mapinote/width/) { get; set; } | Gets or sets width of the visible message window in pixels |
| [XPosition](../../aspose.email.mapi/mapinote/xposition/) { get; set; } | Gets or sets the distance, in pixels, from the left edge of the screen that a user interface displays a Note object |
| [YPosition](../../aspose.email.mapi/mapinote/yposition/) { get; set; } | Gets or sets the distance, in pixels, from the top edge of the screen that a user interface displays a Note object |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the string value of the property specified by tag. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapinote/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapinote/save/#save)(Stream, NoteSaveFormat) | Saves this `MapiNote` to the given stream using specified format. |
| [Save](../../aspose.email.mapi/mapinote/save/#save_1)(string, NoteSaveFormat) | Saves this `MapiNote` into file using specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the content of the body. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the message flags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets MAPI property. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |

## Remarks

This class serves as a wrapper for [`MapiMessage`](../mapimessage/) to simplify the process of handling note information from MAPI properties. It provides a more intuitive interface for accessing and manipulating note data within the MAPI message.

## Examples

The following example demonstrates how to get a `MapiNote` object from a [`MapiMessage`](../mapimessage/).

[C#]

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

[Visual Basic]

```csharp
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

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


