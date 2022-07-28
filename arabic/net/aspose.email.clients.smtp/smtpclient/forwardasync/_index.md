---
title: ForwardAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إعادة توجيه الرسالة المحددة إلى المستلم
type: docs
weight: 140
url: /ar/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipient | String | مستلم الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipient | String | مستلم الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| messageStream | Stream | الدفق الذي يمثل الرسالة بتنسيق eml. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| messageStream | Stream | الدفق الذي يمثل الرسالة بتنسيق eml. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipient | String | مستلم الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipient | String | مستلم الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| message | MailMessage | الرسالة الخاصة بإعادة التوجيه. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| messageStream | Stream | الدفق الذي يمثل الرسالة بتنسيق eml. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

إعادة توجيه الرسالة المحددة إلى المستلم

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sender | String | مرسل الرسالة المعاد توجيهها. |
| recipients | MailAddressCollection | مستلمو الرسالة المعاد توجيهها. |
| messageStream | Stream | الدفق الذي يمثل الرسالة بتنسيق eml. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
