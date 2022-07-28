---
title: ListMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسرد الرسائل. يحصل على معلومات لرسالة البحث
type: docs
weight: 300
url: /ar/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
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

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
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

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

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

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

مجموعة من كائنات Pop3MessageInfo.

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

يسرد الرسائل .

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fields | Pop3ListFields | الحقول التي نريد الحصول عليها |
| closeTransaction | Boolean | يشير إلى ما إذا كان يجب إغلاق المعاملة الحالية ، قبل استرداد القائمة. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) هدف. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../pop3client)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
