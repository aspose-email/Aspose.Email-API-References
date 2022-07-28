---
title: Create
second_title: Aspose.Email för .NET API-referens
description: Skapar den nya PST-filen med det angivna filnamnet.
type: docs
weight: 20
url: /sv/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Skapar den nya PST-filen med det angivna filnamnet.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Filens fullständiga namn. |
| version | FileFormatVersion | PST-filversionen. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om filnamnet är null eller tomt |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Skapar PST i en ström.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen där PST skapas. |
| version | FileFormatVersion | PST-filversionen. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om filnamnet är null eller tomt |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Skapar PST i en ström.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen där PST skapas. |
| version | FileFormatVersion | PST-filversionen. |
| leaveStreamOpen | Boolean | Lämna strömmen öppen när PersonalStorage kasseras. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om filnamnet är null eller tomt |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Skapar den nya PST-filen med det angivna filnamnet.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Det fullständiga namnet på filen. |
| version | FileFormatVersion | PST-filversionen. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om filnamnet är null eller tomt |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Skapar PST i en ström.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen där PST skapas. |
| version | FileFormatVersion | PST-filversionen. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om strömmen är null |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Skapar PST i en ström.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen där PST skapas. |
| version | FileFormatVersion | PST-filversionen. |
| leaveStreamOpen | Boolean | Lämna strömmen öppen när PersonalStorage kasseras. |

### Returvärde

Ett PersonalStorage-objekt som representerar den nya PST.

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | kastar om ANSI-filversionen skapas |
| ArgumentNullException | kastar om strömmen är null |

### Anmärkningar

Observera att det bara är skapandet av Unicode-filversioner som stöds nu.

### Se även

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namnutrymme [Aspose.Email.Storage.Pst](../../personalstorage)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
