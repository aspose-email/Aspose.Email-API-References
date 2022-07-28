---
title: IGraphClient
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt die Schnittstelle für den Exchange-REST-Client dar.
type: docs
weight: 15950
url: /de/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Stellt die Schnittstelle für den Exchange-REST-Client dar.

```csharp
public interface IGraphClient : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Ruft ein Objekt ab oder legt es fest, mit dem das OAuth-Zugriffstoken abgerufen werden kann. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Ruft Daten für den Proxy-Zugriff auf den Exchange-Server ab oder legt sie fest. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Ruft den Ressourcentyp ab oder legt ihn fest. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Ruft die Ressourcen-ID ab oder legt sie fest. Für Benutzer kann dies beispielsweise der Benutzerprinzipalname (UPN) oder die Benutzer-ID sein. |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Ruft Mandanten-ID ab oder legt sie fest |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Ruft die Anzahl der Millisekunden ab, die gewartet werden soll, bevor der Vorgang abläuft, oder legt diese fest. Der Standardwert ist 100.000 Millisekunden (100 Sekunden). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Ruft ein Objekt ab oder legt es fest, mit dem das OAuth-Zugriffstoken abgerufen werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Einen Mailordner und seinen Inhalt in einen anderen Mailordner kopieren. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Eine Nachricht in einen anderen Mailordner kopieren. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Kopiert ein Notizbuch in den Ordner „Notizbücher“ in der Zielbibliothek „Dokumente“. Der Ordner wird erstellt, wenn er nicht vorhanden ist. Für Kopiervorgänge folgen Sie einem asynchronen Aufrufmuster: Rufen Sie zuerst die Kopieraktion auf und fragen Sie dann den Vorgangsendpunkt nach dem Ergebnis ab. Berechtigungen Zum Aufrufen ist eine der folgenden Berechtigungen erforderlich diese API. Delegiert (Arbeits- oder Schulkonto) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegiert (persönliches Microsoft-Konto) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Erstellt einen neuen Anhang für das angegebene Element |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Erstellt eine[`OutlookCategory`](../outlookcategory) Objekt in der Hauptkategorienliste des Benutzers. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Neuen Ordner erstellen. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Neuen Ordner erstellen. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Erstellt eine Nachricht im angegebenen Ordner |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Erstellen Sie ein neues OneNote-Notizbuch. Berechtigungen Zum Aufrufen dieser API ist eine der folgenden Berechtigungen erforderlich. Delegiert (Arbeits- oder Schulkonto) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegiert (persönliches Microsoft-Konto) Notes. Erstellen, Notes.ReadWrite Anwendungshinweise.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Erstellen Sie eine Außerkraftsetzung für einen Absender, der durch eine SMTP-Adresse identifiziert wird. Zukünftige Nachrichten von dieser SMTP-Adresse werden konsistent klassifiziert, wie in der Überschreibung angegeben. Hinweis: - Wenn bereits eine Überschreibung mit derselben SMTP-Adresse vorhanden ist, werden die Felder classifyAs und name dieser Überschreibung mit den bereitgestellten Werten aktualisiert. – Die maximale Anzahl der für ein Postfach unterstützten Außerkraftsetzungen beträgt 1000, basierend auf eindeutigen SMTP-Adressen des Absenders. Berechtigungen: Delegiert (Arbeits- oder Schulkonto) Mail.ReadWrite Delegiert (persönliches Microsoft-Konto) Mail.ReadWrite Anwendung Mail.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Erstellen Sie eine Außerkraftsetzung für einen Absender, der durch eine SMTP-Adresse identifiziert wird. Zukünftige Nachrichten von dieser SMTP-Adresse werden konsistent klassifiziert, wie in der Überschreibung angegeben. Hinweis: - Wenn bereits eine Überschreibung mit derselben SMTP-Adresse vorhanden ist, werden die Felder classifyAs und name dieser Überschreibung mit den bereitgestellten Werten aktualisiert. – Die maximale Anzahl der für ein Postfach unterstützten Außerkraftsetzungen beträgt 1000, basierend auf eindeutigen SMTP-Adressen des Absenders. Berechtigungen: Delegiert (Arbeits- oder Schulkonto) Mail.ReadWrite Delegiert (persönliches Microsoft-Konto) Mail.ReadWrite Anwendung Mail.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Erstellen Sie eine Nachrichtenregel, indem Sie eine Reihe von Bedingungen und Aktionen angeben. Outlook führt diese Aktionen aus, wenn eine eingehende Nachricht im Posteingang des Benutzers die angegebenen Bedingungen erfüllt. Berechtigungen: Zum Aufrufen dieser API ist eine der folgenden Berechtigungen erforderlich Weitere Informationen, einschließlich zum Auswählen von Berechtigungen, finden Sie unter Permissions. Delegated (Arbeits- oder Schulkonto) MailboxSettings.ReadWrite Delegated (persönliches Microsoft-Konto) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Objekt löschen. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Entfernt Anhang |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Ruft den Anhang für die angegebene ID ab |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Abrufen der Eigenschaften und Beziehungen des angegebenen outlookCategory-Objekts. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Ruft Nachricht in angegebener ID ab |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Abrufen der Eigenschaften und Beziehungen eines Notizbuchobjekts. Berechtigungen Zum Aufrufen dieser API ist eine der folgenden Berechtigungen erforderlich. Delegiert (Arbeits- oder Schulkonto) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Delegiert (persönliches Microsoft-Konto) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Abrufen der Eigenschaften und Beziehungen eines Nachrichtenregelobjekts. Berechtigungen Zum Aufrufen dieser API ist eine der folgenden Berechtigungen erforderlich. Weitere Informationen, einschließlich zum Auswählen von Berechtigungen, finden Sie unter Berechtigungen. Delegiert (Arbeits- oder Schulkonto) MailboxSettings.Read Delegiertes (persönliches Microsoft-Konto) MailboxSettings.Read Anwendung MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Ruft Ordner nach einer ID ab. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Abrufen des Status eines OneNote-Vorgangs mit langer Ausführungszeit. Dies gilt für Vorgänge, die den Operation-Location-Header in der Antwort zurückgeben, z. B. CopyNotebook, CopyToNotebook, CopyToSectionGroup und CopyToSection. status-Eigenschaft gibt abgeschlossen oder fehlgeschlagen zurück. Wenn der Status abgeschlossen ist, enthält die resourceLocation-Eigenschaft den Ressourcenendpunkt-URI. Wenn der Status fehlgeschlagen ist, liefern die Eigenschaften error und @api.diagnostics Fehlerinformationen. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Anlagen der übergeordneten Nachricht auflisten. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Alle Kategorien abrufen, die für den Benutzer definiert wurden. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Ordner aus dem übergeordneten Ordner für Ordner auflisten, die in normalen Mail-Clients angezeigt werden, z. B. der Posteingang. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Ordner aus dem übergeordneten Ordner für Ordner auflisten, die in normalen Mail-Clients angezeigt werden, z. B. der Posteingang. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | MessageInfo aus dem übergeordneten Ordner auflisten. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | MessageInfo aus dem übergeordneten Ordner auflisten. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Abrufen einer Liste von Notizbuchobjekten. Berechtigungen Zum Aufrufen dieser API ist eine der folgenden Berechtigungen erforderlich. Delegiert (Geschäfts- oder Schulkonto) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Delegiert (persönliches Microsoft-Konto) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Holen Sie sich die Überschreibungen, die ein Benutzer eingerichtet hat, um Nachrichten von bestimmten Absendern immer auf bestimmte Weise zu klassifizieren. Jede Überschreibung entspricht einer SMTP-Adresse eines Absenders. Anfänglich hat ein Benutzer keine Überschreibungen. Berechtigungen: Eine der Die folgenden Berechtigungen sind erforderlich, um diese API aufzurufen. Weitere Informationen, einschließlich der Auswahl von Berechtigungen, finden Sie unter Berechtigungen. Delegiert (Arbeits- oder Schulkonto) Mail.Read Delegiert (persönliches Microsoft-Konto) Mail.Read Anwendung Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Rufen Sie alle für den Posteingang des Benutzers definierten messageRule-Objekte ab. Berechtigungen Eine der folgenden Berechtigungen ist erforderlich, um diese API aufzurufen. Weitere Informationen, einschließlich der Auswahl von Berechtigungen, finden Sie unter Berechtigungen. Delegierte (Arbeits- oder Schulkonto) MailboxSettings.Read Delegiertes (persönliches Microsoft-Konto) MailboxSettings.Read Anwendung MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Einen Mailordner und seinen Inhalt in einen anderen Mailordner verschieben. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Verschiebt eine Nachricht in einen anderen Mailordner. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | Sendet eine E-Mail-Nachricht |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Eine Nachricht im Entwurfsordner senden. Der Nachrichtenentwurf kann ein Entwurf für eine neue Nachricht, ein Antwortentwurf, ein Antwortentwurf oder ein Weiterleitungsentwurf sein. Die Nachricht wird dann im Ordner "Gesendete Objekte" gespeichert. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | Sendet eine E-Mail-Nachricht |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Nachricht als gelesen markieren |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Aktualisiert die voreingestellte Farbkonstante für die angegebene Kategorie |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Updates-Ordner. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Aktualisiert die Nachricht |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Aktualisiert die Nachricht |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Ändern Sie das classifyAs-Feld einer Außerkraftsetzung wie angegeben. Sie können diese Methode nicht verwenden, um andere Felder in einer ClassificationOverride-Instanz zu ändern. Wenn eine Außerkraftsetzung für einen Absender vorhanden ist und der Absender seinen Anzeigenamen ändert, können Sie CreateOrUpdateOverride verwenden eine Aktualisierung des Namensfelds in der vorhandenen Überschreibung erzwingen. Wenn für einen Absender eine Überschreibung existiert und der Absender seine/ihre SMTP-Adresse ändert, ist das Löschen der vorhandenen Überschreibung und das Erstellen einer neuen mit der neuen SMTP-Adresse die einzige Möglichkeit „Aktualisieren“ Sie die Außerkraftsetzung für diesen Absender. Berechtigungen: Eine der folgenden Berechtigungen ist erforderlich, um diese API aufzurufen. Weitere Informationen, einschließlich der Auswahl von Berechtigungen, finden Sie unter Berechtigungen. Delegiert (Arbeits- oder Schulkonto) Mail.ReadWrite Delegiert (persönliches Microsoft-Konto) Mail.ReadWrite Anwendung Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Ändern Sie die beschreibbaren Eigenschaften eines messageRule-Objekts und speichern Sie die Änderungen. Berechtigungen Eine der folgenden Berechtigungen ist erforderlich, um diese API aufzurufen. Weitere Informationen, einschließlich der Auswahl von Berechtigungen, finden Sie unter Berechtigungen. Delegierte (Arbeits- oder Schulkonto) Postfacheinstellungen. ReadWrite Delegiert (persönliches Microsoft-Konto) MailboxSettings.ReadWrite Anwendung MailboxSettings.ReadWrite |

### Siehe auch

* namensraum [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
