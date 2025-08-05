---
title: MailMessage.GetHtmlBodyText
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup
type: docs
weight: 510
url: /net/aspose.email/mailmessage/gethtmlbodytext/
---
## GetHtmlBodyText(bool) {#gethtmlbodytext_1}

Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup.

```csharp
public virtual string GetHtmlBodyText(bool showUrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| showUrl | Boolean | Defines need to show URL in text. |

## Examples

The following example shows how to get an email message�s HTML body as plain text.

[C#]

```csharp
var eml = MailMessage.Load("HtmlWithUrlSample.eml");
var bodyWithUrl = eml.GetHtmlBodyText(true);// body will contain URL
var bodyWithoutUrl = eml.GetHtmlBodyText(false);// body will not contain URL

Console.WriteLine($@"Body with URL: {bodyWithUrl}");
Console.WriteLine($@"Body without URL: {bodyWithoutUrl}");
```

[Visual Basic]

```csharp
Dim eml = MailMessage.Load("HtmlWithUrlSample.eml")
Dim bodyWithUrl = eml.GetHtmlBodyText(True)
Dim bodyWithoutUrl = eml.GetHtmlBodyText(False)

Console.WriteLine($"Body with URL: {bodyWithUrl}")
Console.WriteLine($"Body without URL: {bodyWithoutUrl}")
```

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## GetHtmlBodyText(HyperlinkRenderingCallback) {#gethtmlbodytext}

Gets the message htmlbody as plain text.

```csharp
public virtual string GetHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| hyperlinkRenderingCallback | HyperlinkRenderingCallback | Reference to custom method for handling rendering of hyperlink. |

### Return Value

Result string of custom handling rendering of hyperlink.

### See Also

* delegate [HyperlinkRenderingCallback](../../hyperlinkrenderingcallback/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


