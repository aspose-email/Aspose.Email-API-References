---
title: MapiTask
second_title: Aspose.Email för .NET API-referens
description: Representerar Outlook Task-objektet.
type: docs
weight: 18670
url: /sv/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Representerar Outlook Task-objektet.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Initierar en ny instans av[`MapiTask`](../mapitask) class. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Initierar en ny instans av[`MapiTask`](../mapitask) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Hämtar eller ställer in acceptansstatus för uppgiften. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Hämtar eller ställer in antalet minuter som användaren faktiskt tillbringade med att arbeta med en uppgift. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Hämtar bilagesamlingen. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Innehåller faktureringsinformation som är kopplad till en artikel. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Hämtar meddelandetexten. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Får[`BodyRtf`](../mapimessageitembase/bodyrtf) av meddelandet konverterat till HTML, om det finns, annars en tom sträng. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Hämtar typen av kroppen. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Innehåller nyckelord eller kategorier för meddelandeobjektet. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Innehåller namnen på de företag som är associerade med en vara. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Hämtar eller ställer in datumet när användaren slutförde arbetet med uppgiften. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Hämtar eller ställer in det datum då användaren förväntar sig att arbetet med uppgiften ska vara slutfört. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Hämtar eller ställer in antalet minuter som användaren förväntar sig att arbeta med en uppgift. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Hämtar indikationsflaggorna för Task-objektet. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Hämtar eller ställer in typen av ändring som senast gjordes i Task-objektet. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Artikel-id, används med en server |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Hämtar eller ställer in datum och tid för den senaste senaste ändringen som gjordes i Task-objektet. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Får en skiftlägeskänslig sträng som identifierar den avsändardefinierade meddelandeklassen, till exempel IPM.Note. Meddelandeklassen anger typen, syftet eller innehållet för meddelandet. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Innehåller information om körsträcka som är associerad med en artikel. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Hämtar eller ställer in tilldelningsstatus för uppgiftsobjektet. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Hämtar den namngivna egenskapsmappingen. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Hämtar eller ställer in framstegen som användaren har gjort på en uppgift. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Hämtar mottagarna av meddelandet. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Hämtar eller ställer in återkommande egenskaper. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Anger hela sökvägen för ljudet som en klient SKA spela när påminnelsen blir försenad. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Hämtar eller ställer in ett värde som anger om en påminnelse är inställd på objektet |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Hämtar eller ställer in den initiala signaltiden för en påminnelse |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Får känsligheten. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Hämtar eller ställer in det datum då användaren förväntar sig att arbetet med uppgiften ska börja. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Hämtar eller ställer in det aktuella tilldelningsläget för aktivitetsobjektet. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Hämtar eller ställer in status för användarens framsteg på uppgiften. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Hämtar eller ställer in ämnet för meddelandet. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Får ett ämnesprefix som vanligtvis indikerar någon åtgärd på ett meddelande, till exempel "FW: " för vidarebefordran. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Hämtar underlagringarna. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Hämtar eller ställer in information om uppgiftsanvändare. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Skapar en instans av MapiTask från den angivna strömmen. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Skapar en instans av MapiTask från den angivna .ics-filen. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Skapar en instans av MapiTask från den angivna strömmen. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Skapar en instans av MapiTask från den angivna .ics-filen. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Hämtar MAPI-egenskap efter egenskapsbeskrivning. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Hämtar värdet för egenskapen som anges av taggen som boolesk typ. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Hämtar värdet för egenskapen specificerad av taggen som DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Hämtar int32-värdet för egenskapen som anges av taggen. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Hämtar värdet för egenskapen specificerad av taggen som Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Hämtar värdet för egenskapen som anges av taggen som Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ger korrekt borttagning av egendom från alla samlingar. |
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Sparar detta[`MapiTask`](../mapitask) till den givna strömmen med angivet format. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Sparar detta[`MapiTask`](../mapitask) till fil med angivet format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Ställer in innehållet i brödtexten. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Ställer in innehållet i brödtexten. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Ställer in meddelandeflaggor. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Anger egenskapen. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Ställer in MAPI-egenskapen. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Försök att hämta egenskapsdata med angiven taggnyckel. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Hämtar värdet för den angivna egenskapen som DateTime-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Hämtar värdet för den angivna egenskapen som Int32-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Hämtar värdet för den angivna egenskapen som lång typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Försök att få en egenskapsdata som sträng med specificerad tagg. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Försök att få en egenskapsdata som sträng med specificerad tagg och teckentabell. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |

### Se även

* class [MapiMessageItemBase](../mapimessageitembase)
* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
