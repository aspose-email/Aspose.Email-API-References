---
title: Find
second_title: Aspose.Email for .NET API 参考
description: 根据其 PropertySet 在列表中查找属性
type: docs
weight: 100
url: /zh/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

根据其 PropertySet 在列表中查找属性

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| propertySets | Guid[] | 要查找的 PropertySet |

### 返回值

数组[`PropertyDescriptor`](../../propertydescriptor)如果在列表中找到具有所需 PropertySet 的对象；否则为空数组。

### 也可以看看

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(string) {#find_7}

在列表中查找具有指定名称的属性

```csharp
public PropertyDescriptor Find(string name)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 用于指代属性的名称。 |

### 返回值

[`PropertyDescriptor`](../../propertydescriptor)如果在列表中找到对象；否则为空。

### 也可以看看

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

发现[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor)列表 中的属性

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | Int32 | 要查找的 ID |
| type | PropertyDataType | 属性的数据类型 |

### 返回值

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor)如果在列表中找到具有定义标记的对象；否则为空。

### 也可以看看

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(int) {#find_6}

发现[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) list 中的属性

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | Int32 | 要查找的 ID |

### 返回值

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor)如果在列表中找到具有已定义标记的对象数组；否则为空数组。

### 也可以看看

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(long) {#find_5}

发现[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor)列表 中的属性

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tag | Int64 | 标记查找 |

### 返回值

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor)如果在列表中找到具有定义标记的对象；否则为空。

### 也可以看看

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

发现[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)根据所需参数列表中的属性

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 物业名称 |
| type | PropertyDataType | 属性的数据类型 |
| propertySet | Guid | 属性的 PropertySet |

### 返回值

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)如果在列表中找到对象；否则为空。

### 也可以看看

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

发现[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)根据所需参数列表中的属性 这是没有数据类型比较的简化搜索操作。

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 物业名称 |
| propertySet | Guid | 属性的 PropertySet |

### 返回值

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)如果在列表中找到对象；否则为空。

### 也可以看看

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

发现[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)根据所需参数列表中的属性

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lid | Int64 | 属性的长 id |
| type | PropertyDataType | 属性的数据类型 |
| propertySet | Guid | 属性的 PropertySet |

### 返回值

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)如果在列表中找到对象；否则为空。

### 也可以看看

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

发现[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)根据所需参数列表中的属性 这是没有数据类型比较的简化搜索操作。

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lid | Int64 | 属性的长 id |
| propertySet | Guid | 属性的 PropertySet |

### 返回值

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)如果在列表中找到对象；否则为空。

### 也可以看看

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* 命名空间 [Aspose.Email.Mapi](../../knownpropertylist)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
