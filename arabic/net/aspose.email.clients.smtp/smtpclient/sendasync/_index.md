---
title: SendAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إنشاء الرسالة المحددة وإرسالها.
type: docs
weight: 180
url: /ar/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

أرسل مجموعة الرسائل المحددة.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | MailMessageCollection | مجموعة الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

أرسل الرسائل المحددة .

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

أرسل مجموعة الرسائل المحددة.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | MailMessageCollection | مجموعة الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

أرسل الرسائل المحددة .

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

أرسل مجموعة الرسائل المحددة.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | MailMessageCollection | مجموعة الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

أرسل الرسائل المحددة .

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

أرسل الرسالة المحددة.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

أرسل مجموعة الرسائل المحددة.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | MailMessageCollection | مجموعة الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

أرسل الرسائل المحددة .

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### أنظر أيضا

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
