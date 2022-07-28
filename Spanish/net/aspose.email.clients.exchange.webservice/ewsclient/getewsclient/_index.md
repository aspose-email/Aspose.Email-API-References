---
title: GetEWSClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Inicializa una nueva instancia delEWSClientaspose.email.clients.exchange.webservice/ewsclient clase basada
type: docs
weight: 10
url: /es/net/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---
## GetEWSClient(string, ICredentials) {#getewsclient_2}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| credentials | ICredentials | Contiene las credenciales para la autenticación. |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string) {#getewsclient_4}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| username | String | El nombre de usuario |
| password | String | La contraseña |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, WebProxy) {#getewsclient_5}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    WebProxy proxy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| username | String | El nombre de usuario |
| password | String | La contraseña |
| proxy | WebProxy | Contiene la configuración del proxy HTTP |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string) {#getewsclient_6}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| username | String | El nombre de usuario |
| password | String | La contraseña |
| domain | String | el nombre de dominio |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string, WebProxy) {#getewsclient_7}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain, WebProxy proxy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| username | String | El nombre de usuario |
| password | String | La contraseña |
| domain | String | el nombre de dominio |
| proxy | WebProxy | Contiene la configuración del proxy HTTP |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, string, ICredentials, WebProxy) {#getewsclient_1}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, string mailboxUri, 
    ICredentials credentials, WebProxy proxy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versiones del servidor de intercambio |
| mailboxUri | String | El URI del buzón |
| credentials | ICredentials | Contiene las credenciales para la autenticación. |
| proxy | WebProxy | Contiene la configuración del proxy HTTP |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, bool, string, string, ICredentials, WebProxy) {#getewsclient}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, 
    bool formbasedAuthenticationRequired, string formbasedAuthenticationLocation, 
    string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versiones del servidor de intercambio |
| formbasedAuthenticationRequired | Boolean | Establezca verdadero si se requiere autenticación basada en formularios; de lo contrario, establezca falso. |
| formbasedAuthenticationLocation | String | url para la autenticación basada en formularios |
| mailboxUri | String | El URI del buzón |
| credentials | ICredentials | Contiene las credenciales para la autenticación. |
| proxy | WebProxy | Contiene la configuración del proxy HTTP |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

---

## GetEWSClient(string, ICredentials, WebProxy) {#getewsclient_3}

Inicializa una nueva instancia del[`EWSClient`](../../ewsclient) clase basada

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailboxUri | String | El URI del buzón |
| credentials | ICredentials | Contiene las credenciales para la autenticación. |
| proxy | WebProxy | Contiene la configuración del proxy HTTP |

### Valor_devuelto

Instancia de la clase basada en el[`EWSClient`](../../ewsclient) clase.

### Ver también

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
