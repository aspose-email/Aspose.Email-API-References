---
title: GetEWSClient
second_title: Aspose.Email für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonEWSClientaspose.email.clients.exchange.webservice/ewsclient basierende Klasse
type: docs
weight: 10
url: /de/net/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---
## GetEWSClient(string, ICredentials) {#getewsclient_2}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| credentials | ICredentials | Enthält die Anmeldeinformationen für die Authentifizierung. |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string) {#getewsclient_4}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| username | String | Der Nutzername |
| password | String | Das Passwort |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, WebProxy) {#getewsclient_5}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    WebProxy proxy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| username | String | Der Nutzername |
| password | String | Das Passwort |
| proxy | WebProxy | Enthält HTTP-Proxy-Einstellungen |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string) {#getewsclient_6}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| username | String | Der Nutzername |
| password | String | Das Passwort |
| domain | String | Der Domänenname |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string, WebProxy) {#getewsclient_7}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain, WebProxy proxy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| username | String | Der Nutzername |
| password | String | Das Passwort |
| domain | String | Der Domänenname |
| proxy | WebProxy | Enthält HTTP-Proxy-Einstellungen |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, string, ICredentials, WebProxy) {#getewsclient_1}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, string mailboxUri, 
    ICredentials credentials, WebProxy proxy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Exchange-Server-Versionen |
| mailboxUri | String | Der URI des Postfachs |
| credentials | ICredentials | Enthält die Anmeldeinformationen für die Authentifizierung. |
| proxy | WebProxy | Enthält HTTP-Proxy-Einstellungen |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, bool, string, string, ICredentials, WebProxy) {#getewsclient}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, 
    bool formbasedAuthenticationRequired, string formbasedAuthenticationLocation, 
    string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Exchange-Server-Versionen |
| formbasedAuthenticationRequired | Boolean | Legen Sie „true“ fest, wenn eine formularbasierte Authentifizierung erforderlich ist, andernfalls legen Sie „false“ fest. |
| formbasedAuthenticationLocation | String | URL für die formularbasierte Authentifizierung |
| mailboxUri | String | Der URI des Postfachs |
| credentials | ICredentials | Enthält die Anmeldeinformationen für die Authentifizierung. |
| proxy | WebProxy | Enthält HTTP-Proxy-Einstellungen |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

---

## GetEWSClient(string, ICredentials, WebProxy) {#getewsclient_3}

Initialisiert eine neue Instanz von[`EWSClient`](../../ewsclient) basierende Klasse

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailboxUri | String | Der URI des Postfachs |
| credentials | ICredentials | Enthält die Anmeldeinformationen für die Authentifizierung. |
| proxy | WebProxy | Enthält HTTP-Proxy-Einstellungen |

### Rückgabewert

Instanz der Klasse basierend auf der[`EWSClient`](../../ewsclient) Klasse.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
