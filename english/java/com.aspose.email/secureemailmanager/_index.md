---
title: SecureEmailManager
second_title: Aspose.Email for Java API Reference
description: Class that provided methods for working with secure emails.
type: docs
weight: 635
url: /java/com.aspose.email/secureemailmanager/
---

**Inheritance:**
java.lang.Object
```
public class SecureEmailManager
```

Class that provided methods for working with secure emails.
## Constructors

| Constructor | Description |
| --- | --- |
| [SecureEmailManager()](#SecureEmailManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#attachSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| [attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options)](#attachSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.email.SignatureOptions-) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| [attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#attachSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| [attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options)](#attachSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.email.SignatureOptions-) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| [checkSignature(MailMessage msg)](#checkSignature-com.aspose.email.MailMessage-) | Checking signature MailMessage. |
| [checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt)](#checkSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Checking signature MailMessage. |
| [checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store)](#checkSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store-) | Checking signature MailMessage. |
| [checkSignature(MapiMessage msg)](#checkSignature-com.aspose.email.MapiMessage-) | Checking signature MapiMessage. |
| [checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt)](#checkSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Checking signature MapiMessage. |
| [checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store)](#checkSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store-) | Checking signature MapiMessage. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecureEmailManager() {#SecureEmailManager--}
```
public SecureEmailManager()
```


### attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#attachSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```


Creates a copy of the specified MailMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Source MailMessage. |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 certificate. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Signed MailMessage
### attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options) {#attachSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.email.SignatureOptions-}
```
public MailMessage attachSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options)
```


Creates a copy of the specified MailMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Source MailMessage. |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 certificate. |
| options | [SignatureOptions](../../com.aspose.email/signatureoptions) | Additional options [SignatureOptions](../../com.aspose.email/signatureoptions) |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Signed MailMessage
### attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#attachSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MapiMessage attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```


Creates a copy of the specified MapiMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Source MapiMessage. |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 certificate. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Signed MapiMessage
### attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options) {#attachSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.email.SignatureOptions-}
```
public MapiMessage attachSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, SignatureOptions options)
```


Creates a copy of the specified MapiMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Source MapiMessage. |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 certificate. |
| options | [SignatureOptions](../../com.aspose.email/signatureoptions) | Additional options [SignatureOptions](../../com.aspose.email/signatureoptions) |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Signed MapiMessage
### checkSignature(MailMessage msg) {#checkSignature-com.aspose.email.MailMessage-}
```
public final SmimeResult checkSignature(MailMessage msg)
```


Checking signature MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage to check. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt) {#checkSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public final SmimeResult checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt)
```


Checking signature MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage to check. |
| certificateForDecrypt | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | The certificate to decrypt the MailMessage if it is encrypted. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store) {#checkSignature-com.aspose.email.MailMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store-}
```
public final SmimeResult checkSignature(MailMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store)
```


Checking signature MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage to check. |
| certificateForDecrypt | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | The certificate to decrypt the MailMessage if it is encrypted. |
| store | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store | Store to look up encryption certificates, if null then X509Store(StoreLocation.CurrentUser) is used. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### checkSignature(MapiMessage msg) {#checkSignature-com.aspose.email.MapiMessage-}
```
public final SmimeResult checkSignature(MapiMessage msg)
```


Checking signature MapiMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The MapiMessage to check. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt) {#checkSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public final SmimeResult checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt)
```


Checking signature MapiMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The MapiMessage to check. |
| certificateForDecrypt | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | The certificate to decrypt the MapiMessage if it is encrypted. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store) {#checkSignature-com.aspose.email.MapiMessage-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store-}
```
public final SmimeResult checkSignature(MapiMessage msg, System.Security.Cryptography.X509Certificates.X509Certificate2 certificateForDecrypt, System.Security.Cryptography.X509Certificates.X509Store store)
```


Checking signature MapiMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The MapiMessage to check. |
| certificateForDecrypt | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | The certificate to decrypt the MapiMessage if it is encrypted. |
| store | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Store | Store to look up encryption certificates, if null then X509Store(StoreLocation.CurrentUser) is used. |

**Returns:**
[SmimeResult](../../com.aspose.email/smimeresult) - Result of checking[SmimeResult](../../com.aspose.email/smimeresult)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

