---
title: IGraphClient
second_title: Aspose.Email för .NET API-referens
description: Representerar gränssnittet för Exchange REST-klienten.
type: docs
weight: 15950
url: /sv/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Representerar gränssnittet för Exchange REST-klienten.

```csharp
public interface IGraphClient : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Hämtar eller ställer in data för proxyåtkomst till Exchange-servern. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Hämtar eller ställer in resurstyp. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Hämtar eller ställer in resurs-id. För användare kan det till exempel vara användarnamn (UPN) eller användar-id |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Hämtar eller ställer in klientidentifierare |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Kopiera en e-postmapp och dess innehåll till en annan e-postmapp. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Kopiera ett meddelande till en annan e-postmapp. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Kopierar en anteckningsbok till mappen Anteckningsböcker i målbiblioteket Dokument. Mappen skapas om den inte finns. För kopieringsoperationer följer du ett asynkront anropsmönster: Anrop först åtgärden Kopiera och efterfråga sedan operationens slutpunkt för resultatet. Permissions En av följande behörigheter krävs för att anropa detta API. Delegerat (arbets- eller skolkonto) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(personligt Microsoft-konto) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All_x000 |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Skapar ny bilaga för specificerad item |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Skapar en[`OutlookCategory`](../outlookcategory) objekt i användarens huvudlista över kategorier. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Skapa ny mapp. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Skapa ny mapp. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Skapar meddelande i angiven mapp |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Skapa en ny OneNote-anteckningsbok. Permissions En av följande behörigheter krävs för att anropa detta API. Delegated (arbets- eller skolkonto) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Microsoft-konto Delegerat_x000 Skapa, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Skapa en åsidosättning för en avsändare som identifieras av en SMTP-adress. Framtida meddelanden från den SMTP-adressen kommer konsekvent att klassificeras som specificerat i åsidosättningen. Obs: - Om en åsidosättning redan finns med samma SMTP-adress, uppdateras klassificeraAs och namnfälten för den åsidosättningen med de angivna värdena. - Det maximala antalet åsidosättanden som stöds för en postlåda är 1000, baserat på unika avsändarens SMTP-adresser. Permissions: Delegated(arbets- eller skolkonto) Mail.ReadWrite Delegated(personligt Microsoft-konto) Mail.ReadWrite Application Mail Application Mail. |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Skapa en åsidosättning för en avsändare som identifieras av en SMTP-adress. Framtida meddelanden från den SMTP-adressen kommer konsekvent att klassificeras som specificerat i åsidosättningen. Obs: - Om en åsidosättning redan finns med samma SMTP-adress, uppdateras klassificeraAs och namnfälten för den åsidosättningen med de angivna värdena. - Det maximala antalet åsidosättanden som stöds för en postlåda är 1000, baserat på unika avsändarens SMTP-adresser. Permissions: Delegated(arbets- eller skolkonto) Mail.ReadWrite Delegated(personligt Microsoft-konto) Mail.ReadWrite Application Mail Application Mail. |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Skapa en meddelanderegel genom att ange en uppsättning villkor och åtgärder. Outlook utför dessa åtgärder om ett inkommande meddelande i användarens inkorg uppfyller de angivna villkoren. Behörigheter: En av följande behörigheter krävs för att anropa detta API. läs mer, inklusive hur du väljer behörigheter, se Permissions. Delegated (jobb- eller skolkonto) MailboxSettings.ReadWrite Delegated (personligt Microsoft-konto) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Ta bort objekt. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Tar bort attachment |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Hämtar bilaga för specificerat id |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Hämta egenskaperna och relationerna för det angivna outlookCategory-objektet. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Hämtar meddelande i angivet id |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Hämta egenskaperna och relationerna för ett anteckningsboksobjekt. Permissions En av följande behörigheter krävs för att anropa detta API. Delegerade (arbets- eller skolkonto) Notes.Create, Notes.Read, Notes.ReadWrite.Alla.Resa.Resa. , Notes.ReadWrite.All Delegerad (personligt Microsoft-konto) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Hämta egenskaperna och relationerna för ett meddelanderegelobjekt. Permissions En av följande behörigheter krävs för att anropa detta API. Om du vill veta mer, inklusive hur du väljer behörigheter, se Behörigheter. Delegerad (jobb- eller skolkonto) MailboxSettings.Read Delegerad (personligt Microsoft-konto) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Hämtar mapp med ett id. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Få status för en långvarig OneNote-operation. Detta gäller operationer som returnerar Operation-Location-huvudet i svaret, såsom CopyNotebook, CopyToNotebook, CopyToSectionGroup och CopyToSection. Du kan polla Operation-Location-slutpunkten tills statusegenskapen returnerar avslutad eller misslyckad. Om statusen är klar innehåller egenskapen resourceLocation resursslutpunkten URI. Om statusen misslyckades ger felet och egenskaperna @api.diagnostics felinformation. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Lista bilagor från det överordnade meddelandet. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Få alla kategorier som har definierats för användaren. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Lista mappar från den överordnade mappen för mappar som visas i vanliga e-postklienter, till exempel inkorgen. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Lista mappar från den överordnade mappen för mappar som visas i vanliga e-postklienter, till exempel inkorgen. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Lista MessageInfo från den överordnade mappen. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Lista MessageInfo från den överordnade mappen. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Hämta en lista över anteckningsbokobjekt. Permissions En av följande behörigheter krävs för att anropa detta API. Delegerat (arbets- eller skolkonto) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read. ReadWrite.All Delegated (personligt Microsoft-konto) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Få de åsidosättningar som en användare har ställt in för att alltid klassificera meddelanden från vissa avsändare på specifika sätt. Varje åsidosättning motsvarar en SMTP-adress för en avsändare. Till en början har en användare inga åsidosättningar. Behörigheter: En av följande behörigheter krävs för att anropa detta API. För att lära dig mer, inklusive hur du väljer behörigheter, se Behörigheter. Delegerad (arbets- eller skolkonto) Mail.Read Delegerad (personligt Microsoft-konto) Mail.Read Application Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Hämta alla messageRule-objekt som definierats för användarens inkorg. Permissions En av följande behörigheter krävs för att anropa detta API. För att lära dig mer, inklusive hur du väljer behörigheter, se Permissions. Delegated (arbets- eller skolkonto) MailboxSettings.Red_x000 Delegerad (personligt Microsoft-konto) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Flytta en e-postmapp och dess innehåll till en annan e-postmapp. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Flytta ett meddelande till en annan e-postmapp. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | Skickar e-postmeddelande |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Skicka ett meddelande i utkastmappen. Utkastmeddelandet kan vara ett nytt meddelandeutkast, svarsutkast, svar-alla-utkast eller ett vidarebefordra utkast. Meddelandet sparas sedan i mappen Skickade objekt. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | Skickar e-postmeddelande |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Markera meddelande som read |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Uppdaterar förinställd färgkonstant för angiven kategori |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Uppdateringsmappen. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Uppdateringar meddelande |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Uppdateringar meddelande |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Ändra classifyAs-fältet för en åsidosättning som specificerat. Du kan inte använda den här metoden för att ändra några andra fält i en ClassificationOverride-instans. Om det finns en åsidosättning för en avsändare och avsändaren ändrar hans/hennes visningsnamn, kan du använda CreateOrUpdateOverride för att tvinga fram en uppdatering av namnfältet i den befintliga åsidosättningen. Om en åsidosättning finns för en avsändare och avsändaren ändrar sin SMTP-adress, är att ta bort den befintliga åsidosättningen och skapa en ny med den nya SMTP-adressen det enda sättet att "uppdatera" åsidosättningen för denna avsändare. Behörigheter: En av följande behörigheter krävs för att anropa detta API. Om du vill veta mer, inklusive hur du väljer behörigheter, se Behörigheter. Delegerad (arbets- eller skolkonto) Mail.ReadWrite Delegated (personligt Microsoft-konto) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Ändra skrivbara egenskaper på ett messageRule-objekt och spara ändringarna. Permissions En av följande behörigheter krävs för att anropa detta API. För att lära dig mer, inklusive hur du väljer behörigheter, se Behörigheter. Delegerade (jobb- eller skolkonto) MailboxSettings. ReadWrite Delegerad (personligt Microsoft-konto) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### Se även

* namnutrymme [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
