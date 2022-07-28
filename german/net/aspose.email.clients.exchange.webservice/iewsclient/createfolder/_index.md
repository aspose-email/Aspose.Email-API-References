---
title: CreateFolder
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt den neuen Ordner mit dem angegebenen Namen im angegebenen übergeordneten Ordner.
type: docs
weight: 500
url: /de/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Erstellt den neuen Ordner mit dem angegebenen Namen im angegebenen übergeordneten Ordner.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentFolderUri | String | Ein URI des übergeordneten Ordners. |
| name | String | Ein Name des zu erstellenden Ordners. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*oder*name* ist`Null`oder`leer`. |

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Erstellt den neuen Ordner

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentFolderUri | String | Der URI des übergeordneten Ordners |
| name | String | Der Name des neuen Ordners |
| permissions | ExchangeFolderPermissionCollection | Eine Berechtigung für einen neuen Ordner |

### Rückgabewert

Gibt Ordnerinformationen zurück

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Erstellt den neuen Ordner

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentFolderUri | String | Der URI des übergeordneten Ordners |
| name | String | Der Name des neuen Ordners |
| permissions | ExchangeFolderPermissionCollection | Eine Berechtigung für einen neuen Ordner |
| folderClass | String | Die Klasse des neuen Ordners |

### Rückgabewert

Gibt Ordnerinformationen zurück

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Erstellt einen neuen Ordner im Stammordner.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name des neuen Ordners |
| folderType | ExchangeFolderType | Art des Ordners |

### Rückgabewert

Gibt Ordnerinformationen zurück

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Erstellt den neuen Ordner

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentFolderUri | String | Der URI des übergeordneten Ordners |
| name | String | Der Name des neuen Ordners |
| folderType | ExchangeFolderType | Art des Ordners |

### Rückgabewert

Gibt Ordnerinformationen zurück

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Erstellt einen neuen Ordner im Stammordner.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name des neuen Ordners |

### Rückgabewert

Gibt Ordnerinformationen zurück

### Siehe auch

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
