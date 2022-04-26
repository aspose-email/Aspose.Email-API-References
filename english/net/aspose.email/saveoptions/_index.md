---
title: SaveOptions
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 18100
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
| [CustomProgressHandler](customprogresshandler) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [MailMessageSaveType](mailmessagesavetype) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| static [DefaultEml](defaulteml) { get; } | Gets options with default values for saving message to Eml format. |
| static [DefaultHtml](defaulthtml) { get; } | Gets options with default values for saving message to Html format. |
| static [DefaultMhtml](defaultmhtml) { get; } | Gets options with default values for saving message to Mhtml format. |
| static [DefaultMsg](defaultmsg) { get; } | Gets options with default values for saving message to Msg(ASCII) format. |
| static [DefaultMsgUnicode](defaultmsgunicode) { get; } | Gets options with default values for saving message to Msg(Unicode) format. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateSaveOptions](createsaveoptions)(MailMessageSaveType) | Creates a save options object of a class suitable for the specified save type. |

### See Also

* namespace [Aspose.Email](../../aspose.email)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->