---
title: MapiMessage
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt ein Dokument im Outlook-Nachrichtenformat dar das analysiert werden kann.
type: docs
weight: 18450
url: /de/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Stellt ein Dokument im Outlook-Nachrichtenformat dar, das analysiert werden kann.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Initialisiert eine neue Instanz von[`MapiMessage`](../mapimessage) Klasse. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Initialisiert eine neue Instanz von[`MapiMessage`](../mapimessage) Klasse. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Initialisiert eine neue Instanz von[`MapiMessage`](../mapimessage) Klasse. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Initialisiert eine neue Instanz von[`MapiMessage`](../mapimessage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Ruft die Anhänge in der Nachricht ab. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Enthält die mit einem Artikel verknüpften Rechnungsinformationen. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Ruft den Nachrichtentext ab. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ruft die ab[`BodyRtf`](../mapimessageitembase/bodyrtf) der in HTML konvertierten Nachricht, falls vorhanden, ansonsten ein leerer String. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Enthält Schlüsselwörter oder Kategorien für das Nachrichtenobjekt. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Ruft Datum und Uhrzeit ab oder legt fest, der Absender der Nachricht eine Nachricht gesendet hat. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Enthält die Namen der Firmen, die einem Artikel zugeordnet sind. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Ruft das Thema der ersten Nachricht in einem Konversationsthread ab. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Ruft Datum und Uhrzeit ab oder legt fest, eine Nachricht zugestellt wurde. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Ruft eine Liste der Anzeigenamen aller Empfänger von Blind Carbon Copy (BCC)-Nachrichten ab, getrennt durch Semikolons (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Ruft eine Liste der Anzeigenamen aller Empfänger von Carbon Copy (CC)-Nachrichten ab, getrennt durch Semikolons (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Ruft den Anzeigenamen für die Nachricht ab. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Ruft ein Präfix des Anzeigenamens ab. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Ruft eine Liste der Anzeigenamen der primären (To) Nachrichtenempfänger ab, getrennt durch Semikolons (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Ruft die Nachrichten-Flags ab. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Ruft die Header der Transportnachricht ab |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Ruft die Nachrichten-ID der Nachricht ab. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ruft eine Zeichenfolge mit Berücksichtigung der Groß-/Kleinschreibung ab, die die vom Absender definierte Nachrichtenklasse identifiziert, z. B. IPM.Hinweis. Die Nachrichtenklasse gibt den Typ, Zweck oder Inhalt der Nachricht an. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Ruft das Outlook-Nachrichtenformat ab. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Enthält die Kilometerinformationen, die einem Artikel zugeordnet sind. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ruft die benannte Eigenschaftszuordnung ab. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Ruft den normalisierten Betreff der Nachricht ab. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Lesebestätigung angefordert wird. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ruft die Empfänger der Nachricht ab. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Ruft die Antwort auf Namen ab oder legt sie fest. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Ruft den E-Mail-Adresstyp des Absenders der Nachricht ab. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Ruft die E-Mail-Adresse des Absenders der Nachricht ab oder legt sie fest. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Ruft den Anzeigenamen des Absenders der Nachricht ab oder legt ihn fest. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Ruft die E-Mail-Adresse des Absenders der Nachricht ab oder legt sie fest. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ruft die Empfindlichkeit ab. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Ruft den Adresstyp für den Messaging-Benutzer ab, der durch den Absender dargestellt wird. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Ruft die E-Mail-Adresse für den Messaging-Benutzer ab, der durch den Absender dargestellt wird, oder legt diese fest. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Ruft den Anzeigenamen für den Messaging-Benutzer ab, der durch den Absender dargestellt wird, oder legt ihn fest. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Ruft die E-Mail-Adresse für den Messaging-Benutzer ab, der durch den Absender dargestellt wird, oder legt diese fest. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ruft den Betreff der Nachricht ab oder legt ihn fest. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ruft ein Betreff-Präfix ab, das normalerweise eine Aktion für eine Nachricht angibt, z. B. "FW: " zum Weiterleiten. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ruft die Unterspeicher ab. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Ruft die transportspezifischen Nachrichtenumschlaginformationen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Erstellt eine Instanz von MapiMessage aus der MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Erstellt eine Instanz von MapiMessage aus der MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Erstellt eine Instanz von MapiMessage aus der MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Erstellt eine Instanz von MapiMessage aus einer Sammlung von Mapi-Eigenschaften. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Lädt Nachricht aus Stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Lädt Nachricht aus Datei. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Lädt Nachricht aus Stream mit zusätzlichen Optionen. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Lädt Nachricht aus Datei mit zusätzlichen Optionen. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Lädt Nachrichten aus der Datenstruktur des Transport Neutral Encapsulation Format (TNEF) |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Lädt Nachrichten aus der Datenstruktur des Transport Neutral Encapsulation Format (TNEF) |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Fügt die benutzerdefinierte Eigenschaft hinzu. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Fügt die benutzerdefinierte Eigenschaft hinzu. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Prüft, ob diese Nachricht als Bounce-Nachricht behandelt werden kann. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Ruft eine Sammlung benutzerdefinierter MapiProperties ab. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ruft MAPI-Eigenschaft nach Eigenschaftsdeskriptor ab. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als booleschen Typ ab. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als DateTime-Typ ab. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ruft den int32-Wert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Typ Long (int64) ab. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Short-Typ ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ermöglicht das korrekte Entfernen von Eigentum aus allen Sammlungen. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Speichert im angegebenen Stream als Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Speichert in der angegebenen Datei als Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Speichert Nachricht als Stream mit zusätzlichen Optionen. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Speichert Nachricht als Datei mit zusätzlichen Optionen. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Speichert im angegebenen Stream als Outlook-Dateivorlage (OFT-Format). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Speichert in der angegebenen Datei als Outlook-Dateivorlage (OFT-Format). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Nachricht im TNEF-Format speichern. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Nachricht im TNEF-Format speichern. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Legt den Inhalt des Körpers fest. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Legt den Inhalt des Körpers fest. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Setzt die Meldungsflags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Legt die Eigenschaft fest. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Legt die MAPI-Eigenschaft fest. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Legt den Eigenschaftswert der Zeichenfolge fest. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Erstellt eine Instanz von MailMessage aus dieser MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | MapiMessage in IMapiMessageItem object in Abhängigkeit von MessageClass konvertieren. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Versuchen Sie, die Eigenschaftsdaten mit dem angegebenen Tag-Schlüssel abzurufen. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ruft den Wert der angegebenen Eigenschaft als DateTime-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ruft den Wert der angegebenen Eigenschaft als Int32-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ruft den Wert der angegebenen Eigenschaft als Long-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit dem angegebenen Tag zu erhalten. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit angegebenem Tag und Codepage abzurufen. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Zerstört die Anhänge in den angegebenen Outlook-Nachrichtendateien. DestroyAttachments ignoriert das Analysieren von Anhängen. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Bestimmt, ob der angegebene Stream ein MSG-Format hat. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Bestimmt, ob die angegebene Datei ein MSG-Format hat. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Entfernt alle Anhänge aus den angegebenen Outlook-Nachrichtendateien. |

### Bemerkungen

Instanzen der MapiMessage-Klasse werden verwendet, um Microsoft Outlook-Nachrichtendokumentdateien darzustellen, die von der MapiMessageReader-Klasse geparst werden. Um auf Absender, Empfänger und Inhalt einer E-Mail-Nachricht zuzugreifen, verwenden Sie die zugeordneten Eigenschaften der MapiMessage-Klasse.

### Beispiele

Das folgende Beispiel zeigt, wie Outlook-Nachrichtendateien gelesen werden.

[C#]

[Visual Basic]

```csharp
// Outlook-Nachrichtendateien öffnen
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/ Betreff lesen
onsole.WriteLine("Subject:" + msg.Subject);

/Absender
onsole.WriteLine("From:" + msg.SenderName);

/Nachrichtentext
onsole.WriteLine("Body:" + msg.Body);

/Anhänge
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Öffnen Sie Outlook-Nachrichtendateien 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'Thema lesen 
Console.WriteLine("Subject:" + msg.Subject) 

'Absender 
Console.WriteLine("From:" + msg.SenderName) 

'Nachrichtentext 
Console.WriteLine("Body:" + msg.Body) 

'Anhänge 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Siehe auch

* class [MapiMessageItemBase](../mapimessageitembase)
* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
