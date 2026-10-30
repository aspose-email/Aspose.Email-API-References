---
title: SecureEmailManager.CheckSignature
second_title: Aspose.Email for .NET API Reference
description: SecureEmailManager method. Verifies the signature of the message
type: docs
weight: 30
url: /net/aspose.email/secureemailmanager/checksignature/
---
## CheckSignature(MapiMessage) {#checksignature_3}

Verifies the signature of the message.

```csharp
public SmimeResult CheckSignature(MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The message to check. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MapiMessage, X509Certificate2) {#checksignature_4}

Verifies the signature of the message, decrypting it first if needed.

```csharp
public SmimeResult CheckSignature(MapiMessage msg, X509Certificate2 certificateForDecrypt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The message to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the message with, if it is encrypted. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MapiMessage, X509Certificate2, X509Store) {#checksignature_5}

Verifies the signature of the message, decrypting it first if needed.

```csharp
public SmimeResult CheckSignature(MapiMessage msg, X509Certificate2 certificateForDecrypt, 
    X509Store store)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The message to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the message with, if it is encrypted. |
| store | X509Store | The store to search for the decryption certificate; `null` for the store of the current user. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage) {#checksignature}

Verifies the signature of the message.

```csharp
public SmimeResult CheckSignature(MailMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The message to check. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage, X509Certificate2) {#checksignature_1}

Verifies the signature of the message, decrypting it first if needed.

```csharp
public SmimeResult CheckSignature(MailMessage msg, X509Certificate2 certificateForDecrypt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The message to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the message with, if it is encrypted. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage, X509Certificate2, X509Store) {#checksignature_2}

Verifies the signature of the message, decrypting it first if needed.

```csharp
public SmimeResult CheckSignature(MailMessage msg, X509Certificate2 certificateForDecrypt, 
    X509Store store)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The message to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the message with, if it is encrypted. |
| store | X509Store | The store to search for the decryption certificate; `null` for the store of the current user. |

### Return Value

The result of the check, with the signing and encryption certificates.

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)


