---
title: Class ImapMessageFlags
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapMessageFlags class. Represents the flags associated with the message
type: docs
weight: 16410
url: /net/aspose.email.clients.imap/imapmessageflags/
---
## ImapMessageFlags class

Represents the flags associated with the message.

```csharp
public class ImapMessageFlags : IEquatable<ImapMessageFlags>
```

## Properties

| Name | Description |
| --- | --- |
| static [Answered](../../aspose.email.clients.imap/imapmessageflags/answered/) { get; } | Message has been answered. |
| static [Deleted](../../aspose.email.clients.imap/imapmessageflags/deleted/) { get; } | Message is "deleted" for removal by later EXPUNGE. |
| static [Draft](../../aspose.email.clients.imap/imapmessageflags/draft/) { get; } | Message has been marked as a draft. |
| static [Empty](../../aspose.email.clients.imap/imapmessageflags/empty/) { get; } | Flags are not set |
| static [Flagged](../../aspose.email.clients.imap/imapmessageflags/flagged/) { get; } | Message is "flagged" for urgent/special attention. |
| static [IsRead](../../aspose.email.clients.imap/imapmessageflags/isread/) { get; } | Message has been read. |
| static [Recent](../../aspose.email.clients.imap/imapmessageflags/recent/) { get; } | Message is "recently" arrived in this mailbox. |

## Methods

| Name | Description |
| --- | --- |
| static [BitwiseAnd](../../aspose.email.clients.imap/imapmessageflags/bitwiseand/)(ImapMessageFlags, ImapMessageFlags) | Implements the operator &amp;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor/#bitwiseor)(ImapMessageFlags, ImapMessageFlags) | Implements the operator &#x7C;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor/#bitwiseor_1)(ImapMessageFlags, string) | Implements the operator &#x7C;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor/#bitwiseor_2)(string, ImapMessageFlags) | Implements the operator &#x7C;. |
| static [Keyword](../../aspose.email.clients.imap/imapmessageflags/keyword/)(string) | Message has been marked by custom flag. |
| virtual [Equals](../../aspose.email.clients.imap/imapmessageflags/equals/#equals)(ImapMessageFlags) | Determines whether the specified object is equal to the current object. |
| override [Equals](../../aspose.email.clients.imap/imapmessageflags/equals/#equals_1)(object) | Determines whether the specified Object is equal to this instance. |
| override [GetHashCode](../../aspose.email.clients.imap/imapmessageflags/gethashcode/)() | Returns a hash code for this instance. |
| [HasFlag](../../aspose.email.clients.imap/imapmessageflags/hasflag/)(ImapMessageFlags) | Returns true if "who" contains the "flag" |
| [IsEmpty](../../aspose.email.clients.imap/imapmessageflags/isempty/)() | Determines whether this instance is empty. |
| [Split](../../aspose.email.clients.imap/imapmessageflags/split/)() | Split to Array. |
| override [ToString](../../aspose.email.clients.imap/imapmessageflags/tostring/)() | Returns a String that represents this instance. |
| [operator &amp;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseand/) | Implements the operator &amp;. |
| [operator &#x7C;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseor/#op_bitwiseor) | Implements the operator &#x7C;. (3 operators) |
| [operator ==](../../aspose.email.clients.imap/imapmessageflags/op_equality/) | Implements the operator ==. |
| [implicit operator](../../aspose.email.clients.imap/imapmessageflags/op_implicit/) | Performs an implicit conversion from Int64 to `ImapMessageFlags`. |
| [operator !=](../../aspose.email.clients.imap/imapmessageflags/op_inequality/) | Implements the operator !=. |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


