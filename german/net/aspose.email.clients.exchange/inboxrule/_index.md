---
title: InboxRule
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt eine Posteingangsregel dar
type: docs
weight: 3510
url: /de/net/aspose.email.clients.exchange/inboxrule/
---
## InboxRule class

Stellt eine Posteingangsregel dar

```csharp
public sealed class InboxRule
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [InboxRule](inboxrule)() | Initialisiert eine neue Instanz von[`InboxRule`](../inboxrule) Klasse |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.email.clients.exchange/inboxrule/actions) { get; set; } | Ruft die Aktionen ab oder legt sie fest, die bei einer Nachricht ausgeführt werden sollen, wenn die Bedingungen erfüllt sind. |
| [Conditions](../../aspose.email.clients.exchange/inboxrule/conditions) { get; set; } | Ruft die Bedingungen ab oder legt sie fest, die bei Erfüllung die Regelaktionen für diese Regel auslösen. |
| [DisplayName](../../aspose.email.clients.exchange/inboxrule/displayname) { get; set; } | Ruft den Anzeigenamen einer Regel ab oder legt ihn fest. |
| [Exceptions](../../aspose.email.clients.exchange/inboxrule/exceptions) { get; set; } | Ruft die Ausnahmen ab oder legt sie fest, die alle verfügbaren Regelausnahmebedingungen für die Posteingangsregel darstellen. |
| [IsEnabled](../../aspose.email.clients.exchange/inboxrule/isenabled) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Regel aktiviert ist. |
| [IsInError](../../aspose.email.clients.exchange/inboxrule/isinerror) { get; } | Ruft einen Wert ab, der angibt, ob sich die Regel in einem Fehlerzustand befindet. |
| [IsNotSupported](../../aspose.email.clients.exchange/inboxrule/isnotsupported) { get; } | Ruft einen Wert ab, der angibt, ob die Regel nicht mit den verwalteten Code-APIs geändert werden kann. |
| [IsReadOnly](../../aspose.email.clients.exchange/inboxrule/isreadonly) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Regel schreibgeschützt ist. |
| [Priority](../../aspose.email.clients.exchange/inboxrule/priority) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die Reihenfolge angibt, in der eine Regel ausgeführt werden soll. |
| [RuleId](../../aspose.email.clients.exchange/inboxrule/ruleid) { get; set; } | Ruft die Regelkennung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateRuleDeleteContaining](../../aspose.email.clients.exchange/inboxrule/createruledeletecontaining)(string[]) | Erstellt eine Posteingangsregel, die Nachrichten löscht, die die angegebenen Zeichenfolgen entweder im Text oder im Betreff enthalten |
| static [CreateRuleDeleteFrom](../../aspose.email.clients.exchange/inboxrule/createruledeletefrom)(MailAddress) | Erstellt eine Posteingangsregel, die Nachrichten von angegebenen Absendern löscht |
| static [CreateRuleMoveContaining](../../aspose.email.clients.exchange/inboxrule/createrulemovecontaining)(string[], string) | Erstellt eine Posteingangsregel, die Nachrichten mit den angegebenen Zeichenfolgen entweder im Text oder im Betreff in den angegebenen Ordner verschiebt |
| static [CreateRuleMoveFrom](../../aspose.email.clients.exchange/inboxrule/createrulemovefrom)(MailAddress, string) | Erstellt eine Posteingangsregel, die Nachrichten von bestimmten Absendern in den angegebenen Ordner verschiebt |

### Siehe auch

* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->