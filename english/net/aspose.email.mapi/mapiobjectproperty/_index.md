---
title: Class MapiObjectProperty
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiObjectProperty class. Represents a Custom object included in Outlook Message documents
type: docs
weight: 18700
url: /net/aspose.email.mapi/mapiobjectproperty/
---
## MapiObjectProperty class

Represents a Custom object included in Outlook Message documents.

```csharp
public class MapiObjectProperty : MapiProperty
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data/) { get; } | Gets the binary data. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype/) { get; } | Gets the data type. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor/) { get; } | Gets descriptor of MAPI property |
| [DocumentName](../../aspose.email.mapi/mapiobjectproperty/documentname/) { get; } | Gets the document name. |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier/) { get; } | Gets the indifier. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed/) { get; } | Indicates whether the property is a named property. |
| [IsOutlookMessage](../../aspose.email.mapi/mapiobjectproperty/isoutlookmessage/) { get; } | Indicates whether the object property is an embedded outlook message. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned/) { get; set; } | Indicates whether the binary data is signed. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries/) { get; } | Gets the MV entries list. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name/) { get; } | Gets the name. |
| [OleDocumentFormat](../../aspose.email.mapi/mapiobjectproperty/oledocumentformat/) { get; } | Gets the Ole format type. |
| [Properties](../../aspose.email.mapi/mapiobjectproperty/properties/) { get; } | Gets a collection of MAPI properties. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname/) { get; } | Gets the PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag/) { get; } | Gets the tag. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean/)() | Gets the first bytes of the binary data as boolean. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency/)() | Gets the Currency as string using the specified code page. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime/)() | Gets the first bytes of the binary data as datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble/)() | Gets the bytes of the binary data as double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat/)() | Gets the bytes of the binary data as float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate/)() | Gets the bytes of the binary data as DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid/)() | Gets the bytes of the binary data as Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32/)() | Gets the first 4 bytes of the binary data as int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong/)() | Gets the first 8 bytes of the binary data as long. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort/)() | Gets the first 2 bytes of the binary data as short. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)() | Gets the binary data as string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)(int) | Gets the binary data as string using the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue/)() | Gets value as object |
| [ToMapiMessage](../../aspose.email.mapi/mapiobjectproperty/tomapimessage/)() | Creates the MapiMessage from object data. |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring/)() | Returns a String that represents the current Object. |

### See Also

* class [MapiProperty](../mapiproperty/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


