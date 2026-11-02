---
title: Interface INamedPropertyTagProvider
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.INamedPropertyTagProvider interface. Provides property tags for named properties so that a named property can be stored in a property collection
type: docs
weight: 16620
url: /net/aspose.email.mapi/inamedpropertytagprovider/
---
## INamedPropertyTagProvider interface

Provides property tags for named properties, so that a named property can be stored in a property collection.

```csharp
public interface INamedPropertyTagProvider
```

## Methods

| Name | Description |
| --- | --- |
| [GenerateNamedPropertyTag](../../aspose.email.mapi/inamedpropertytagprovider/generatenamedpropertytag/#generatenamedpropertytag_2)(long) | Generates a tag for a new named property of the specified type. |
| [GenerateNamedPropertyTag](../../aspose.email.mapi/inamedpropertytagprovider/generatenamedpropertytag/#generatenamedpropertytag)(MapiPropertyType) | Generates a tag for a new named property of the specified type. |
| [GenerateNamedPropertyTag](../../aspose.email.mapi/inamedpropertytagprovider/generatenamedpropertytag/#generatenamedpropertytag_1)(PropertyDataType) | Generates a tag for a new named property of the specified type. |
| [GetTagFromNamedProperty](../../aspose.email.mapi/inamedpropertytagprovider/gettagfromnamedproperty/#gettagfromnamedproperty)(long) | Gets the tag under which a named property with a numeric ID is stored. |
| [GetTagFromNamedProperty](../../aspose.email.mapi/inamedpropertytagprovider/gettagfromnamedproperty/#gettagfromnamedproperty_1)(string) | Gets the tag under which a named property with a string name is stored. |

## Remarks

A named property is identified by a property set GUID and a name or numeric ID; inside a message it is stored under a tag from the range `0x8000`–`0xFFFE`, assigned by the message. [`MapiPropertyCollection`](../mapipropertycollection/) implements this interface.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


