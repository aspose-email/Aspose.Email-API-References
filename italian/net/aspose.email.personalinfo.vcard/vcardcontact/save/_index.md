---
title: Save
second_title: Aspose.Email per riferimento all'API .NET
description: Salva questoMapiContactaspose.email.mapi/mapicontact al file vCard con opzioni predefinite. La versione vCard supportata è 2.1
type: docs
weight: 150
url: /it/net/aspose.email.personalinfo.vcard/vcardcontact/save/
---
## Save(string) {#save_3}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact) al file vCard con opzioni predefinite. La versione vCard supportata è 2.1

```csharp
public void Save(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Un nome di file vCard |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *filePath* è`nullo`o`vuoto` |

### Guarda anche

* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact)al file specificato con un formato utilizzando le opzioni predefinite. Il formato di salvataggio supportato è vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Un nome di file vCard |
| saveFormat | ContactSaveFormat | Un formato di salvataggio |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *filePath* è`nullo`o`vuoto` |
| NotSupportedException | il formato specificato non è supportato |

### Guarda anche

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact) in un file utilizzando le opzioni di salvataggio specificate. Le opzioni di salvataggio supportate sono[`VCardSaveOptions`](../../vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Un nome di file vCard |
| saveOptions | ContactSaveOptions | Opzioni di salvataggio |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *filePath* è`nullo`o`vuoto` |
| ArgumentNullException | *saveOptions* è`nullo` |
| NotSupportedException | alcune opzioni di salvataggio non sono supportate |

### Guarda anche

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact) nello stream specificato con il formato vCard. La versione vCard supportata è 2.1

```csharp
public void Save(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso in cui salvare |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *stream* è`nullo` |
| NotSupportedException | *stream* non supporta la scrittura |

### Guarda anche

* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact) allo stream specificato con un formato utilizzando le opzioni predefinite. Il formato di salvataggio supportato è vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso in cui salvare |
| saveFormat | ContactSaveFormat | Un formato di salvataggio |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *stream* è`nullo` |
| NotSupportedException | *stream* non supporta la scrittura |
| NotSupportedException | Il formato specificato non è supportato |

### Guarda anche

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Salva questo[`MapiContact`](../../../aspose.email.mapi/mapicontact) al flusso specificato utilizzando le opzioni di salvataggio specificate. Le opzioni di salvataggio supportate sono[`VCardSaveOptions`](../../vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso in cui salvare |
| saveOptions | ContactSaveOptions | Opzioni di salvataggio |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *stream*o*saveOptions* è`nullo` |
| NotSupportedException | *stream* non supporta la scrittura |
| ArgumentException | errato*saveOptions* |
| NotSupportedException | alcune opzioni di salvataggio non sono supportate |

### Guarda anche

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* spazio dei nomi [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
