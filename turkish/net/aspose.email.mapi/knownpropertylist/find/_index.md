---
title: Find
second_title: Aspose.Email for .NET API Referansı
description: PropertySet ye göre listedeki özellikleri bulur
type: docs
weight: 100
url: /tr/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

PropertySet 'ye göre listedeki özellikleri bulur

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| propertySets | Guid[] | Bulmak için PropertySet |

### Geri dönüş değeri

dizisi[`PropertyDescriptor`](../../propertydescriptor)Listede bulunursa, gerekli PropertySet'e sahip nesneler; aksi takdirde boş dizi.

### Ayrıca bakınız

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Belirtilen ada sahip listedeki özelliği bulur

```csharp
public PropertyDescriptor Find(string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Özelliğe atıfta bulunmak için kullanılan ad. |

### Geri dönüş değeri

[`PropertyDescriptor`](../../propertydescriptor) listede bulunursa nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Bulunur[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) listesindeki özellik

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| id | Int32 | bulmak için kimlik |
| type | PropertyDataType | Bir mülkün veri türü |

### Geri dönüş değeri

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) listede bulunursa tanımlı etiketli nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Bulunur[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) list içindeki özellikler

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| id | Int32 | bulmak için kimlik |

### Geri dönüş değeri

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Listede bulunursa, tanımlı etikete sahip nesne dizisi; aksi takdirde boş dizi.

### Ayrıca bakınız

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Bulunur[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) listesindeki özellik

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| tag | Int64 | Bulunacak etiket |

### Geri dönüş değeri

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) listede bulunursa tanımlı etiketli nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Bulunur[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) gerekli parametrelere göre listedeki özellik

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Bir mülkün adı |
| type | PropertyDataType | Bir mülkün veri türü |
| propertySet | Guid | Bir özelliğin PropertySet'i |

### Geri dönüş değeri

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) listede bulunursa nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Bulunur[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)gerekli parametrelere göre listedeki özellik Bu, veri türü karşılaştırması olmadan basitleştirilmiş arama işlemidir.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Bir mülkün adı |
| propertySet | Guid | Bir özelliğin PropertySet'i |

### Geri dönüş değeri

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) listede bulunursa nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Bulunur[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) gerekli parametrelere göre listedeki özellik

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| lid | Int64 | Bir mülkün uzun kimliği |
| type | PropertyDataType | Bir mülkün veri türü |
| propertySet | Guid | Bir özelliğin PropertySet'i |

### Geri dönüş değeri

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) listede bulunursa nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Bulunur[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)gerekli parametrelere göre listedeki özellik Bu, veri türü karşılaştırması olmadan basitleştirilmiş arama işlemidir.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| lid | Int64 | Bir mülkün uzun kimliği |
| propertySet | Guid | Bir özelliğin PropertySet'i |

### Geri dönüş değeri

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) listede bulunursa nesne; aksi takdirde boş.

### Ayrıca bakınız

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* ad alanı [Aspose.Email.Mapi](../../knownpropertylist)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
