---
title: SmtpException.SmtpException
second_title: Aspose.Email for .NET API Reference
description: SmtpException constructor. Initializes a new instance of the SmtpException class with the status code returned by the server
type: docs
weight: 10
url: /net/aspose.email/smtpexception/smtpexception/
---
## SmtpException(SmtpStatusCode) {#constructor_1}

Initializes a new instance of the [`SmtpException`](../) class with the status code returned by the server.

```csharp
public SmtpException(SmtpStatusCode statusCode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | SmtpStatusCode | The SMTP status code. |

### See Also

* enum [SmtpStatusCode](../../../aspose.email.clients.smtp/smtpstatuscode/)
* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(SmtpStatusCode, string) {#constructor_2}

Initializes a new instance of the [`SmtpException`](../) class with the status code returned by the server and an error message.

```csharp
public SmtpException(SmtpStatusCode statusCode, string message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | SmtpStatusCode | The SMTP status code. |
| message | String | The message that describes the error. |

### See Also

* enum [SmtpStatusCode](../../../aspose.email.clients.smtp/smtpstatuscode/)
* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException() {#constructor}

Initializes a new instance of the [`SmtpException`](../) class.

```csharp
public SmtpException()
```

### See Also

* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(string) {#constructor_3}

Initializes a new instance of the [`SmtpException`](../) class with the specified error message.

```csharp
public SmtpException(string message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |

### See Also

* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(string, SendMessagesResult) {#constructor_4}

Initializes a new instance of the [`SmtpException`](../) class with an error message and the result of sending several messages.

```csharp
public SmtpException(string message, SendMessagesResult result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |
| result | SendMessagesResult | The sent and failed messages. |

### See Also

* class [SendMessagesResult](../../../aspose.email.clients.smtp/sendmessagesresult/)
* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(string, Exception) {#constructor_6}

Initializes a new instance of the [`SmtpException`](../) class with the specified error message and a reference to the exception that caused it.

```csharp
public SmtpException(string message, Exception innerException)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |
| innerException | Exception | The exception that caused this exception, or `null`. |

### See Also

* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(string, Exception, MailMessage) {#constructor_7}

Initializes a new instance of the [`SmtpException`](../) class for a message that could not be sent.

```csharp
public SmtpException(string message, Exception innerException, MailMessage mailMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |
| innerException | Exception | The exception that caused this exception, or `null`. |
| mailMessage | MailMessage | The message that could not be sent. |

### See Also

* class [MailMessage](../../mailmessage/)
* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)

---

## SmtpException(string, MailMessage) {#constructor_5}

Initializes a new instance of the [`SmtpException`](../) class for a message that could not be sent.

```csharp
public SmtpException(string message, MailMessage mailMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |
| mailMessage | MailMessage | The message that could not be sent. |

### See Also

* class [MailMessage](../../mailmessage/)
* class [SmtpException](../)
* namespace [Aspose.Email](../../smtpexception/)
* assembly [Aspose.Email](../../../)


