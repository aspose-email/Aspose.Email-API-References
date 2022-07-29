---
title: ImapMessageFlags
second_title: Aspose.Email för .NET API-referens
description: Representerar flaggorna som är kopplade till meddelandet.
type: docs
weight: 16360
url: /sv/net/aspose.email.clients.imap/imapmessageflags/
---
## ImapMessageFlags class

Representerar flaggorna som är kopplade till meddelandet.

```csharp
public class ImapMessageFlags : IEquatable<ImapMessageFlags>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Answered](../../aspose.email.clients.imap/imapmessageflags/answered) { get; } | Meddelande har besvarats. |
| static [Deleted](../../aspose.email.clients.imap/imapmessageflags/deleted) { get; } | Meddelandet "raderas" för borttagning senare EXPUNGE. |
| static [Draft](../../aspose.email.clients.imap/imapmessageflags/draft) { get; } | Meddelandet har markerats som ett utkast. |
| static [Empty](../../aspose.email.clients.imap/imapmessageflags/empty) { get; } | Flaggor är inte inställda |
| static [Flagged](../../aspose.email.clients.imap/imapmessageflags/flagged) { get; } | Meddelandet är "flaggat" för brådskande/särskild uppmärksamhet. |
| static [IsRead](../../aspose.email.clients.imap/imapmessageflags/isread) { get; } | Meddelandet har lästs. |
| static [Recent](../../aspose.email.clients.imap/imapmessageflags/recent) { get; } | Meddelandet har "nyligen" kommit till den här brevlådan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [BitwiseAnd](../../aspose.email.clients.imap/imapmessageflags/bitwiseand)(ImapMessageFlags, ImapMessageFlags) | Implementerar operatorn &amp;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor)(ImapMessageFlags, ImapMessageFlags) | Implementerar operatorn &#x7C;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor_1)(ImapMessageFlags, string) | Implementerar operatorn &#x7C;. |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor_2)(string, ImapMessageFlags) | Implementerar operatorn &#x7C;. |
| static [Keyword](../../aspose.email.clients.imap/imapmessageflags/keyword)(string) | Meddelandet har markerats med anpassad flagga. |
| virtual [Equals](../../aspose.email.clients.imap/imapmessageflags/equals#equals)(ImapMessageFlags) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| override [Equals](../../aspose.email.clients.imap/imapmessageflags/equals#equals_1)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| override [GetHashCode](../../aspose.email.clients.imap/imapmessageflags/gethashcode)() | Returnerar en hash-kod för denna instans. |
| [HasFlag](../../aspose.email.clients.imap/imapmessageflags/hasflag)(ImapMessageFlags) | Returnerar sant om "vem" innehåller "flaggan" |
| [IsEmpty](../../aspose.email.clients.imap/imapmessageflags/isempty)() | Avgör om denna instans är tom. |
| [Split](../../aspose.email.clients.imap/imapmessageflags/split)() | Dela upp till Array. |
| override [ToString](../../aspose.email.clients.imap/imapmessageflags/tostring)() | Returnerar enString som representerar denna instans. |
| [operator &amp;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseand) | Implementerar operatorn &amp;. |
| [operator &#x7C;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseor#op_bitwiseor) | Implementerar operatorn &#x7C;. (3 operators) |
| [operator ==](../../aspose.email.clients.imap/imapmessageflags/op_equality) | Implementerar operatorn ==. |
| [implicit operator](../../aspose.email.clients.imap/imapmessageflags/op_implicit) | Utför en implicit konvertering frånInt64 till[`ImapMessageFlags`](../imapmessageflags) . |
| [operator !=](../../aspose.email.clients.imap/imapmessageflags/op_inequality) | Implementerar operatorn !=. |

### Se även

* namnutrymme [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->