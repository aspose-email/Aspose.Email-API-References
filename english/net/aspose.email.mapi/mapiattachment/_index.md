---
title: MapiAttachment
second_title: Aspose.Email for .NET API Reference
description: Represents the attachment in the Email message.
type: docs
weight: 17890
url: /net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Represents the attachment in the E-mail message.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Properties

| Name | Description |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Gets or sets binary attachment data. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Gets the code page. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Gets the content. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Gets the display name of the ole object in an attachment. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Gets a filename extension that indicates the document type of an attachment. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Gets an attachment's base filename and extension, excluding path. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | The item id, uses with a server |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Gets an attachment's long filename and extension, excluding path. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Gets formatting information about a Multipurpose Internet Mail Extensions (MIME) attachment. |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Gets the named properties of message. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Gets an attachment object typically accessed through the OLE IStorage interface. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Gets the property stream. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Gets the sub storages. |

## Methods

| Name | Description |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Gets the string value of the property specified by tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Save attachment content. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Save attachment content. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Sets MAPI property. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |

### See Also

* class [MapiPropertyContainer](../mapipropertycontainer)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
