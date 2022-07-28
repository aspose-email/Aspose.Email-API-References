---
title: ListMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسرد الرسائل .
type: docs
weight: 1140
url: /ar/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

سرد الرسائل في المجلد المحدد

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| mailbox | String | علبة البريد المستخدمة لتهيئة فئة معرف المجلد. |
| folder | String | مجلد للبحث عن الرسائل فيه |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) يحتوي على رسائل من المجلد المحدد

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| mailbox | String | علبة البريد المستخدمة لتهيئة فئة معرف المجلد. |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

سرد الرسائل في المجلد المحدد

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) يحتوي على رسائل من المجلد المحدد

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

سرد الرسائل في المجلد المحدد

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |
| extendedProperties | IEnumerable`1 | الخصائص الممتدة للرسائل المستردة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) يحتوي على رسائل من المجلد المحدد

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه . |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) الذي يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه . |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |
| recursive | Boolean | يشير إلى ما إذا كانت قائمة متكررة أم لا. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) الذي يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| iDs | IEnumerable`1 | تعداد هويات الرسائل |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) الذي يحتوي على رسائل ذات.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

سرد الرسائل في مجلد صندوق الوارد.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) من مجلد البريد الوارد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
