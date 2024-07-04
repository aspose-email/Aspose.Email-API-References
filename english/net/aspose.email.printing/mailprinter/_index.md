---
title: Class MailPrinter
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Printing.MailPrinter class. Represents a printer for mail messages
type: docs
weight: 20030
url: /net/aspose.email.printing/mailprinter/
---
## MailPrinter class

Represents a printer for mail messages.

```csharp
public sealed class MailPrinter : IPrintSettingsProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [MailPrinter](mailprinter/#constructor)() | Initializes a new instance of the `MailPrinter` class with A4 paper setting for page size and 0.5in margin for all sides. |
| [MailPrinter](mailprinter/#constructor_1)(IPrintSettingsProvider) | Initializes a new instance of the `MailPrinter` class using given settings provider. |

## Properties

| Name | Description |
| --- | --- |
| [CultureName](../../aspose.email.printing/mailprinter/culturename/) { get; set; } | Gets or sets the culture name in the format languagecode2-country/regioncode2. |
| [DpiX](../../aspose.email.printing/mailprinter/dpix/) { get; set; } | Gets or sets the horizontal DPI. |
| [DpiY](../../aspose.email.printing/mailprinter/dpiy/) { get; set; } | Gets or sets the vertical DPI. |
| [FormattingFlags](../../aspose.email.printing/mailprinter/formattingflags/) { get; set; } | Gets or sets the printer options. |
| [MarginBottom](../../aspose.email.printing/mailprinter/marginbottom/) { get; set; } | Gets or sets the bottom margin. |
| [MarginLeft](../../aspose.email.printing/mailprinter/marginleft/) { get; set; } | Gets or sets the left margin. |
| [MarginRight](../../aspose.email.printing/mailprinter/marginright/) { get; set; } | Gets or sets the right margin. |
| [MarginTop](../../aspose.email.printing/mailprinter/margintop/) { get; set; } | Gets or sets the top margin. |
| [PageHeight](../../aspose.email.printing/mailprinter/pageheight/) { get; set; } | Gets or sets the height of the page. |
| [PageUnit](../../aspose.email.printing/mailprinter/pageunit/) { get; set; } | Gets or sets the page unit. |
| [PageWidth](../../aspose.email.printing/mailprinter/pagewidth/) { get; set; } | Gets or sets the width of the page. |

## Methods

| Name | Description |
| --- | --- |
| [Print](../../aspose.email.printing/mailprinter/print/#print)(MailMessage, Stream, PrintFormat) | Prints the specified message object using the desired format. |
| [Print](../../aspose.email.printing/mailprinter/print/#print_1)(MailMessage, string, PrintFormat) | Prints the specified message object using the desired format. |
| [Print](../../aspose.email.printing/mailprinter/print/#print_2)(MapiMessage, Stream, PrintFormat) | Prints the specified MSG object using the desired format. |
| [Print](../../aspose.email.printing/mailprinter/print/#print_3)(MapiMessage, string, PrintFormat) | Prints the specified MSG object using the desired format. |

### See Also

* interface [IPrintSettingsProvider](../iprintsettingsprovider/)
* namespace [Aspose.Email.Printing](../../aspose.email.printing/)
* assembly [Aspose.Email](../../)


