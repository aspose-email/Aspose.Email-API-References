---
title: CheckSignature
second_title: Aspose.Email per riferimento all'API .NET
description: Verifica la firma del file eml specificato.
type: docs
weight: 580
url: /it/net/aspose.email/mailmessage/checksignature/
---
## CheckSignature(string) {#checksignature_1}

Verifica la firma del file eml specificato.

```csharp
public static bool CheckSignature(string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Un nome file (eml). |

### Valore di ritorno

`Vero` se la firma è valida; altrimenti,`falso`.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *fileName* è`nullo`o`vuoto`. |
| FileNotFoundException | Il specificato*fileName* non esiste. |
| NotSupportedException | Il tipo di firma non è supportato. |
| InvalidOperationException | Il messaggio di posta non è firmato o il tipo di firma non è specificato. |

### Guarda anche

* class [MailMessage](../../mailmessage)
* spazio dei nomi [Aspose.Email](../../mailmessage)
* assemblea [Aspose.Email](../../../)

---

## CheckSignature(Stream) {#checksignature}

Verifica la firma del messaggio eml specificato.

```csharp
public static bool CheckSignature(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso contenente il messaggio in formato eml. |

### Valore di ritorno

`Vero` se la firma è valida; altrimenti,`falso`.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *stream* è`nullo`. |
| NotSupportedException | Il tipo di firma non è supportato. |
| InvalidOperationException | Il messaggio di posta non è firmato o il tipo di firma non è specificato. |

### Guarda anche

* class [MailMessage](../../mailmessage)
* spazio dei nomi [Aspose.Email](../../mailmessage)
* assemblea [Aspose.Email](../../../)

---

## CheckSignature()

Verifica della firma esistente MailMessage.

```csharp
public virtual X509Certificate2[] CheckSignature()
```

### Valore di ritorno

Certificati dei firmatari X.509

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Genera se il messaggio di posta non è firmato o la firma non è verificata. |

### Guarda anche

* class [MailMessage](../../mailmessage)
* spazio dei nomi [Aspose.Email](../../mailmessage)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->