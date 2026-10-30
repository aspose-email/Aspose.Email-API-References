---
title: MailMessage.GetHtmlBodyText
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Gets the text of the HTML body without the markup
type: docs
weight: 510
url: /net/aspose.email/mailmessage/gethtmlbodytext/
---
## GetHtmlBodyText(bool) {#gethtmlbodytext_1}

Gets the text of the HTML body without the markup.

```csharp
public virtual string GetHtmlBodyText(bool showUrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| showUrl | Boolean | `true` to write the URLs of hyperlinks after their text. |

### Return Value

The text of the HTML body.

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

Gets the text of the HTML body without the markup, rendering hyperlinks with a custom method.

```csharp
public virtual string GetHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| hyperlinkRenderingCallback | HyperlinkRenderingCallback | The method that renders each hyperlink as text. |

### Return Value

The text of the HTML body.

### See Also

* delegate [HyperlinkRenderingCallback](../../hyperlinkrenderingcallback/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


