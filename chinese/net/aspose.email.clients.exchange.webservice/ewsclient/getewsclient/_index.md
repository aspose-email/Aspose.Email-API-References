---
title: GetEWSClient
second_title: Aspose.Email for .NET API 参考
description: 初始化EWSClientaspose.email.clients.exchange.webservice/ewsclient基于类
type: docs
weight: 10
url: /zh/net/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---
## GetEWSClient(string, ICredentials) {#getewsclient_2}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| credentials | ICredentials | 包含用于身份验证的凭据。 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string) {#getewsclient_4}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| username | String | 用户名 |
| password | String | 密码 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, WebProxy) {#getewsclient_5}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    WebProxy proxy)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| username | String | 用户名 |
| password | String | 密码 |
| proxy | WebProxy | 包含 HTTP 代理设置 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string) {#getewsclient_6}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| username | String | 用户名 |
| password | String | 密码 |
| domain | String | 域名 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string, WebProxy) {#getewsclient_7}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain, WebProxy proxy)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| username | String | 用户名 |
| password | String | 密码 |
| domain | String | 域名 |
| proxy | WebProxy | 包含 HTTP 代理设置 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, string, ICredentials, WebProxy) {#getewsclient_1}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, string mailboxUri, 
    ICredentials credentials, WebProxy proxy)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Exchange 服务器版本 |
| mailboxUri | String | 邮箱的URI |
| credentials | ICredentials | 包含用于身份验证的凭据。 |
| proxy | WebProxy | 包含 HTTP 代理设置 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, bool, string, string, ICredentials, WebProxy) {#getewsclient}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, 
    bool formbasedAuthenticationRequired, string formbasedAuthenticationLocation, 
    string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Exchange 服务器版本 |
| formbasedAuthenticationRequired | Boolean | 如果需要基于表单的身份验证，则设置为 true，否则设置为 false。 |
| formbasedAuthenticationLocation | String | 用于基于表单的身份验证的 url |
| mailboxUri | String | 邮箱的URI |
| credentials | ICredentials | 包含用于身份验证的凭据。 |
| proxy | WebProxy | 包含 HTTP 代理设置 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

---

## GetEWSClient(string, ICredentials, WebProxy) {#getewsclient_3}

初始化[`EWSClient`](../../ewsclient)基于类

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailboxUri | String | 邮箱的URI |
| credentials | ICredentials | 包含用于身份验证的凭据。 |
| proxy | WebProxy | 包含 HTTP 代理设置 |

### 返回值

基于类的实例[`EWSClient`](../../ewsclient)班级。

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
