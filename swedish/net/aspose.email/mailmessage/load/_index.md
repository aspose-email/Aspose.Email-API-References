---
title: Load
second_title: Aspose.Email för .NET API-referens
description: Ladda meddelande från file
type: docs
weight: 20
url: /sv/net/aspose.email/mailmessage/load/
---
## Load(string) {#load_2}

Ladda meddelande från file

```csharp
public static MailMessage Load(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Meddelandefilnamn. Meddelandefilen måste vara i eml- eller msg-format. |

### Returvärde

E-postmeddelande

### Se även

* class [MailMessage](../../mailmessage)
* namnutrymme [Aspose.Email](../../mailmessage)
* hopsättning [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Ladda meddelande från stream

```csharp
public static MailMessage Load(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Stream som representerar meddelande i eml- eller msg-format |

### Returvärde

E-postmeddelande

### Se även

* class [MailMessage](../../mailmessage)
* namnutrymme [Aspose.Email](../../mailmessage)
* hopsättning [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Ladda meddelande från fil med ytterligare alternativ.

```csharp
public static MailMessage Load(string fileName, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Källfilens sökvägString. |
| options | LoadOptions | Ytterligare alternativ[`LoadOptions`](../../loadoptions). |

### Returvärde

Mail meddelande[`MailMessage`](../../mailmessage).

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Om*fileName* är inget. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [MailMessage](../../mailmessage)
* namnutrymme [Aspose.Email](../../mailmessage)
* hopsättning [Aspose.Email](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Ladda meddelande från stream med ytterligare alternativ.

```csharp
public static MailMessage Load(Stream stream, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | KällströmStream. |
| options | LoadOptions | Ytterligare alternativ[`LoadOptions`](../../loadoptions). |

### Returvärde

Mail meddelande[`MailMessage`](../../mailmessage).

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Om*stream* är inget. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [MailMessage](../../mailmessage)
* namnutrymme [Aspose.Email](../../mailmessage)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->