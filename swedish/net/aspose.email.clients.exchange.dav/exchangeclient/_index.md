---
title: ExchangeClient
second_title: Aspose.Email för .NET API-referens
description: ExchangeClient-klassen tillåter applikationer att hantera e-postlåda i Microsoft Exchange Server genom att använda WebDav Exchange Store Protocol.
type: docs
weight: 3150
url: /sv/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

ExchangeClient-klassen tillåter applikationer att hantera e-postlåda i Microsoft Exchange Server genom att använda WebDav Exchange Store Protocol.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Initiera en ny instans av klassen[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Initiera en ny instans av klassen[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Initiera en ny instans av klassen[`ExchangeClient`](../exchangeclient) |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Hämtar eller ställer in klientcertifikatet. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Hämtar eller ställer in cookie-behållaren. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Hämtar eller ställer in autentiseringsuppgifterna |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Hämtar eller ställer in kodningen. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Indikerar om man ska hålla sig vid liv. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Hämtar eller ställer in loggfilens namn |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Hämtar brevlådeinformationen. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Hämtar eller ställer in postlådan uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Indikerar om förautentisering ska göras. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Hämtar eller ställer in proxyn. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Hämtar eller ställer in ett värde som anger om [skicka i bitar]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Hämtar eller ställer in värde som indikerar om datum måste användas i loggfilens namn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Laddar upp e-postmeddelandet till den angivna mappen |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Säkerhetskopierar innehållet i de angivna mapparna |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Säkerhetskopierar innehållet i de angivna mapparna |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Skapar ett kontaktobjekt i Exchange-butiken. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Skapar den nya mappen med det angivna namnet i den angivna överordnade mappen. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Tar bort kontakten. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Tar bort kontakten. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Tar bort kontakten. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Tar bort mappen |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Tar bort e-postmeddelandet. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Tar bort e-postmeddelandet. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Hämtar bilagan |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Hämtar mapi-meddelandet med angiven uri. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Hämtar e-postmeddelandet med angiven uri. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Kontrollerar om den angivna mappen finns. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Kontrollerar om den angivna mappen finns. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Listar kontakter som finns i den angivna mappen på server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Hämtar mappinformationen. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Listar postlådor i den globala adresslistan. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Få information om brevlådan |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Hämtar brevlådeinformationen |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Få storleken på maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Få storleken på maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Returnerar utbytesserverversion info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Listar kontakter som finns i den angivna mappen på server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Listar postlådor i den globala adresslistan. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Lista meddelandena i den angivna mappen |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Listar e-postmeddelandet i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Lista meddelandena i den angivna mappen |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Listar meddelandena. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Listar meddelandena efter id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Hämtar samling av offentliga mappar från den offentliga rotmappen |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Hämtar samling av offentliga underordnade mappar från parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Hämtar samling av underordnade mappar från parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Flyttar objekt. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Flyttar objekt. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Flyttar meddelandet. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Flyttar meddelandet. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Flyttar meddelandet. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Flyttar meddelandet. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Löser tvetydiga postlådevisningsnamn. Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använda utbyteskommando. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Återställer utbytesmappar från den givna personliga lagringen. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Återställer utbytesmappar från den givna personliga lagringen. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Återställer utbytesmappar från den angivna personliga lagringsfilen. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Återställer de angivna utbytesmapparna från den givna personliga lagringen. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Återställer de angivna utbytesmapparna från den givna personliga lagringen. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Återställer de angivna utbytesmapparna från den angivna personliga lagringsfilen. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Sparar meddelandet. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Sparar e-postmeddelande som anges av URI:n till det lokala filsystemet. E-postmeddelandefilen är RFC 822-kompatibelt format (EML).  om du vill analysera e-postmeddelandefilerna, använd[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Skickar e-postmeddelandet. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Markerar det angivna meddelandet som läst. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Markerar det angivna meddelandet som läst. |

### Se även

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
