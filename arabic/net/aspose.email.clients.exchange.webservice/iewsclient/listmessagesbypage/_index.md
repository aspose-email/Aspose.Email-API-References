---
title: ListMessagesByPage
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: سرد الرسائل في المجلد المحدد .
type: docs
weight: 1150
url: /ar/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |
| offset | Int32 | إزاحة الصفحة التالية في العرض |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |
| offset | Int32 | إزاحة الصفحة التالية في العرض |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |
| pageOffset | Int32 | إزاحة العنصر التالي في العرض |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| pageInfo | PageInfo | معلومات الصفحة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

سرد الرسائل في المجلد المحدد .

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| pageInfo | PageInfo | معلومات الصفحة |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
