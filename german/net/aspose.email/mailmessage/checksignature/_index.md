---
title: CheckSignature
second_title: Aspose.Email für .NET-API-Referenz
description: Prüft die Signatur der angegebenen EML-Datei.
type: docs
weight: 580
url: /de/net/aspose.email/mailmessage/checksignature/
---
## CheckSignature(string) {#checksignature_1}

Prüft die Signatur der angegebenen EML-Datei.

```csharp
public static bool CheckSignature(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Ein Dateiname (eml). |

### Rückgabewert

`WAHR` ob die Unterschrift gültig ist; Andernfalls,`FALSCH`.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | *fileName* ist`Null`oder`leer`. |
| FileNotFoundException | Die angegebene*fileName* existiert nicht. |
| NotSupportedException | Signaturtyp wird nicht unterstützt. |
| InvalidOperationException | Die E-Mail-Nachricht ist nicht signiert oder der Signaturtyp ist nicht angegeben. |

### Siehe auch

* class [MailMessage](../../mailmessage)
* namensraum [Aspose.Email](../../mailmessage)
* Montage [Aspose.Email](../../../)

---

## CheckSignature(Stream) {#checksignature}

Prüft die Signatur der angegebenen EML-Nachricht.

```csharp
public static bool CheckSignature(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Nachricht im EML-Format enthält. |

### Rückgabewert

`WAHR` ob die Unterschrift gültig ist; Andernfalls,`FALSCH`.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *stream* ist`Null`. |
| NotSupportedException | Signaturtyp wird nicht unterstützt. |
| InvalidOperationException | Die E-Mail-Nachricht ist nicht signiert oder der Signaturtyp ist nicht angegeben. |

### Siehe auch

* class [MailMessage](../../mailmessage)
* namensraum [Aspose.Email](../../mailmessage)
* Montage [Aspose.Email](../../../)

---

## CheckSignature()

Prüfung der Signatur vorhandener MailMessage.

```csharp
public virtual X509Certificate2[] CheckSignature()
```

### Rückgabewert

X.509-Unterzeichnerzertifikate

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn die E-Mail-Nachricht nicht signiert oder die Signatur nicht verifiziert ist. |

### Siehe auch

* class [MailMessage](../../mailmessage)
* namensraum [Aspose.Email](../../mailmessage)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->