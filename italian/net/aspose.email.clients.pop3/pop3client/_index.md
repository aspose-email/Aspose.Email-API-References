---
title: Pop3Client
second_title: Aspose.Email per riferimento all'API .NET
description: Consente alle applicazioni di accedere e manipolare i messaggi utilizzando Post Office Protocol versione 3 POP3.
type: docs
weight: 16880
url: /it/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Consente alle applicazioni di accedere e manipolare i messaggi utilizzando Post Office Protocol versione 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_1)(string) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_3)(string, int) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Inizializza una nuova istanza di[`Pop3Client`](../pop3client) classe |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Ottiene o imposta il token di accesso. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Ottiene o imposta l'enumerazione dei tipi di autenticazione consentiti dall'utente |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contiene la raccolta di certificati client |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Ottiene o imposta il valore che definisce la modalità di allocazione della connessione nell'ambiente a più thread Esistono i seguenti tipi di connessione: - La connessione principale è una connessione creata ed eliminata insieme al client di posta. Non può essere creata o eliminata manualmente. - La connessione predefinita è la connessione predefinita per alcuni thread. Se esiste una connessione predefinita e ConnectionAsgmtMode lo consente, tutti i metodi del client di posta elettronica eseguiti in questo thread utilizzeranno implicitamente questa connessione. Può esistere solo una connessione predefinita per thread. Può essere creato manualmente o automaticamente. Dipende dalla proprietà EmailClient.ConnectionAsgmtMode. Queste connessioni possono essere create manualmente con il metodo EmailClient.CreateConnection(createAsDefaultConnection = true). Se la connessione predefinita non viene utilizzata (dipende dalla modalità di allocazione della connessione), viene utilizzata implicitamente la connessione principale al suo posto. - Le connessioni indipendenti sono connessioni che sono non collegati a thread. Possono essere creati manualmente e devono essere utilizzati esplicitamente come parametro del metodo. Queste connessioni possono essere create manualmente con il metodo EmailClient.CreateConnection() o EmailClient.CreateConnection(createAsDefaultConnection = false). Sono disponibili i seguenti tipi di allocazione della connessione: - ConnectionAsgmtType.UseMainOrDefault Questa modalità viene utilizzata per impostazione predefinita nei client di posta elettronica. Il client di posta elettronica utilizza la connessione principale per tutte le operazioni da più thread se la connessione predefinita non è stata creata o la connessione non è stata passata esplicitamente come parametro del metodo. La connessione principale è una connessione creata contemporaneamente al client di posta elettronica. L'utente può creare connessioni predefinite per i thread con il metodo CreateConnection. Se viene creata la connessione predefinita per il thread, viene utilizzata implicitamente per tutti i metodi del client di posta elettronica richiamati in questo thread. Se la connessione predefinita per il thread non viene creata, viene utilizzata la connessione principale per tutti i metodi del client di posta elettronica richiamati in questo thread. L'utente può anche creare connessioni non collegate a thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. La connessione predefinita può essere solo una per thread. Notare che le connessioni predefinite funzionano correttamente se l'utente utilizza oggetti Thread per la programmazione multitasking. Se l'utente utilizza ConnectionPool o utilizza oggetti Task per la programmazione multitasking, questa modalità può portare a un comportamento errato di un programma. Per evitare questo problema l'utente deve eliminare manualmente la connessione predefinita (se la utilizza) alla fine del codice che viene eseguito in il thread. - ConnectionAsgmtType.UseMain Il client di posta elettronica utilizza la connessione principale per tutte le operazioni da più thread. La connessione principale è una connessione creata contemporaneamente al client di posta elettronica. L'utente non può creare connessioni predefinite. L'utente può creare connessioni non collegate a thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. - ConnectionAsgmtType.UseDefault Il client di posta elettronica utilizza implicitamente solo connessioni predefinite per tutte le operazioni da più thread. La connessione principale non viene utilizzata in questa modalità. Se la connessione predefinita non è stata creata per alcuni thread (prima chiamata del metodo del client di posta elettronica), il client di posta elettronica crea la connessione predefinita implicitamente per il thread prima dell'esecuzione della prima operazione. L'utente non può creare connessioni predefinite per i thread con il metodo CreateConnection perché vengono create automaticamente. Quando viene creata la connessione predefinita per il thread, viene utilizzata implicitamente per tutti i metodi del client di posta elettronica richiamati in questo thread.read. L'utente può anche creare connessioni non collegate ai thread (non connessioni predefinite) con il metodo CreateConnection. Se l'utente desidera utilizzare altre connessioni (non principali e non predefinite) deve passare questa connessione esplicitamente come parametro di un metodo che desidera utilizzare. L'utente può inoltre creare un numero qualsiasi di connessioni. La connessione predefinita può essere solo una per thread. Notare che le connessioni predefinite funzionano correttamente se l'utente utilizza oggetti Thread per la programmazione multitasking. Se l'utente utilizza ConnectionPool o utilizza oggetti Task per la programmazione multitasking, questa modalità potrebbe portare a un comportamento errato di un programma. Per evitare questo problema l'utente deve eliminare manualmente la connessione predefinita alla fine del codice che viene eseguito nel thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Periodo di verifica della connessione in millisecondi. Il valore predefinito è 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Ottiene o imposta la quantità di connessioni in modalità multiconnessione |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Ottiene lo stato corrente della connessione. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Ottiene la connessione corrente in base all'opzione ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Ottiene la porta predefinita per client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Ottiene o imposta un valore che consente di abilitare/disabilitare logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Ottiene o imposta il timeout di saluto utilizzato quando si stabilisce una connessione. Notare che il timeout di saluto non può essere infinito. I client di posta elettronica possono eseguire operazioni abbastanza lunghe. Per limitare il tempo delle operazioni gli utenti devono utilizzare[`Timeout`](../../aspose.email.clients/emailclient/timeout)proprietà. I valori per questa proprietà devono avere intervalli lunghi per non impedire operazioni di lunga durata. Ma in alcuni casi, se EmailClient utilizzerà solo la proprietà Timeout, la connessione potrebbe richiedere molto tempo. Ad esempio, il client di posta può utilizzare la modalità automatica per stabilire la connessione. In questa modalità, il client di posta elettronica esamina tutti i parametri di connessione possibili fino a quando la connessione non viene stabilita. Server SMTP, IMAP e POP3 in caso di connessione corretta che stabiliscono la stringa di saluto di invio al client. I server possono utilizzare l'avvio della connessione SSL/TLS implicito o esplicito (START TLS). Se la modalità di connessione non corrisponde (ad esempio, il server attende una connessione SSL implicita ma il client tenta di stabilire una connessione SSL non protetta o esplicita), il server non invierà una stringa di saluto. In questo caso, l'utente attenderà a lungo finché il timeout non raggiunge una stringa di saluto e il client passa all'opzione di connessione successiva. Per evitare questo problema, è stata introdotta la proprietà GreetingTimeout. Questa proprietà consente di impostare il timeout per la stringa di saluto, e di ridurre il tempo di creazione automatica della connessione. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ottiene o imposta il nome host. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Ottiene o imposta il nome del file di registro |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Ottiene o imposta la password. Le limitazioni della password sono definite dall'implementazione del server, a cui il client si connette. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Ottiene o imposta la porta. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Ottiene o imposta il proxy per il client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Modalità di sicurezza per un client di posta |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Ottiene l'enumerazione dei tipi di autenticazione del server supportati |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definisce le versioni dei protocolli di crittografia SSL/TLS da utilizzare. SI PREGA DI PRESTARE ATTENZIONE, è possibile impostare solo le versioni di protocollo che sono supportate da .net framework. SE ALCUNE VERSIONI DI PROTOCOLLO NON SONO SUPPORTATE DALLA VERSIONE ATTUALE DI .NET FRAMEWORK, SARANNO IGNORATI E SALTATI. POTREBBE PORTARE AL DOWNGRADE DEL LIVELLO DI SICUREZZA TLS. IN QUESTO CASO NON VERRÀ GENERATA ECCEZIONE!!! Per favore, guarda[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentazione per maggiori dettagli. Utilizzare[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) metodo se si desidera impostare i protocolli di crittografia senza alcun controllo di compatibilità. Il valore predefinito è: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (nel caso in cui la versione corrente di .net framework supporti queste versioni di TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Ottiene o imposta il timeout per le operazioni di posta |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Ottiene o imposta TokenProvider consentendo di recuperare il token di accesso. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indica se viene utilizzata l'autenticazione. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Ottiene o imposta un valore che indica se la data deve essere utilizzata nel nome del file di registro. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Ottiene o imposta un valore booleano che controlla se le DefaultCredentials vengono inviate con le richieste. Questa opzione viene utilizzata SOLO con l'autenticazione NTLM! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Ottiene o imposta un valore che indica se il client deve utilizzare più connessioni per operazioni con carichi pesanti. Si prega di notare che l'utilizzo di questa modalità non necessario comporta un aumento delle prestazioni. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ottiene o imposta l'oggetto che indica se la modalità pipelining è abilitata. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Ottiene o imposta il nome utente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Conferma le eliminazioni |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Conferma le eliminazioni |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Conferma le eliminazioni |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Conferma le eliminazioni |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crea una nuova connessione indipendente per le operazioni non collegate ai thread (non connessione predefinita). L'invocazione di questo metodo è simile all'invocazione di CreateConnection(createAsDefaultConnection = false) Si prega di vedere di più nella documentazione per la proprietà EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crea una nuova connessione (predefinita o indipendente) per le operazioni. Ulteriori informazioni nella documentazione per la proprietà EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Elimina il messaggio |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Elimina il messaggio |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Elimina il messaggio |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Elimina il messaggio |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Elimina tutti i messaggi |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Elimina tutti i messaggi |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Elimina tutti i messaggi |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Elimina tutti i messaggi |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Elimina tutti i messaggi |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Elimina tutti i messaggi |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalizza tutte le operazioni con un server. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Recupera il messaggio |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Recupera il messaggio |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Recupera il messaggio |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Recupera il messaggio |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Recupera i messaggi |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Recupera i messaggi |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Recupera i messaggi |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Recupera i messaggi |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Recupera i messaggi in modo asincrono |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Ottiene la dimensione della casella di posta |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Ottiene la dimensione della casella di posta |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Ottiene la dimensione della casella di posta |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Ottiene la dimensione della casella di posta |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Ottiene la dimensione della casella di posta |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Ottiene la dimensione della casella di posta |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Ottiene il conteggio dei messaggi |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Ottiene il conteggio dei messaggi |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Ottiene il conteggio dei messaggi |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Ottiene il conteggio dei messaggi |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Ottiene il conteggio dei messaggi |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Ottiene la dimensione del messaggio |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Ottiene la dimensione del messaggio |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Ottiene la dimensione del messaggio |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Ottiene l'id univoco del messaggio |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Ottiene l'id univoco del messaggio |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Ottiene l'id univoco del messaggio |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Ottiene l'id univoco del messaggio |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Ottiene l'id univoco del messaggio |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Ottiene l'id univoco del messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Elenca i messaggi. Ottiene un'informazione per ogni messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Elenca i messaggi. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Elenca i messaggi. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Carica l'elenco di Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Carica l'elenco di Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | Comando 'Nessuna operazione' |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | Comando 'Nessuna operazione' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | Comando 'Nessuna operazione' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Ripristina le impostazioni di registrazione predefinite. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Recupera e salva il messaggio in un file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Recupera e salva il messaggio in un file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Recupera e salva il messaggio in un file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Recupera e salva il messaggio in un file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Recupera e salva il messaggio come stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Recupera e salva il messaggio in un file |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definisce le versioni dei protocolli di crittografia SSL/TLS da utilizzare. Questo metodo non è sicuro e imposta i protocolli di crittografia senza alcun controllo di compatibilità. Utilizzare[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) per impostare in modo sicuro solo i protocolli sicuramente supportati da .net framework. Nota, se il tuo attuale framework .net non supporta questo livello di sicurezza, verrà generata un'eccezione quando si tenta di stabilire una connessione al server. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Esegue la convalida delle credenziali |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Esegue la convalida delle credenziali |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Esegue la convalida delle credenziali |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crea una nuova istanza di[`Pop3Client`](../pop3client) classe |

### Guarda anche

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
