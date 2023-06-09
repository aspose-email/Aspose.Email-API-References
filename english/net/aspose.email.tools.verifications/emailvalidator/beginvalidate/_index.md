---
title: EmailValidator.BeginValidate
second_title: Aspose.Email for .NET API Reference
description: EmailValidator method. Begins an asynchronous validating process for an email address
type: docs
weight: 70
url: /net/aspose.email.tools.verifications/emailvalidator/beginvalidate/
---
## EmailValidator.BeginValidate method

Begins an asynchronous validating process for an email address.

```csharp
public IAsyncResult BeginValidate(string mailAddress, ValidationPolicy policy, 
    out ValidationResult result, AsyncCallback asyncCallback, object stateObject)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | String | The email address to be validated. |
| policy | ValidationPolicy | The policy of the validating process. |
| result | ValidationResult& | The result of the validating process. |
| asyncCallback | AsyncCallback | The AsyncCallback delegate |
| stateObject | Object | An object that contains state information for this request. |

### Return Value

An IAsyncResult that references the asynchronous connection.

### See Also

* enum [ValidationPolicy](../../validationpolicy/)
* class [ValidationResult](../../validationresult/)
* class [EmailValidator](../)
* namespace [Aspose.Email.Tools.Verifications](../../emailvalidator/)
* assembly [Aspose.Email](../../../)


