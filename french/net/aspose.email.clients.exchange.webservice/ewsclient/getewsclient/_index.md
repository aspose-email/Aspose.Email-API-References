---
title: GetEWSClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Initialise une nouvelle instance duEWSClientaspose.email.clients.exchange.webservice/ewsclient classe basée
type: docs
weight: 10
url: /fr/net/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---
## GetEWSClient(string, ICredentials) {#getewsclient_2}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| credentials | ICredentials | Contient les informations d'identification pour l'authentification. |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string) {#getewsclient_4}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| username | String | L'identifiant |
| password | String | Le mot de passe |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, WebProxy) {#getewsclient_5}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    WebProxy proxy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| username | String | L'identifiant |
| password | String | Le mot de passe |
| proxy | WebProxy | Contient les paramètres de proxy HTTP |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string) {#getewsclient_6}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| username | String | L'identifiant |
| password | String | Le mot de passe |
| domain | String | Le nom de domaine |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(string, string, string, string, WebProxy) {#getewsclient_7}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, string username, string password, 
    string domain, WebProxy proxy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| username | String | L'identifiant |
| password | String | Le mot de passe |
| domain | String | Le nom de domaine |
| proxy | WebProxy | Contient les paramètres de proxy HTTP |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, string, ICredentials, WebProxy) {#getewsclient_1}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, string mailboxUri, 
    ICredentials credentials, WebProxy proxy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versions du serveur Exchange |
| mailboxUri | String | L'URI de la boîte aux lettres |
| credentials | ICredentials | Contient les informations d'identification pour l'authentification. |
| proxy | WebProxy | Contient les paramètres de proxy HTTP |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(ExchangeVersion, bool, string, string, ICredentials, WebProxy) {#getewsclient}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(ExchangeVersion serverVersion, 
    bool formbasedAuthenticationRequired, string formbasedAuthenticationLocation, 
    string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| serverVersion | ExchangeVersion | Versions du serveur Exchange |
| formbasedAuthenticationRequired | Boolean | Définissez true si une authentification basée sur un formulaire est requise, sinon définissez false. |
| formbasedAuthenticationLocation | String | URL pour l'authentification par formulaire |
| mailboxUri | String | L'URI de la boîte aux lettres |
| credentials | ICredentials | Contient les informations d'identification pour l'authentification. |
| proxy | WebProxy | Contient les paramètres de proxy HTTP |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* enum [ExchangeVersion](../../exchangeversion)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

---

## GetEWSClient(string, ICredentials, WebProxy) {#getewsclient_3}

Initialise une nouvelle instance du[`EWSClient`](../../ewsclient) classe basée

```csharp
public static IEWSClient GetEWSClient(string mailboxUri, ICredentials credentials, WebProxy proxy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailboxUri | String | L'URI de la boîte aux lettres |
| credentials | ICredentials | Contient les informations d'identification pour l'authentification. |
| proxy | WebProxy | Contient les paramètres de proxy HTTP |

### Return_Value

Instance de la classe basée sur le[`EWSClient`](../../ewsclient) classer.

### Voir également

* interface [IEWSClient](../../iewsclient)
* class [EWSClient](../../ewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../ewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
