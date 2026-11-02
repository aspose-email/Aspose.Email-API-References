---
title: TimeoutException.TimeoutException
second_title: Aspose.Email for .NET API Reference
description: TimeoutException constructor. Initializes a new instance of the TimeoutException class with the specified error message
type: docs
weight: 10
url: /net/aspose.email/timeoutexception/timeoutexception/
---
## TimeoutException(string) {#constructor_1}

Initializes a new instance of the [`TimeoutException`](../) class with the specified error message.

```csharp
public TimeoutException(string message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message that describes the error. |

### See Also

* class [TimeoutException](../)
* namespace [Aspose.Email](../../timeoutexception/)
* assembly [Aspose.Email](../../../)

---

## TimeoutException(string, params object[]) {#constructor_3}

Initializes a new instance of the [`TimeoutException`](../) class with an error message built from a composite format string.

```csharp
public TimeoutException(string format, params object[] parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | String | A composite format string, as for `String.Format`. |
| parameters | Object[] | The objects to insert into *format*. |

### See Also

* class [TimeoutException](../)
* namespace [Aspose.Email](../../timeoutexception/)
* assembly [Aspose.Email](../../../)

---

## TimeoutException(string, int) {#constructor_2}

Initializes a new instance of the [`TimeoutException`](../) class with an error message built from a format string and the timeout.

```csharp
public TimeoutException(string format, int timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | String | A composite format string with one placeholder, `{0}`, for the timeout. |
| timeout | Int32 | The timeout, in milliseconds. |

### See Also

* class [TimeoutException](../)
* namespace [Aspose.Email](../../timeoutexception/)
* assembly [Aspose.Email](../../../)

---

## TimeoutException(string, string, int) {#constructor_4}

Initializes a new instance of the [`TimeoutException`](../) class with an error message built from a format string, the command and the timeout.

```csharp
public TimeoutException(string format, string command, int timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | String | A composite format string with placeholders `{0}` for the command and `{1}` for the timeout. |
| command | String | The command that timed out. |
| timeout | Int32 | The timeout, in milliseconds. |

### See Also

* class [TimeoutException](../)
* namespace [Aspose.Email](../../timeoutexception/)
* assembly [Aspose.Email](../../../)

---

## TimeoutException() {#constructor}

Initializes a new instance of the [`TimeoutException`](../) class.

```csharp
public TimeoutException()
```

### See Also

* class [TimeoutException](../)
* namespace [Aspose.Email](../../timeoutexception/)
* assembly [Aspose.Email](../../../)


