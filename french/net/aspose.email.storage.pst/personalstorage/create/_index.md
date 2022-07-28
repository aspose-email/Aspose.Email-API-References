---
title: Create
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée le nouveau fichier PST avec le nom de fichier spécifié.
type: docs
weight: 20
url: /fr/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Crée le nouveau fichier PST avec le nom de fichier spécifié.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Le nom complet du fichier. |
| version | FileFormatVersion | La version du fichier PST. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le nom du fichier est nul ou vide |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Crée le PST dans un flux.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel PST est créé. |
| version | FileFormatVersion | La version du fichier PST. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le nom du fichier est nul ou vide |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Crée le PST dans un flux.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel PST est créé. |
| version | FileFormatVersion | La version du fichier PST. |
| leaveStreamOpen | Boolean | Laissez le flux ouvert lorsque PersonalStorage est supprimé. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le nom du fichier est nul ou vide |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Crée le nouveau fichier PST avec le nom de fichier spécifié.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Le nom complet du fichier. |
| version | FileFormatVersion | La version du fichier PST. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le nom du fichier est nul ou vide |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Crée le PST dans un flux.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel PST est créé. |
| version | FileFormatVersion | La version du fichier PST. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le flux est nul |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Crée le PST dans un flux.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel PST est créé. |
| version | FileFormatVersion | La version du fichier PST. |
| leaveStreamOpen | Boolean | Laissez le flux ouvert lorsque PersonalStorage est supprimé. |

### Return_Value

Un objet PersonalStorage qui représente le nouveau PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | lève si la version du fichier ANSI est créée |
| ArgumentNullException | lance si le flux est nul |

### Remarques

Notez que seule la création de version de fichier Unicode est désormais prise en charge.

### Voir également

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espace de noms [Aspose.Email.Storage.Pst](../../personalstorage)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
