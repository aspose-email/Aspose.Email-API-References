---
title: Class SaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.SaveOptions class. Serves as the abstract base class for formatspecific options when saving MailMessage to various email formats EML EMLX MSG MHTML HTML etc.. This class provides common configuration properties such as custom progress handlers and save type configuration
type: docs
weight: 18810
url: /net/aspose.email/saveoptions/
---
## SaveOptions class

Serves as the abstract base class for format-specific options when saving [`MailMessage`](../mailmessage/) to various email formats (EML, EMLX, MSG, MHTML, HTML, etc.). This class provides common configuration properties such as custom progress handlers and save type configuration.

```csharp
public abstract class SaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| static [DefaultEml](../../aspose.email/saveoptions/defaulteml/) { get; } | Gets new options with the default settings for saving to EML. |
| static [DefaultEmlx](../../aspose.email/saveoptions/defaultemlx/) { get; } | Gets new options with the default settings for saving to EMLX. |
| static [DefaultHtml](../../aspose.email/saveoptions/defaulthtml/) { get; } | Gets new options with the default settings for saving to HTML. |
| static [DefaultMhtml](../../aspose.email/saveoptions/defaultmhtml/) { get; } | Gets new options with the default settings for saving to MHTML. |
| static [DefaultMsg](../../aspose.email/saveoptions/defaultmsg/) { get; } | Gets new options with the default settings for saving to MSG with ANSI strings. |
| static [DefaultMsgUnicode](../../aspose.email/saveoptions/defaultmsgunicode/) { get; } | Gets new options with the default settings for saving to MSG with Unicode strings. |
| static [DefaultOft](../../aspose.email/saveoptions/defaultoft/) { get; } | Gets new options with the default settings for saving to Outlook template (OFT). |

## Methods

| Name | Description |
| --- | --- |
| static [CreateSaveOptions](../../aspose.email/saveoptions/createsaveoptions/)(MailMessageSaveType) | Creates save options of the class that matches the specified format. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`EmlSaveOptions`](../emlsaveoptions/), [`MsgSaveOptions`](../msgsaveoptions/), [`HtmlSaveOptions`](../htmlsaveoptions/), and [`MhtSaveOptions`](../mhtsaveoptions/). Do not instantiate this class directly. Use the format-specific subclasses or the static factory methods like [`DefaultEml`](./defaulteml/), [`DefaultMsg`](./defaultmsg/), [`DefaultHtml`](./defaulthtml/), etc.

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


