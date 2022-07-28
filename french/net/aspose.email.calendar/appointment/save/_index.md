---
title: Save
second_title: Référence de l'API Aspose.Email pour .NET
description: Enregistre le rendez-vous dans le flux avec les options denregistrement spécifiées
type: docs
weight: 350
url: /fr/net/aspose.email.calendar/appointment/save/
---
## Save(Stream, AppointmentSaveOptions) {#save_2}

Enregistre le rendez-vous dans le flux avec les options d'enregistrement spécifiées

```csharp
public void Save(Stream stream, AppointmentSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveOptions | AppointmentSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *saveOptions*ou*stream* est`nul` |
| NotSupportedException | les options d'enregistrement spécifiées ne sont pas prises en charge |
| NotSupportedException | le flux ne prend pas en charge l'écriture |

### Voir également

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Enregistre le rendez-vous dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut

```csharp
public void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un chemin de fichier |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* est`nul`ou`vide` |

### Voir également

* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Enregistre le rendez-vous dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut

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
| ArgumentOutOfRangeException | *filePath* est`nul`ou`vide` |
| NotSupportedException | Les options d'enregistrement spécifiées ne sont pas prises en charge |

### Voir également

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveOptions) {#save_5}

Enregistre le rendez-vous dans le fichier avec les options d'enregistrement spécifiées

```csharp
public void Save(string filePath, AppointmentSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un chemin de fichier |
| saveOptions | AppointmentSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* est`nul`ou`vide` |
| ArgumentNullException | *saveOptions* est`nul` |
| NotSupportedException | Les options d'enregistrement spécifiées ne sont pas prises en charge |

### Voir également

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Enregistre le rendez-vous dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut

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

* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Enregistre le rendez-vous dans le flux avec le format spécifié à l'aide des options d'enregistrement par défaut

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
| NotSupportedException | Les options d'enregistrement spécifiées ne sont pas prises en charge |
| NotSupportedException | le flux ne prend pas en charge l'écriture |

### Voir également

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* espace de noms [Aspose.Email.Calendar](../../appointment)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
