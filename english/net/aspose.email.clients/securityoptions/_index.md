---
title: Enum SecurityOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.SecurityOptions enum. Security mode for a mail client
type: docs
weight: 16950
url: /net/aspose.email.clients/securityoptions/
---
## SecurityOptions enumeration

Security mode for a mail client

```csharp
[Flags]
public enum SecurityOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `1` | Connection is not secured. |
| SSLExplicit | `2` | Uses the STARTTLS command to start SSL/TLS connection. |
| SSLImplicit | `4` | Establishes a SSL/TLS connection first. |
| SSLAuto | `6` | Uses SSL/TLS implicit or SSL/TLS explicit mode automatically. |
| Auto | `7` | Auto selection mode |

### See Also

* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


