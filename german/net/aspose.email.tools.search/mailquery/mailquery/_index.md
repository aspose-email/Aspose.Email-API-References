---
title: MailQuery
second_title: Aspose.Email für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonMailQueryaspose.email.tools.search/mailquery Klasse.
type: docs
weight: 10
url: /de/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Initialisiert eine neue Instanz von[`MailQuery`](../../mailquery) Klasse.

```csharp
public MailQuery(string queryString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| queryString | String | Die Abfragezeichenfolge. |

### Bemerkungen

Die Abfragezeichenfolge sollte die folgende Ansicht haben.

Das Beispiel eines einfachen Ausdrucks:

'&lt;Feldname&gt;' &lt;Vergleichsoperator&gt; '&lt;Feldwert&gt;',

wo &lt;Feldname&gt; - der Name eines Nachrichtenfeldes, durch das gefiltert wird, &lt;Vergleichsoperator&gt; - Vergleichsoperatoren ermöglichen, wie der Name schon sagt, den Vergleich des Nachrichtenfeldes und des angegebenen Wertes, &lt;Feldwert&gt; - Wert zu mit einem Nachrichtenfeld verglichen werden.

Die Anzahl einfacher Ausdrücke kann zusammengesetzt werden, z. B.: (&lt;Einfacher Ausdruck 1&gt; &amp; &lt;Einfacher Ausdruck 2&gt;) &#x7C; &lt;Einfacher Ausdruck 3&gt;,

where "&amp;" - logischer UND-Operator, "&#x7C;" - Logischer ODER-Operator

Als Feldname (&lt;Feldname&gt;) sind derzeit folgende Werte erlaubt:

„An“ – stellt ein TO-Feld der Nachricht dar, „Text“ – stellt eine Zeichenfolge im Header oder Hauptteil der Nachricht dar, „Bcc“ – stellt ein BCC-Feld der Nachricht dar, „Body“ – stellt eine Zeichenfolge im Hauptteil der Nachricht, „Cc“ – stellt ein CC-Feld der Nachricht dar, „From“ – stellt ein Absenderfeld der Nachricht dar, „Subject“ – stellt eine Zeichenfolge im Betreff der Nachricht dar, „InternalDate“ – stellt ein internes Datum dar Datum der Nachricht, "SentDate" - repräsentiert ein Sendedatum der Nachricht

Zusätzlich sind folgende Feldnamen für das IMAP-Protokoll erlaubt:

„Beantwortet“ – repräsentiert ein /Beantwortet-Flag von Nachricht „Gesehen“ – repräsentiert ein /Gesehen-Flag von Nachricht „Flagge“ – repräsentiert ein /Flag-Flag von Nachricht „Entwurf“ – repräsentiert ein /Entwurf-Flag von Nachricht „Gelöscht“ – repräsentiert ein Gelöscht/-Flag von message „Recent“ – stellt ein Gelöscht/-Flag von message dar „MessageSize“ – stellt eine Größe (in Bytes) von message dar

Zusätzlich sind folgende Feldnamen für Exchange erlaubt:

„IsRead“ – Zeigt an, ob die Nachricht gelesen wurde „HasAttachment“ – Gibt an, ob die Nachricht Anhänge hat oder nicht „IsSubmitted“ – Gibt an, ob die Nachricht an den Postausgang gesendet wurde „ContentClass“ – stellt eine Inhaltsklasse von item dar

Zusätzlich sind folgende Feldnamen für pst/ost-Dateien erlaubt:

„MessageClass“ – Stellt eine Nachrichtenklasse dar „ContainerClass“ – Stellt einen Ordnercontainer dar class „Importance“ – Stellt eine Nachrichtenwichtigkeit dar „MessageSize“ – Stellt eine Größe (in Bytes) von Message „FolderName“ dar – Stellt einen Ordnernamen dar „ContentsCount“ - stellt die Gesamtzahl der Elemente im Ordner dar "UnreadContentsCount" - stellt die Anzahl der ungelesenen Elemente im Ordner dar. "Unterordner" - Zeigt an, ob der Ordner Unterordner hat "Gelesen" - die Nachricht wird als gelesen markiert " HasAttachment“ – die Nachricht hat mindestens einen Anhang „Nicht gesendet“ – die Nachricht wird noch verfasst „unverändert“ – die Nachricht wurde nicht geändert, seit sie zum ersten Mal gespeichert (falls nicht gesendet) oder zugestellt wurde (falls gesendet) „FromMe " - der Benutzer, der die Nachricht erhält, war auch der Benutzer, der die Nachricht gesendet hat "Erneut senden" - die Nachricht enthält eine Anfrage für einen erneuten Sendevorgang mit einem Unzustellbarkeitsbericht_x000 d_ „NotifyRead“ – der Benutzer, der die Nachricht gesendet hat, hat eine Benachrichtigung angefordert, wenn ein Empfänger sie zum ersten Mal liest „NotifyUnread“ – der Benutzer, der die Nachricht gesendet hat, hat eine Benachrichtigung angefordert, wenn ein Empfänger sie vor dem Lesen löscht oder das Nachrichtenobjekt abläuft „EverRead“ – die Nachricht wurde mindestens einmal gelesen

Der Feldwert (&lt;Feldwert&gt;) kann die folgenden Werte annehmen: Für Textfelder – eine beliebige Zeichenfolge, Für Datumsfelder – die Zeichenfolge im Format „d-MMM-jjj“, z. "10-Feb-2009", Für Flags (Felder vom booleschen Typ) - entweder "True" oder "False"

### Beispiele

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Siehe auch

* class [MailQuery](../../mailquery)
* namensraum [Aspose.Email.Tools.Search](../../mailquery)
* Montage [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Initialisiert eine neue Instanz von[`MailQuery`](../../mailquery) Klasse.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Bemerkungen

Die Sortierabfragezeichenfolge sollte die folgende Ansicht haben.

Das Beispiel eines einfachen Ausdrucks:

'&lt;Feldname&gt;' OrderBy ['ASC'&#x7C;'DESC'],

where &lt;Feldname&gt; - der Name eines Nachrichtenfeldes, nach dem sortiert wird, ['ASC'&#x7C;'DESC'] - Sortieroperatoren, erlauben aufsteigend oder absteigend zu sortieren,

Die Anzahl einfacher Ausdrücke kann zusammengesetzt werden, z. B.: (&lt;Einfacher Ausdruck 1&gt; &amp; &lt;Einfacher Ausdruck 2&gt;),

### Beispiele

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Siehe auch

* class [MailQuery](../../mailquery)
* namensraum [Aspose.Email.Tools.Search](../../mailquery)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
