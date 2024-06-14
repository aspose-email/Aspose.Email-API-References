---
title: Class MapiJournal
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiJournal class. Represents the Outlook Journal object
type: docs
weight: 18530
url: /net/aspose.email.mapi/mapijournal/
---
## MapiJournal class

Represents the Outlook Journal object.

```csharp
public sealed class MapiJournal : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiJournal](mapijournal/#constructor)() | Initializes a new instance of the `MapiJournal` class. |
| [MapiJournal](mapijournal/#constructor_1)(string, string, string, string) | Initializes a new instance of the `MapiJournal` class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments/) { get; } | Gets the attachments in the message. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf/) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the type of the body. |
| [BriefDescription](../../aspose.email.mapi/mapijournal/briefdescription/) { get; set; } | Gets or sets the brief description of activity that is being recorded. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Contains keywords or categories for the message object. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Contains the names of the companies that are associated with an item. |
| [Description](../../aspose.email.mapi/mapijournal/description/) { get; set; } | Gets or sets the description of activity that is being recorded. |
| [DocumentStatus](../../aspose.email.mapi/mapijournal/documentstatus/) { get; set; } | Gets or sets the status of document. |
| [Duration](../../aspose.email.mapi/mapijournal/duration/) { get; } | Gets the duration of the activity. |
| [EndTime](../../aspose.email.mapi/mapijournal/endtime/) { get; set; } | Gets or sets the time at which the activity ended. |
| [Flags](../../aspose.email.mapi/mapijournal/flags/) { get; set; } | Gets or sets a flags that contains metadata about the Journal object. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | The item id, uses with a server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Contains the mileage information that is associated with an item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the named property mapping. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets the recipients of the message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets the Sensitivity. |
| [StartTime](../../aspose.email.mapi/mapijournal/starttime/) { get; set; } | Gets or sets the time at which the activity began. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the supported item type. |

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
| [GetUnderlyingMessage](../../aspose.email.mapi/mapijournal/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapijournal/save/#save)(Stream) | Saves the specified stream. |
| [Save](../../aspose.email.mapi/mapijournal/save/#save_1)(string) | Saves the specified file name. |
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

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


