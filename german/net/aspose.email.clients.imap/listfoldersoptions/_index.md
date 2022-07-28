---
title: ListFoldersOptions
second_title: Aspose.Email für .NET-API-Referenz
description: Die Auswahloptionen für die Ordnerliste Bitte beachten Sie dass diese Optionen unterstützt werden falls der Server RFC 5258 IMAP LIST Command Extensions unterstützt Weitere Details finden Sie unter https//tools.ietf.org/html/rfc5258
type: docs
weight: 16510
url: /de/net/aspose.email.clients.imap/listfoldersoptions/
---
## ListFoldersOptions enumeration

Die Auswahloptionen für die Ordnerliste Bitte beachten Sie, dass diese Optionen unterstützt werden, falls der Server RFC 5258 "IMAP LIST Command Extensions" unterstützt Weitere Details finden Sie unter https://tools.ietf.org/html/rfc5258

```csharp
[Flags]
public enum ListFoldersOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Nicht definiert |
| Subscribed | `1` | SUBSCRIBED – bewirkt, dass der LIST-Befehl abonnierte Namen auflistet, anstelle der vorhandenen Mailboxen. Hierbei handelt es sich häufig um eine Teilmenge der tatsächlichen Postfächer. Diese Liste kann auch die Namen nicht vorhandener Postfächer enthalten. In jedem Fall MUSS die Liste genau die Postfachnamen enthalten, die dem kanonischen Listenmuster entsprechen und abonniert sind. Diese Option soll den LSUB-Befehl ergänzen. Besonders hervorzuheben sind die von dieser Option zurückgegebenen Postfachattribute im Vergleich zu den von LSUB zurückgegebenen. Bei letzterem spiegeln die zurückgegebenen Attribute möglicherweise nicht den tatsächlichen Attributstatus des Postfachnamens wider, und das \NoSelect-Attribut hat eine zweite besondere Bedeutung (es zeigt an, dass dieses Postfach selbst nicht abonniert ist, aber untergeordnete Postfächer hat das sind). Bei der hier beschriebenen Auswahloption ABONNIERT sind die Attribute korrekt und vollständig und haben keine besondere Bedeutung. „LSUB“ und „LIST (SUBSCRIBED)“ sind daher nicht dasselbe, und einige Server müssen erhebliche zusätzliche Arbeit leisten, um auf „LIST (SUBSCRIBED)“ zu antworten. Aus diesem Grund SOLLTEN Clients weiterhin „LSUB“ verwenden, es sei denn, sie möchten ausdrücklich die zusätzlichen Informationen, die von „LIST (SUBSCRIBED)“ angeboten werden. Diese Option definiert ein neues Mailbox-Attribut, „\Subscribed“, das angibt, dass es sich um einen Mailbox-Namen handelt abonniert. Das Attribut „\Subscribed“ MUSS unterstützt und genau berechnet werden, wenn die Auswahloption „ABONNIERT“ angegeben ist. Beachten Sie, dass die Auswahloption „ABONNIERT“ die Rückgabeoption „ABONNIERT“ impliziert (siehe unten). |
| Remote | `2` | REMOTE - bewirkt, dass der LIST-Befehl sowohl entfernte als auch lokale Mailboxen anzeigt, wie in [MBRef] beschrieben. Diese Option soll den Befehl RLIST und in Verbindung mit der Auswahloption SUBSCRIBED den Befehl RLSUB ersetzen. Diese Option definiert ein neues Mailbox-Attribut "\Remote", das anzeigt, dass eine Mailbox eine Remote-Mailbox ist. Die Das Attribut „\Remote“ MUSS genau berechnet werden, wenn die Option REMOTE angegeben ist. Die Auswahloption REMOTE hat keine Interaktion mit anderen Optionen. Ihre Wirkung besteht darin, den Server anzuweisen, die anderen Optionen, falls vorhanden, auf Remote-Mailboxen anzuwenden zusätzlich zu den lokalen. Insbesondere hat es keine Interaktion mit RECURSIVEMATCH (siehe unten). Eine Anfrage für (REMOTE RECURSIVEMATCH) ist ungültig, da eine Anfrage für (RECURSIVEMATCH) ungültig ist. Eine Anforderung für (REMOTE RECURSIVEMATCH SUBSCRIBED) fragt nach allen abonnierten Postfächern, sowohl lokal als auch remote. |
| RecursiveMatch | `4` | RECURSIVEMATCH – Diese Option zwingt den Server, Informationen über übergeordnete Postfächer zurückzugeben, die nicht mit anderen Auswahloptionen übereinstimmen, aber einige untergeordnete Postfächer haben, die dies tun. Informationen über Kinder werden im erweiterten Datenelement CHILDINFO zurückgegeben. Hinweis 1: Damit ein übergeordnetes Postfach zurückgegeben werden kann, muss es immer noch mit dem kanonischen LIST-Muster übereinstimmen. Hinweis 2: Bei der Rückgabe des erweiterten Datenelements CHILDINFO spielt es keine Rolle, ob das Unterpostfach mit der kanonischen LIST übereinstimmt oder nicht Muster. Die Option RECURSIVEMATCH DARF NICHT als einzige Auswahlmöglichkeit (bzw. nur bei REMOTE) vorkommen, da sie nur Sinn macht, wenn auch andere Auswahlmöglichkeiten verwendet werden. Der Server MUSS in einem solchen Fall eine BAD-getaggte Antwort zurückgeben. Beachten Sie, dass selbst wenn die Option RECURSIVEMATCH angegeben ist, der Client immer noch in der Lage sein MUSS, einen Fall zu bearbeiten, wenn ein erweitertes Datenelement CHILDINFO zurückgegeben wird und es keine Submailboxen gibt, die die Auswahlkriterien des nachfolgenden LIST-Befehls erfüllen, da sie können gelöscht/umbenannt werden, nachdem die LIST-Antwort gesendet wurde, aber bevor der Client darauf zugreifen konnte. |

### Siehe auch

* namensraum [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
