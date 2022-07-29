---
title: DeleteMessage
second_title: Référence de l'API Aspose.Email pour .NET
description: Supprime le message
type: docs
weight: 70
url: /fr/net/aspose.email.clients.pop3/pop3client/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Supprime le message

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_1}

Supprime le message

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_2}

Supprime le message

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_3}

Supprime le message

```csharp
public void DeleteMessage(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |

### Remarques

Le serveur POP3 marque le message comme supprimé. Le serveur POP3 ne supprime pas réellement le message jusqu'à ce que la session POP3 entre dans l'état UPDATE.

### Voir également

* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->