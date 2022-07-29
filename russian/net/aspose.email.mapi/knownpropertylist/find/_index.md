---
title: Find
second_title: Справочник по Aspose.Email для .NET API
description: Находит свойства в списке в соответствии с их PropertySet
type: docs
weight: 100
url: /ru/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Находит свойства в списке в соответствии с их PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| propertySets | Guid[] | Набор свойств, чтобы найти |

### Возвращаемое значение

Массив[`PropertyDescriptor`](../../propertydescriptor)объекты с требуемым PropertySet, если они найдены в списке; иначе пустой массив.

### Смотрите также

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Находит свойство в списке с указанным именем

```csharp
public PropertyDescriptor Find(string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя, используемое для ссылки на свойство. |

### Возвращаемое значение

[`PropertyDescriptor`](../../propertydescriptor) объект, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Находит[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) свойство в списке

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | Int32 | идентификатор, чтобы найти |
| type | PropertyDataType | Тип данных свойства |

### Возвращаемое значение

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) объект с определенным тегом, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Находит[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) свойства в list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | Int32 | идентификатор, чтобы найти |

### Возвращаемое значение

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Массив объектов с определенным тегом, если он найден в списке; иначе пустой массив.

### Смотрите также

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Находит[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) свойство в списке

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tag | Int64 | Отметьте, чтобы найти |

### Возвращаемое значение

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) объект с определенным тегом, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Находит[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) свойство в списке по требуемым параметрам

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Название свойства |
| type | PropertyDataType | Тип данных свойства |
| propertySet | Guid | PropertySet свойства |

### Возвращаемое значение

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) объект, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Находит[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)свойство в списке по требуемым параметрам Это упрощенная операция поиска без сравнения типов данных.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Название свойства |
| propertySet | Guid | PropertySet свойства |

### Возвращаемое значение

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) объект, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Находит[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) свойство в списке по требуемым параметрам

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| lid | Int64 | Длинный идентификатор свойства |
| type | PropertyDataType | Тип данных свойства |
| propertySet | Guid | PropertySet свойства |

### Возвращаемое значение

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) объект, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Находит[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)свойство в списке по требуемым параметрам Это упрощенная операция поиска без сравнения типов данных.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| lid | Int64 | Длинный идентификатор свойства |
| propertySet | Guid | PropertySet свойства |

### Возвращаемое значение

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) объект, если он найден в списке; в противном случае ноль.

### Смотрите также

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* пространство имен [Aspose.Email.Mapi](../../knownpropertylist)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
