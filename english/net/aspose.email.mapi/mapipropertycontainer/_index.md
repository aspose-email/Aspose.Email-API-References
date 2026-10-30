---
title: Class MapiPropertyContainer
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiPropertyContainer class. The base class of the objects that consist of MAPI properties messages attachments and recipients
type: docs
weight: 17420
url: /net/aspose.email.mapi/mapipropertycontainer/
---
## MapiPropertyContainer class

The base class of the objects that consist of MAPI properties: messages, attachments and recipients.

```csharp
public class MapiPropertyContainer
```

## Properties

| Name | Description |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty/)(PropertyDescriptor) | Gets a MAPI property by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/#getpropertystring)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/#getpropertystring_1)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/#setproperty)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/#setproperty_1)(PropertyDescriptor, object) | Sets the value of a MAPI property, creating the property if needed. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/#trygetpropertystring_2)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/#trygetpropertystring_3)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/#trygetpropertystring)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/#trygetpropertystring_1)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |

## Remarks

Properties are read and written either by tag, with the constants of [`MapiPropertyTag`](../mapipropertytag/), or by descriptor, with the descriptors of [`KnownPropertyList`](../knownpropertylist/). Descriptors also cover named properties, which have no fixed tag.

## Examples

This example reads properties by tag and by descriptor, and adds a custom named property.

[C#]

```csharp
var msg = MapiMessage.Load("message.msg");

// by tag
string subject = msg.GetPropertyString(MapiPropertyTag.PR_SUBJECT);
DateTime? delivered = msg.GetPropertyDateTime(MapiPropertyTag.PR_MESSAGE_DELIVERY_TIME);

// by descriptor; works for named properties too
MapiProperty importance = msg.GetProperty(KnownPropertyList.Importance);

// a custom named property in the PS_PUBLIC_STRINGS property set
var projectCode = new PidNamePropertyDescriptor("ProjectCode", PropertyDataType.String,
    KnownPropertySets.PublicStrings);
msg.SetProperty(projectCode, "PRJ-42");
msg.Save("message-with-code.msg");
```

[Visual Basic]

```csharp
Dim msg = MapiMessage.Load("message.msg")

' by tag
Dim subject As String = msg.GetPropertyString(MapiPropertyTag.PR_SUBJECT)
Dim delivered As DateTime? = msg.GetPropertyDateTime(MapiPropertyTag.PR_MESSAGE_DELIVERY_TIME)

' by descriptor; works for named properties too
Dim importance As MapiProperty = msg.GetProperty(KnownPropertyList.Importance)

' a custom named property in the PS_PUBLIC_STRINGS property set
Dim projectCode = New PidNamePropertyDescriptor("ProjectCode", PropertyDataType.String,
    KnownPropertySets.PublicStrings)
msg.SetProperty(projectCode, "PRJ-42")
msg.Save("message-with-code.msg")
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


