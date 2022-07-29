---
title: AttachSignature
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital.
type: docs
weight: 390
url: /es/net/aspose.email/mailmessage/attachsignature/
---
## AttachSignature(X509Certificate2, bool) {#attachsignature_3}

Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate, bool detached)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate2 | Certificado X.509. |
| detached | Boolean | .Si tachado es verdadero, la firma se separa. Si tachado es falso (valor predeterminado), la firma no se separa. |

### Ver también

* class [MailMessage](../../mailmessage)
* espacio de nombres [Aspose.Email](../../mailmessage)
* asamblea [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner, bool) {#attachsignature_1}

Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer, bool detached)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signer | CmsSigner | Sistema.Seguridad.Criptografía.Pkcs.CmsSigner. |
| detached | Boolean | .Si tachado es verdadero, la firma se separa. Si tachado es falso (valor predeterminado), la firma no se separa. |

### Valor_devuelto

El mensaje de correo firmado.

### Ver también

* class [MailMessage](../../mailmessage)
* espacio de nombres [Aspose.Email](../../mailmessage)
* asamblea [Aspose.Email](../../../)

---

## AttachSignature(X509Certificate2) {#attachsignature_2}

Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate2 | Certificado X.509. |

### Valor_devuelto

El mensaje de correo firmado.

### Ver también

* class [MailMessage](../../mailmessage)
* espacio de nombres [Aspose.Email](../../mailmessage)
* asamblea [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner) {#attachsignature}

Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signer | CmsSigner | Sistema.Seguridad.Criptografía.Pkcs.CmsSigner. |

### Valor_devuelto

El mensaje de correo firmado.

### Ver también

* class [MailMessage](../../mailmessage)
* espacio de nombres [Aspose.Email](../../mailmessage)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->