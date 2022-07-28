---
title: DeleteMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Supprime le message
type: docs
weight: 80
url: /fr/net/aspose.email.clients.pop3/pop3client/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Supprime le message

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_2}

Supprime le message

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_4}

Supprime le message

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_6}

Supprime le message

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_1}

Supprime le message

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_3}

Supprime le message

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_5}

Supprime le message

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_7}

Supprime le message

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
