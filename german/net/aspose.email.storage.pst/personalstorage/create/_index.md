---
title: Create
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt die neue PST-Datei mit dem angegebenen Dateinamen.
type: docs
weight: 20
url: /de/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Erstellt die neue PST-Datei mit dem angegebenen Dateinamen.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der vollständige Name der Datei. |
| version | FileFormatVersion | Die Version der PST-Datei. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | löst aus, wenn der Dateiname null oder leer ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Erstellt die PST in einem Stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem PST erstellt wird. |
| version | FileFormatVersion | Die Version der PST-Datei. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | löst aus, wenn der Dateiname null oder leer ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Erstellt die PST in einem Stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem PST erstellt wird. |
| version | FileFormatVersion | Die Version der PST-Datei. |
| leaveStreamOpen | Boolean | Lassen Sie den Stream geöffnet, wenn PersonalStorage verworfen wird. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | löst aus, wenn der Dateiname null oder leer ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Erstellt die neue PST-Datei mit dem angegebenen Dateinamen.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der vollständige Name der Datei. |
| version | FileFormatVersion | Die Version der PST-Datei. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | löst aus, wenn der Dateiname null oder leer ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Erstellt die PST in einem Stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem PST erstellt wird. |
| version | FileFormatVersion | Die Version der PST-Datei. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | wirft, wenn stream null ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Erstellt die PST in einem Stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem PST erstellt wird. |
| version | FileFormatVersion | Die Version der PST-Datei. |
| leaveStreamOpen | Boolean | Lassen Sie den Stream geöffnet, wenn PersonalStorage verworfen wird. |

### Rückgabewert

Ein PersonalStorage-Objekt, das die neue PST darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | löst aus, wenn eine ANSI-Dateiversion erstellt wird |
| ArgumentNullException | wirft, wenn stream null ist |

### Bemerkungen

Beachten Sie, dass jetzt nur die Erstellung von Unicode-Dateiversionen unterstützt wird.

### Siehe auch

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namensraum [Aspose.Email.Storage.Pst](../../personalstorage)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
