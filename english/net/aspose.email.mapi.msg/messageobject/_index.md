---
title: Class MessageObject
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.Msg.MessageObject class. Represents an Outlook message object. Evaluation limits only 1 attachment and 1 recipient are read when message is being loaded watermark will be added when the message is being saved
type: docs
weight: 18990
url: /net/aspose.email.mapi.msg/messageobject/
---
## MessageObject class

Represents an Outlook message object. Evaluation limits: only 1 attachment and 1 recipient are read when message is being loaded, watermark will be added when the message is being saved.

```csharp
public sealed class MessageObject : IMessageObjectPropertyContainer
```

## Constructors

| Name | Description |
| --- | --- |
| [MessageObject](messageobject/#constructor)(Stream, MessageObjectLoadFormat) | Initializes a new instance of the `MessageObject` class. |
| [MessageObject](messageobject/#constructor_1)(string, MessageObjectLoadFormat) | Initializes a new instance of the `MessageObject` class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi.msg/messageobject/attachments/) { get; } | Gets the attachments of the `MessageObject`. |
| [Codepage](../../aspose.email.mapi.msg/messageobject/codepage/) { get; } | Gets the codepage used to encode/decode string properties in case PT_STRING8 type for them is used. |
| [Properties](../../aspose.email.mapi.msg/messageobject/properties/) { get; } | Gets the properties of the `MessageObject`. |
| [Recipients](../../aspose.email.mapi.msg/messageobject/recipients/) { get; } | Gets the recipients of the `MessageObject`. |

## Methods

| Name | Description |
| --- | --- |
| [GetIdForNamedProperty](../../aspose.email.mapi.msg/messageobject/getidfornamedproperty/)() | Gets the id to be used for named property, named properties are special properties and should have their ids in range [0x8000,0xfffe] aligned starting from 0x8000 sequentally. Use this method to find the available id cause it could be hard to calculate it yourself. |
| [Save](../../aspose.email.mapi.msg/messageobject/save/#save)(Stream, MessageObjectSaveFormat) | Saves the current message object to the specified stream. |
| [Save](../../aspose.email.mapi.msg/messageobject/save/#save_1)(string, MessageObjectSaveFormat) | Saves the current message object to the specified file. |

### See Also

* interface [IMessageObjectPropertyContainer](../imessageobjectpropertycontainer/)
* namespace [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg/)
* assembly [Aspose.Email](../../)


