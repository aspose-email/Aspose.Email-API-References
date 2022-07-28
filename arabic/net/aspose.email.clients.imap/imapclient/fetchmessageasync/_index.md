---
title: FetchMessageAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يجلب الرسالة
type: docs
weight: 660
url: /ar/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| ignoreAttachment | Boolean | قيمة تحدد ما إذا كان يجب عدم تحميل المرفقات. إذا كان مضبوطًا على`حقيقي` ، فلن يتم جلب سوى رؤوس الرسائل ونص الرسالة ومعلومات المرفقات. لم يتم تحميل محتوى المرفق |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| ignoreAttachment | Boolean | قيمة تحدد ما إذا كان يجب عدم تحميل المرفقات. إذا كان مضبوطًا على`حقيقي` ، فلن يتم جلب سوى رؤوس الرسائل ونص الرسالة ومعلومات المرفقات. لم يتم تحميل محتوى المرفق |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | المعرف الفريد للرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | المعرف الفريد للرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| ignoreAttachment | Boolean | قيمة تحدد ما إذا كان يجب عدم تحميل المرفقات. إذا كان مضبوطًا على`حقيقي` ، فلن يتم جلب سوى رؤوس الرسائل ونص الرسالة ومعلومات المرفقات. لم يتم تحميل محتوى المرفق |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | رقم تسلسل الرسالة |
| ignoreAttachment | Boolean | قيمة تحدد ما إذا كان يجب عدم تحميل المرفقات. إذا كان مضبوطًا على`حقيقي` ، فلن يتم جلب سوى رؤوس الرسائل ونص الرسالة ومعلومات المرفقات. لم يتم تحميل محتوى المرفق |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | المعرف الفريد للرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

يجلب الرسالة

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | المعرف الفريد للرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
