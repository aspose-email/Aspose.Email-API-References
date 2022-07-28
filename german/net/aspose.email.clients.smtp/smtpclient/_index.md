---
title: SmtpClient
second_title: Aspose.Email für .NET-API-Referenz
description: Ermöglicht Anwendungen das Senden von Nachrichten über das Simple Mail Transfer Protocol SMTP.
type: docs
weight: 17030
url: /de/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Ermöglicht Anwendungen das Senden von Nachrichten über das Simple Mail Transfer Protocol (SMTP).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse mithilfe der Konfigurationsdatei settings. |
| [SmtpClient](smtpclient#constructor_2)(string) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Initialisiert eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Ruft das Zugriffstoken ab oder legt es fest. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Ruft die Aufzählung der vom Benutzer zugelassenen Authentifizierungstypen ab oder legt sie fest |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Enthält eine Sammlung von Client-Zertifikaten |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Ruft den Wert ab oder legt ihn fest, der den Modus der Verbindungszuweisung in der Umgebung mit mehreren Threads definiert Es gibt folgende Verbindungstypen: - Die Hauptverbindung ist eine Verbindung, die zusammen mit dem E-Mail-Client erstellt und verworfen wird. Sie kann nicht manuell erstellt oder verworfen werden. - Standardverbindung ist Standardverbindung für einige Threads. Wenn eine Standardverbindung existiert und ConnectionAsgmtMode erlaubt, werden alle Methoden des E-Mail-Clients, die in diesem Thread ausgeführt werden, implizit diese Verbindung verwenden. Pro Thread kann nur eine Standardverbindung existieren. Es kann manuell oder automatisch erstellt werden. Dies hängt von der Eigenschaft EmailClient.ConnectionAsgmtMode ab. Diese Verbindungen können manuell mit der Methode EmailClient.CreateConnection(createAsDefaultConnection = true) erstellt werden. Wenn die Standardverbindung nicht verwendet wird (abhängig vom Verbindungszuweisungsmodus), wird stattdessen implizit die Hauptverbindung verwendet. - Unabhängige Verbindungen sind Verbindungen, die vorhanden sind nicht mit Threads verknüpft. Sie können manuell erstellt werden und müssen explizit als Methodenparameter verwendet werden. Diese Verbindungen können manuell mit der EmailClient.CreateConnection()-Methode oder der EmailClient.CreateConnection(createAsDefaultConnection = false)-Methode erstellt werden. Es gibt folgende Verbindungszuweisungstypen: - ConnectionAsgmtType.UseMainOrDefault Dieser Modus wird standardmäßig in E-Mail-Clients verwendet. Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads, wenn keine Standardverbindung erstellt wurde oder die Verbindung nicht explizit als Methodenparameter übergeben wurde. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann Standardverbindungen für Threads mit der CreateConnection-Methode erstellen. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden. Wenn die Standardverbindung für Thread nicht erstellt wird, wird die Hauptverbindung für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden thread. Der Benutzer kann mit der CreateConnection-Methode auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung (falls er sie verwendet) am Ende des Codes, der ausgeführt wird, manuell entfernen the thread. - ConnectionAsgmtType.UseMain Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann keine Standardverbindungen erstellen. Der Benutzer kann mit der CreateConnection-Methode Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. - ConnectionAsgmtType.UseDefault Der E-Mail-Client verwendet implizit nur Standardverbindungen für alle Vorgänge aus mehreren Threads. Die Hauptverbindung wird in diesem Modus nicht verwendet. Wenn für einen Thread keine Standardverbindung erstellt wurde (erster Aufruf der E-Mail-Client-Methode), erstellt der E-Mail-Client implizit eine Standardverbindung für den Thread, bevor die erste Operation ausgeführt wird. Der Benutzer kann dies nicht Erstellen Sie Standardverbindungen für Threads mit der CreateConnection-Methode, da sie automatisch erstellt werden. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden.read. Der Benutzer kann auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen) mit der CreateConnection-Methode. Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung manuell am Ende des Codes entfernen, der im Thread ausgeführt wird. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Zeitraum der Verbindungsprüfung in Millisekunden. Standardwert ist 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Ruft die Anzahl der Verbindungen im Mehrfachverbindungsmodus ab oder legt sie fest |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Ruft den aktuellen Zustand der Verbindung ab. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Ruft aktuelle Verbindung gemäß Option ConnectionAsgmtMode ab |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Ruft den Standardport für client ab |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Ruft die Übermittlungsmethode ab oder legt sie fest. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Ruft oder setzt einen Wert, der das Aktivieren/Deaktivieren von Logger ermöglicht |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Ermittelt oder setzt das Begrüßungs-Timeout, das beim Verbindungsaufbau verwendet wird. Bitte beachten Sie, dass das Begrüßungs-Timeout nicht unendlich sein kann. E-Mail-Clients können lange genug Operationen ausführen. Um die Betriebszeit zu begrenzen, müssen Benutzer verwenden[`Timeout`](../../aspose.email.clients/emailclient/timeout)Eigentum. Werte für diese Eigenschaft müssen lange Intervalle haben, um lange Operationen nicht zu verhindern. Aber in einigen Fällen, wenn EmailClient nur Timeout-Eigenschaften verwendet, kann der Verbindungsaufbau sehr lange dauern. Beispielsweise kann der Mail-Client den automatischen Modus zum Verbindungsaufbau verwenden. In diesem Modus durchläuft der E-Mail-Client alle möglichen Verbindungsparameter, bis die Verbindung aufgebaut ist. SMTP-, IMAP- und POP3-Server senden im Falle eines korrekten Verbindungsaufbaus eine Begrüßungszeichenfolge an den Client. Server können die implizite oder explizite (START TLS) SSL/TLS-Verbindungsinitiierung verwenden. Wenn der Verbindungsmodus nicht übereinstimmt (z. B. wenn der Server auf eine implizite SSL-Verbindung wartet, aber der Client versucht, eine nicht gesicherte oder explizite SSL-Verbindung aufzubauen), sendet der Server keine Begrüßungszeichenfolge. In diesem Fall wartet der Benutzer lange, bis der Timeout eine Begrüßungszeichenfolge erreicht, und der Client wechselt zur nächsten Verbindungsoption. Um dieses Problem zu vermeiden, wurde die Eigenschaft GreetingTimeout eingeführt. Mit dieser Eigenschaft können Sie das Timeout für die Begrüßungszeichenfolge festlegen und die Zeit für den automatischen Verbindungsaufbau verkürzen. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Ruft eine HELO/EHLO-Zeichenfolge ab oder legt sie fest. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ruft den Hostnamen ab oder legt ihn fest. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Ruft den Protokolldateinamen ab oder legt ihn fest |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Ruft das Passwort ab oder legt es fest. Passwortbeschränkungen werden durch die Serverimplementierung definiert, mit der sich der Client verbindet. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Ruft das Verzeichnis ab oder legt es fest, in dem Anwendungen E-Mail-Nachrichten speichern, die vom lokalen SMTP-Server verarbeitet werden sollen. Bitte beachten: Nur absolute Pfade sind zulässig. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Ruft den Port ab oder legt ihn fest. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Ruft den Proxy für den Client ab oder legt ihn fest |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Sicherheitsmodus für einen Mailclient |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Ruft das Verzeichnis ab oder legt es fest, in dem Anwendungen E-Mail-Nachrichten speichern, die durch Senden in der SMTP-Warteschlange verarbeitet werden sollen. Bitte beachten: Nur absolute Pfade sind zulässig. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Ruft die Aufzählung der vom Server unterstützten Authentifizierungstypen ab |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Definiert die Versionen der zu verwendenden SSL/TLS-Verschlüsselungsprotokolle. BITTE BEACHTEN SIE, dass Sie nur die Protokollversionen einstellen können, die von .net framework unterstützt werden. WENN EINIGE PROTOKOLLVERSIONEN VON IHRER AKTUELLEN VERSION NICHT UNTERSTÜTZT WERDEN VON .NET FRAMEWORK WERDEN SIE IGNORIERT UND ÜBERSPRINGT. ES KANN ZU EINEM DOWNGRADE DER TLS-SICHERHEITSSTUFE FÜHREN. IN DIESEM FALL WIRD KEINE AUSNAHME ERZEUGT!!! Bitte sehen[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) Dokumentation für weitere Details. Bitte verwenden[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) -Methode, wenn Sie die Verschlüsselungsprotokolle ohne Kompatibilitätsprüfungen festlegen möchten. Der Standardwert ist: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (falls Ihre aktuelle Version von .net Framework diese Versionen von TLS unterstützt) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Ruft das Timeout für E-Mail-Operationen ab oder setzt es |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Ruft den TokenProvider ab oder legt ihn fest, um Zugriffstoken abzurufen. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Gibt an, ob Authentifizierung verwendet wird. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob das Datum im Namen der Protokolldatei verwendet werden muss. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der steuert, ob die DefaultCredentials mit Anforderungen gesendet werden. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Client mehrere Verbindungen für stark belastete Operationen verwenden muss. Bitte beachten Sie, dass die Verwendung dieses Modus nicht notwendigerweise zu einer Leistungssteigerung führen muss. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ruft ein Objekt ab oder legt es fest, das angibt, ob der Pipelining-Modus aktiviert ist. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Ruft den Benutzernamen ab oder legt ihn fest. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Erhält oder setzt einen booleschen Wert, der steuert, ob die Nachrichten im TNEF-Format gesendet werden. Beachten Sie, dass die Nachricht jetzt im TNEF-Format gesendet wird, wenn eine Nachricht geladen wird, die tnef enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Erstellt eine neue unabhängige Verbindung für Vorgänge, die nicht mit Threads verknüpft sind (keine Standardverbindung). Der Aufruf dieser Methode ähnelt dem Aufruf von CreateConnection (createAsDefaultConnection = false) Weitere Informationen finden Sie in der Dokumentation zur Eigenschaft EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Erstellt eine neue (Standard- oder unabhängige) Verbindung für Vorgänge. Weitere Informationen finden Sie in der Dokumentation zur Eigenschaft EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Schließt alle Operationen mit einem Server ab. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Leitet die angegebene Nachricht an Empfänger weiter |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Leitet die angegebene Nachricht an Empfänger weiter |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Leitet die angegebene Nachricht an Empfänger weiter |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | Befehl „Keine Operation“ |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | Befehl „Keine Operation“ |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | Befehl „Keine Operation“ |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Setzt die Protokollierungseinstellungen auf die Standardeinstellungen zurück. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Senden Sie die angegebenen Nachrichten. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Senden Sie die angegebene Nachricht. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Sendet die angegebene Nachrichtensammlung. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Senden Sie die angegebenen Nachrichten. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Senden Sie die angegebene Nachricht. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Sendet die angegebene Nachrichtensammlung. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Erstellt und sendet die angegebene Nachricht. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Erstellt und sendet die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Senden Sie die angegebenen Nachrichten. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Sendet die angegebene Nachrichtensammlung. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Senden Sie die angegebenen Nachrichten. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Sendet die angegebene Nachrichtensammlung. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Senden Sie die angegebenen Nachrichten. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Sendet die angegebene Nachrichtensammlung. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Senden Sie die angegebenen Nachrichten. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Senden Sie die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Sendet die angegebene Nachrichtensammlung. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Erstellt und sendet die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Erstellt und sendet die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Erstellt und sendet die angegebene Nachricht. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Erstellt und sendet die angegebene Nachricht. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Nachrichten an Warteschlange anhängen |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Definiert die Versionen der zu verwendenden SSL/TLS-Verschlüsselungsprotokolle. Diese Methode ist nicht sicher und stellt die Verschlüsselungsprotokolle ohne Kompatibilitätsprüfungen ein. Verwenden[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) -Eigenschaft, um nur Protokolle sicher festzulegen, die definitiv vom .net-Framework unterstützt werden. Bitte beachten Sie, dass, wenn Ihr aktuelles .net-Framework diese Sicherheitsstufe nicht unterstützt, eine Ausnahme ausgelöst wird, wenn versucht wird, eine Verbindung zum Server herzustellen. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Führt die Validierung der Anmeldeinformationen aus |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Führt die Validierung der Anmeldeinformationen aus |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Erstellt eine neue Instanz von[`SmtpClient`](../smtpclient) Klasse |

### Siehe auch

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* namensraum [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
