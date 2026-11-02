---
title: Class MapiPropertyCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiPropertyCollection class. The MAPI properties of a message attachment or recipient keyed by tag
type: docs
weight: 17410
url: /net/aspose.email.mapi/mapipropertycollection/
---
## MapiPropertyCollection class

The MAPI properties of a message, attachment or recipient, keyed by tag.

```csharp
public class MapiPropertyCollection : IDictionary<long, MapiProperty>, INamedPropertyTagProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiPropertyCollection](mapipropertycollection/)() | Initializes a new instance of the `MapiPropertyCollection` class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.email.mapi/mapipropertycollection/count/) { get; } | Gets the number of properties in the collection. |
| [IsReadOnly](../../aspose.email.mapi/mapipropertycollection/isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [Item](../../aspose.email.mapi/mapipropertycollection/item/) { get; set; } | Gets or sets the value associated with the specified key. (2 indexers) |
| [Keys](../../aspose.email.mapi/mapipropertycollection/keys/) { get; } | Gets the tags of the properties in the collection. |
| [Values](../../aspose.email.mapi/mapipropertycollection/values/) { get; } | Gets the properties in the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.mapi/mapipropertycollection/add/#add_2)(KeyValuePair&lt;long, MapiProperty&gt;) | Adds a property under a tag. |
| virtual [Add](../../aspose.email.mapi/mapipropertycollection/add/#add)(MapiProperty) | Adds a property under its own tag. |
| virtual [Add](../../aspose.email.mapi/mapipropertycollection/add/#add_1)(long, MapiProperty) | Adds a property under the specified tag. |
| [Clear](../../aspose.email.mapi/mapipropertycollection/clear/)() | Removes all properties from the collection. |
| [Contains](../../aspose.email.mapi/mapipropertycollection/contains/)(KeyValuePair&lt;long, MapiProperty&gt;) | Determines whether the collection contains the tag and property pair. |
| [ContainsKey](../../aspose.email.mapi/mapipropertycollection/containskey/)(long) | Determines whether the collection contains a property with the tag. |
| [CopyTo](../../aspose.email.mapi/mapipropertycollection/copyto/)(KeyValuePair&lt;long, MapiProperty&gt;[], int) | Copies the tag and property pairs to an array. |
| [GetEnumerator](../../aspose.email.mapi/mapipropertycollection/getenumerator/)() | Returns an enumerator over the tag and property pairs. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycollection/getproperty/)(PropertyDescriptor) | Gets a property by its descriptor. |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove_2)(KeyValuePair&lt;long, MapiProperty&gt;) | Removes the tag and property pair. |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove_1)(long) | Removes the property with the specified tag. |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove)(PropertyDescriptor) | Removes the property with the specified descriptor. |
| [TryGetValue](../../aspose.email.mapi/mapipropertycollection/trygetvalue/)(long, out MapiProperty) | Gets the property with the specified tag, if there is one. |

## Remarks

Returned by [`Properties`](../mapipropertycontainer/properties/). For typed access the methods of [`MapiPropertyContainer`](../mapipropertycontainer/), such as [`GetPropertyString`](../mapipropertycontainer/getpropertystring/), are usually more convenient.

### See Also

* class [MapiProperty](../mapiproperty/)
* interface [INamedPropertyTagProvider](../inamedpropertytagprovider/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


