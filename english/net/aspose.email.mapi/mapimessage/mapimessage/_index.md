---
title: MapiMessage.MapiMessage
second_title: Aspose.Email for .NET API Reference
description: MapiMessage constructor. Initializes a new instance of the MapiMessage class an empty message
type: docs
weight: 10
url: /net/aspose.email.mapi/mapimessage/mapimessage/
---
## MapiMessage() {#constructor}

Initializes a new instance of the [`MapiMessage`](../) class: an empty message.

```csharp
public MapiMessage()
```

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(OutlookMessageFormat) {#constructor_1}

Initializes a new instance of the [`MapiMessage`](../) class: an empty message in the specified format.

```csharp
public MapiMessage(OutlookMessageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | OutlookMessageFormat | The format of the message: Unicode or ANSI. |

### See Also

* enum [OutlookMessageFormat](../../outlookmessageformat/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string, OutlookMessageFormat) {#constructor_3}

Initializes a new instance of the [`MapiMessage`](../) class with a sender, recipients, a subject and a body, in the specified format.

```csharp
public MapiMessage(string from, string to, string subject, string body, OutlookMessageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | The address of the sender. |
| to | String | The addresses of the To recipients, separated by semicolons (`;`). |
| subject | String | The subject. |
| body | String | The plain-text body. |
| format | OutlookMessageFormat | The format of the message: Unicode or ANSI. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *to* is `null` or empty. |
| ArgumentException | An address in *from* or *to* is not valid. |
| InvalidEnumArgumentException | *format* is not a valid value. |

### See Also

* enum [OutlookMessageFormat](../../outlookmessageformat/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string) {#constructor_2}

Initializes a new instance of the [`MapiMessage`](../) class with a sender, recipients, a subject and a body, in Unicode format.

```csharp
public MapiMessage(string from, string to, string subject, string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | The address of the sender. |
| to | String | The addresses of the To recipients, separated by semicolons (`;`). |
| subject | String | The subject. |
| body | String | The plain-text body. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *to* is `null` or empty. |
| ArgumentException | An address in *from* or *to* is not valid. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


