---
title: Class MapiNote
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiNote class. Represents a MAPI note sticky note item
type: docs
weight: 17370
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
| [MapiNote](mapinote/#constructor_1)(string, string) | Initializes a new instance of the `MapiNote` class with a subject and a body. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments/) { get; } | Gets the attachments of the item. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Gets or sets the billing information of the item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the body of the item as HTML, converted from [`BodyRtf`](../mapimessageitembase/bodyrtf/); an empty string when there is no RTF body. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the body of the item in RTF format. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Gets or sets the categories of the item. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Color](../../aspose.email.mapi/mapinote/color/) { get; set; } | Gets or sets the background color of the note. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Gets or sets the names of the companies associated with the item. |
| [CreationDate](../../aspose.email.mapi/mapinote/creationdate/) { get; set; } | Gets or sets the date and time the note was created. |
| [Height](../../aspose.email.mapi/mapinote/height/) { get; set; } | Gets or sets the height of the note window, in pixels. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | Gets the identifier of the item on the mail server, for items obtained from a server; `null` otherwise. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets or sets the message class of the item, such as `IPM.Note` for an e-mail message. The class determines the type of the item. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Gets or sets the mileage information of the item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of the item. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the mapping between the named properties and the tags they are stored under. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream of the item. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets or sets the recipients of the item. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets or sets the sensitivity of the item: normal, personal, private or confidential. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets the prefix of the subject, such as `RE: ` or `FW: `. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub-storages of the item. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |
| [Width](../../aspose.email.mapi/mapinote/width/) { get; set; } | Gets or sets the width of the note window, in pixels. |
| [XPosition](../../aspose.email.mapi/mapinote/xposition/) { get; set; } | Gets or sets the distance of the note window from the left edge of the screen, in pixels. |
| [YPosition](../../aspose.email.mapi/mapinote/yposition/) { get; set; } | Gets or sets the distance of the note window from the top edge of the screen, in pixels. |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.mapi/mapinote/load/#load)(Stream) | Loads a `MapiNote` from the specified stream. |
| static [Load](../../aspose.email.mapi/mapinote/load/#load_1)(string) | Loads a `MapiNote` from the specified file. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Releases the resources used by the item. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the item by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapinote/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Removes a property from the item, including its named-property mapping. |
| [Save](../../aspose.email.mapi/mapinote/save/#save)(Stream) | Saves this `MapiNote` to the given stream. |
| [Save](../../aspose.email.mapi/mapinote/save/#save_2)(string) | Saves this `MapiNote` to the given file. |
| [Save](../../aspose.email.mapi/mapinote/save/#save_1)(Stream, NoteSaveFormat) | Saves the note to a stream in the specified format. Only MSG is supported. |
| [Save](../../aspose.email.mapi/mapinote/save/#save_3)(string, NoteSaveFormat) | Saves the note to a file in the specified format. Only MSG is supported. |
| [SaveAsync](../../aspose.email.mapi/mapinote/saveasync/#saveasync)(Stream, NoteSaveFormat, CancellationToken) | Saves this `MapiNote` to the given stream using specified format asynchronously. The supported save format is MSG. |
| [SaveAsync](../../aspose.email.mapi/mapinote/saveasync/#saveasync_1)(string, NoteSaveFormat, CancellationToken) | Saves this `MapiNote` into file using specified format asynchronously. The supported save format is MSG. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the body of the item in the specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the body of the item in the specified format, optionally compressing it. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Sets the body of the item in RTF format, optionally compressing it. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the flags of the message, such as read or unsent. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property of the item. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| static [LoadAsync](../../aspose.email.mapi/mapinote/loadasync/#loadasync)(Stream, CancellationToken) | Loads a `MapiNote` from the specified stream asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapinote/loadasync/#loadasync_1)(string, CancellationToken) | Loads a `MapiNote` from the specified file asynchronously. |

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


