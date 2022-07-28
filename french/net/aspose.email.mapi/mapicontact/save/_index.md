---
title: Save
second_title: Référence de l'API Aspose.Email pour .NET
description: Enregistre ceciMapiContactaspose.email.mapi/mapicontact au fichier vCard avec une option par défaut. La version vCard prise en charge est 2.1
type: docs
weight: 140
url: /fr/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Enregistre ceci[`MapiContact`](../../mapicontact) au fichier vCard avec une option par défaut. La version vCard prise en charge est 2.1

```csharp
public void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |

### Voir également

* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Enregistre ceci[`MapiContact`](../../mapicontact)au fichier spécifié avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |
| saveFormat | ContactSaveFormat | Un format de sauvegarde |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |
| NotSupportedException | le format spécifié n'est pas pris en charge |

### Voir également

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Enregistre ceci[`MapiContact`](../../mapicontact) dans le fichier à l'aide des options d'enregistrement spécifiées. Les options d'enregistrement prises en charge sont[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |
| saveOptions | ContactSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |
| ArgumentNullException | *saveOptions* est`nul` |
| NotSupportedException | certaines options de sauvegarde ne sont pas prises en charge |

### Voir également

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Enregistre ceci[`MapiContact`](../../mapicontact) dans le flux donné au format vCard. La version vCard prise en charge est 2.1

```csharp
public void Save(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* est`nul` |
| NotSupportedException | *stream* ne prend pas en charge l'écriture |

### Voir également

* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Enregistre ceci[`MapiContact`](../../mapicontact) au flux donné avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveFormat | ContactSaveFormat | Un format de sauvegarde |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* est`nul` |
| NotSupportedException | *stream* ne prend pas en charge l'écriture |
| NotSupportedException | Le format spécifié n'est pas pris en charge |

### Voir également

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Enregistre ceci[`MapiContact`](../../mapicontact) au flux donné en utilisant les options de sauvegarde spécifiées. Les options de sauvegarde prises en charge sont[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveOptions | ContactSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream*ou*saveOptions* est`nul` |
| NotSupportedException | *stream* ne prend pas en charge l'écriture |
| ArgumentException | Incorrect*saveOptions* |
| NotSupportedException | certaines options de sauvegarde ne sont pas prises en charge |

### Voir également

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* espace de noms [Aspose.Email.Mapi](../../mapicontact)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
