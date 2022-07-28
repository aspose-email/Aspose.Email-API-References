---
title: Pop3Client
second_title: Aspose.Email för .NET API-referens
description: Tillåter applikationer att komma åt och manipulera meddelanden genom att använda Post Office Protocol Version 3 POP3.
type: docs
weight: 16880
url: /sv/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Tillåter applikationer att komma åt och manipulera meddelanden genom att använda Post Office Protocol Version 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_1)(string) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_3)(string, int) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initierar en ny instans av[`Pop3Client`](../pop3client) klass |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Hämtar eller ställer in åtkomsttoken. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Hämtar eller ställer in uppräkning av tillåtna av användarautentiseringstyper |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Innehåller samling av klientcertifikat |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Hämtar eller ställer in ett värde som definierar läget för anslutningstilldelning i flera trådar environment Det finns följande anslutningstyper: - Huvudanslutning skapas och disponeras tillsammans med e-postklienten. Den kan inte skapas eller kasseras manuellt._d_0000 manuellt. Standardanslutning är standardanslutning för vissa trådar. Om standardanslutning finns och ConnectionAsgmtMode tillåter, kommer alla metoder för e-postklient som körs i denna tråd att implicit använda denna anslutning. Endast en standardanslutning kan finnas per tråd. Det kan skapas manuellt eller automatiskt. Det beror på egenskapen EmailClient.ConnectionAsgmtMode. Dessa anslutningar kan skapas manuellt med metoden EmailClient.CreateConnection(createAsDefaultConnection = true). Om standardanslutningen inte används (beror på anslutningstilldelningsläget), används huvudanslutningen implicit istället för den. - Oberoende anslutningar är anslutningar inte länkade till trådar. De kan skapas manuellt och måste användas explicit som metodparameter. Dessa anslutningar kan skapas manuellt med metoden EmailClient.CreateConnection() eller EmailClient.CreateConnection(createAsDefaultConnection = false)-metoden. Det finns följande anslutningstilldelningstyper: Anslutning_0d_0 i standardläge. 0 E-postklienten använder huvudanslutning för alla operationer från flera trådar om standardanslutningen inte har skapats, eller anslutningen inte har skickats som metodparameter explicit. Huvudanslutning är en anslutning som skapas samtidigt som e-postklienten. Användaren kan skapa standardanslutningar för trådar med metoden CreateConnection. Om standardanslutning för tråd skapas, används den implicit för alla metoder för e-postklient som anropas i denna tråd. Om standardanslutning för tråd inte skapas, används huvudanslutning för alla metoder för e-postklient som anropas i denna tråd thread. Användaren kan också skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. Standardanslutning kan endast vara en per tråd. Observera att standardanslutningar fungerar korrekt om användaren använder trådobjekt för multitasking-programmering. Om användaren använder ConnectionPool eller använder Task-objekt för multitasking-programmering kan detta läge leda till felaktigt beteende hos ett program. För att undvika detta problem måste användaren manuellt kassera standardanslutningen (om han använder den) i slutet av koden som körs i tråden. - ConnectionAsgmtType.UseMain E-postklienten använder huvudanslutning för alla operationer från flera trådar. Huvudanslutning är anslutning som skapas samtidigt som e-postklienten. Användaren kan inte skapa standardanslutningar. Användaren kan skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. - ConnectionAsgmtType.UseDefault E-postklienten använder implicit endast standardanslutningar för alla operationer från flera trådar. Huvudanslutning används inte i det här läget. Om standardanslutning inte har skapats för någon tråd (första anropet av e-postklientmetoden), skapar e-postklient standardanslutning implicit för tråden innan den första operationen utförs. Användaren kan inte skapa standardanslutningar för trådar med metoden CreateConnection eftersom de skapas automatiskt. När standardanslutning för tråd skapas, används den implicit för alla metoder för e-postklienter som anropas i denna thread.read. Användaren kan också skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. Standardanslutning kan endast vara en per tråd. Observera att standardanslutningar fungerar korrekt om användaren använder trådobjekt för multitasking-programmering. Om användaren använder ConnectionPool eller använder Task-objekt för multitasking-programmering kan detta läge leda till felaktigt beteende hos ett program. För att undvika detta problem måste användaren manuellt kassera standardanslutningen i slutet av koden som körs i tråden. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Tid för anslutningskontroll i millisekunder. Standardvärdet är 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Hämtar eller ställer in antal anslutningar i fleranslutningsläge |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Hämtar aktuell status för anslutningen. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Får aktuell anslutning enligt ConnectionAsgmtMode option |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Får standardport för client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Hämtar eller ställer in värde som tillåter aktivera/inaktivera logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Hämtar eller ställer in hälsningstimeouten som används när en anslutning upprättas. Observera att hälsningstidsgränsen inte kan vara oändlig. E-postklienter kan utföra tillräckligt långa operationer. För att begränsa drifttiden måste användarna använda[`Timeout`](../../aspose.email.clients/emailclient/timeout)fast egendom. Värden för den här egenskapen måste ha långa intervall för att inte förhindra långtidsoperationer. Men i vissa fall, om EmailClient endast kommer att använda Timeout-egenskap, kan det ta lång tid att upprätta anslutning. Till exempel kan e-postklienten använda det automatiska läget för att upprätta anslutning. I det här läget går e-postklienten igenom alla möjliga anslutningsparametrar tills anslutningen upprättas. SMTP-, IMAP- och POP3-servrar i händelse av korrekt anslutning upprättande skicka hälsningssträng till klienten. Servrar kan använda implicit eller explicit (START TLS) SSL/TLS-anslutningsinitiering. Om anslutningsläget inte matchar (t.ex. väntar servern på en implicit SSL-anslutning men klienten försöker upprätta en icke-säker eller explicit SSL-anslutning), kommer servern inte att skicka en hälsningssträng. I det här fallet kommer användaren att vänta länge tills timeouten når en hälsningssträng och klienten går till nästa anslutningsalternativ. För att undvika detta problem har egenskapen GreetingTimeout introducerats. Med den här egenskapen kan du ställa in timeout för hälsningssträngen, och minska tiden för automatisk upprättande av anslutning. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Hämtar eller ställer in värdnamnet. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Hämtar eller ställer in loggfilens namn |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Hämtar eller ställer in lösenordet. Lösenordsbegränsningar definieras av serverimplementeringen, vilken klient ansluter. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Hämtar eller ställer in porten. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Hämtar eller ställer in proxy för client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Säkerhetsläge för en e-postklient |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Får uppräkning av som stöds av serverautentiseringstyper |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definierar versionerna av SSL/TLS-krypteringsprotokoll som ska användas. VÄNLIGEN VÄS UPPMÄRKSAMHET, du kan endast ställa in de versioner av protokollet som stöds av .net framework. OM NÅGRA VERSIONER AV PROTOKOLL INTE STÖDS AV DIN AV .NET FRAMEWORK KOMMER DE ATT IGNORERAS OCH HOPPAS OVER. DET KAN LEDA TILL NEDGRADERA TLS-SÄKERHETSNIVÅN. I DETTA FALL KOMMER INTE UNDANTAG ATT GENERERAS!!! Snälla, se[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) dokumentation för mer information. Använd[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) metod om du vill ställa in krypteringsprotokollen utan några kompatibilitetskontroller. Standardvärdet är: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (om din nuvarande version av .net framework stöder dessa versioner av TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Hämtar eller ställer in timeout för e-postoperationer |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Hämtar eller ställer in TokenProvider som tillåter att hämta åtkomsttoken. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indikerar om autentisering används. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Hämtar eller ställer in värde som indikerar om datum måste användas i loggfilens namn. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Hämtar eller ställer in ett booleskt värde som styr om DefaultCredentials skickas med förfrågningar. Det här alternativet används ENDAST med NTLM-autentisering! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Hämtar eller ställer in värde som indikerar om klienten måste använda flera anslutningar för tungt belastade operationer. Observera att användning av detta läge inte nödvändigt måste leda till att prestanda ökar. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Hämtar eller ställer in objekt som indikerar om pipelining-läget är aktiverat. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Hämtar eller ställer in användarnamnet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Begå raderingarna |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Begå raderingarna |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Begå raderingarna |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Begå raderingarna |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Skapar ny oberoende anslutning för operationer som inte är länkade till trådar (inte standardanslutning). Anropandet av denna metod liknar anropandet av CreateConnection(createAsDefaultConnection = false) Se mer i dokumentationen för egenskapen EmailClient.ConnectionAsgmtMode._x000. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Skapar en ny (standard eller oberoende) anslutning för operationer. Se mer i dokumentationen för egenskapen EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Tar bort meddelandet |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Tar bort meddelandet |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Tar bort meddelandet |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Tar bort meddelandet |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Tar bort alla meddelanden |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Tar bort alla meddelanden |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Tar bort alla meddelanden |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Tar bort alla meddelanden |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Tar bort alla meddelanden |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Tar bort alla meddelanden |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Slutför alla operationer med en server. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Hämtar meddelandet |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Hämtar meddelandet |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Hämtar meddelandet |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Hämtar meddelandet |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Hämtar meddelandena |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Hämtar meddelandena |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Hämtar meddelandena |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Hämtar meddelandena |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Hämtar meddelandena asynkront |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Hämtar postlådans status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Hämtar postlådans status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Hämtar postlådans status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Hämtar postlådans status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Hämtar postlådans status info |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Får storleken på brevlådan |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Får storleken på brevlådan |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Får storleken på brevlådan |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Får storleken på brevlådan |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Får storleken på brevlådan |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Får storleken på brevlådan |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Hämtar meddelandet count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Hämtar meddelandet count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Hämtar meddelandet count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Hämtar meddelandet count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Hämtar meddelandet count |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Hämtar meddelandet headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Hämtar meddelandet headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Hämtar meddelandet headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Hämtar storleken på meddelandet |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Hämtar storleken på meddelandet |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Hämtar storleken på meddelandet |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Hämtar meddelandet unikt id |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Hämtar meddelandet unikt id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Hämtar meddelandet unikt id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Hämtar meddelandet unikt id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Hämtar meddelandet unikt id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Hämtar meddelandet unikt id |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Listar meddelandena. Får en information för sökmeddelande |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Listar meddelandena. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Listar meddelandena. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Laddar lista med Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Laddar lista med Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | 'Ingen operation' kommando |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | 'Ingen operation' kommando |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Återställer loggningsinställningarna till standard. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Hämtar och sparar meddelandet i en file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Hämtar och sparar meddelandet som en stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Hämtar och sparar meddelandet i en file |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definierar versionerna av SSL/TLS-krypteringsprotokoll som ska användas. Denna metod är inte säker och ställer in krypteringsprotokollen utan några kompatibilitetskontroller. Använd[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) egenskap för att säkert endast ställa in protokoll som definitivt stöds av .net framework. Observera att om ditt nuvarande .net-ramverk inte stöder denna säkerhetsnivå kommer ett undantag att skapas när du försöker upprätta en anslutning till servern. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Utför behörighetsvalidering |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Utför behörighetsvalidering |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Skapar en ny instans av[`Pop3Client`](../pop3client) klass |

### Se även

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
