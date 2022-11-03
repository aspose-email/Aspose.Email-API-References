---
title: MapiConversionOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 460
url: /email/python-net/aspose.email.mapi/mapiconversionoptions/
---

## MapiConversionOptions class

This class allows the user to specify additional options when converting from MailMessage to MapiMessage.

The MapiConversionOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiConversionOptions()|Initializes a new instance of the|
|MapiConversionOptions(format)|Initializes a new instance of the MapiConversionOptions class|
## Properties
| Name | Description |
| :- | :- |
|format|Represents outlook message format.|
|preserve_signature|Set to true, if signature is to be preserved.|
|use_body_compression|Set to true, if need RTF body compression.|
|preserve_original_dates|Gets or sets a value indicating whether it is necessary to generate <br/>            new saving and modification dates when converting a message.|
|preserve_original_addresses|Gets or sets a value indicating whether it is necessary to keep <br/>            original value of mail addresses (without validation).|
|preserve_embedded_message_format|Gets or sets a value indicating whether it is necessary to preserve EML format of <br/>            embedded message at converting to MapiMessage. By default the value is false.|
|ascii_format|Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False).|
|unicode_format|Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False).|
|forced_rtf_body_for_appointment|Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment.<br/>            Default value is true.|

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/slides/python-net/)

