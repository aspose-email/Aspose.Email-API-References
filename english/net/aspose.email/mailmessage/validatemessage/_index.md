---
title: MailMessage.ValidateMessage
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Validate eml message for corresponding to mime specification
type: docs
weight: 600
url: /net/aspose.email/mailmessage/validatemessage/
---
## ValidateMessage(string) {#validatemessage_1}

Validate eml message for corresponding to mime specification.

```csharp
public static EmlValidationErrorCollection ValidateMessage(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | A file name (eml). |

### Return Value

A [`EmlValidationErrorCollection`](../../emlvalidationerrorcollection/) containing the found validation error messages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| FileNotFoundException | The specified *fileName* doesn't exist. |

### See Also

* class [EmlValidationErrorCollection](../../emlvalidationerrorcollection/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## ValidateMessage(Stream) {#validatemessage}

Validate eml message for corresponding to mime specification.

```csharp
public static EmlValidationErrorCollection ValidateMessage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream containing the message in eml format. |

### Return Value

A [`EmlValidationErrorCollection`](../../emlvalidationerrorcollection/) containing the found validation error messages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |

### See Also

* class [EmlValidationErrorCollection](../../emlvalidationerrorcollection/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


