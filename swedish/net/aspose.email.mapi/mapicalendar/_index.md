---
title: MapiCalendar
second_title: Aspose.Email för .NET API-referens
description: Representerar mapi-kalenderobjektet
type: docs
weight: 17910
url: /sv/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Representerar mapi-kalenderobjektet

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Initierar en ny instans av[`MapiCalendar`](../mapicalendar) klass |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Initierar en ny instans av[`MapiCalendar`](../mapicalendar) class. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Initierar en ny instans av[`MapiCalendar`](../mapicalendar) class. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Initierar en ny instans av[`MapiCalendar`](../mapicalendar) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Hämtar eller ställer in ett värde som anger om ett mötessvarsobjekt är ett motförslag. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Hämtar bilagasamlingen. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Får eller ställer in deltagarna |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Innehåller faktureringsinformation som är kopplad till en artikel. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Hämtar meddelandetexten. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Får[`BodyRtf`](../mapimessageitembase/bodyrtf) av meddelandet konverterat till HTML, om det finns, annars en tom sträng. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Hämtar typen av kroppen. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Hämtar eller ställer in upptagetstatus |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Innehåller nyckelord eller kategorier för meddelandeobjektet. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Hämtar eller ställer in de åtgärder som användaren har vidtagit på detta mötesobjekt. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Innehåller namnen på de företag som är associerade med en vara. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Hämtar eller ställer in slutdatum och tid för händelsen. Om datumet inte är inställt, standardvärde förDateTime returneras. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Hämtar eller ställer in tidszonsinformation som anger tidszonen för egenskapen EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Hämtar eller ställer in ett värde som anger om händelsen är en heldagshändelse |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Artikel-id, används med en server |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Hämtar eller ställer in kategorierna för kalenderobjektet |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Hämtar eller ställer in platsen för händelsen |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Får en skiftlägeskänslig sträng som identifierar den avsändardefinierade meddelandeklassen, till exempel IPM.Note. Meddelandeklassen anger typen, syftet eller innehållet för meddelandet. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Innehåller information om körsträcka som är associerad med en artikel. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Hämtar den namngivna egenskapsmappingen. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Hämtar eller ställer in arrangören. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Hämtar mottagarna av meddelandet. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Hämtar eller ställer in upprepningsegenskaperna |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Hämtar eller ställer in intervallet, i minuter, mellan den tidpunkt då påminnelsen först blir försenad och starttiden för kalenderobjektet |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Anger hela sökvägen för ljudet som en klient SKA spela när påminnelsen blir försenad. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Hämtar eller ställer in ett värde som anger om en påminnelse är inställd på objektet |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Får känsligheten. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Hämtar eller ställer in sekvensnumret |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Hämtar eller ställer in startdatum och tid för händelsen. Om datumet inte är inställt, standardvärde förDateTime returneras. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Hämtar eller ställer in tidszonsinformation som anger tidszonen för egenskapen StartDate |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Hämtar eller ställer in ämnet för meddelandet. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Får ett ämnesprefix som vanligtvis indikerar någon åtgärd på ett meddelande, till exempel "FW: " för vidarebefordran. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Hämtar underlagringarna. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Får den unika identifieraren |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Frigör alla resurser. |
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
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Sparar kalenderobjekt till filen med iCalendar-format med standardsparalternativen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Sparar kalenderobjekt till filen med iCalendar-format med standardsparalternativen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Sparar kalenderobjekt i strömmen med angivet format med standardsparalternativen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Sparar kalender i strömmen med angivna sparalternativ |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Sparar kalenderobjekt till filen med angivet format med standardsparalternativen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Sparar kalenderobjekt till filen med angivet format med standardsparalternativen |
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
