---
title: KnownPropertyList.Find
second_title: Aspose.Email for .NET API Reference
description: KnownPropertyList method. Finds properties in list according to its PropertySet
type: docs
weight: 100
url: /net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Finds properties in list according to its PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet to find |

### Return Value

Array of [`PropertyDescriptor`](../../propertydescriptor/) objects with required PropertySet if found in the list; otherwise empty array.

### See Also

* class [PropertyDescriptor](../../propertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Finds property in list with specified name

```csharp
public PropertyDescriptor Find(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name used to refer to the property. |

### Return Value

[`PropertyDescriptor`](../../propertydescriptor/) object if found in the list; otherwise null.

### See Also

* class [PropertyDescriptor](../../propertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Finds [`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) property in list

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | Int32 | id to find |
| type | PropertyDataType | Data type of a property |

### Return Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) object with defined tag if found in the list; otherwise null.

### See Also

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Finds [`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) properties in list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | Int32 | id to find |

### Return Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) Array of objects with defined tag if found in the list; otherwise empty array.

### See Also

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Finds [`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) property in list

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | Tag to find |

### Return Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor/) object with defined tag if found in the list; otherwise null.

### See Also

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Finds [`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor/) property in list according to required parameters

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of a property |
| type | PropertyDataType | Data type of a property |
| propertySet | Guid | PropertySet of a property |

### Return Value

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor/) object if found in the list; otherwise null.

### See Also

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Finds [`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor/) property in list according to required parameters This is simplified search operation without data type comparison.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of a property |
| propertySet | Guid | PropertySet of a property |

### Return Value

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor/) object if found in the list; otherwise null.

### See Also

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Finds [`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor/) property in list according to required parameters

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lid | Int64 | Long id of a property |
| type | PropertyDataType | Data type of a property |
| propertySet | Guid | PropertySet of a property |

### Return Value

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor/) object if found in the list; otherwise null.

### See Also

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Finds [`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor/) property in list according to required parameters This is simplified search operation without data type comparison.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lid | Int64 | Long id of a property |
| propertySet | Guid | PropertySet of a property |

### Return Value

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor/) object if found in the list; otherwise null.

### See Also

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor/)
* class [KnownPropertyList](../)
* namespace [Aspose.Email.Mapi](../../knownpropertylist/)
* assembly [Aspose.Email](../../../)


