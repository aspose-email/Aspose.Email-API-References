---
title: Pop3Client
second_title: Aspose.Email für .NET-API-Referenz
description: Ermöglicht Anwendungen den Zugriff auf und die Bearbeitung von -Nachrichten mithilfe von Post Office Protocol Version 3 POP3.
type: docs
weight: 16880
url: /de/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Ermöglicht Anwendungen den Zugriff auf und die Bearbeitung von -Nachrichten mithilfe von Post Office Protocol Version 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_1)(string) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_3)(string, int) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initialisiert eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Ruft das Zugriffstoken ab oder legt es fest. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Ruft die Aufzählung der vom Benutzer zugelassenen Authentifizierungstypen ab oder legt sie fest |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Enthält eine Sammlung von Client-Zertifikaten |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Ruft den Wert ab oder legt ihn fest, der den Modus der Verbindungszuweisung in der Umgebung mit mehreren Threads definiert Es gibt folgende Verbindungstypen: - Die Hauptverbindung ist eine Verbindung, die zusammen mit dem E-Mail-Client erstellt und verworfen wird. Sie kann nicht manuell erstellt oder verworfen werden. - Standardverbindung ist Standardverbindung für einige Threads. Wenn eine Standardverbindung existiert und ConnectionAsgmtMode erlaubt, werden alle Methoden des E-Mail-Clients, die in diesem Thread ausgeführt werden, implizit diese Verbindung verwenden. Pro Thread kann nur eine Standardverbindung existieren. Es kann manuell oder automatisch erstellt werden. Dies hängt von der Eigenschaft EmailClient.ConnectionAsgmtMode ab. Diese Verbindungen können manuell mit der Methode EmailClient.CreateConnection(createAsDefaultConnection = true) erstellt werden. Wenn die Standardverbindung nicht verwendet wird (abhängig vom Verbindungszuweisungsmodus), wird stattdessen implizit die Hauptverbindung verwendet. - Unabhängige Verbindungen sind Verbindungen, die vorhanden sind nicht mit Threads verknüpft. Sie können manuell erstellt werden und müssen explizit als Methodenparameter verwendet werden. Diese Verbindungen können manuell mit der EmailClient.CreateConnection()-Methode oder der EmailClient.CreateConnection(createAsDefaultConnection = false)-Methode erstellt werden. Es gibt folgende Verbindungszuweisungstypen: - ConnectionAsgmtType.UseMainOrDefault Dieser Modus wird standardmäßig in E-Mail-Clients verwendet. Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads, wenn keine Standardverbindung erstellt wurde oder die Verbindung nicht explizit als Methodenparameter übergeben wurde. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann Standardverbindungen für Threads mit der CreateConnection-Methode erstellen. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden. Wenn die Standardverbindung für Thread nicht erstellt wird, wird die Hauptverbindung für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden thread. Der Benutzer kann mit der CreateConnection-Methode auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung (falls er sie verwendet) am Ende des Codes, der ausgeführt wird, manuell entfernen the thread. - ConnectionAsgmtType.UseMain Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann keine Standardverbindungen erstellen. Der Benutzer kann mit der CreateConnection-Methode Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. - ConnectionAsgmtType.UseDefault Der E-Mail-Client verwendet implizit nur Standardverbindungen für alle Vorgänge aus mehreren Threads. Die Hauptverbindung wird in diesem Modus nicht verwendet. Wenn für einen Thread keine Standardverbindung erstellt wurde (erster Aufruf der E-Mail-Client-Methode), erstellt der E-Mail-Client implizit eine Standardverbindung für den Thread, bevor die erste Operation ausgeführt wird. Der Benutzer kann dies nicht Erstellen Sie Standardverbindungen für Threads mit der CreateConnection-Methode, da sie automatisch erstellt werden. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden.read. Der Benutzer kann auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen) mit der CreateConnection-Methode. Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung manuell am Ende des Codes entfernen, der im Thread ausgeführt wird. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Zeitraum der Verbindungsprüfung in Millisekunden. Standardwert ist 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Ruft die Anzahl der Verbindungen im Mehrfachverbindungsmodus ab oder legt sie fest |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Ruft den aktuellen Zustand der Verbindung ab. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Ruft aktuelle Verbindung gemäß Option ConnectionAsgmtMode ab |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Ruft den Standardport für client ab |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Ruft oder setzt einen Wert, der das Aktivieren/Deaktivieren von Logger ermöglicht |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Ermittelt oder setzt das Begrüßungs-Timeout, das beim Verbindungsaufbau verwendet wird. Bitte beachten Sie, dass das Begrüßungs-Timeout nicht unendlich sein kann. E-Mail-Clients können lange genug Operationen ausführen. Um die Betriebszeit zu begrenzen, müssen Benutzer verwenden[`Timeout`](../../aspose.email.clients/emailclient/timeout)Eigentum. Werte für diese Eigenschaft müssen lange Intervalle haben, um lange Operationen nicht zu verhindern. Aber in einigen Fällen, wenn EmailClient nur Timeout-Eigenschaften verwendet, kann der Verbindungsaufbau sehr lange dauern. Beispielsweise kann der Mail-Client den automatischen Modus zum Verbindungsaufbau verwenden. In diesem Modus durchläuft der E-Mail-Client alle möglichen Verbindungsparameter, bis die Verbindung aufgebaut ist. SMTP-, IMAP- und POP3-Server senden im Falle eines korrekten Verbindungsaufbaus eine Begrüßungszeichenfolge an den Client. Server können die implizite oder explizite (START TLS) SSL/TLS-Verbindungsinitiierung verwenden. Wenn der Verbindungsmodus nicht übereinstimmt (z. B. wenn der Server auf eine implizite SSL-Verbindung wartet, aber der Client versucht, eine nicht gesicherte oder explizite SSL-Verbindung aufzubauen), sendet der Server keine Begrüßungszeichenfolge. In diesem Fall wartet der Benutzer lange, bis der Timeout eine Begrüßungszeichenfolge erreicht, und der Client wechselt zur nächsten Verbindungsoption. Um dieses Problem zu vermeiden, wurde die Eigenschaft GreetingTimeout eingeführt. Mit dieser Eigenschaft können Sie das Timeout für die Begrüßungszeichenfolge festlegen und die Zeit für den automatischen Verbindungsaufbau verkürzen. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ruft den Hostnamen ab oder legt ihn fest. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Ruft den Protokolldateinamen ab oder legt ihn fest |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Ruft das Passwort ab oder legt es fest. Passwortbeschränkungen werden durch die Serverimplementierung definiert, mit der sich der Client verbindet. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Ruft den Port ab oder legt ihn fest. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Ruft den Proxy für den Client ab oder legt ihn fest |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Sicherheitsmodus für einen Mailclient |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Ruft die Aufzählung der vom Server unterstützten Authentifizierungstypen ab |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definiert die Versionen der zu verwendenden SSL/TLS-Verschlüsselungsprotokolle. BITTE BEACHTEN SIE, dass Sie nur die Protokollversionen einstellen können, die von .net framework unterstützt werden. WENN EINIGE PROTOKOLLVERSIONEN VON IHRER AKTUELLEN VERSION NICHT UNTERSTÜTZT WERDEN VON .NET FRAMEWORK WERDEN SIE IGNORIERT UND ÜBERSPRINGT. ES KANN ZU EINEM DOWNGRADE DER TLS-SICHERHEITSSTUFE FÜHREN. IN DIESEM FALL WIRD KEINE AUSNAHME ERZEUGT!!! Bitte sehen[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) Dokumentation für weitere Details. Bitte verwenden[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) -Methode, wenn Sie die Verschlüsselungsprotokolle ohne Kompatibilitätsprüfungen festlegen möchten. Der Standardwert ist: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (falls Ihre aktuelle Version von .net Framework diese Versionen von TLS unterstützt) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Ruft das Timeout für E-Mail-Operationen ab oder setzt es |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Ruft den TokenProvider ab oder legt ihn fest, um Zugriffstoken abzurufen. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Gibt an, ob Authentifizierung verwendet wird. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob das Datum im Namen der Protokolldatei verwendet werden muss. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der steuert, ob die DefaultCredentials mit Anfragen gesendet werden. Diese Option wird NUR mit NTLM-Authentifizierung verwendet! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Client mehrere Verbindungen für stark belastete Operationen verwenden muss. Bitte beachten Sie, dass die Verwendung dieses Modus nicht notwendigerweise zu einer Leistungssteigerung führen muss. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ruft ein Objekt ab oder legt es fest, das angibt, ob der Pipelining-Modus aktiviert ist. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Ruft den Benutzernamen ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Übernehmen Sie die Löschungen |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Übernehmen Sie die Löschungen |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Übernehmen Sie die Löschungen |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Übernehmen Sie die Löschungen |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Erstellt eine neue unabhängige Verbindung für Vorgänge, die nicht mit Threads verknüpft sind (keine Standardverbindung). Der Aufruf dieser Methode ähnelt dem Aufruf von CreateConnection (createAsDefaultConnection = false) Weitere Informationen finden Sie in der Dokumentation zur Eigenschaft EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Erstellt eine neue (Standard- oder unabhängige) Verbindung für Vorgänge. Weitere Informationen finden Sie in der Dokumentation zur Eigenschaft EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Löscht die Nachricht |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Löscht die Nachricht |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Löscht die Nachricht |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Löscht die Nachricht |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Löscht die Nachricht |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Löscht alle Nachrichten |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Löscht alle Nachrichten |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Löscht alle Nachrichten |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Löscht alle Nachrichten |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Löscht alle Nachrichten |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Löscht alle Nachrichten |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Schließt alle Operationen mit einem Server ab. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Ruft die Nachricht ab |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Ruft die Nachricht ab |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Ruft die Nachricht ab |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Ruft die Nachricht ab |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Ruft die Nachricht ab |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Ruft die Nachrichten ab |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Ruft die Nachrichten ab |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Ruft die Nachrichten ab |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Ruft die Nachrichten ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Ruft die Nachrichten asynchron ab |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Ruft die Nachrichten asynchron ab |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Ruft den Postfachstatus ab info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Ruft den Postfachstatus ab info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Ruft den Postfachstatus ab info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Ruft den Postfachstatus ab info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Ruft den Postfachstatus ab info |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Ruft die Größe des Postfachs ab |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Ruft die Größe des Postfachs ab |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Ruft die Größe des Postfachs ab |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Ruft die Größe des Postfachs ab |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Ruft die Größe des Postfachs ab |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Ruft die Größe des Postfachs ab |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Ruft die Nachrichtenanzahl ab |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Ruft die Nachrichtenanzahl ab |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Ruft die Nachrichtenanzahl ab |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Ruft die Nachrichtenkopfzeilen ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Ruft die Informationen für diese Nachricht ab |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Ruft die Größe der Nachricht ab |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Ruft die Größe der Nachricht ab |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Ruft die Größe der Nachricht ab |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Ruft die Größe der Nachricht ab |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Ruft die Größe der Nachricht ab |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Ruft die eindeutige Nachricht id ab |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Ruft die eindeutige Nachricht id ab |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Ruft die eindeutige Nachricht id ab |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Ruft die eindeutige Nachricht id ab |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Ruft die eindeutige Nachricht id ab |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Ruft die eindeutige Nachricht id ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Listet die Nachrichten auf. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Listet die Nachrichten auf. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Listet die Nachrichten auf. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Lädt Liste von Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Lädt Liste von Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | Befehl „Keine Operation“ |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | Befehl „Keine Operation“ |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Setzt die Protokollierungseinstellungen auf die Standardeinstellungen zurück. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Ruft die Nachricht ab und speichert sie als Stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Ruft die Nachricht ab und speichert sie in einer Datei |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definiert die Versionen der zu verwendenden SSL/TLS-Verschlüsselungsprotokolle. Diese Methode ist nicht sicher und stellt die Verschlüsselungsprotokolle ohne Kompatibilitätsprüfungen ein. Verwenden[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) -Eigenschaft, um nur Protokolle sicher festzulegen, die definitiv vom .net-Framework unterstützt werden. Bitte beachten Sie, dass, wenn Ihr aktuelles .net-Framework diese Sicherheitsstufe nicht unterstützt, eine Ausnahme ausgelöst wird, wenn versucht wird, eine Verbindung zum Server herzustellen. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Stellt die Nachrichten wieder her. Wenn Nachrichten vom POP3-Server als gelöscht markiert wurden, werden sie nicht markiert. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Führt die Validierung der Anmeldeinformationen aus |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Erstellt eine neue Instanz von[`Pop3Client`](../pop3client) Klasse |

### Siehe auch

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
