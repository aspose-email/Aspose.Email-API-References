---
title: Class MapiPropertyCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiPropertyCollection class. Represents the collection of MapiProperty items
type: docs
weight: 18730
url: /net/aspose.email.mapi/mapipropertycollection/
---
## MapiPropertyCollection class

Represents the collection of MapiProperty items.

```csharp
public class MapiPropertyCollection : IDictionary<long, MapiProperty>, INamedPropertyTagProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiPropertyCollection](mapipropertycollection/)() | Creates a new instance of class MapiProperty. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.email.mapi/mapipropertycollection/count/) { get; } | Gets the number of elements contained in the collection. |
| [IsReadOnly](../../aspose.email.mapi/mapipropertycollection/isreadonly/) { get; } | Gets a value indicating whether the collection is read only. |
| [Item](../../aspose.email.mapi/mapipropertycollection/item/) { get; set; } | Gets or sets the value associated with the specified key. (2 indexers) |
| [Keys](../../aspose.email.mapi/mapipropertycollection/keys/) { get; } | Gets a System.Collections.Generic.ICollection&lt;long&gt; containing the keys in the collection. |
| [Values](../../aspose.email.mapi/mapipropertycollection/values/) { get; } | Gets an System.Collections.Generic.ICollection&lt;MapiProperty&gt; containing the values in the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.mapi/mapipropertycollection/add/#add_2)(KeyValuePair&lt;long, MapiProperty&gt;) |  |
| virtual [Add](../../aspose.email.mapi/mapipropertycollection/add/#add)(MapiProperty) | Adds a MapiProperty item with specified tag. |
| virtual [Add](../../aspose.email.mapi/mapipropertycollection/add/#add_1)(long, MapiProperty) | Adds a MapiProperty item with specified tag. |
| [Clear](../../aspose.email.mapi/mapipropertycollection/clear/)() | Removes all of the elements from the collection. |
| [Contains](../../aspose.email.mapi/mapipropertycollection/contains/)(KeyValuePair&lt;long, MapiProperty&gt;) |  |
| [ContainsKey](../../aspose.email.mapi/mapipropertycollection/containskey/)(long) | Determines whether the collection contains a property with the specified tag. |
| [CopyTo](../../aspose.email.mapi/mapipropertycollection/copyto/)(KeyValuePair&lt;long, MapiProperty&gt;[], int) |  |
| [GetEnumerator](../../aspose.email.mapi/mapipropertycollection/getenumerator/)() |  |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycollection/getproperty/)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove_2)(KeyValuePair&lt;long, MapiProperty&gt;) |  |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove_1)(long) | Removes the property with the specified tag from the collection. |
| [Remove](../../aspose.email.mapi/mapipropertycollection/remove/#remove)(PropertyDescriptor) | Removes the property with the specified property descriptor from the collection. |
| [TryGetValue](../../aspose.email.mapi/mapipropertycollection/trygetvalue/)(long, out MapiProperty) | Gets the property associated with the specified tag. |

### See Also

* class [MapiProperty](../mapiproperty/)
* interface [INamedPropertyTagProvider](../inamedpropertytagprovider/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


