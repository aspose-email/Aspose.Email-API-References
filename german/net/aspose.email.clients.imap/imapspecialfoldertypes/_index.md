---
title: ImapSpecialFolderTypes
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert die Aufzählung von Postfächern für besondere Zwecke Weitere Details siehe RFC6154 http//tools.ietf.org/html/rfc6154
type: docs
weight: 16490
url: /de/net/aspose.email.clients.imap/imapspecialfoldertypes/
---
## ImapSpecialFolderTypes enumeration

Repräsentiert die Aufzählung von Postfächern für besondere Zwecke Weitere Details siehe RFC6154 http://tools.ietf.org/html/rfc6154

```csharp
public enum ImapSpecialFolderTypes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NotSpecified | `0` | Wenn IMAP LIST Extension for Special-Use Mailboxes (RFC6154) unterstützt wird, bedeutet dies, dass die Mailbox regulär ist und nicht für spezielle Zwecke verwendet wird. |
| All | `1` | Dieses Postfach enthält alle Nachrichten im Nachrichtenspeicher des Benutzers. Implementierungen KÖNNEN einige Meldungen weglassen, wie etwa die in \Trash und \Junk. Wenn diese spezielle Verwendung unterstützt wird, handelt es sich fast sicher um ein virtuelles Postfach. |
| Archive | `2` | Dieses Postfach wird zum Archivieren von Nachrichten verwendet. Die Bedeutung eines "archivierten" Postfachs ist serverabhängig; normalerweise wird es verwendet, um Nachrichten aus dem Posteingang zu entfernen, oder sie auf andere Weise aus dem Weg des Benutzers zu halten, während sie dennoch zugänglich sind. |
| Drafts | `3` | Dieses Postfach wird normalerweise verwendet, um Nachrichtenentwürfe zu speichern, Nachrichten, die verfasst, aber noch nicht gesendet wurden. Bei einigen Serverimplementierungen kann dies ein virtuelles Postfach sein, das Nachrichten aus anderen Postfächern enthält, die mit dem Symbol „\Entwurf“ gekennzeichnet sind. Nachrichtenkennzeichen. Alternativ könnte dies auch nur ein Hinweis sein, dass ein Kunde Entwürfe hier abgelegt hat. |
| Flagged | `4` | Dieses Postfach stellt alle Nachrichten dar, die irgendwie als „wichtig“ gekennzeichnet sind. Wenn diese spezielle Verwendung unterstützt wird, stellt es wahrscheinlich ein virtuelles Postfach dar, das Nachrichten (von anderen Postfächern) sammelt, die mit dem Nachrichtenflag „\Flagged“ gekennzeichnet sind. |
| Junk | `5` | In diesem Postfach werden Nachrichten aufbewahrt, die als Junk-Mail eingestuft werden. Einige Serverimplementierungen können Nachrichten hier automatisch ablegen. Alternativ könnte dies auch nur ein Hinweis für einen clientseitigen Spamfilter sein. |
| Sent | `6` | Dieses Postfach wird verwendet, um Kopien von Nachrichten zu speichern, die gesendet wurden. Einige Serverimplementierungen können Nachrichten hier automatisch ablegen. Alternativ könnte dies auch nur ein Hinweis sein, dass ein Client gesendete Nachrichten hier speichert. |
| Trash | `7` | Dieses Postfach wird zum Speichern von Nachrichten verwendet, die gelöscht oder zum Löschen markiert wurden. In einigen Serverimplementierungen kann dies ein virtuelles Postfach sein, das Nachrichten aus anderen Postfächern enthält, die mit dem Nachrichten-Flag "\Deleted" markiert sind. Alternativ könnte dies auch nur ein Hinweis sein, dass ein Client, der das IMAP-Modell "\Deleted" nicht verwenden möchte, dies als seinen Papierkorb verwenden sollte. In Serverimplementierungen, die strikt das IMAP-Modell "\Deleted" erwarten, wird diese spezielle Verwendung wahrscheinlich nicht unterstützt. |
| Important | `8` | Dieses Postfach wird verwendet, um Nachrichten zu speichern, die als wichtig markiert wurden. Das Postfachattribut „\Important“ ist ein Signal dafür, dass das Postfach Nachrichten enthält, die für den Benutzer wahrscheinlich wichtig sind. In einer Implementierung, die auch die Option „$Important " Schlüsselwort, stellt diese spezielle Verwendung wahrscheinlich ein virtuelles Postfach dar, das Nachrichten (von anderen Postfächern) sammelt, die mit dem Schlüsselwort "$Important" gekennzeichnet sind. In anderen Implementierungen platziert das System Nachrichten möglicherweise automatisch dort, basierend auf der gleichen Art von Heuristik, die für das Schlüsselwort „$Important“ angegeben ist. Die Unterscheidung zwischen „\Important“ und „\Flagged“ für Postfächer ist ähnlich wie die zwischen „$Important“ und „\Flagged“ für Nachrichten. https://tools.ietf.org/html/rfc8457 |

### Siehe auch

* namensraum [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->