---
title: Find
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: البحث عن الخصائص في القائمة وفقًا لمجموعة PropertySet
type: docs
weight: 100
url: /ar/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

البحث عن الخصائص في القائمة وفقًا لمجموعة PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet للبحث عن |

### قيمة الإرجاع

مصفوفة من[`PropertyDescriptor`](../../propertydescriptor)كائنات مع PropertySet المطلوبة إذا وجدت في القائمة ؛ مجموعة فارغة خلاف ذلك.

### أنظر أيضا

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(string) {#find_7}

البحث عن خاصية في قائمة بالاسم المحدد

```csharp
public PropertyDescriptor Find(string name)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | الاسم المستخدم للإشارة إلى الخاصية. |

### قيمة الإرجاع

[`PropertyDescriptor`](../../propertydescriptor) الكائن إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

يجد[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) خاصية في القائمة

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| id | Int32 | معرف لتجد |
| type | PropertyDataType | نوع بيانات الخاصية |

### قيمة الإرجاع

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) كائن بعلامة محددة إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(int) {#find_6}

يجد[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) خصائص في list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| id | Int32 | معرف لتجد |

### قيمة الإرجاع

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) مصفوفة كائنات بعلامة محددة إذا وجدت في القائمة ؛ مجموعة فارغة خلاف ذلك.

### أنظر أيضا

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(long) {#find_5}

يجد[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) خاصية في القائمة

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| tag | Int64 | علامة للبحث |

### قيمة الإرجاع

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) كائن بعلامة محددة إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

يجد[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) الخاصية في القائمة وفقًا للمعلمات المطلوبة

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم الممتلكات |
| type | PropertyDataType | نوع بيانات الخاصية |
| propertySet | Guid | مجموعة الممتلكات |

### قيمة الإرجاع

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) الكائن إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

يجد[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)الخاصية في القائمة وفقًا للمعلمات المطلوبة هذه عملية بحث مبسطة بدون مقارنة نوع البيانات .

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم الممتلكات |
| propertySet | Guid | مجموعة الممتلكات |

### قيمة الإرجاع

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) الكائن إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

يجد[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) الخاصية في القائمة وفقًا للمعلمات المطلوبة

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| lid | Int64 | معرف طويل للممتلكات |
| type | PropertyDataType | نوع بيانات الخاصية |
| propertySet | Guid | مجموعة الممتلكات |

### قيمة الإرجاع

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) الكائن إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

يجد[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)الخاصية في القائمة وفقًا للمعلمات المطلوبة هذه عملية بحث مبسطة بدون مقارنة نوع البيانات .

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| lid | Int64 | معرف طويل للممتلكات |
| propertySet | Guid | مجموعة الممتلكات |

### قيمة الإرجاع

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) الكائن إذا وجد في القائمة ؛ خلاف ذلك باطل.

### أنظر أيضا

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* مساحة الاسم [Aspose.Email.Mapi](../../knownpropertylist)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
