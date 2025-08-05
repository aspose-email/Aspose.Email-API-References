---
title: EmailValidator.Validate
second_title: Aspose.Email for .NET API Reference
description: EmailValidator method. Validating the email address
type: docs
weight: 70
url: /net/aspose.email.tools.verifications/emailvalidator/validate/
---
## Validate(string, ValidationPolicy, out ValidationResult) {#validate}

Validating the email address

```csharp
public void Validate(string mailAddress, ValidationPolicy policy, out ValidationResult result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | String | The mail address to be validated. |
| policy | ValidationPolicy | The policy of the validating process. |
| result | ValidationResult& | The result of the validating process. |

### See Also

* enum [ValidationPolicy](../../validationpolicy/)
* class [ValidationResult](../../validationresult/)
* class [EmailValidator](../)
* namespace [Aspose.Email.Tools.Verifications](../../emailvalidator/)
* assembly [Aspose.Email](../../../)

---

## Validate(string, out ValidationResult) {#validate_1}

Validate email address, with the MailServer validation policy.

```csharp
public void Validate(string mailAddress, out ValidationResult result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | String | The Email address to be validated. |
| result | ValidationResult& | The result of the validation. |

### See Also

* class [ValidationResult](../../validationresult/)
* class [EmailValidator](../)
* namespace [Aspose.Email.Tools.Verifications](../../emailvalidator/)
* assembly [Aspose.Email](../../../)


