---
title: SmtpClient
second_title: Aspose.Email för .NET API-referens
description: Tillåter att program skickar meddelanden genom att använda Simple Mail Transfer Protocol SMTP.
type: docs
weight: 17030
url: /sv/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Tillåter att program skickar meddelanden genom att använda Simple Mail Transfer Protocol (SMTP).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Initierar en ny instans av[`SmtpClient`](../smtpclient) klass genom att använda konfigurationsfilinställningar. |
| [SmtpClient](smtpclient#constructor_2)(string) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Initierar en ny instans av[`SmtpClient`](../smtpclient) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Hämtar eller ställer in åtkomsttoken. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Hämtar eller ställer in uppräkning av tillåtna av användarautentiseringstyper |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Innehåller samling av klientcertifikat |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Hämtar eller ställer in ett värde som definierar läget för anslutningstilldelning i flera trådar environment Det finns följande anslutningstyper: - Huvudanslutning skapas och disponeras tillsammans med e-postklienten. Den kan inte skapas eller kasseras manuellt._d_0000 manuellt. Standardanslutning är standardanslutning för vissa trådar. Om standardanslutning finns och ConnectionAsgmtMode tillåter, kommer alla metoder för e-postklient som körs i denna tråd att implicit använda denna anslutning. Endast en standardanslutning kan finnas per tråd. Det kan skapas manuellt eller automatiskt. Det beror på egenskapen EmailClient.ConnectionAsgmtMode. Dessa anslutningar kan skapas manuellt med metoden EmailClient.CreateConnection(createAsDefaultConnection = true). Om standardanslutningen inte används (beror på anslutningstilldelningsläget), används huvudanslutningen implicit istället för den. - Oberoende anslutningar är anslutningar inte länkade till trådar. De kan skapas manuellt och måste användas explicit som metodparameter. Dessa anslutningar kan skapas manuellt med metoden EmailClient.CreateConnection() eller EmailClient.CreateConnection(createAsDefaultConnection = false)-metoden. Det finns följande anslutningstilldelningstyper: Anslutning_0d_0 i standardläge. 0 E-postklienten använder huvudanslutning för alla operationer från flera trådar om standardanslutningen inte har skapats, eller anslutningen inte har skickats som metodparameter explicit. Huvudanslutning är en anslutning som skapas samtidigt som e-postklienten. Användaren kan skapa standardanslutningar för trådar med metoden CreateConnection. Om standardanslutning för tråd skapas, används den implicit för alla metoder för e-postklient som anropas i denna tråd. Om standardanslutning för tråd inte skapas, används huvudanslutning för alla metoder för e-postklient som anropas i denna tråd thread. Användaren kan också skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. Standardanslutning kan endast vara en per tråd. Observera att standardanslutningar fungerar korrekt om användaren använder trådobjekt för multitasking-programmering. Om användaren använder ConnectionPool eller använder Task-objekt för multitasking-programmering kan detta läge leda till felaktigt beteende hos ett program. För att undvika detta problem måste användaren manuellt kassera standardanslutningen (om han använder den) i slutet av koden som körs i tråden. - ConnectionAsgmtType.UseMain E-postklienten använder huvudanslutning för alla operationer från flera trådar. Huvudanslutning är anslutning som skapas samtidigt som e-postklienten. Användaren kan inte skapa standardanslutningar. Användaren kan skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. - ConnectionAsgmtType.UseDefault E-postklienten använder implicit endast standardanslutningar för alla operationer från flera trådar. Huvudanslutning används inte i det här läget. Om standardanslutning inte har skapats för någon tråd (första anropet av e-postklientmetoden), skapar e-postklient standardanslutning implicit för tråden innan den första operationen utförs. Användaren kan inte skapa standardanslutningar för trådar med metoden CreateConnection eftersom de skapas automatiskt. När standardanslutning för tråd skapas, används den implicit för alla metoder för e-postklienter som anropas i denna thread.read. Användaren kan också skapa anslutningar som inte är länkade till trådar (inte standardanslutningar) med metoden CreateConnection. Om användaren vill använda andra anslutningar (inte main och inte standard) måste han skicka denna anslutning uttryckligen som parameter för en metod som han vill använda. Användaren kan dessutom skapa valfritt antal anslutningar. Standardanslutning kan endast vara en per tråd. Observera att standardanslutningar fungerar korrekt om användaren använder trådobjekt för multitasking-programmering. Om användaren använder ConnectionPool eller använder Task-objekt för multitasking-programmering kan detta läge leda till felaktigt beteende hos ett program. För att undvika detta problem måste användaren manuellt kassera standardanslutningen i slutet av koden som körs i tråden. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Tid för anslutningskontroll i millisekunder. Standardvärdet är 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Hämtar eller ställer in antal anslutningar i fleranslutningsläge |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Hämtar aktuell status för anslutningen. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Får aktuell anslutning enligt ConnectionAsgmtMode option |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Får standardport för client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Hämtar eller ställer in leveransmetoden. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Hämtar eller ställer in värde som tillåter aktivera/inaktivera logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Hämtar eller ställer in hälsningstimeouten som används när en anslutning upprättas. Observera att hälsningstidsgränsen inte kan vara oändlig. E-postklienter kan utföra tillräckligt långa operationer. För att begränsa drifttiden måste användarna använda[`Timeout`](../../aspose.email.clients/emailclient/timeout)fast egendom. Värden för den här egenskapen måste ha långa intervall för att inte förhindra långtidsoperationer. Men i vissa fall, om EmailClient endast kommer att använda Timeout-egenskap, kan det ta lång tid att upprätta anslutning. Till exempel kan e-postklienten använda det automatiska läget för att upprätta anslutning. I det här läget går e-postklienten igenom alla möjliga anslutningsparametrar tills anslutningen upprättas. SMTP-, IMAP- och POP3-servrar i händelse av korrekt anslutning upprättande skicka hälsningssträng till klienten. Servrar kan använda implicit eller explicit (START TLS) SSL/TLS-anslutningsinitiering. Om anslutningsläget inte matchar (t.ex. väntar servern på en implicit SSL-anslutning men klienten försöker upprätta en icke-säker eller explicit SSL-anslutning), kommer servern inte att skicka en hälsningssträng. I det här fallet kommer användaren att vänta länge tills timeouten når en hälsningssträng och klienten går till nästa anslutningsalternativ. För att undvika detta problem har egenskapen GreetingTimeout introducerats. Med den här egenskapen kan du ställa in timeout för hälsningssträngen, och minska tiden för automatisk upprättande av anslutning. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Hämtar eller ställer in en HELO/EHLO-sträng. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Hämtar eller ställer in värdnamnet. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Hämtar eller ställer in loggfilens namn |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Hämtar eller ställer in lösenordet. Lösenordsbegränsningar definieras av serverimplementeringen, vilken klient ansluter. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Hämtar eller ställer in katalogen där applikationer sparar e-postmeddelanden som ska behandlas av den lokala SMTP-servern. Observera: endast absolut sökväg är tillåten. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Hämtar eller ställer in porten. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Hämtar eller ställer in proxy för client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Säkerhetsläge för en e-postklient |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Hämtar eller ställer in katalogen där applikationer sparar e-postmeddelanden som ska bearbetas genom att skicka i SMTP-kö. Observera: endast absolut sökväg är tillåten. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Får uppräkning av som stöds av serverautentiseringstyper |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definierar versionerna av SSL/TLS-krypteringsprotokoll som ska användas. VÄNLIGEN VÄS UPPMÄRKSAMHET, du kan endast ställa in de versioner av protokollet som stöds av .net framework. OM NÅGRA VERSIONER AV PROTOKOLL INTE STÖDS AV DIN AV .NET FRAMEWORK KOMMER DE ATT IGNORERAS OCH HOPPAS OVER. DET KAN LEDA TILL NEDGRADERA TLS-SÄKERHETSNIVÅN. I DETTA FALL KOMMER INTE UNDANTAG ATT GENERERAS!!! Snälla, se[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) dokumentation för mer information. Använd[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) metod om du vill ställa in krypteringsprotokollen utan några kompatibilitetskontroller. Standardvärdet är: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (om din nuvarande version av .net framework stöder dessa versioner av TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Hämtar eller ställer in timeout för e-postoperationer |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Hämtar eller ställer in TokenProvider som tillåter att hämta åtkomsttoken. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indikerar om autentisering används. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Hämtar eller ställer in värde som indikerar om datum måste användas i loggfilens namn. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Hämtar eller ställer in ett booleskt värde som styr om DefaultCredentials skickas med förfrågningar. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Hämtar eller ställer in värde som indikerar om klienten måste använda flera anslutningar för tungt belastade operationer. Observera att användning av detta läge inte nödvändigt måste leda till att prestanda ökar. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Hämtar eller ställer in objekt som indikerar om pipelining-läget är aktiverat. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Hämtar eller ställer in användarnamnet. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Hämtar eller ställer in ett booleskt värde som styr om meddelandena skickas i TNEF-format. Observera att nu skickas meddelande i TNEF-format när ett meddelande laddas innehåller tnef. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Skapar ny oberoende anslutning för operationer som inte är länkade till trådar (inte standardanslutning). Anropandet av denna metod liknar anropandet av CreateConnection(createAsDefaultConnection = false) Se mer i dokumentationen för egenskapen EmailClient.ConnectionAsgmtMode._x000. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Skapar en ny (standard eller oberoende) anslutning för operationer. Se mer i dokumentationen för egenskapen EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Slutför alla operationer med en server. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Vidarebefordrar specificerat meddelande till recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Vidarebefordrar specificerat meddelande till recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Vidarebefordrar specificerat meddelande till recipient |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | 'Ingen operation' kommando |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | 'Ingen operation' kommando |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | 'Ingen operation' kommando |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Återställer loggningsinställningarna till standard. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Skicka de angivna meddelandena. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Skicka det angivna meddelandet. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Skicka den angivna meddelandesamlingen. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Skicka det angivna meddelandet. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Skicka de angivna meddelandena. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Skicka det angivna meddelandet. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Skicka den angivna meddelandesamlingen. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Skicka det angivna meddelandet. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Skapar och skickar det angivna meddelandet. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Skapar och skickar det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Skicka de angivna meddelandena. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Skicka den angivna meddelandesamlingen. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Skicka de angivna meddelandena. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Skicka den angivna meddelandesamlingen. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Skicka de angivna meddelandena. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Skicka den angivna meddelandesamlingen. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Skicka de angivna meddelandena. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Skicka det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Skicka den angivna meddelandesamlingen. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Skapar och skickar det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Skapar och skickar det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Skapar och skickar det angivna meddelandet. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Skapar och skickar det angivna meddelandet. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Lägg till meddelanden till queue |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definierar versionerna av SSL/TLS-krypteringsprotokoll som ska användas. Denna metod är inte säker och ställer in krypteringsprotokollen utan några kompatibilitetskontroller. Använd[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) egenskap för att säkert endast ställa in protokoll som definitivt stöds av .net framework. Observera att om ditt nuvarande .net-ramverk inte stöder denna säkerhetsnivå kommer ett undantag att skapas när du försöker upprätta en anslutning till servern. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Utför behörighetsvalidering |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Utför behörighetsvalidering |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Utför behörighetsvalidering |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Skapar en ny instans av[`SmtpClient`](../smtpclient) klass |

### Se även

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* namnutrymme [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
