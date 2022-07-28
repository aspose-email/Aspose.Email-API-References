---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email för .NET API-referens
description: 
type: docs
weight: 80
url: /sv/net/aspose.email.clients.activesync.transportlayer/
---


## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AccountInformation](./accountinformation) | Innehåller användarens kontoinformation. |
| [ActiveSyncTLClient](./activesynctlclient) | Grundklass för ActiveSync-klientimplementeringar |
| [AutodiscoverResult](./autodiscoverresult) | Resultat av Autodiscover-operationen |
| [Body](./body) | Anger ett datafält med variabel längd i fritt format som är associerat med ett lagrat objekt på servern. |
| [BodyPart](./bodypart) | Anger detaljer om meddelandedelen av ett e-postmeddelande i ett svar. BodyPart-elementet MÅSTE inkluderas i ett kommandosvar när BodyPartPreference anges i en begäran. |
| [BodyPreference](./bodypreference) | Innehåller preferensinformation relaterad till typen och storleken på information som returneras från sökning, synkronisering eller hämtning. |
| [CertificateStatuses](./certificatestatuses) | Indikerar om certifikatet har validerats. |
| [DataContainer](./datacontainer) | Innehåller data för ett visst objekt, till exempel en kontakt, e-postmeddelande, kalendermöte eller uppgiftsobjekt. DataContainern kan användas för att ändra objekt, lägga till objekt eller hämta objekt på klientenheten eller servern. |
| [DeviceInformation](./deviceinformation) | Begäran som används för att skicka klientenhetens egenskaper till servern. |
| [DevicePasswordRequest](./devicepasswordrequest) | Anger begäran om att ställa in återställningslösenord för klientenheten av servern. För att rensa ett befintligt återställningslösenord MÅSTE klienten skicka ett tomt lösenord. |
| [EASProvisionDoc](./easprovisiondoc) | Anger samlingen av säkerhetsinställningar för enhetsprovisionering. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Innehåller begäran om att ta bort innehållet i en mapp. EmptyFolderContents stöder ett enda underordnat element i Options-elementet, DeleteSubFolders, som avgör om undermappar som finns i mappen tas bort. Om alternativet DeleteSubFolders inte ingår i begäran raderas inte undermapparna till det angivna CollectionId. |
| [FolderInfo](./folderinfo) | FolderInfo-klassen innehåller mappinformation |
| [FolderSyncResult](./foldersyncresult) | Innehåller ändringar av mapphierarkin. |
| [ItemEstimate](./itemestimate) | Innehåller en bedömning av den begärda mappen |
| [ItemEstimateOptions](./itemestimateoptions) | Innehåller element som filtrerar resultaten av GetItemEstimate-operationen. |
| [ItemEstimateRequest](./itemestimaterequest) | Innehåller ItemEstimate begäran parametrar |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifierar brödtexten i svaret som innehållande operationen som tar bort innehållet i en mapp. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Innehåller egenskaperna som returneras för objekt(er) i svaret. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Innehåller begäran om att hämta ett objekt från servern. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Innehåller svar om att hämta ett objekt från servern. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Innehåller begäran om att flytta en konversation till en specifik mapp. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifierar brödtexten i svaret som innehållande operationen som flyttar en given konversation. |
| [ItemOperationsRequest](./itemoperationsrequest) | Innehåller ItemOperations-begäran. |
| [ItemOperationsResponse](./itemoperationsresponse) | Innehåller ItemOperations-svar. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Innehåller alternativen för ItemOperations.EmptyFolderContents operation |
| [ItOpFetchOptions](./itopfetchoptions) | Innehåller alternativen för ItemOperations.Fetch-operationen. |
| [ItOpMoveOptions](./itopmoveoptions) | Innehåller alternativen för ItemOperations.Move-operationen. |
| [MeetingResponseRequest](./meetingresponserequest) | Anger mötesförfrågan som besvaras, svaret på mötesbegäran och mappen på servern som mötesförfrågan finns i. |
| [MeetingResponseResult](./meetingresponseresult) | Mötessvarsresultat objekt |
| [MoveItemData](./moveitemdata) | Innehåller information om att flytta objekt |
| [MoveItemResponse](./moveitemresponse) | Innehåller information som beskriver de flyttade föremålen. |
| [OOFMessage](./oofmessage) | Anger OOF-meddelandet för en viss publik. Exchange 2007, Exchange 2010 och Exchange 2013 kräver att svarsmeddelandet för okända externa och kända externa målgrupper är detsamma. Egenskapen stöder följande tre målgrupper för ett OOF-meddelande: Intern — En användare som är i samma organisation som den sändande användaren. Känd extern — En användare som är utanför den sändande användarens organisation, men som är representerad i den sändande användarens kontakter. Okänd extern — En användare som är utanför den sändande användarens organisation. organisation och är inte representerad i den avsändande användarens kontakter. |
| [OOFReqParametrs](./oofreqparametrs) | Hämtar OOF-informationsinställningar från servern. |
| [OOFRequest](./oofrequest) | Anger en klass för hämtning och inställning av OOF-information (Out of Office). |
| [OOFResponse](./oofresponse) | Anger en klass för hämtning och inställning av OOF-information (Out of Office). |
| [OOFSettings](./oofsettings) | OOF informationsinställningar. |
| [PictureRequest](./picturerequest) | Indikerar att klienten begär att foton ska returneras i serversvaret. Bilden stöds inte när protokollversionen är 12.1 eller 14.0. Innehåller data relaterade till fotobegäran. |
| [PictureRespose](./picturerespose) | Innehåller data relaterade till kontaktfoton. Bilden stöds inte när protokollversionen är 12.1 eller 14.0. |
| [PingParameter](./pingparameter) | Innehåller ping-kommandot parametrar |
| [ProvisionPolicy](./provisionpolicy) | Anger en säkerhetspolicy. |
| [ProvisionPolicyData](./provisionpolicydata) | Anger inställningarna för en policy. |
| [ProvisionRequest](./provisionrequest) | Innehåller begäran om information för provision command |
| [ProvisionResponse](./provisionresponse) | Innehåller svarsinformation för provision command |
| [QueryType](./querytype) | Anger nyckelorden som ska användas för att matcha posterna i butiken som söks efter. Värdet på frågan används som ett prefix-strängmatchningsmönster och returnerar poster som matchar början av strängen. Till exempel, sökning efter "John" skulle matcha "John Frum" eller "Barry Johnson", men skulle inte matcha "James Littlejohn". Alla icke-tomma textegenskaper i GAL som indexeras med hjälp av ANR jämförs med Query-elementet värde. Sökjämförelser utförs genom att använda skiftlägesokänslig matchning. För en Windows SharePoint Services-dokumentbibliotekssökning stöder detta protokoll frågor i följande form: LinkId == värde, där värdet anger webbadressen till objektet eller mappen och LinkId indikerar att värdet ska jämföras med länk-ID-egenskapen. För postlådesökning är frågesyntaxen följande: - Mappar kan anges på följande sätt: Specificerad ID Specificerad mapp och undermappar Alla e-postmappar, inklusive utkast, Inkorg och undermappar, Utkorg och Skickade objekt - Den grundläggande sökordsfrågan kan bestå av följande: Grundoperatorn: Och (avsnitt 2.2.3.10) Ett dateTime-filter som specificeras med hjälp av GreaterThan (avsnitt 2.2.3.Than) och Less. element (avsnitt 2.2.3.87) Fritextelement (avsnitt 2.2.3.73) som innehåller nyckelord Den grundläggande sökordsfrågan körs mot alla indexerade egenskaper. |
| [Recipient](./recipient) | Representerar en enda mottagare som har lösts. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Indikerar för servern att ledig/upptagen-data begärs av klienten och identifierar start- och sluttid för ledig/upptagen-data som ska hämtas. Tillgängligheten stöds inte när protokollversionen är 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifierar status och ledig/upptagen-data för användarna eller distributionslistor som identifierats i begäran för den tid som identifierats av StartTime och EndTime. När tillgängligheten ingår i en ResolveRecipients-förfrågan, hämtar servern ledig/upptagen-information för de identifierade användarna i Till-elementen som ingår i begäran, och returnerar ledig/upptagen-informationen i MergedFreeBusy i svaret. När servern analyserar begäran löser servern först mottagarna som identifierats av To-elementen och bestämmer sedan användarens ledig/upptagen-information för den angivna tidsperioden, innan den returnerar ledig/upptagen-data i MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Innehåller information om certifikaten för en mottagare. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Innehåller alternativen för att lösa listan över mottagare. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Innehåller information för att lösa mottagare. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Innehåller information om huruvida mottagaren löstes. Om mottagaren löstes, innehåller den också typen av mottagare, e-postadressen som mottagaren löste till och, valfritt, S/MIME-certifikatet för mottagaren. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Innehåller informationsinställningar för rättighetshantering hämtade från servern. |
| [RightsManagementLicense](./rightsmanagementlicense) | Innehåller inställningarna för rättighetspolicymall för mallen som tillämpas på e-postmeddelandet som synkroniseras. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Innehåller mallens identifierare, namn och beskrivning av en rättighetspolicymall som är tillgänglig på klienten. |
| [SearchCondition](./searchcondition) | Anger ett villkor för sökförfrågningar |
| [SearchOptions](./searchoptions) | Innehåller sökalternativen. Användarnamnet och lösenordet kan endast skickas i begäran efter att ha mottagit ett statusvärde på 14. Servern kräver dessa uppgifter för att komma åt de begärda resurserna. Klienten MÅSTE bara skicka dessa över en säker eller pålitlig anslutning, och endast som svar på ett statusvärde på 14. De alternativ som stöds varierar beroende på butiken som söks. Följande tabell listar de giltiga alternativen för varje butik. GAL: Range, UserName, Password, Picture Mailbox: Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport Endast användarnamn 0, DocumentLibrary: BodyPreference är giltigt i _0 kommandobegäranden som inkluderar ett ConversationId. |
| [SearchQuery](./searchquery) | Anger nyckelorden som ska användas för att matcha posterna i butiken som söks efter. Värdet på frågan används som ett prefix-strängmatchningsmönster och returnerar poster som matchar början av strängen. Till exempel, sökning efter "John" skulle matcha "John Frum" eller "Barry Johnson", men skulle inte matcha "James Littlejohn". Alla icke-tomma textegenskaper i GAL som indexeras med hjälp av ANR jämförs med Query-elementet värde. Sökjämförelser utförs med hjälp av skiftlägesokänslig matchning. För en Windows SharePoint Services-dokumentbibliotekssökning stöder detta protokoll frågor i följande form: LinkId == värde, där värde anger URL:en för objektet eller mappen och LinkId indikerar att värdet ska jämföras med länk-ID-egenskapen. För postlådesökning är frågesyntaxen följande: - Mappar kan anges på följande sätt: Specificerad ID Specificerad mapp och undermappar Alla e-postmappar, inklusive utkast, Inkorg och undermappar, Utkorg och Skickade objekt - Den grundläggande sökordsfrågan kan bestå av följande: Grundoperatorn: Och (avsnitt 2.2.3.10) Ett dateTime-filter som specificeras med hjälp av GreaterThan (avsnitt 2.2.3.Than) och Less. element (avsnitt 2.2.3.87) Fritextelement (avsnitt 2.2.3.73) som innehåller nyckelord Den grundläggande sökordsfrågan körs mot alla indexerade egenskaper. |
| [SearchRequest](./searchrequest) | Innehåller information om sökförfrågan |
| [SearchRequestStore](./searchrequeststore) | Ange namn, fråga och alternativ för sökningen. |
| [SearchResponse](./searchresponse) | Innehåller söksvarsinformation |
| [SearchResponseStore](./searchresponsestore) | Innehåller elementen Status, Result, Range och Total för de returnerade postlådeposterna. |
| [SearchResult](./searchresult) | Behållare för ett enskilt matchande postlådeobjekt. När butiken som det söks på är postlådan: - Det finns ett resultatelement för varje matchning som finns i brevlådan. Om inga matchningar hittas finns ett tomt Result-element i Store container-elementet i svaret XML. - Inuti Result-elementet innehåller Properties-elementet en lista med begärda egenskaper för postlådeobjektet. När butiken som är som genomsöks är dokumentbiblioteket: - Det första resultatet som returneras i söksvaret är metadata för rotmappen eller objektet som LinkId-värdet pekar på. Klienten kan välja att ignorera denna post om den inte kräver det. - Om elementvärdet documentlibrary:LinkId i begäran pekar på en mapp, returneras mappens metadataegenskaper som det första objektet, och innehållet i mappen returneras som efterföljande resultat. Området gäller för dessa resultat utan skillnad; index 0 skulle till exempel alltid vara för rotobjektet som länken pekar till. - Om elementvärdet documentlibrary:LinkId i begäran pekar på ett objekt, returneras endast ett resultat: metadata för objektet. - Inuti resultatelementet innehåller elementet Egenskaper en lista över begärda egenskaper för postlådeobjektet. |
| [SearchResultProperties](./searchresultproperties) | Sökkommandosvaret Egenskaper är en behållare för egenskaper som gäller för en enskild post som matchar söksträngen Query-element. Till exempel innehåller elementet Properties ett element för varje icke-tom, textvärderad GAL-egenskap som är kopplad till den matchande GAL-posten. Endast de egenskaper som är kopplade till den specifika GAL-posten returneras; därför kan olika uppsättningar egenskaper returneras i svaret XML för olika matchande GAL-poster. Varje element i Properties-behållaren omfångas till lämpligt namnområde som anges i sökelementet på toppnivå. |
| [ServerInfo](./serverinfo) | Serverinställningar i Autodiscover operation |
| [SettingsRequest](./settingsrequest) | Kommandot Inställningar stöder hämta och ställ in operationer på globala egenskaper och OOF-inställningar (Out of Office) för användaren. Kommandot Inställningar skickar också enhetsinformation till servern, implementerar återställning av enhetens lösenord/PIN-kod och hämtar en lista över användarens e-postadresser. |
| [SettingsResponse](./settingsresponse) | Anger ett svar med OOF-inställningar (Out of Office) och lista över användarens konton. |
| [SmartRequest](./smartrequest) | Innehåller information om smart begäran |
| [SmartRequestSource](./smartrequestsource) | Innehåller information om källmeddelandet. |
| [Status](./status) | Indikerar resultatet av en operation. |
| [SyncAddClientOperation](./syncaddclientoperation) | Skapar ett nytt objekt i en samling på klienten. |
| [SyncAddResponse](./syncaddresponse) | Anger att ett nytt objekt måste skapas i en samling. |
| [SyncAddServerOperation](./syncaddserveroperation) | Skapar ett nytt objekt i en samling på servern. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Innehåller egenskaper för ett befintligt objekt på klientenheten som ändrades. Det ändrade objektet identifieras av dess ServerId-element. |
| [SyncChangeResponse](./syncchangeresponse) | tjänar till att indikera att ett objekt har modifierats. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Innehåller egenskaper för ett befintligt objekt på servern som ändrades. Det ändrade objektet identifieras av dess ServerId-element. |
| [SyncCollectionRequest](./synccollectionrequest) | Klass innehåller kommandon och alternativ som gäller en viss samling. |
| [SyncCollectionResponse](./synccollectionresponse) | Klass innehåller kommandon och alternativ som gäller för ett synkroniseringssvar. |
| [SyncCommandsRequest](./synccommandsrequest) | Innehåller operationer som gäller en samling. Tillgängliga operationer är Lägg till, Ta bort, Ändra, Hämta och SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Innehåller operationer som gäller en samling. Tillgängliga operationer är Lägg till, Ta bort, Ändra, Hämta och SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Tar bort ett objekt på klientenheten eller servern. Objektet identifieras av dess ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Begär applikationsdata för ett objekt som trunkerades i ett synkroniseringssvar från servern. |
| [SyncOperationResponse](./syncoperationresponse) | Basabstrakt klass för synkroniseringsoperationssvar |
| [SyncOperationsResponse](./syncoperationsresponse) | Innehåller svar på operationer som Lägg till, Hämta, Ändra som bearbetas av servern. Svaret innehåller en statuskod och annan information, beroende på operationen. |
| [SyncOptions](./syncoptions) | Anger alternativ som styr vissa aspekter av hur synkroniseringen utförs. |
| [SyncRequest](./syncrequest) | Innehåller synkroniseringsbegäran parametrar |
| [UserInformationResponse](./userinformationresponse) | Innehåller status för begäran och en lista över en användares kontoinformation (e-postadresser). |
| [ValueConverter](./valueconverter) | Klass konverterar ActiveSync-protokollversionen från strängrepresentation till enum och tillbaka. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | ActiveSync-klientgränssnitt |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Base ActiveSync-klientgränssnitt |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum anger typ av autentisering |
| [AirSync](./airsync) | AirSync-namnområdet för ActiveSync-protokollet |
| [AirSyncBase](./airsyncbase) | AirSyncBase-namnområdet för ActiveSync-protokollet |
| [AirsyncClass](./airsyncclass) | Identifierar objektets klass. Följande klasser stöds för brevlådesökningar när protokollversionen är 12.1: - Email - Calendar - Contacts - Tasks - Tasks - Tasks är endast tillgängligt för SMS. protokollet. |
| [AirsyncFilterType](./airsyncfiltertype) | Anger ett valfritt tidsfönster för objekten |
| [AllowBluetooth](./allowbluetooth) | Anger användningen av Bluetooth på enheten. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions anger versionerna av ActiveSync-protokollet. |
| [BehaviorReplacement](./behaviorreplacement) | Anger hur konflikten som uppstår när ett objekt har ändrats på både klienten och servern ska lösas. Värdet anger vilket objekt – klientobjektet eller serverobjektet – som ska behållas om det finns en konflikt. |
| [BodyType](./bodytype) | Anger formattypen för objektets innehåll. |
| [Calendar](./calendar) | Kalendernamnområde för ActiveSync-protokollet |
| [CertificateRetrieval](./certificateretrieval) | Anger om S/MIME-certifikat SKA returneras av servern för varje löst mottagare. |
| [CommandCodes](./commandcodes) | Följande tabell ger de numeriska koder som motsvarar ActiveSync-kommandona. Den numeriska koden används i kommandokodsfältet i den base64-kodade URI:n för att specificera kommandot. |
| [CommandParameters](./commandparameters) | Kommandoparametrar. |
| [ComposeMail](./composemail) | ComposeMail-namnrymden för ActiveSync-protokollet |
| [Contacts](./contacts) | Contacts namespace för ActiveSync-protokollet |
| [Contacts2](./contacts2) | Namnutrymmet Contacts2 för ActiveSync-protokollet |
| [DocumentLibrary](./documentlibrary) | DocumentLibrary-namnutrymmet för ActiveSync-protokollet |
| [Email](./email) | E-postnamnområde för ActiveSync-protokollet |
| [Email2](./email2) | Email2 namnutrymme för ActiveSync-protokollet |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Anger algoritmen som används vid kryptering av S/MIME-meddelanden. |
| [FolderClass](./folderclass) | Anger innehållsklassen för mappen som ska övervakas. |
| [FolderHierarchy](./folderhierarchy) | FolderHierarchy namespace för ActiveSync-protokollet |
| [FolderTypes](./foldertypes) | Anger typen av mapp som uppdaterades (döptes om eller flyttades) eller lades till på servern. |
| [GAL](./gal) | GAL-namnrymden för ActiveSync-protokollet |
| [GetItemEstimate](./getitemestimate) | GetItemEstimate namnutrymme för ActiveSync-protokollet |
| [ItemOperations](./itemoperations) | ItemOperations namnutrymme för ActiveSync-protokollet |
| [MaxAgeFilter](./maxagefilter) | Anger det maximala antalet kalenderdagar som kan synkroniseras. |
| [MeetingResponse](./meetingresponse) | MeetingResponse-namnutrymmet för ActiveSync-protokollet |
| [MergedFreeBusy](./mergedfreebusy) | Anger ledig/upptagen information för användarna eller distributionslistan. |
| [MIMESupport](./mimesupport) | Aktiverar MIME-stöd för e-postobjekt som skickas från servern till klienten. |
| [MIMETruncation](./mimetruncation) | Anger om MIME-data för e-postobjektet SKA trunkeras när det skickas från servern till klienten. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Anger den nödvändiga komplexitetsnivån för klientlösenordet. Till exempel: Om värdet på MinDevicePasswordComplexCharacters är 2, skulle ett lösenord med både stora och små bokstäver räcka, liksom ett lösenord med gemener och siffror. |
| [Move](./move) | Flytta namnutrymmet för ActiveSync-protokollet |
| [Namespace](./namespace) | ActiveSync-kodsidor |
| [Notes](./notes) | Anteckningar namnutrymme för ActiveSync-protokollet |
| [OofState](./oofstate) | Anger tillgängligheten för Oof-egenskapen. |
| [Ping](./ping) | Pinga namnutrymmet för ActiveSync-protokollet |
| [Provision](./provision) | Tillhandahålla namnutrymmet för ActiveSync-protokollet |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | Värdet indikerar framgång eller misslyckande för klienten att tillämpa policyinställningarna som hämtats från servern. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | Värdet indikerar framgång eller misslyckande av en fjärrspolning på klienten. |
| [RecipientType](./recipienttype) | Indikerar typen av mottagare. |
| [ResolveRecipients](./resolverecipients) | ResolveRecipients namnområde för ActiveSync-protokollet |
| [RightsManagement](./rightsmanagement) | RightsManagement namnutrymme för ActiveSync-protokollet |
| [Search](./search) | Sök namnutrymme för ActiveSync-protokollet |
| [ServerType](./servertype) | Anger servertypen |
| [Settings](./settings) | Inställningar namnutrymme för ActiveSync-protokollet |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Anger algoritmen som används vid signering av S/MIME-meddelanden. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Styr förhandlingen av krypteringsalgoritmen. |
| [StoreType](./storetype) | Innehåller infarmation som anger platsen för operationerna. |
| [Tasks](./tasks) | Uppgifter namnutrymme för ActiveSync-protokollet |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Anger typen av mapp som ska skapas. |
| [UserResponse](./userresponse) | Indikerar om mötet accepteras, preliminärt accepteras eller avvisas. |
| [ValidateCert](./validatecert) | ValidateCert namnutrymme för ActiveSync-protokollet |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
