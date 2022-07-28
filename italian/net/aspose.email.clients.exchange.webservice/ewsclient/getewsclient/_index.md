---
title: GetEWSClient
second_title: Aspose.Email per riferimento all'API .NET
description: Inizializza una nuova istanza diEWSClientaspose.email.clients.exchange.webservice/ewsclient classe basata
type: docs
weight: 10
url: /it/net/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---
## GetEWSClient(string, ICredentials) {#getewsclient_2}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| credentials | ICredentials | Contiene le credenziali per l'autenticazione. |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string) {#getewsclient_4}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| username | String | Il nome utente |
| password | String | La password |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, WebProxy) {#getewsclient_5}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    WebProxy proxy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| username | String | Il nome utente |
| password | String | La password |
| proxy | WebProxy | Contiene le impostazioni del proxy HTTP |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string) {#getewsclient_6}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| username | String | Il nome utente |
| password | String | La password |
| domain | String | Il nome di dominio |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string, WebProxy) {#getewsclient_7}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain, WebProxy proxy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| username | String | Il nome utente |
| password | String | La password |
| domain | String | Il nome di dominio |
| proxy | WebProxy | Contiene le impostazioni del proxy HTTP |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, string, ICredentials, WebProxy) {#getewsclient_1}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, string mailboxUri, 
    ICredentials credentials, WebProxy proxy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versioni del server di scambio |
| mailboxUri | String | L'URI della cassetta postale |
| credentials | ICredentials | Contiene le credenziali per l'autenticazione. |
| proxy | WebProxy | Contiene le impostazioni del proxy HTTP |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, bool, string, string, ICredentials, WebProxy) {#getewsclient}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, 
    bool formbasedAuthenticationRequired, string formbasedAuthenticationLocation, 
    string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versioni del server di scambio |
| formbasedAuthenticationRequired | Boolean | Imposta true se è richiesta l'autenticazione basata su modulo, altrimenti imposta false. |
| formbasedAuthenticationLocation | String | URL per l'autenticazione basata su modulo |
| mailboxUri | String | L'URI della cassetta postale |
| credentials | ICredentials | Contiene le credenziali per l'autenticazione. |
| proxy | WebProxy | Contiene le impostazioni del proxy HTTP |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

---

## GetEWSClient(string, ICredentials, WebProxy) {#getewsclient_3}

Inizializza una nuova istanza di[`EWSClient`](../../ewsclient) classe basata

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailboxUri | String | L'URI della cassetta postale |
| credentials | ICredentials | Contiene le credenziali per l'autenticazione. |
| proxy | WebProxy | Contiene le impostazioni del proxy HTTP |

### Valore di ritorno

Istanza della classe basata su[`EWSClient`](../../ewsclient) classe.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
