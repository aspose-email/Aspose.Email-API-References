---
title: HtmlSaveOptions
second_title: Aspose.Email für .NET-API-Referenz
description: Ermöglicht die Angabe zusätzlicher Optionen beim Speichern von MailMessage im HTML-Format.
type: docs
weight: 17550
url: /de/net/aspose.email/htmlsaveoptions/
---
## HtmlSaveOptions class

Ermöglicht die Angabe zusätzlicher Optionen beim Speichern von MailMessage im HTML-Format.

```csharp
public class HtmlSaveOptions : HeadersFormattingOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um eine MailMessage im HTML-Format zu speichern. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat) { get; set; } | Format nach Kopfzeilen. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat) { get; set; } | Format vor Kopfzeilen. |
| [CheckBodyContentEncoding](../../aspose.email/htmlsaveoptions/checkbodycontentencoding) { get; set; } | Definiert, ob beim Speichern die Codierung des Nachrichtentextinhalts überprüft werden muss. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles) { get; set; } | Ruft die zusätzlichen CSS-Stile für den Formatierer ab oder legt sie fest. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler) { get; set; } | Stellt eine Methode dar, die normalerweise von der aufrufenden Seite bereitgestellt wird, und verarbeitet Fortschrittsereignisse. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat) { get; set; } | Standardformat der Kopfzeile. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat) { get; set; } | Standardseitenkopfformat. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates) { get; } | Ruft die Formatvorlagen ab. |
| [HtmlFormatOptions](../../aspose.email/htmlsaveoptions/htmlformatoptions) { get; set; } | Liest oder setzt zusätzliche Optionen beim Speichern im HTML-Format. Standardwert ist HtmlFormatOptions.None. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype) { get; set; } | Repräsentiert den Speichertyp der E-Mail-Nachricht. Sie kann im Format eml, msg (ASCII oder Unicode), mhtml oder html vorliegen. Der Standardwert ist Eml. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields) { get; set; } | Definiert Gruppen von Kontaktfeldern, die in die mhtml-Ausgabe aufgenommen werden. Der Standardwert ist ContactFieldsSet.AllExisting. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders) { get; } | Ruft eine Liste der Header zum Rendern ab. |
| [ResourceRenderingMode](../../aspose.email/htmlsaveoptions/resourcerenderingmode) { get; set; } | Stellt verschiedene Modi zum Rendern von Ressourcen in HTML bereit. Standardwert EmbedIntoHtml. |
| [SaveResourceHandler](../../aspose.email/htmlsaveoptions/saveresourcehandler) { get; set; } | Dieser Handler wird aufgerufen, um alle Nachrichtenanhänge zu speichern, wenn EmbedResources falsch ist. |

### Siehe auch

* class [HeadersFormattingOptions](../headersformattingoptions)
* namensraum [Aspose.Email](../../aspose.email)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->