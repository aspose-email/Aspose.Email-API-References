---
title: "Aspose::Email::Mapi::Msg::MessageObject class"
linktitle: "MessageObject"
articleTitle: "MessageObject"
second_title: "Aspose.Email for C++"
description: "Represents an Outlook message object."
type: docs
weight: 10
url: /cpp/aspose.email.mapi.msg/messageobject/
---

## MessageObject class

**Inherits:** Aspose::Email::Mapi::Msg::IMessageObjectPropertyContainer

Represents an Outlook message object. Evaluation limits: only 1 attachment and 1 recipient are read when message is being loaded, watermark will be added when the message is being saved.

## Constructors

| Name | Description |
| --- | --- |
| [MessageObject (3 overloads)](./messageobject/) | Initializes a new instance of the MessageObject class, used internally for embedded messages. |

## Methods

| Name | Description |
| --- | --- |
| [get_Attachments](./get_attachments/) | Gets the attachments of the MessageObject . |
| [get_Codepage](./get_codepage/) | Gets the codepage used to encode/decode string properties in case MapiType::PT_STRING8 type for them is used. |
| [get_Properties](./get_properties/) | Gets the properties of the MessageObject . |
| [get_Recipients](./get_recipients/) | Gets the recipients of the MessageObject . |
| [GetIdForNamedProperty](./getidfornamedproperty/) | Gets the id to be used for named property, named properties are special properties and should have their ids in range [0x8000,0xfffe] aligned starting from 0x8000 sequentally. Use this method to find the available id cause it could be hard to calculate it yourself. |
| [Save (2 overloads)](./save/) | Saves the current message object to the specified stream. |

