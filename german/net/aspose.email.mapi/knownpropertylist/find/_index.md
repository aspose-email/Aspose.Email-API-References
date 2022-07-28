---
title: Find
second_title: Aspose.Email für .NET-API-Referenz
description: Findet Eigenschaften in der Liste gemäß ihrem PropertySet
type: docs
weight: 100
url: /de/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Findet Eigenschaften in der Liste gemäß ihrem PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet zu finden |

### Rückgabewert

Anordnung von[`PropertyDescriptor`](../../propertydescriptor)Objekte mit erforderlichem PropertySet, falls in der Liste gefunden; andernfalls leeres Array.

### Siehe auch

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Findet Eigenschaft in der Liste mit dem angegebenen Namen

```csharp
public PropertyDescriptor Find(string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name, der verwendet wird, um auf die Eigenschaft zu verweisen. |

### Rückgabewert

[`PropertyDescriptor`](../../propertydescriptor) Objekt, wenn es in der Liste gefunden wird; sonst null.

### Siehe auch

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

findet[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Eigenschaft in Liste

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | Int32 | ID zu finden |
| type | PropertyDataType | Datentyp einer Eigenschaft |

### Rückgabewert

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Objekt mit definiertem Tag, falls in der Liste gefunden; sonst null.

### Siehe auch

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(int) {#find_6}

findet[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Eigenschaften in list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | Int32 | ID zu finden |

### Rückgabewert

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Array von Objekten mit definiertem Tag, falls in der Liste gefunden; andernfalls leeres Array.

### Siehe auch

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(long) {#find_5}

findet[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Eigenschaft in Liste

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tag | Int64 | Tag zu finden |

### Rückgabewert

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Objekt mit definiertem Tag, falls in der Liste gefunden; sonst null.

### Siehe auch

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

findet[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) Eigenschaft in der Liste gemäß den erforderlichen Parametern

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name einer Eigenschaft |
| type | PropertyDataType | Datentyp einer Eigenschaft |
| propertySet | Guid | PropertySet einer Eigenschaft |

### Rückgabewert

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) Objekt, wenn es in der Liste gefunden wird; sonst null.

### Siehe auch

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

findet[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)Eigenschaft in der Liste gemäß den erforderlichen Parametern Dies ist eine vereinfachte Suchoperation ohne Datentypvergleich.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name einer Eigenschaft |
| propertySet | Guid | PropertySet einer Eigenschaft |

### Rückgabewert

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) Objekt, wenn es in der Liste gefunden wird; sonst null.

### Siehe auch

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

findet[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) Eigenschaft in der Liste gemäß den erforderlichen Parametern

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lid | Int64 | Lange ID einer Eigenschaft |
| type | PropertyDataType | Datentyp einer Eigenschaft |
| propertySet | Guid | PropertySet einer Eigenschaft |

### Rückgabewert

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) Objekt, wenn es in der Liste gefunden wird; sonst null.

### Siehe auch

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

findet[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)Eigenschaft in der Liste gemäß den erforderlichen Parametern Dies ist eine vereinfachte Suchoperation ohne Datentypvergleich.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lid | Int64 | Lange ID einer Eigenschaft |
| propertySet | Guid | PropertySet einer Eigenschaft |

### Rückgabewert

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) Objekt, wenn es in der Liste gefunden wird; sonst null.

### Siehe auch

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* namensraum [Aspose.Email.Mapi](../../knownpropertylist)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
