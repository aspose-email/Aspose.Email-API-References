---
title: HyperlinkRenderingCallback
second_title: Aspose.Email for Java API Reference
description: Represents a method that renders a hyperlink of the HTML body as text for .
type: docs
weight: 782
url: /java/com.aspose.email/hyperlinkrenderingcallback/
---
```
public interface HyperlinkRenderingCallback
```

Represents a method that renders a hyperlink of the HTML body as text, for [MailMessage.getHtmlBodyText(boolean)](../../com.aspose.email/mailmessage\#getHtmlBodyText-boolean-).

The method receives  source : the HTML of the hyperlink. It returns the text to write in place of the hyperlink.
## Methods

| Method | Description |
| --- | --- |
| [invoke(String source)](#invoke-java.lang.String-) |  |
### invoke(String source) {#invoke-java.lang.String-}
```
public abstract String invoke(String source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String |  |

**Returns:**
java.lang.String
