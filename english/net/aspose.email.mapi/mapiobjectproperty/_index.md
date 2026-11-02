---
title: Class MapiObjectProperty
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiObjectProperty class. An object embedded in an attachment such as an attached Outlook message or an OLE document
type: docs
weight: 17380
url: /net/aspose.email.mapi/mapiobjectproperty/
---
## MapiObjectProperty class

An object embedded in an attachment, such as an attached Outlook message or an OLE document.

```csharp
public class MapiObjectProperty : MapiProperty
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data/) { get; } | Gets the value of the property as bytes. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype/) { get; } | Gets the data type of the property: the low-order 16 bits of [`Tag`](../mapiproperty/tag/). |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor/) { get; } | Gets the descriptor of the property. |
| [DocumentName](../../aspose.email.mapi/mapiobjectproperty/documentname/) { get; } | Gets the name of the embedded document. |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier/) { get; } | Gets the property ID: the high-order 16 bits of [`Tag`](../mapiproperty/tag/). |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed/) { get; } | Gets a value indicating whether the property is a named property. |
| [IsOutlookMessage](../../aspose.email.mapi/mapiobjectproperty/isoutlookmessage/) { get; } | Gets a value indicating whether the object is an Outlook message. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned/) { get; set; } | Gets or sets a value indicating whether the value is a signed number. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries/) { get; } | Gets the values of a multi-valued property. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name/) { get; } | Gets the name of the property. |
| [OleDocumentFormat](../../aspose.email.mapi/mapiobjectproperty/oledocumentformat/) { get; } | Gets the format of the embedded OLE document, such as a Word document or an Excel worksheet. |
| [Properties](../../aspose.email.mapi/mapiobjectproperty/properties/) { get; } | Gets the MAPI properties of the embedded object. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname/) { get; } | Gets the name of the tag of the property, such as `PR_SUBJECT`, if it is known. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag/) { get; } | Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean/)() | Gets the value as a Boolean. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency/)() | Gets the value of a currency property. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime/)() | Gets the value of a date and time (PT_SYSTIME) property. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble/)() | Gets the value as a 64-bit floating-point number. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat/)() | Gets the value as a 32-bit floating-point number. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate/)() | Gets the value of a floating date (PT_APPTIME) property: a number of days since December 30, 1899. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid/)() | Gets the value as a GUID. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32/)() | Gets the value as a 32-bit integer. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong/)() | Gets the value as a 64-bit integer. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort/)() | Gets the value as a 16-bit integer. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)() | Gets the value as a string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)(int) | Gets the value as a string, decoding an ANSI string with the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue/)() | Gets the value as an object of the .NET type that matches the data type. |
| [ToMapiMessage](../../aspose.email.mapi/mapiobjectproperty/tomapimessage/)() | Gets the embedded Outlook message. |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring/)() | Returns a string that represents the property. |

## Remarks

Returned by [`ObjectData`](../mapiattachment/objectdata/). For an attached message [`IsOutlookMessage`](./isoutlookmessage/) is `true` and [`ToMapiMessage`](./tomapimessage/) returns it.

### See Also

* class [MapiProperty](../mapiproperty/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


