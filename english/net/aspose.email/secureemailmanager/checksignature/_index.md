---
title: SecureEmailManager.CheckSignature
second_title: Aspose.Email for .NET API Reference
description: SecureEmailManager method. Checking signature MapiMessage
type: docs
weight: 30
url: /net/aspose.email/secureemailmanager/checksignature/
---
## CheckSignature(MapiMessage) {#checksignature_3}

Checking signature MapiMessage.

```csharp
public SmimeResult CheckSignature(MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The MapiMessage to check. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MapiMessage, X509Certificate2) {#checksignature_4}

Checking signature MapiMessage.

```csharp
public SmimeResult CheckSignature(MapiMessage msg, X509Certificate2 certificateForDecrypt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The MapiMessage to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the MapiMessage if it is encrypted. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MapiMessage, X509Certificate2, X509Store) {#checksignature_5}

Checking signature MapiMessage.

```csharp
public SmimeResult CheckSignature(MapiMessage msg, X509Certificate2 certificateForDecrypt, 
    X509Store store)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MapiMessage | The MapiMessage to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the MapiMessage if it is encrypted. |
| store | X509Store | Store to look up encryption certificates, if null then X509Store(StoreLocation.CurrentUser) is used. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage) {#checksignature}

Checking signature MailMessage.

```csharp
public SmimeResult CheckSignature(MailMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The MailMessage to check. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage, X509Certificate2) {#checksignature_1}

Checking signature MailMessage.

```csharp
public SmimeResult CheckSignature(MailMessage msg, X509Certificate2 certificateForDecrypt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The MailMessage to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the MailMessage if it is encrypted. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(MailMessage, X509Certificate2, X509Store) {#checksignature_2}

Checking signature MailMessage.

```csharp
public SmimeResult CheckSignature(MailMessage msg, X509Certificate2 certificateForDecrypt, 
    X509Store store)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The MailMessage to check. |
| certificateForDecrypt | X509Certificate2 | The certificate to decrypt the MailMessage if it is encrypted. |
| store | X509Store | Store to look up encryption certificates, if null then X509Store(StoreLocation.CurrentUser) is used. |

### Return Value

Result of checking[`SmimeResult`](../../smimeresult/)

### See Also

* class [SmimeResult](../../smimeresult/)
* class [MailMessage](../../mailmessage/)
* class [SecureEmailManager](../)
* namespace [Aspose.Email](../../secureemailmanager/)
* assembly [Aspose.Email](../../../)


