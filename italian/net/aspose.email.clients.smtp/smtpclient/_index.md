---
title: SmtpClient
second_title: Aspose.Email per riferimento all'API .NET
description: Consente alle applicazioni di inviare messaggi utilizzando il protocollo SMTP Simple Mail Transfer Protocol.
type: docs
weight: 17030
url: /it/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Consente alle applicazioni di inviare messaggi utilizzando il protocollo SMTP (Simple Mail Transfer Protocol).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe utilizzando le impostazioni del file di configurazione. |
| [SmtpClient](smtpclient#constructor_2)(string) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Inizializza una nuova istanza di[`SmtpClient`](../smtpclient) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Ottiene o imposta il token di accesso. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Ottiene o imposta l'enumerazione dei tipi di autenticazione consentiti dall'utente |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contiene la raccolta di certificati client |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Ottiene o imposta il valore che definisce la modalità di allocazione della connessione nell'ambiente a più thread Esistono i seguenti tipi di connessione: - La connessione principale è una connessione creata ed eliminata insieme al client di posta. Non può essere creata o eliminata manualmente. - La connessione predefinita è la connessione predefinita per alcuni thread. Se esiste una connessione predefinita e ConnectionAsgmtMode lo consente, tutti i metodi del client di posta elettronica eseguiti in questo thread utilizzeranno implicitamente questa connessione. Può esistere solo una connessione predefinita per thread. Può essere creato manualmente o automaticamente. Dipende dalla proprietà EmailClient.ConnectionAsgmtMode. Queste connessioni possono essere create manualmente con il metodo EmailClient.CreateConnection(createAsDefaultConnection = true). Se la connessione predefinita non viene utilizzata (dipende dalla modalità di allocazione della connessione), viene utilizzata implicitamente la connessione principale al suo posto. - Le connessioni indipendenti sono connessioni che sono non collegati a thread. Possono essere creati manualmente e devono essere utilizzati esplicitamente come parametro del metodo. Queste connessioni possono essere create manualmente con il metodo EmailClient.CreateConnection() o EmailClient.CreateConnection(createAsDefaultConnection = false). Sono disponibili i seguenti tipi di allocazione della connessione: - ConnectionAsgmtType.UseMainOrDefault Questa modalità viene utilizzata per impostazione predefinita nei client di posta elettronica. Il client di posta elettronica utilizza la connessione principale per tutte le operazioni da più thread se la connessione predefinita non è stata creata o la connessione non è stata passata esplicitamente come parametro del metodo. La connessione principale è una connessione creata contemporaneamente al client di posta elettronica. L'utente può creare connessioni predefinite per i thread con il metodo CreateConnection. Se viene creata la connessione predefinita per il thread, viene utilizzata implicitamente per tutti i metodi del client di posta elettronica richiamati in questo thread. Se la connessione predefinita per il thread non viene creata, viene utilizzata la connessione principale per tutti i metodi del client di posta elettronica richiamati in questo thread. L'utente può anche creare connessioni non collegate a thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. La connessione predefinita può essere solo una per thread. Notare che le connessioni predefinite funzionano correttamente se l'utente utilizza oggetti Thread per la programmazione multitasking. Se l'utente utilizza ConnectionPool o utilizza oggetti Task per la programmazione multitasking, questa modalità può portare a un comportamento errato di un programma. Per evitare questo problema l'utente deve eliminare manualmente la connessione predefinita (se la utilizza) alla fine del codice che viene eseguito in il thread. - ConnectionAsgmtType.UseMain Il client di posta elettronica utilizza la connessione principale per tutte le operazioni da più thread. La connessione principale è una connessione creata contemporaneamente al client di posta elettronica. L'utente non può creare connessioni predefinite. L'utente può creare connessioni non collegate a thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. - ConnectionAsgmtType.UseDefault Il client di posta elettronica utilizza implicitamente solo connessioni predefinite per tutte le operazioni da più thread. La connessione principale non viene utilizzata in questa modalità. Se la connessione predefinita non è stata creata per alcuni thread (prima chiamata del metodo del client di posta elettronica), il client di posta elettronica crea la connessione predefinita implicitamente per il thread prima dell'esecuzione della prima operazione. L'utente non può creare connessioni predefinite per i thread con il metodo CreateConnection perché vengono create automaticamente. Quando viene creata la connessione predefinita per il thread, viene utilizzata implicitamente per tutti i metodi del client di posta elettronica richiamati in questo thread.read. L'utente può anche creare connessioni non collegate ai thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. La connessione predefinita può essere solo una per thread. Notare che le connessioni predefinite funzionano correttamente se l'utente utilizza oggetti Thread per la programmazione multitasking. Se l'utente utilizza ConnectionPool o utilizza oggetti Task per la programmazione multitasking, questa modalità potrebbe portare a un comportamento errato di un programma. Per evitare questo problema l'utente deve eliminare manualmente la connessione predefinita alla fine del codice che viene eseguito nel thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Periodo di verifica della connessione in millisecondi. Il valore predefinito è 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Ottiene o imposta la quantità di connessioni in modalità multiconnessione |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Ottiene lo stato corrente della connessione. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Ottiene la connessione corrente in base all'opzione ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Ottiene la porta predefinita per client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Ottiene o imposta il metodo di consegna. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Ottiene o imposta un valore che consente di abilitare/disabilitare logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Ottiene o imposta il timeout di saluto utilizzato quando si stabilisce una connessione. Notare che il timeout di saluto non può essere infinito. I client di posta elettronica possono eseguire operazioni abbastanza lunghe. Per limitare il tempo delle operazioni gli utenti devono utilizzare[`Timeout`](../../aspose.email.clients/emailclient/timeout)proprietà. I valori per questa proprietà devono avere intervalli lunghi per non impedire operazioni di lunga durata. Ma in alcuni casi, se EmailClient utilizzerà solo la proprietà Timeout, la connessione potrebbe richiedere molto tempo. Ad esempio, il client di posta può utilizzare la modalità automatica per stabilire la connessione. In questa modalità, il client di posta elettronica esamina tutti i parametri di connessione possibili fino a quando la connessione non viene stabilita. Server SMTP, IMAP e POP3 in caso di connessione corretta che stabiliscono la stringa di saluto di invio al client. I server possono utilizzare l'avvio della connessione SSL/TLS implicito o esplicito (START TLS). Se la modalità di connessione non corrisponde (ad esempio, il server attende una connessione SSL implicita ma il client tenta di stabilire una connessione SSL non protetta o esplicita), il server non invierà una stringa di saluto. In questo caso, l'utente attenderà a lungo finché il timeout non raggiunge una stringa di saluto e il client passa all'opzione di connessione successiva. Per evitare questo problema, è stata introdotta la proprietà GreetingTimeout. Questa proprietà consente di impostare il timeout per la stringa di saluto, e di ridurre il tempo di creazione automatica della connessione. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Ottiene o imposta una stringa HELO/EHLO. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ottiene o imposta il nome host. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Ottiene o imposta il nome del file di registro |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Ottiene o imposta la password. Le limitazioni della password sono definite dall'implementazione del server, a cui il client si connette. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Ottiene o imposta la directory in cui le applicazioni salvano i messaggi di posta che devono essere elaborati dal server SMTP locale. Nota: è consentito solo il percorso assoluto. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Ottiene o imposta la porta. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Ottiene o imposta il proxy per il client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Modalità di sicurezza per un client di posta |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Ottiene o imposta la directory in cui le applicazioni salvano i messaggi di posta da elaborare inviandoli nella coda SMTP. Nota: è consentito solo il percorso assoluto. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Ottiene l'enumerazione dei tipi di autenticazione del server supportati |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definisce le versioni dei protocolli di crittografia SSL/TLS da utilizzare. SI PREGA DI PRESTARE ATTENZIONE, è possibile impostare solo le versioni di protocollo che sono supportate da .net framework. SE ALCUNE VERSIONI DI PROTOCOLLO NON SONO SUPPORTATE DALLA VERSIONE ATTUALE DI .NET FRAMEWORK, SARANNO IGNORATI E SALTATI. POTREBBE PORTARE AL DOWNGRADE DEL LIVELLO DI SICUREZZA TLS. IN QUESTO CASO NON VERRÀ GENERATA ECCEZIONE!!! Per favore, guarda[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentazione per maggiori dettagli. Utilizzare[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) metodo se si desidera impostare i protocolli di crittografia senza alcun controllo di compatibilità. Il valore predefinito è: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (nel caso in cui la versione corrente di .net framework supporti queste versioni di TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Ottiene o imposta il timeout per le operazioni di posta |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Ottiene o imposta TokenProvider consentendo di recuperare il token di accesso. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indica se viene utilizzata l'autenticazione. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Ottiene o imposta un valore che indica se la data deve essere utilizzata nel nome del file di registro. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Ottiene o imposta un valore booleano che controlla se le DefaultCredentials vengono inviate con le richieste. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Ottiene o imposta un valore che indica se il client deve utilizzare più connessioni per operazioni con carichi pesanti. Si prega di notare che l'utilizzo di questa modalità non necessario comporta un aumento delle prestazioni. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ottiene o imposta l'oggetto che indica se la modalità pipelining è abilitata. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Ottiene o imposta il nome utente. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Ottiene o imposta un valore booleano che controlla se i messaggi vengono inviati in formato TNEF. Nota che ora il messaggio viene inviato in formato TNEF quando viene caricato un messaggio contiene tnef. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crea una nuova connessione indipendente per le operazioni non collegate ai thread (non connessione predefinita). L'invocazione di questo metodo è simile all'invocazione di CreateConnection(createAsDefaultConnection = false) Si prega di vedere di più nella documentazione per la proprietà EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crea una nuova connessione (predefinita o indipendente) per le operazioni. Ulteriori informazioni nella documentazione per la proprietà EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalizza tutte le operazioni con un server. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Inoltra il messaggio specificato al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Inoltra il messaggio specificato al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Inoltra il messaggio specificato al destinatario |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | Comando 'Nessuna operazione' |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | Comando 'Nessuna operazione' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Ripristina le impostazioni di registrazione predefinite. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Invia i messaggi specificati. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Invia il messaggio specificato. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Invia la raccolta di messaggi specificata. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Invia il messaggio specificato. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Invia i messaggi specificati. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Invia il messaggio specificato. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Invia la raccolta di messaggi specificata. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Invia il messaggio specificato. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Crea e invia il messaggio specificato. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Crea e invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Invia i messaggi specificati. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Invia la raccolta di messaggi specificata. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Invia i messaggi specificati. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Invia la raccolta di messaggi specificata. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Invia i messaggi specificati. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Invia la raccolta di messaggi specificata. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Invia i messaggi specificati. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Invia la raccolta di messaggi specificata. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Crea e invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Crea e invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Crea e invia il messaggio specificato. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Crea e invia il messaggio specificato. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Aggiungi messaggi alla coda |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definisce le versioni dei protocolli di crittografia SSL/TLS da utilizzare. Questo metodo non è sicuro e imposta i protocolli di crittografia senza alcun controllo di compatibilità. Utilizzare[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) per impostare in modo sicuro solo i protocolli sicuramente supportati da .net framework. Nota, se il tuo attuale framework .net non supporta questo livello di sicurezza, verrà generata un'eccezione quando si tenta di stabilire una connessione al server. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Esegue la convalida delle credenziali |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Esegue la convalida delle credenziali |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crea una nuova istanza di[`SmtpClient`](../smtpclient) classe |

### Guarda anche

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
