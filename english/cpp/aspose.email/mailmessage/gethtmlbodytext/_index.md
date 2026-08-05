---
title: "Aspose::Email::MailMessage::GetHtmlBodyText method"
linktitle: "GetHtmlBodyText"
articleTitle: "GetHtmlBodyText"
second_title: "Aspose.Email for C++"
description: "Gets the message html body as plain text."
type: docs
weight: 620
url: /cpp/aspose.email/mailmessage/gethtmlbodytext/
---

## GetHtmlBodyText (1 of 2) {#gethtmlbodytext_1}

Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup.

**Returns:** virtual System::String Aspose::Email::

```cpp
GetHtmlBodyText(bool showUrl)
```

| Parameter | Description |
| --- | --- |
| showUrl | Defines need to show URL in text. |

---

## GetHtmlBodyText (2 of 2) {#gethtmlbodytext_2}

Gets the message htmlbody as plain text.

**Returns:** Result string of custom handling rendering of hyperlink.

```cpp
GetHtmlBodyText(Common::Transform::HyperlinkRenderingCallback hyperlinkRenderingCallback)
```

| Parameter | Description |
| --- | --- |
| hyperlinkRenderingCallback | Reference to custom method for handling rendering of hyperlink. |

