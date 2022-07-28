---
title: DeleteMessage
second_title: Référence de l'API Aspose.Email pour .NET
description: Marque un message avec le numéro de séquence spécifié comme supprimé
type: docs
weight: 560
url: /fr/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
