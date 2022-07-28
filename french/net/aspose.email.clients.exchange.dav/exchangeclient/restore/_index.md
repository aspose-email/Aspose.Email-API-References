---
title: Restore
second_title: Référence de l'API Aspose.Email pour .NET
description: Restaure les dossiers déchange à partir du fichier de stockage personnel spécifié.
type: docs
weight: 350
url: /fr/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Restaure les dossiers d'échange à partir du fichier de stockage personnel spécifié.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Chemin d'accès au fichier de stockage personnel. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* n'est pas spécifié. |

### Voir également

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Restaure les dossiers d'échange à partir du stockage personnel donné.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux contenant un espace de stockage personnel. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | La*stream* ne prend pas en charge la lecture. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* est`nul`. |

### Voir également

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Restaure les dossiers d'échange à partir du stockage personnel donné.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pst | PersonalStorage | Un stockage personnel contenant les dossiers imap sauvegardés. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* est`nul`. |

### Voir également

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Restaure les dossiers d'échange spécifiés à partir du fichier de stockage personnel spécifié.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Chemin d'accès au fichier de stockage personnel. |
| folders | ExchangeFolderInfoCollection | Un dossier à restaurer. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* n'est pas spécifié. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* est`nul`. |

### Voir également

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux contenant un espace de stockage personnel. |
| folders | ExchangeFolderInfoCollection | Un dossier à restaurer. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | La*stream* ne prend pas en charge la lecture. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*ou*folders* est`nul`. |

### Voir également

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pst | PersonalStorage | Un stockage personnel contenant les dossiers d'échange sauvegardés. |
| folders | ExchangeFolderInfoCollection | Un dossier à restaurer. |
| options | RestoreOptions | Options de restauration. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*ou*folders* est`nul`. |

### Voir également

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
