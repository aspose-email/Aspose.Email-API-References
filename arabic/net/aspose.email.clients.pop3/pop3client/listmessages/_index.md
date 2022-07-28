---
title: ListMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسرد الرسائل. يحصل على معلومات لرسالة البحث
type: docs
weight: 290
url: /ar/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | قائمة UniqueId لـ[`Pop3MessageInfo`](../../pop3messageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | التسلسل قائمة أرقام[`Pop3MessageInfo`](../../pop3messageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueIdLst | IEnumerable`1 | قائمة UniqueId لـ[`Pop3MessageInfo`](../../pop3messageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumberLst | IEnumerable`1 | التسلسل قائمة أرقام[`Pop3MessageInfo`](../../pop3messageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

مجموعة من كائنات Pop3MessageInfo .

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

مجموعة من كائنات Pop3MessageInfo .

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |

### قيمة الإرجاع

Pop3MessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

يسرد الرسائل .

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

Pop3MessageInfoCollection

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
