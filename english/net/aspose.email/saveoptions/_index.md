---
title: Class SaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.SaveOptions class. This is an abstract base class for classes that allow the user to specify additional options when saving a MailMessage into a particular format
type: docs
weight: 20070
url: /net/aspose.email/saveoptions/
---
## SaveOptions class

This is an abstract base class for classes that allow the user to specify additional options when saving a MailMessage into a particular format.

```csharp
public abstract class SaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| static [DefaultEml](../../aspose.email/saveoptions/defaulteml/) { get; } | Gets options with default values for saving message to Eml format. |
| static [DefaultEmlx](../../aspose.email/saveoptions/defaultemlx/) { get; } | Gets options with default values for saving message to Emlx format. |
| static [DefaultHtml](../../aspose.email/saveoptions/defaulthtml/) { get; } | Gets options with default values for saving message to Html format. |
| static [DefaultMhtml](../../aspose.email/saveoptions/defaultmhtml/) { get; } | Gets options with default values for saving message to Mhtml format. |
| static [DefaultMsg](../../aspose.email/saveoptions/defaultmsg/) { get; } | Gets options with default values for saving message to Msg(ASCII) format. |
| static [DefaultMsgUnicode](../../aspose.email/saveoptions/defaultmsgunicode/) { get; } | Gets options with default values for saving message to Msg(Unicode) format. |
| static [DefaultOft](../../aspose.email/saveoptions/defaultoft/) { get; } | Gets options with default values for saving message to Outlook template (Oft) format. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateSaveOptions](../../aspose.email/saveoptions/createsaveoptions/)(MailMessageSaveType) | Creates a save options object of a class suitable for the specified save type. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


