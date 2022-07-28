---
title: ExchangeClient
second_title: Aspose.Email für .NET-API-Referenz
description: Die ExchangeClient-Klasse ermöglicht es Anwendungen das E-Mail-Postfach in Microsoft Exchange Server mithilfe des WebDav Exchange Store-Protokolls zu verwalten.
type: docs
weight: 3150
url: /de/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

Die ExchangeClient-Klasse ermöglicht es Anwendungen, das E-Mail-Postfach in Microsoft Exchange Server mithilfe des WebDav Exchange Store-Protokolls zu verwalten.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Initialisiert eine neue Instanz der Klasse[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Initialisiert eine neue Instanz der Klasse[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Initialisiert eine neue Instanz der Klasse[`ExchangeClient`](../exchangeclient) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Ruft das Client-Zertifikat ab oder legt es fest. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Ruft den Cookie-Container ab oder legt ihn fest. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Ruft die Anmeldeinformationen ab oder legt sie fest |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Ruft die Codierung ab oder legt sie fest. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Gibt an, ob am Leben erhalten werden soll. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Ruft den Protokolldateinamen ab oder legt ihn fest |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Ruft die Postfachinformationen ab. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Holt oder setzt das Postfach uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Gibt an, ob eine Vorauthentifizierung durchgeführt werden soll. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Ruft den Proxy ab oder legt ihn fest. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [chunked senden]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Ruft die Anzahl der Millisekunden ab, die gewartet werden soll, bevor der Vorgang abläuft, oder legt diese fest. Der Standardwert ist 100.000 Millisekunden (100 Sekunden). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob das Datum im Namen der Protokolldatei verwendet werden muss. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Lädt die E-Mail-Nachricht in den angegebenen Ordner hoch |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Lädt die E-Mail-Nachricht in den angegebenen Ordner hoch |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Sichert den Inhalt der angegebenen Ordner |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Sichert den Inhalt der angegebenen Ordner |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Erstellt ein Kontaktelement im Exchange Store. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Erstellt den neuen Ordner mit dem angegebenen Namen im angegebenen übergeordneten Ordner. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Löscht den Kontakt. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Löscht den Kontakt. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Löscht den Kontakt. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Löscht den Ordner |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Löscht die E-Mail-Nachricht. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Löscht die E-Mail-Nachricht. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Ruft den Anhang ab |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Ruft die Mapi-Nachricht mit dem angegebenen uri ab. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Ruft die E-Mail-Nachricht mit dem angegebenen uri ab. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Prüft, ob der angegebene Ordner existiert. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Prüft, ob der angegebene Ordner existiert. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Listet Kontakte auf, die sich im angegebenen Ordner auf server befinden |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Ruft die Ordnerinformationen ab. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Listet Postfächer in der globalen Adressliste auf. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Holen Sie sich die Informationen der Mailbox |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Ruft die Postfachinformationen ab |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Holen Sie sich die Größe der Mailbox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Holen Sie sich die Größe der Mailbox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Gibt die Version des Exchange-Servers zurück info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Listet Kontakte auf, die sich im angegebenen Ordner auf server befinden |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Listet Postfächer in der globalen Adressliste auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Listet die Nachrichten im angegebenen Ordner auf |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Listet die E-Mail-Nachricht im angegebenen Ordner auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Listet die Nachrichten im angegebenen Ordner auf |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Listet die Nachrichten auf. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Listet die Nachrichten nach ID auf. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Ruft eine Sammlung öffentlicher Ordner aus dem öffentlichen Stammordner ab |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Ruft Sammlung von untergeordneten öffentlichen Ordnern von parent ab |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Ruft eine Sammlung von untergeordneten Ordnern von parent ab |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Verschiebt Gegenstände. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Verschiebt Gegenstände. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Verschiebt die Nachricht. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Verschiebt die Nachricht. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Verschiebt die Nachricht. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Verschiebt die Nachricht. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Löst mehrdeutige Mailbox-Anzeigenamen auf. Hinweis: Die maximale Anzahl zurückgegebener Kontakte beträgt 100. Dies ist eine Einschränkung des verwendeten Austauschbefehls. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Stellt Austauschordner aus dem angegebenen persönlichen Speicher wieder her. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Stellt Austauschordner aus dem angegebenen persönlichen Speicher wieder her. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Stellt Austauschordner aus der angegebenen persönlichen Speicherdatei wieder her. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Stellt die angegebenen Austauschordner aus dem angegebenen persönlichen Speicher wieder her. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Stellt die angegebenen Austauschordner aus dem angegebenen persönlichen Speicher wieder her. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Stellt die angegebenen Austauschordner aus der angegebenen persönlichen Speicherdatei wieder her. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Speichert die Nachricht. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Speichert die vom URI angegebene E-Mail-Nachricht im lokalen Dateisystem. Die E-Mail-Nachrichtendatei ist im RFC 822-kompatiblen Format (EML).  wenn Sie die E-Mail-Nachrichtendateien parsen möchten, verwenden Sie[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Sendet die E-Mail-Nachricht. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Markiert die angegebene Nachricht als gelesen. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Markiert die angegebene Nachricht als gelesen. |

### Siehe auch

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
