---
title: VCardContact
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un contact vCard
type: docs
weight: 19570
url: /fr/net/aspose.email.personalinfo.vcard/vcardcontact/
---
## VCardContact class

Représente un contact vCard

```csharp
public sealed class VCardContact
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [VCardContact](vcardcontact)() | Initialise une nouvelle instance du[`VCardContact`](../vcardcontact) classe |

## Propriétés

| Nom | La description |
| --- | --- |
| [DeliveryAddresses](../../aspose.email.personalinfo.vcard/vcardcontact/deliveryaddresses) { get; set; } | Obtient ou définit une adresse de livraison |
| [Emails](../../aspose.email.personalinfo.vcard/vcardcontact/emails) { get; set; } | Obtient ou définit les adresses e-mail d'un contact |
| [ExplanatoryInfo](../../aspose.email.personalinfo.vcard/vcardcontact/explanatoryinfo) { get; set; } | Obtient ou définit une information explicative vCard |
| [ExtendedProperties](../../aspose.email.personalinfo.vcard/vcardcontact/extendedproperties) { get; set; } | Obtient ou définit une propriété étendue |
| [Geo](../../aspose.email.personalinfo.vcard/vcardcontact/geo) { get; set; } | Obtient ou définit un positionnement global |
| [IdentificationInfo](../../aspose.email.personalinfo.vcard/vcardcontact/identificationinfo) { get; set; } | Obtient ou définit une propriété d'identification |
| [Labels](../../aspose.email.personalinfo.vcard/vcardcontact/labels) { get; set; } | Obtient ou définit une adresse de livraison |
| [Mailer](../../aspose.email.personalinfo.vcard/vcardcontact/mailer) { get; set; } | Obtient ou définit un mailer |
| [Organization](../../aspose.email.personalinfo.vcard/vcardcontact/organization) { get; set; } | Obtient ou définit les informations d'une organisation |
| [Security](../../aspose.email.personalinfo.vcard/vcardcontact/security) { get; set; } | Obtient ou définit une propriété de sécurité |
| [TelephoneNumbers](../../aspose.email.personalinfo.vcard/vcardcontact/telephonenumbers) { get; set; } | Obtient ou définit les numéros de téléphone d'un contact |
| [TimeZone](../../aspose.email.personalinfo.vcard/vcardcontact/timezone) { get; set; } | Obtient ou définit un timeZone |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load)(Stream) | Lectures[`VCardContact`](../vcardcontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_4)(string) | Lectures[`VCardContact`](../vcardcontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_3)(Stream, CancellationToken) | Lectures[`VCardContact`](../vcardcontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_1)(Stream, Encoding) | Lectures[`VCardContact`](../vcardcontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_7)(string, CancellationToken) | Lectures[`VCardContact`](../vcardcontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_5)(string, Encoding) | Lectures[`VCardContact`](../vcardcontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_2)(Stream, Encoding, CancellationToken) | Lectures[`VCardContact`](../vcardcontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_6)(string, Encoding, CancellationToken) | Lectures[`VCardContact`](../vcardcontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save)(Stream) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact) dans le flux donné au format vCard. La version vCard prise en charge est 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_3)(string) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact) au fichier vCard avec une option par défaut. La version vCard prise en charge est 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_1)(Stream, ContactSaveFormat) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact) au flux donné avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_2)(Stream, ContactSaveOptions) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact) au flux donné en utilisant les options de sauvegarde spécifiées. Les options de sauvegarde prises en charge sont[`VCardSaveOptions`](../vcardsaveoptions) |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_4)(string, ContactSaveFormat) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact)au fichier spécifié avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard. |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_5)(string, ContactSaveOptions) | Enregistre ceci[`MapiContact`](../../aspose.email.mapi/mapicontact) dans le fichier à l'aide des options d'enregistrement spécifiées. Les options d'enregistrement prises en charge sont[`VCardSaveOptions`](../vcardsaveoptions) |
| static [IsMultiContacts](../../aspose.email.personalinfo.vcard/vcardcontact/ismulticontacts)(Stream) | Vérifie si le flux source contient plusieurs contacts. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple)(Stream, Encoding) | Charge la liste des contacts à partir du flux multi-contacts. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_2)(string, Encoding) | Charge la liste des contacts à partir du fichier multi-contacts. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_1)(Stream, Encoding, CancellationToken) | Charge la liste des contacts à partir du flux multi-contacts. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_3)(string, Encoding, CancellationToken) | Charge la liste des contacts à partir du flux multi-contacts. |

### Voir également

* espace de noms [Aspose.Email.PersonalInfo.VCard](../../aspose.email.personalinfo.vcard)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
