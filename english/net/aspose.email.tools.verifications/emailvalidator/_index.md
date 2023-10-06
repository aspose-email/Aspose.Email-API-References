---
title: Class EmailValidator
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Tools.Verifications.EmailValidator class. EmailValidator class provides the capability to validate email addresses
type: docs
weight: 20910
url: /net/aspose.email.tools.verifications/emailvalidator/
---
## EmailValidator class

EmailValidator class provides the capability to validate e-mail addresses.

```csharp
public sealed class EmailValidator
```

## Constructors

| Name | Description |
| --- | --- |
| [EmailValidator](emailvalidator/)() | Create an instance of EmailValidator. |

## Properties

| Name | Description |
| --- | --- |
| [DnsServers](../../aspose.email.tools.verifications/emailvalidator/dnsservers/) { get; set; } | Gets or sets the Dns server list to use in the email validation. |
| [Timeout](../../aspose.email.tools.verifications/emailvalidator/timeout/) { get; set; } | Gets or sets the length of time (in milliseconds) until the request times out. |

## Methods

| Name | Description |
| --- | --- |
| [BeginValidate](../../aspose.email.tools.verifications/emailvalidator/beginvalidate/)(string, ValidationPolicy, out ValidationResult, AsyncCallback, object) | Begins an asynchronous validating process for an email address. |
| [EndValidate](../../aspose.email.tools.verifications/emailvalidator/endvalidate/)(out ValidationResult, IAsyncResult) | Ends an asynchronous validating process for an email address. |
| [Validate](../../aspose.email.tools.verifications/emailvalidator/validate/#validate_1)(string, out ValidationResult) | Validate email address, with the MailServer validation policy. |
| [Validate](../../aspose.email.tools.verifications/emailvalidator/validate/#validate)(string, ValidationPolicy, out ValidationResult) | Validating the email address |

## Events

| Name | Description |
| --- | --- |
| event [DomainValidating](../../aspose.email.tools.verifications/emailvalidator/domainvalidating/) | This event occurs when validating the domain of an email addresss. |
| event [MailServerValidating](../../aspose.email.tools.verifications/emailvalidator/mailservervalidating/) | This event occurs when validating an email addresss on its mail server. |
| event [SyntaxValidating](../../aspose.email.tools.verifications/emailvalidator/syntaxvalidating/) | This event occurs when validating the syntax of an email addresss. |

### See Also

* namespace [Aspose.Email.Tools.Verifications](../../aspose.email.tools.verifications/)
* assembly [Aspose.Email](../../)


