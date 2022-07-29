---
title: UnselectFolder
second_title: Référence de l'API Aspose.Email pour .NET
description: Supprime définitivement tous les messages marqués comme supprimés pour le dossier actuellement sélectionné et supprime létat sélectionné pour ce dossier.
type: docs
weight: 1250
url: /fr/net/aspose.email.clients.imap/imapclient/unselectfolder/
---
## UnselectFolder(IConnection) {#unselectfolder_1}

Supprime définitivement tous les messages marqués comme supprimés pour le dossier actuellement sélectionné et supprime l'état sélectionné pour ce dossier.

```csharp
public void UnselectFolder(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## UnselectFolder() {#unselectfolder}

Supprime définitivement tous les messages marqués comme supprimés pour le dossier actuellement sélectionné et supprime l'état sélectionné pour ce dossier.

```csharp
public void UnselectFolder()
```

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## UnselectFolder(IConnection, bool) {#unselectfolder_2}

Désélectionne le dossier actuellement sélectionné. si la propriété doNotExpunge est vraie, tous les messages sont marqués comme supprimés sont supprimés, sinon la suppression est annulée. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC3691 Voir plus https://tools. ietf.org/html/rfc3691

```csharp
public void UnselectFolder(IConnection connection, bool doNotExpunge)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| doNotExpunge | Boolean | Spécifie si les messages marqués comme supprimés doivent être supprimés. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## UnselectFolder(bool) {#unselectfolder_3}

Désélectionne le dossier actuellement sélectionné. si la propriété doNotExpunge est vraie, tous les messages sont marqués comme supprimés sont supprimés, sinon la suppression est annulée. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC3691 Voir plus https://tools. ietf.org/html/rfc3691

```csharp
public void UnselectFolder(bool doNotExpunge)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| doNotExpunge | Boolean | Spécifie si les messages marqués comme supprimés doivent être supprimés. |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->