---
title: Save
second_title: Référence de l'API Aspose.Email pour .NET
description: Enregistre lobjet de calendrier dans le fichier au format spécifié à laide des options denregistrement par défaut
type: docs
weight: 220
url: /fr/net/aspose.email.mapi/mapicalendar/save/
---
## Save(string, MapiCalendarSaveOptions) {#save_5}

Enregistre l'objet de calendrier dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut

```csharp
public void Save(string filePath, MapiCalendarSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un chemin de fichier |
| saveOptions | MapiCalendarSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |
| NotSupportedException | les options d'enregistrement spécifiées ne sont pas prises en charge |

### Voir également

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions)
* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, MapiCalendarSaveOptions) {#save_2}

Enregistre le calendrier dans le flux avec les options d'enregistrement spécifiées

```csharp
public void Save(Stream stream, MapiCalendarSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveOptions | MapiCalendarSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *saveOptions*ou*stream* est`nul` |
| NotSupportedException | les options d'enregistrement spécifiées ne sont pas prises en charge |
| NotSupportedException | le flux ne prend pas en charge l'écriture |

### Voir également

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions)
* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Enregistre l'objet calendrier dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut

```csharp
public void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un chemin de fichier |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |

### Voir également

* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Enregistre l'objet de calendrier dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un chemin de fichier |
| saveFormat | AppointmentSaveFormat | Un format de sauvegarde |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |
| NotSupportedException | Le spécifié*saveFormat* n'est pas pris en charge |

### Voir également

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat)
* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Enregistre l'objet calendrier dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut

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
| NotSupportedException | le flux ne prend pas en charge l'écriture |

### Voir également

* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Enregistre l'objet de calendrier dans le flux avec le format spécifié à l'aide des options d'enregistrement par défaut

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveFormat | AppointmentSaveFormat | Un format de sauvegarde |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* est`nul` |
| NotSupportedException | Le spécifié*saveFormat* n'est pas pris en charge |
| NotSupportedException | le flux ne prend pas en charge l'écriture |

### Voir également

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat)
* class [MapiCalendar](../../mapicalendar)
* espace de noms [Aspose.Email.Mapi](../../mapicalendar)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
