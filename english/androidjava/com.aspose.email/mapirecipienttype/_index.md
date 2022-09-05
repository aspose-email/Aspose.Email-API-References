---
title: MapiRecipientType
second_title: Aspose.Email for Android via Java API Reference
description:  Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient.
type: docs
weight: 278
url: /java/com.aspose.email/mapirecipienttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiRecipientType extends System.Enum
```

Represent the PR\_RECIPIENT\_TYPE property which contains the recipient type for a message recipient.
## Fields

| Field | Description |
| --- | --- |
| [MAPI_BCC](#MAPI-BCC) | The recipient is a blind carbon copy (BCC) recipient. |
| [MAPI_CC](#MAPI-CC) | The recipient is a carbon copy (CC) recipient, a recipient that receives a message in addition to the primary recipients. |
| [MAPI_P1](#MAPI-P1) | The recipient did not successfully receive the message on the previous attempt. |
| [MAPI_SUBMITTED](#MAPI-SUBMITTED) | The recipient has already received the message and does not need to receive it again. |
| [MAPI_TO](#MAPI-TO) | The recipient is a primary (To) recipient. |
| [Unknown](#Unknown) | Unknow. |
### MAPI_BCC {#MAPI-BCC}
```
public static final int MAPI_BCC
```


The recipient is a blind carbon copy (BCC) recipient. Primary and carbon copy recipients are unaware of the existence of BCC recipients.

### MAPI_CC {#MAPI-CC}
```
public static final int MAPI_CC
```


The recipient is a carbon copy (CC) recipient, a recipient that receives a message in addition to the primary recipients.

### MAPI_P1 {#MAPI-P1}
```
public static final int MAPI_P1
```


The recipient did not successfully receive the message on the previous attempt. This is a resend of an earlier transmission.

### MAPI_SUBMITTED {#MAPI-SUBMITTED}
```
public static final int MAPI_SUBMITTED
```


The recipient has already received the message and does not need to receive it again. This is a resend of an earlier transmission. This flag is set in conjunction with the MAPI\_TO, MAPI\_CC, and MAPI\_BCC values.

### MAPI_TO {#MAPI-TO}
```
public static final int MAPI_TO
```


The recipient is a primary (To) recipient. Clients are required to handle primary recipients; all other types are optional.

### Unknown {#Unknown}
```
public static final int Unknown
```


Unknow.

