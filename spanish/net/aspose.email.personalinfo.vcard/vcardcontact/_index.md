---
title: VCardContact
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un contacto vCard
type: docs
weight: 19570
url: /es/net/aspose.email.personalinfo.vcard/vcardcontact/
---
## VCardContact class

Representa un contacto vCard

```csharp
public sealed class VCardContact
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VCardContact](vcardcontact)() | Inicializa una nueva instancia del[`VCardContact`](../vcardcontact) clase |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DeliveryAddresses](../../aspose.email.personalinfo.vcard/vcardcontact/deliveryaddresses) { get; set; } | Obtiene o establece una dirección de entrega |
| [Emails](../../aspose.email.personalinfo.vcard/vcardcontact/emails) { get; set; } | Obtiene o establece las direcciones de correo electrónico de un contacto |
| [ExplanatoryInfo](../../aspose.email.personalinfo.vcard/vcardcontact/explanatoryinfo) { get; set; } | Obtiene o establece una información explicativa de vCard |
| [ExtendedProperties](../../aspose.email.personalinfo.vcard/vcardcontact/extendedproperties) { get; set; } | Obtiene o establece una propiedad extendida |
| [Geo](../../aspose.email.personalinfo.vcard/vcardcontact/geo) { get; set; } | Obtiene o establece un posicionamiento global |
| [IdentificationInfo](../../aspose.email.personalinfo.vcard/vcardcontact/identificationinfo) { get; set; } | Obtiene o establece unas propiedades de identificación |
| [Labels](../../aspose.email.personalinfo.vcard/vcardcontact/labels) { get; set; } | Obtiene o establece una dirección de entrega |
| [Mailer](../../aspose.email.personalinfo.vcard/vcardcontact/mailer) { get; set; } | Obtiene o establece un mailer |
| [Organization](../../aspose.email.personalinfo.vcard/vcardcontact/organization) { get; set; } | Obtiene o establece información de una organización |
| [Security](../../aspose.email.personalinfo.vcard/vcardcontact/security) { get; set; } | Obtiene o establece una propiedad de seguridad |
| [TelephoneNumbers](../../aspose.email.personalinfo.vcard/vcardcontact/telephonenumbers) { get; set; } | Obtiene o establece los números de teléfono de un contacto |
| [TimeZone](../../aspose.email.personalinfo.vcard/vcardcontact/timezone) { get; set; } | Obtiene o establece una zona horaria |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load)(Stream) | Lecturas[`VCardContact`](../vcardcontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_4)(string) | Lecturas[`VCardContact`](../vcardcontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_3)(Stream, CancellationToken) | Lecturas[`VCardContact`](../vcardcontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_1)(Stream, Encoding) | Lecturas[`VCardContact`](../vcardcontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_7)(string, CancellationToken) | Lecturas[`VCardContact`](../vcardcontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_5)(string, Encoding) | Lecturas[`VCardContact`](../vcardcontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_2)(Stream, Encoding, CancellationToken) | Lecturas[`VCardContact`](../vcardcontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_6)(string, Encoding, CancellationToken) | Lecturas[`VCardContact`](../vcardcontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save)(Stream) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact) en el flujo dado con formato vCard. La versión vCard admitida es 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_3)(string) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact) al archivo vCard con opciones predeterminadas. La versión compatible de vCard es 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_1)(Stream, ContactSaveFormat) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact) a la transmisión dada con un formato usando las opciones predeterminadas. El formato de guardado admitido es vCard |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_2)(Stream, ContactSaveOptions) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact) a la transmisión dada usando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../vcardsaveoptions) |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_4)(string, ContactSaveFormat) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact)al archivo especificado con un formato utilizando las opciones predeterminadas. El formato de guardado compatible es vCard. |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_5)(string, ContactSaveOptions) | Guarda esto[`MapiContact`](../../aspose.email.mapi/mapicontact) en un archivo utilizando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../vcardsaveoptions) |
| static [IsMultiContacts](../../aspose.email.personalinfo.vcard/vcardcontact/ismulticontacts)(Stream) | Comprueba si el flujo de origen contiene varios contactos. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple)(Stream, Encoding) | Carga la lista de contactos del flujo de contactos múltiples. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_2)(string, Encoding) | Carga la lista de contactos desde un archivo de contacto múltiple. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_1)(Stream, Encoding, CancellationToken) | Carga la lista de contactos del flujo de contactos múltiples. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_3)(string, Encoding, CancellationToken) | Carga la lista de contactos del flujo de contactos múltiples. |

### Ver también

* espacio de nombres [Aspose.Email.PersonalInfo.VCard](../../aspose.email.personalinfo.vcard)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
