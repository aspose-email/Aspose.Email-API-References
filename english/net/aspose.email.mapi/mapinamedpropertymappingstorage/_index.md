---
title: Class MapiNamedPropertyMappingStorage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiNamedPropertyMappingStorage class. The mapping between the named properties of a message and the tags they are stored under
type: docs
weight: 17360
url: /net/aspose.email.mapi/mapinamedpropertymappingstorage/
---
## MapiNamedPropertyMappingStorage class

The mapping between the named properties of a message and the tags they are stored under.

```csharp
public sealed class MapiNamedPropertyMappingStorage : MapiPropertyContainer
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiNamedPropertyMappingStorage](mapinamedpropertymappingstorage/)() | Initializes a new instance of the `MapiNamedPropertyMappingStorage` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Content](../../aspose.email.mapi/mapinamedpropertymappingstorage/content/) { get; } | Gets the content of the storage. |
| [Name](../../aspose.email.mapi/mapinamedpropertymappingstorage/name/) { get; } | Gets the name of the storage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |

## Methods

| Name | Description |
| --- | --- |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping/#addnamedpropertymapping)(MapiProperty, long, Guid) | Registers a property as a named property with a numeric ID. |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping/#addnamedpropertymapping_1)(MapiProperty, string, Guid) | Registers a property as a named property with a string name. |
| [GetNextAvailablePropertyId](../../aspose.email.mapi/mapinamedpropertymappingstorage/getnextavailablepropertyid/)(MapiPropertyType) | Gets a free tag in the named property range for a new property of the specified type. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty/)(PropertyDescriptor) | Gets a MAPI property by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property, creating the property if needed. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |

## Remarks

Returned by [`NamedPropertyMapping`](../mapimessageitembase/namedpropertymapping/). To add a named property by hand, get a free ID with [`GetNextAvailablePropertyId`](./getnextavailablepropertyid/), set the property under that tag and register it with [`AddNamedPropertyMapping`](./addnamedpropertymapping/). Setting a property through a [`PidLidPropertyDescriptor`](../pidlidpropertydescriptor/) or [`PidNamePropertyDescriptor`](../pidnamepropertydescriptor/) does all of this for you.

### See Also

* class [MapiPropertyContainer](../mapipropertycontainer/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


