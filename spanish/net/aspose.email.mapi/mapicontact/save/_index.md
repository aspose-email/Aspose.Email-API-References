---
title: Save
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda estoMapiContactaspose.email.mapi/mapicontact al archivo vCard con opciones predeterminadas. La versión compatible de vCard es 2.1
type: docs
weight: 140
url: /es/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Guarda esto[`MapiContact`](../../mapicontact) al archivo vCard con opciones predeterminadas. La versión compatible de vCard es 2.1

```csharp
public void Save(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Un nombre de archivo vCard |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |

### Ver también

* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Guarda esto[`MapiContact`](../../mapicontact)al archivo especificado con un formato utilizando las opciones predeterminadas. El formato de guardado compatible es vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Un nombre de archivo vCard |
| saveFormat | ContactSaveFormat | Un formato de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |
| NotSupportedException | el formato especificado no es compatible |

### Ver también

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Guarda esto[`MapiContact`](../../mapicontact) en un archivo utilizando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Un nombre de archivo vCard |
| saveOptions | ContactSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |
| ArgumentNullException | *saveOptions* es`nulo` |
| NotSupportedException | alguna opción de guardar no es compatible |

### Ver también

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Guarda esto[`MapiContact`](../../mapicontact) en el flujo dado con formato vCard. La versión vCard admitida es 2.1

```csharp
public void Save(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream* es`nulo` |
| NotSupportedException | *stream* no admite escritura |

### Ver también

* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Guarda esto[`MapiContact`](../../mapicontact) a la transmisión dada con un formato usando las opciones predeterminadas. El formato de guardado admitido es vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |
| saveFormat | ContactSaveFormat | Un formato de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream* es`nulo` |
| NotSupportedException | *stream* no admite escritura |
| NotSupportedException | El formato especificado no es compatible |

### Ver también

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Guarda esto[`MapiContact`](../../mapicontact) a la transmisión dada usando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |
| saveOptions | ContactSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream*o*saveOptions* es`nulo` |
| NotSupportedException | *stream* no admite escritura |
| ArgumentException | incorrecto*saveOptions* |
| NotSupportedException | alguna opción de guardar no es compatible |

### Ver también

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* espacio de nombres [Aspose.Email.Mapi](../../mapicontact)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
