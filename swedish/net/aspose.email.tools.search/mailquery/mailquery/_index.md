---
title: MailQuery
second_title: Aspose.Email för .NET API-referens
description: Initierar en ny instans avMailQueryaspose.email.tools.search/mailquery klass.
type: docs
weight: 10
url: /sv/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Initierar en ny instans av[`MailQuery`](../../mailquery) klass.

```csharp
public MailQuery(string queryString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queryString | String | Frågesträngen. |

### Anmärkningar

Frågesträngen bör ha följande vy.

Exemplet på ett enkelt uttryck:

'&lt;Fältnamn&gt;' &lt;Jämförelseoperator&gt; '&lt;Fältvärde&gt;',

där &lt;Fältnamn&gt; - namnet på ett meddelandefält genom vilket filtrering görs, &lt;Comparison operator&gt; - jämförelseoperatorer, som deras namn antyder, tillåter att jämföra meddelandefält och specificerat värde, &lt;Fältvärde&gt; - värde till jämföras med ett meddelandefält.

Antalet enkla uttryck kan göra ett sammansatt ett, ex.: (&lt;Enkelt uttryck 1&gt; &amp; &lt;Enkelt uttryck 2&gt;) &#x7C; &lt;Enkelt uttryck 3&gt;,

där "&amp;" - logisk-AND-operator, "&#x7C;" - logical-OR operator

För närvarande är följande värden tillåtna som fältnamn (&lt;Fältnamn&gt;):

"Till" - representerar ett TO-fält i meddelandet, "Text" - representerar strängen i meddelandets rubrik eller brödtext, "Bcc" - representerar ett BCC-fält i meddelandet, "Body" - representerar en sträng i meddelandet meddelandetext, "Cc" - representerar ett CC-fält för meddelande, "Från" - representerar ett Från-fält för meddelande, "Ämne" - representerar en sträng i meddelandets ämne, "InternalDate" - representerar ett internt datum datum för meddelande, "SentDate" - representerar ett skickat datum för meddelande

Dessutom är följande fältnamn tillåtna för IMAP-protokoll:

"Answered" - representerar en /Besvarad flagga för meddelande "Seen" - representerar en /Seen flagga för meddelande "Flaggad" - representerar en /Flaggad flagga för meddelande "Utkast" - representerar en /Draft-flagga för meddelande_x00 a Deleted/ flag of message "Recent" - representerar en Deleted/-flagga för message "MessageSize" - representerar en storlek (i byte) av message

Dessutom är följande fältnamn tillåtna för Exchange:

"IsRead" - Indikerar om meddelandet har lästs "HasAttachment" - Indikerar om meddelandet har attachments "IsSubmitted" - Indikerar om meddelandet har skickats till Outbox "Contentx0 content class" för item_d_x0 content class0 - representerar

Dessutom är följande fältnamn tillåtna för pst/ost-filer:

"MessageClass" - Representerar ett meddelande class "ContainerClass" - Representerar en mappbehållare class "Importance" - Representerar ett meddelande important "MessageSize" - representerar en storlek (i byte) av message_ "representerar mappnamn_Content"_x000000_mappnamn_Kont. - representerar ett totalt antal objekt i mappen "UnreadContentsCount" - representerar antalet olästa objekt i mappen. "Undermappar" - Indikerar om mappen har undermappar "Läst" - meddelandet är markerat som läst " HasAttachment" - meddelandet har minst en attachment "Ej skickat" - meddelandet komponeras fortfarande "Omodifierat" - meddelandet har inte ändrats sedan det först sparades (om det inte skickades) eller så levererades det (om det skickades) "FromMe " - användaren som tog emot meddelandet var också användaren som skickade meddelandet "Sänd igen" - meddelandet innehåller en begäran om en återsändningsoperation med en utebliven leveransrapport_x000 d_ "NotifyRead" - användaren som skickade meddelandet har begärt meddelande när en mottagare först läser it "NotifyUnread" - användaren som skickade meddelandet har begärt meddelande när en mottagare raderar det innan läsning eller meddelandeobjektet expires "EverRead" - den meddelandet har lästs minst en gång

Fältvärdet (&lt;Fältvärde&gt;) kan ha följande värden: För textfält - valfri sträng, För datumtypfält - strängen i formatet "d-MMM-ååå", t.ex. "10-Feb-2009", För flaggor (fält av boolesk typ) - antingen "True" eller "False"

### Exempel

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Se även

* class [MailQuery](../../mailquery)
* namnutrymme [Aspose.Email.Tools.Search](../../mailquery)
* hopsättning [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Initierar en ny instans av[`MailQuery`](../../mailquery) klass.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Anmärkningar

Sorteringsfrågesträngen bör ha följande vy.

Exemplet på ett enkelt uttryck:

'&lt;Fältnamn&gt;' OrderBy ['ASC'&#x7C;'DESC'],

där &lt;Fältnamn&gt; - namnet på ett meddelandefält genom vilket sortering görs, ['ASC'&#x7C;'DESC'] - sorteringsoperatorer, tillåt att sortera stigande eller fallande,

Antalet enkla uttryck kan göra ett sammansatt, ex.: (&lt;Enkelt uttryck 1&gt; &amp; &lt;Enkelt uttryck 2&gt;),

### Exempel

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Se även

* class [MailQuery](../../mailquery)
* namnutrymme [Aspose.Email.Tools.Search](../../mailquery)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
