---
title: Find
second_title: Aspose.Email för .NET API-referens
description: Hittar egenskaper i listan enligt dess PropertySet
type: docs
weight: 100
url: /sv/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Hittar egenskaper i listan enligt dess PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet att hitta |

### Returvärde

Uppsättning av[`PropertyDescriptor`](../../propertydescriptor)objekt med nödvändig PropertySet om de finns i listan; annars tom array.

### Se även

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Hittar egendom i listan med specificerat namn

```csharp
public PropertyDescriptor Find(string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namnet som används för att hänvisa till fastigheten. |

### Returvärde

[`PropertyDescriptor`](../../propertydescriptor) objekt om det finns i listan; annars null.

### Se även

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Hittar[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) egenskap i listan

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | Int32 | id att hitta |
| type | PropertyDataType | Datatyp för en egenskap |

### Returvärde

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objekt med definierad tagg om det finns i listan; annars null.

### Se även

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Hittar[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) egenskaper i list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | Int32 | id att hitta |

### Returvärde

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Array av objekt med definierad tagg om de finns i listan; annars tom array.

### Se även

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Hittar[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) egenskap i listan

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tag | Int64 | Tagga för att hitta |

### Returvärde

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objekt med definierad tagg om det finns i listan; annars null.

### Se även

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Hittar[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) egenskap i listan enligt nödvändiga parametrar

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namn på en fastighet |
| type | PropertyDataType | Datatyp för en egenskap |
| propertySet | Guid | PropertySet av en fastighet |

### Returvärde

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objekt om det finns i listan; annars null.

### Se även

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Hittar[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)egenskap i listan enligt obligatoriska parametrar Detta är en förenklad sökoperation utan jämförelse av datatyp.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namn på en fastighet |
| propertySet | Guid | PropertySet av en fastighet |

### Returvärde

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objekt om det finns i listan; annars null.

### Se även

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Hittar[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) egenskap i listan enligt nödvändiga parametrar

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lid | Int64 | Långt id för en fastighet |
| type | PropertyDataType | Datatyp för en egenskap |
| propertySet | Guid | PropertySet av en fastighet |

### Returvärde

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objekt om det finns i listan; annars null.

### Se även

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Hittar[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)egenskap i listan enligt obligatoriska parametrar Detta är en förenklad sökoperation utan jämförelse av datatyp.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lid | Int64 | Långt id för en fastighet |
| propertySet | Guid | PropertySet av en fastighet |

### Returvärde

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objekt om det finns i listan; annars null.

### Se även

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namnutrymme [Aspose.Email.Mapi](../../knownpropertylist)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
