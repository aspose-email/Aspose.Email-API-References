---
title: ListMessagesByPage
second_title: Aspose.Email for .NET API 参考
description: 列出指定文件夹中的邮件
type: docs
weight: 1150
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| itemsPerPage | Int32 | 页面中的项目数 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索条件。 |
| itemsPerPage | Int32 | 页面中的项目数 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| itemsPerPage | Int32 | 页面中的项目数 |
| offset | Int32 | 视图中下一页的偏移量 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索条件。 |
| itemsPerPage | Int32 | 页面中的项目数 |
| offset | Int32 | 视图中下一页的偏移量 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| itemsPerPage | Int32 | 页面中的项目数 |
| pageOffset | Int32 | 视图中下一项的偏移量 |
| options | ExchangeListMessagesOptions | 指定列表的设置 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| pageInfo | PageInfo | 一页信息 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| pageInfo | PageInfo | 一页信息 |
| options | ExchangeListMessagesOptions | 指定列表的设置 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
