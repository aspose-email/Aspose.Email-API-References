---
title: MessageObject.MessageObject
second_title: Aspose.Email for .NET API Reference
description: MessageObject constructor. Initializes a new instance of the MessageObject class
type: docs
weight: 10
url: /net/aspose.email.mapi.msg/messageobject/messageobject/
---
## MessageObject(Stream, MessageObjectLoadFormat) {#constructor}

Initializes a new instance of the [`MessageObject`](../) class.

```csharp
public MessageObject(Stream stream, MessageObjectLoadFormat loadFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to initialize this object from. |
| loadFormat | MessageObjectLoadFormat | The source format message object is stored with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If given stream is null. |
| ArgumentOutOfRangeException | If specified *loadFormat* is not supported. |

### See Also

* enum [MessageObjectLoadFormat](../../messageobjectloadformat/)
* class [MessageObject](../)
* namespace [Aspose.Email.Mapi.Msg](../../messageobject/)
* assembly [Aspose.Email](../../../)

---

## MessageObject(string, MessageObjectLoadFormat) {#constructor_1}

Initializes a new instance of the [`MessageObject`](../) class.

```csharp
public MessageObject(string fileName, MessageObjectLoadFormat loadFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of the file to read from. |
| loadFormat | MessageObjectLoadFormat | The source format message object is stored with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | If specified *loadFormat* is not supported. |

## Remarks

In addition same set of exceptions could be thrown as for the FileMode) call.

### See Also

* enum [MessageObjectLoadFormat](../../messageobjectloadformat/)
* class [MessageObject](../)
* namespace [Aspose.Email.Mapi.Msg](../../messageobject/)
* assembly [Aspose.Email](../../../)


