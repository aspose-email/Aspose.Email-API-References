---
title: AppendMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحميل رسائل البريد إلى المجلد الحالي
type: docs
weight: 390
url: /ar/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

تحميل رسائل البريد إلى المجلد الحالي

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي .

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

تحميل رسائل البريد إلى المجلد الحالي

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

لتحميل رسائل البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي .

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

تحميل رسائل البريد إلى المجلد الحالي

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي .

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

تحميل رسائل البريد إلى المجلد الحالي

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

لتحميل رسائل البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي .

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | IEnumerable`1 | تعداد رسائل البريد الإلكتروني المراد تحميلها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
