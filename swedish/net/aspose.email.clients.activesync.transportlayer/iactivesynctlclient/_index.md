---
title: IActiveSyncTLClient
second_title: Aspose.Email för .NET API-referens
description: ActiveSync-klientgränssnitt
type: docs
weight: 1310
url: /sv/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

ActiveSync-klientgränssnitt

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Innehåller ett värde som används av servern för att markera synkroniseringstillståndet för en varje synkroniserad samling. Där ordboksnyckeln är server-ID och ordboksvärdet är SyncKey. För kommandon GetItemEstimate och Sync. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Används av servern för att spåra klientens nuvarande tillstånd. Endast för operationer med mappar |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | HeartbeatInterval-elementet är ett underordnat element till Ping-elementet i Ping-kommandoförfrågningar och svar. I Ping-kommandoförfrågningar anger den hur lång tid, i sekunder, som servern SKA vänta innan den skickar ett svar om inga nya objekt läggs till i den angivna uppsättningen mappar, som specificerats i avsnitt 3.1.5.6. HeartbeatInterval-elementet returneras också av servern med en statuskod på 5 och anger antingen det lägsta eller maximala intervallet som är tillåtet när klienten har begärt ett hjärtslagsintervall som ligger utanför det acceptabla intervallet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | The FolderCreate skapar en ny mapp som en underordnad mapp till den angivna överordnade mappen. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Tar bort samlingen med den matchande identifieraren. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync synkroniserar samlingshierarkin men synkroniserar inte objekten i själva samlingarna. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync synkroniserar samlingshierarkin men synkroniserar inte objekten i själva samlingarna. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | Kommandot FolderUpdate flyttar en mapp från en plats till en annan på servern. Kommandot används också för att byta namn på en mapp. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | Kommandot FolderUpdate flyttar en mapp från en plats till en annan på servern. Kommandot används också för att byta namn på en mapp. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment hämtar en e-postbilaga från servern. GetAttachment stöds inte när protokollversionen är 14.0 eller 14.1. Använd elementet Fetch i kommandot ItemOperations istället. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | Kommandot GetItemEstimate får en uppskattning av antalet objekt i en samling eller mapp på servern som måste synkroniseras. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | Kommandot GetItemEstimate får en uppskattning av antalet objekt i en samling eller mapp på servern som måste synkroniseras. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | Kommandot GetItemEstimate får en uppskattning av antalet objekt i en samling eller mapp på servern som måste synkroniseras. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations tillhandahåller batch-onlinehantering av Fetch-, EmptyFolderContents och Move-operationerna. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | Kommandot MoveItems flyttar ett eller flera objekt från en mapp på servern till en annan. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | Kommandot MoveItems flyttar ett eller flera objekt från en mapp på servern till en annan. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | Kommandot MoveItems flyttar ett eller flera objekt från en mapp på servern till en annan. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Kommandot Provision gör det möjligt för klientenheter att begära de säkerhetspolicyinställningar som administratören ställer in från servern, såsom det lägsta kravet på lösenordslängd för personligt identifieringsnummer (PIN). |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Återställ SyncKeys för GetItemEstimate och Sync-operationer för alla samlingar. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | Återställ SyncKey för GetItemEstimate och Sync-operationer för definierad samling. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Återställ SyncKey för operationer med mappar |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients används för att lösa en lista över tillhandahållna mottagare, för att hämta deras ledig/upptagen-information och valfritt för att hämta sina S/MIME-certifikat så att klienter kan skicka krypterade S/MIME-e-postmeddelanden. Hämtning av ledig/upptagen information att använda Availability-elementet i ResolveRecipients-kommandot stöds inte när protokollversionen är 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | Sökningen används för att hitta poster i en adressbok, brevlåda eller dokumentbibliotek (UNC eller Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | SendMail används av klienter för att skicka MIME-formaterade e-postmeddelanden till servern. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | SendMail används av klienter för att skicka MIME-formaterade e-postmeddelanden till servern. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | SendMail används av klienter för att skicka MIME-formaterade e-postmeddelanden till servern. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | SendMail används av klienter för att skicka MIME-formaterade e-postmeddelanden till servern. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Inställningarna stöder hämta och ställa in operationer på globala egenskaper och OOF-inställningar (Out of Office) för användaren. Inställningarna skickar också enhetsinformation till servern, implementerar enhetslösenord/PIN-återställning och hämtar en lista över användarens e-postadresser. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | Kommandot SmartForward används av klienter för att vidarebefordra meddelanden utan att hämta det fullständiga, ursprungliga meddelandet från servern. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | SmartReply-kommandot används av klienter för att svara på meddelanden utan att hämta hela originalmeddelandet från servern. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Synkroniseringen synkroniserar ändringar i en samling mellan klienten och servern. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | Kommandot ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post. |

### Se även

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
