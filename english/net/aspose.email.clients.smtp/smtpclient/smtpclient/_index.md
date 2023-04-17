---
title: SmtpClient.SmtpClient
second_title: Aspose.Email for .NET API Reference
description: SmtpClient constructor. Initializes a new instance of the SmtpClient class
type: docs
weight: 10
url: /net/aspose.email.clients.smtp/smtpclient/smtpclient/
---
## SmtpClient() {#constructor}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient()
```

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(Configuration) {#constructor_1}

Initializes a new instance of the [`SmtpClient`](../) class by using configuration file settings.

```csharp
public SmtpClient(Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| configuration | Configuration | The configuration. |

## Remarks

Initializes the Host, Port, Username, Password properties for the new SmtpClient.

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string) {#constructor_2}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, SecurityOptions) {#constructor_3}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int) {#constructor_4}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, SecurityOptions) {#constructor_5}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, string) {#constructor_14}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| password | String | The password. Password limitations are defined by server implementation, which the client connects. |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, string, SecurityOptions) {#constructor_15}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, string password, SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| password | String | The password. Password limitations are defined by server implementation, which the client connects. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, string) {#constructor_8}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| password | String | The password. Password limitations are defined by server implementation, which the client connects. |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, string, SecurityOptions) {#constructor_9}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, string password, 
    SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| password | String | The password. Password limitations are defined by server implementation, which the client connects. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, string, bool) {#constructor_16}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, string authInfo, bool useOAuth)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| authInfo | String | The user password or XOAUTH2 access token |
| useOAuth | Boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, string, bool, SecurityOptions) {#constructor_17}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, string authInfo, bool useOAuth, 
    SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| authInfo | String | The user password or XOAUTH2 access token |
| useOAuth | Boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, string, bool) {#constructor_10}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, string authInfo, bool useOAuth)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| authInfo | String | The user password or XOAUTH2 access token |
| useOAuth | Boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, string, bool, SecurityOptions) {#constructor_11}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, string authInfo, bool useOAuth, 
    SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| authInfo | String | The user password or XOAUTH2 access token |
| useOAuth | Boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, ITokenProvider) {#constructor_12}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, ITokenProvider tokenProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| tokenProvider | ITokenProvider | TokenProvider allowing to retrieve access token. |

### See Also

* interface [ITokenProvider](../../../aspose.email.clients/itokenprovider/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, string, ITokenProvider, SecurityOptions) {#constructor_13}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, string username, ITokenProvider tokenProvider, 
    SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| username | String | The username. |
| tokenProvider | ITokenProvider | TokenProvider allowing to retrieve access token. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* interface [ITokenProvider](../../../aspose.email.clients/itokenprovider/)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, ITokenProvider) {#constructor_6}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, ITokenProvider tokenProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| tokenProvider | ITokenProvider | TokenProvider allowing to retrieve access token. |

### See Also

* interface [ITokenProvider](../../../aspose.email.clients/itokenprovider/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## SmtpClient(string, int, string, ITokenProvider, SecurityOptions) {#constructor_7}

Initializes a new instance of the [`SmtpClient`](../) class.

```csharp
public SmtpClient(string host, int port, string username, ITokenProvider tokenProvider, 
    SecurityOptions securityOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The name of the host used for SMTP. |
| port | Int32 | The port used for SMTP. |
| username | String | The username. |
| tokenProvider | ITokenProvider | TokenProvider allowing to retrieve access token. |
| securityOptions | SecurityOptions | Security mode for a mail client |

### See Also

* interface [ITokenProvider](../../../aspose.email.clients/itokenprovider/)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)


