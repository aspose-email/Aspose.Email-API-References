---
title: MapiMessage.MapiMessage
second_title: Aspose.Email for .NET API Reference
description: MapiMessage constructor. Initializes a new instance of the MapiMessage class
type: docs
weight: 10
url: /net/aspose.email.mapi/mapimessage/mapimessage/
---
## MapiMessage() {#constructor}

Initializes a new instance of the [`MapiMessage`](../) class.

```csharp
public MapiMessage()
```

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(OutlookMessageFormat) {#constructor_1}

Initializes a new instance of the [`MapiMessage`](../) class.

```csharp
public MapiMessage(OutlookMessageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | OutlookMessageFormat | Defines whether to use Unicode or ASCII encoding for this message. |

### See Also

* enum [OutlookMessageFormat](../../outlookmessageformat/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string, OutlookMessageFormat) {#constructor_3}

Initializes a new instance of the [`MapiMessage`](../) class.

```csharp
public MapiMessage(string from, string to, string subject, string body, OutlookMessageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | The From address. |
| to | String | The addresses of recipients. Note, that addresses are separated by semicolon. |
| subject | String | The message subject. |
| body | String | The message body. |
| format | OutlookMessageFormat | Defines whether to use Unicode or ASCII encoding for this message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Is being thrown if address of recipient is null or empty. |
| ArgumentException | Is being thrown if sender or recipient address is not in a recognized format. |
| InvalidEnumArgumentException | Is being thrown if *format* parameter is not a valid enumeration member. |

### See Also

* enum [OutlookMessageFormat](../../outlookmessageformat/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string) {#constructor_2}

Initializes a new instance of the [`MapiMessage`](../) class.

```csharp
public MapiMessage(string from, string to, string subject, string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | The From address. |
| to | String | The addresses of recipients. Note, that addresses are separated by semicolon. |
| subject | String | The message subject. |
| body | String | The message body. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if address of recipient is null or empty. |
| ArgumentException | throws if sender or recipient address is not in a recognized format. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


