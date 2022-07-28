---
title: MailMessage
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert eine E-Mail-Nachricht. Es ermöglicht den Zugriff auf Nachrichteneigenschaften ex. Betreff Text Absender- und Empfängeradressen usw. Es kann auch über unterstützte E-Mail-Protokolle gesendet und zugestellt werden.
type: docs
weight: 17710
url: /de/net/aspose.email/mailmessage/
---
## MailMessage class

Repräsentiert eine E-Mail-Nachricht. Es ermöglicht den Zugriff auf Nachrichteneigenschaften, ex. Betreff, Text, Absender- und Empfängeradressen usw. Es kann auch über unterstützte E-Mail-Protokolle gesendet und zugestellt werden.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider, ISerializable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MailMessage](mailmessage#constructor)() | Initialisiert eine neue Instanz von[`MailMessage`](../mailmessage) Klasse |
| [MailMessage](mailmessage#constructor_2)(bool) | Initialisiert eine neue Instanz von[`MailMessage`](../mailmessage) Klasse |
| [MailMessage](mailmessage#constructor_1)(MailAddress, MailAddress) | Initialisiert eine neue Instanz von[`MailMessage`](../mailmessage) Klasse |
| [MailMessage](mailmessage#constructor_3)(string, string) | Initialisiert eine neue Instanz von[`MailMessage`](../mailmessage) Klasse |
| [MailMessage](mailmessage#constructor_4)(string, string, string, string) | Initialisiert eine neue Instanz von[`MailMessage`](../mailmessage) Klasse |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Ruft die Sammlung alternativer Ansichten von message ab |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Ruft die Sammlung von Anhängen der Nachricht ab |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Ruft die Adresssammlung ab oder legt sie fest, die die BCC-Empfänger der Nachricht enthält |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Ruft die Klartextdarstellung des Nachrichtentexts ab oder legt sie fest. Wenn der Text-/Klartextteil in einer Nachricht vorhanden ist, gibt die Eigenschaft ihre Textdaten zurück. Andernfalls gibt die Eigenschaft den Textinhalt der HtmlBody-Eigenschaft ohne HTML-Markup zurück. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Ruft die Codierung von body ab oder legt sie fest |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Ruft die Adresssammlung ab oder legt sie fest, die die CC-Empfänger enthält |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Ruft das Datum der Nachricht ab oder setzt es |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Ruft die Lieferbenachrichtigungen ab oder legt sie fest |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Ruft einen Epilogtext ab oder legt ihn fest. Er befindet sich hinter der letzten Grenze. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Holt oder setzt die Von-Adresse |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Ruft Header-Sammlung von message ab |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Ruft HTML body ab oder legt es fest |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Nachrichtentext in Html vorliegt |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Ruft oder legt einen Wert fest, der angibt, ob eine Nachricht gesendet wurde oder nicht. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Ruft einen Wert ab, der angibt, ob die Nachricht verschlüsselt ist. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Ruft einen Wert ab, der angibt, ob die Nachricht schreibgeschützt ist |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Ruft einen Wert ab, der angibt, ob die Nachricht signiert ist. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Ruft die Sammlung verknüpfter Ressourcen von message ab |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Ruft die Nachrichten-ID ab oder setzt sie |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Ruft einen Wert ab, der angibt, ob die ursprüngliche EML-Nachricht im TNEF-Format vorliegt. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Ruft einen Präambeltext ab oder legt ihn fest. Er befindet sich vor der ersten Grenze und enthält im Allgemeinen einen erläuternden Hinweis für nicht MIME-konforme Leser. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Ruft die bevorzugte Kodierung für alle Texteigenschaften ab oder legt sie fest |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Holt oder setzt die Priorität von Nachricht |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Ruft die Lesebestätigungsadresse ab oder legt sie fest. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Ruft die Liste der Adressen ab oder legt sie fest, an die auf die E-Mail-Nachricht antworten soll |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Ruft die ReversePath-Adresse ab oder legt sie fest |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Holt oder setzt Absenderadresse |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Ruft die Empfindlichkeit von message ab oder legt sie fest |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Ruft die Betreffzeile ab oder legt sie fest |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Ruft die Kodierung von subject ab oder legt sie fest |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Ruft den -Offset der koordinierten Weltzeit (UTC) für die Nachrichtendaten ab oder legt ihn fest. Diese Eigenschaft definiert die Zeitzonendifferenz zwischen der Ortszeit und UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Ruft die Adresssammlung ab oder legt sie fest, die die Empfänger von Nachricht enthält |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Holt oder setzt X-Mailer die Software , die die E-Mail-Nachricht erstellt hat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Load](../../aspose.email/mailmessage/load#load)(Stream) | Nachricht von stream laden |
| static [Load](../../aspose.email/mailmessage/load#load_2)(string) | Nachricht aus Datei laden |
| static [Load](../../aspose.email/mailmessage/load#load_1)(Stream, LoadOptions) | Nachricht aus Stream mit zusätzlichen Optionen laden. |
| static [Load](../../aspose.email/mailmessage/load#load_3)(string, LoadOptions) | Nachricht aus Datei mit zusätzlichen Optionen laden. |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Nachricht eine alternative Ansicht hinzufügen |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Anhang zu Nachricht hinzufügen |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature)(CmsSigner) | Erstellt eine signierte Nachricht. Erstellt eine schreibgeschützte Kopie der angegebenen MailMessage und fügt ihr eine digitale Signatur hinzu. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_2)(X509Certificate2) | Erstellt eine signierte Nachricht. Erstellt eine schreibgeschützte Kopie der angegebenen MailMessage und fügt ihr eine digitale Signatur hinzu. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_1)(CmsSigner, bool) | Erstellt eine signierte Nachricht. Erstellt eine schreibgeschützte Kopie der angegebenen MailMessage und fügt ihr eine digitale Signatur hinzu. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_3)(X509Certificate2, bool) | Erstellt eine signierte Nachricht. Erstellt eine schreibgeschützte Kopie der angegebenen MailMessage und fügt ihr eine digitale Signatur hinzu. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Prüft, ob diese Nachricht als Bounce-Nachricht behandelt werden kann. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Prüfung der Signatur vorhandener MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Klont diese Instanz |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Erstellt die Lesebestätigung. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt)() | entschlüsselt diese Nachricht |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt_1)(X509Certificate2) | entschlüsselt diese Nachricht |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Gibt alle von der MailMessage verwendeten Ressourcen frei |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Signiert diese Nachricht mit der DKIM-Signatur (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt)(X509Certificate2) | verschlüsselt diese Nachricht |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt_1)(X509Certificate2[]) | verschlüsselt diese Nachricht |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Bestimmt, ob das angegebene Objekt gleich dem aktuellen Objekt ist. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Gibt einen Enumerator zurück, der eine Sammlung durchläuft. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Gibt einen Hashcode für object zurück |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext_1)(bool) | Ruft den HTML-Text der Nachricht als einfachen Text ab. Diese Methode analysiert die HtmlBody-Eigenschaft und gibt Nur-Text-Inhalt zurück, wobei das HTML-Markup ignoriert wird. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext)(HyperlinkRenderingCallback) | Ruft den HTML-Text der Nachricht als einfachen Text ab. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | Bevölkert aSerializationInfo mit den Daten, die zum Serialisieren des Zielobjekts benötigt werden. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Importiert Nachricht von stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Erstellt den TNEF-Inhalt. Beachten Sie, dass der tnef-Anhang erstellt wird, wenn eine Nachricht ursprünglich TNEF enthielt und ohne FileCompatibilityMode.PreserveTnefAttachments-Flag geladen wurde, Das heißt, diese Methode erstellt keine tnef-Nachricht aus der regulären. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Signatur entfernen |
| virtual [Save](../../aspose.email/mailmessage/save#save)(Stream) | Nachricht als Stream speichern |
| virtual [Save](../../aspose.email/mailmessage/save#save_2)(string) | Nachricht als Datei speichern |
| virtual [Save](../../aspose.email/mailmessage/save#save_1)(Stream, SaveOptions) | Nachricht als Stream mit zusätzlichen Optionen speichern. |
| virtual [Save](../../aspose.email/mailmessage/save#save_3)(string, SaveOptions) | Nachricht als Datei mit zusätzlichen Optionen speichern. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Legt den HTML-Text fest. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature)(Stream) | Prüft die Signatur der angegebenen EML-Nachricht. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature_1)(string) | Prüft die Signatur der angegebenen EML-Datei. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage)(Stream) | EML-Nachricht validieren, damit sie der MIME-Spezifikation entspricht. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage_1)(string) | EML-Nachricht validieren, damit sie der MIME-Spezifikation entspricht. |

### Siehe auch

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* namensraum [Aspose.Email](../../aspose.email)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
