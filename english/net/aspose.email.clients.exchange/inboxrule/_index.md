---
title: Class InboxRule
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.InboxRule class. Represents a inbox rule
type: docs
weight: 2070
url: /net/aspose.email.clients.exchange/inboxrule/
---
## InboxRule class

Represents a inbox rule

```csharp
public sealed class InboxRule
```

## Constructors

| Name | Description |
| --- | --- |
| [InboxRule](inboxrule/)() | Initializes a new instance of the `InboxRule` class |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.email.clients.exchange/inboxrule/actions/) { get; set; } | Gets or sets the actions to be taken on a message when the conditions are fulfilled. |
| [Conditions](../../aspose.email.clients.exchange/inboxrule/conditions/) { get; set; } | Gets or sets the conditions that, when fulfilled, will trigger the rule actions for that rule. |
| [DisplayName](../../aspose.email.clients.exchange/inboxrule/displayname/) { get; set; } | Gets or sets the display name of a rule. |
| [Exceptions](../../aspose.email.clients.exchange/inboxrule/exceptions/) { get; set; } | Gets or sets the exceptions that represent all the available rule exception conditions for the inbox rule. |
| [IsEnabled](../../aspose.email.clients.exchange/inboxrule/isenabled/) { get; set; } | Gets or sets a value indicating whether the rule is enabled. |
| [IsInError](../../aspose.email.clients.exchange/inboxrule/isinerror/) { get; } | Gets a value indicating whether the rule is in an error condition. |
| [IsNotSupported](../../aspose.email.clients.exchange/inboxrule/isnotsupported/) { get; } | Gets a value indicating whether the rule cannot be modified with the managed code APIs. |
| [IsReadOnly](../../aspose.email.clients.exchange/inboxrule/isreadonly/) { get; set; } | Gets or sets a value indicating whether the rule is read-only. |
| [Priority](../../aspose.email.clients.exchange/inboxrule/priority/) { get; set; } | Gets or sets a value that indicates the order in which a rule is to be run. |
| [RuleId](../../aspose.email.clients.exchange/inboxrule/ruleid/) { get; set; } | Gets or sets the rule identifier. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateRuleDeleteContaining](../../aspose.email.clients.exchange/inboxrule/createruledeletecontaining/)(string[]) | Creates inbox rule that deletes messages containing the specified strings in either the body or the subject |
| static [CreateRuleDeleteFrom](../../aspose.email.clients.exchange/inboxrule/createruledeletefrom/)(MailAddress) | Creates inbox rule that deletes messages from specified senders |
| static [CreateRuleMoveContaining](../../aspose.email.clients.exchange/inboxrule/createrulemovecontaining/)(string[], string) | Creates inbox rule that moves messages containing the specified strings in either the body or the subject into the specified folder |
| static [CreateRuleMoveFrom](../../aspose.email.clients.exchange/inboxrule/createrulemovefrom/)(MailAddress, string) | Creates inbox rule that moves messages from specified senders into the specified folder |

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


