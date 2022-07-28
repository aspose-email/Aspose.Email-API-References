---
title: SmtpClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Permet aux applications denvoyer des messages à laide du protocole SMTP Simple Mail Transfer Protocol.
type: docs
weight: 17030
url: /fr/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Permet aux applications d'envoyer des messages à l'aide du protocole SMTP (Simple Mail Transfer Protocol).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe en utilisant les paramètres du fichier de configuration. |
| [SmtpClient](smtpclient#constructor_2)(string) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Initialise une nouvelle instance du[`SmtpClient`](../smtpclient) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Obtient ou définit le jeton d'accès. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Obtient ou définit l'énumération des types d'authentification autorisés par l'utilisateur |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contient une collection de certificats clients |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Obtient ou définit la valeur qui définit le mode d'allocation de connexion dans plusieurs threads environment Il existe les types de connexion suivants : - La connexion principale est une connexion créée et supprimée avec le client de messagerie. Elle ne peut pas être créée ou supprimée manuellement. - La connexion par défaut est la connexion par défaut pour certains threads. Si la connexion par défaut existe et que ConnectionAsgmtMode le permet, toutes les méthodes du client de messagerie exécutées dans ce thread utiliseront implicitement cette connexion. Une seule connexion par défaut peut exister par thread. Il peut être créé manuellement ou automatiquement. Cela dépend de la propriété EmailClient.ConnectionAsgmtMode. Ces connexions peuvent être créées manuellement avec la méthode EmailClient.CreateConnection(createAsDefaultConnection = true). Si la connexion par défaut n'est pas utilisée (dépend du mode d'allocation de la connexion), la connexion principale est implicitement utilisée à sa place. - Les connexions indépendantes sont des connexions qui sont non liés aux threads. Ils peuvent être créés manuellement et doivent être utilisés explicitement comme paramètre de méthode. Ces connexions peuvent être créées manuellement avec la méthode EmailClient.CreateConnection() ou la méthode EmailClient.CreateConnection(createAsDefaultConnection = false). Il existe les types d'allocation de connexion suivants : - ConnectionAsgmtType.UseMainOrDefault Ce mode est utilisé par défaut dans les clients de messagerie. Le client de messagerie utilise la connexion principale pour toutes les opérations à partir de plusieurs threads si la connexion par défaut n'a pas été créée ou si la connexion n'a pas été explicitement transmise en tant que paramètre de méthode. La connexion principale est une connexion qui est créée en même temps que le client de messagerie. L'utilisateur peut créer des connexions par défaut pour les threads avec la méthode CreateConnection. Si la connexion par défaut pour le fil est créée, elle est utilisée implicitement pour toutes les méthodes du client de messagerie qui sont invoquées dans ce fil. Si la connexion par défaut pour le fil n'est pas créée, la connexion principale est utilisée pour toutes les méthodes du client de messagerie qui sont invoquées dans ce fil. thread. L'utilisateur peut également créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. La connexion par défaut ne peut être qu'une par thread. Veuillez noter que les connexions par défaut fonctionnent correctement si l'utilisateur utilise des objets Thread pour la programmation multitâche. Si l'utilisateur utilise ConnectionPool ou utilise des objets de tâche pour la programmation multitâche, ce mode peut entraîner un mauvais comportement d'un programme. Pour éviter ce problème, l'utilisateur doit supprimer manuellement la connexion par défaut (s'il l'utilise) à la fin du code qui s'exécute dans le thread. - ConnectionAsgmtType.UseMain Le client de messagerie utilise la connexion principale pour toutes les opérations à partir de plusieurs threads. La connexion principale est une connexion qui est créée en même temps que le client de messagerie. L'utilisateur ne peut pas créer de connexions par défaut. L'utilisateur peut créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. - ConnectionAsgmtType.UseDefault Le client de messagerie utilise implicitement uniquement les connexions par défaut pour toutes les opérations à partir de plusieurs threads. La connexion principale n'est pas utilisée dans ce mode. Si la connexion par défaut n'a pas été créée pour un thread (première invocation de la méthode du client de messagerie), le client de messagerie crée implicitement une connexion par défaut pour le thread avant l'exécution de la première opération. L'utilisateur ne peut pas créez des connexions par défaut pour les threads avec la méthode CreateConnection car elles sont créées automatiquement. Lorsque la connexion par défaut pour le thread est créée, elle est utilisée implicitement pour toutes les méthodes du client de messagerie qui sont invoquées dans ce thread.read. L'utilisateur peut également créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. La connexion par défaut ne peut être qu'une par thread. Veuillez noter que les connexions par défaut fonctionnent correctement si l'utilisateur utilise des objets Thread pour la programmation multitâche. Si l'utilisateur utilise ConnectionPool ou utilise des objets Task pour la programmation multitâche, ce mode peut entraîner un mauvais comportement d'un programme. Pour éviter ce problème, l'utilisateur doit supprimer manuellement la connexion par défaut à la fin du code qui s'exécute dans le thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Période de vérification de la connexion en millisecondes. La valeur par défaut est de 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Obtient ou définit la quantité de connexions en mode multi-connexion |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Obtient l'état actuel de la connexion. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Obtient la connexion actuelle selon l'option ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Obtient le port par défaut pour le client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Obtient ou définit la méthode de livraison. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Obtient ou définit la valeur qui permet d'activer/désactiver l'enregistreur |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Obtient ou définit le délai d'expiration du message d'accueil utilisé lors de l'établissement d'une connexion. Veuillez noter que le délai d'expiration du message d'accueil ne peut pas être infini. Les clients de messagerie peuvent exécuter des opérations suffisamment longues. Pour limiter le temps des opérations, les utilisateurs doivent utiliser[`Timeout`](../../aspose.email.clients/emailclient/timeout)propriété. Les valeurs de cette propriété doivent avoir de longs intervalles pour ne pas empêcher les opérations de longue durée. Mais dans certains cas, si EmailClient utilise uniquement la propriété Timeout, l'établissement de la connexion peut prendre beaucoup de temps. Par exemple, le client de messagerie peut utiliser le mode automatique pour établir la connexion. Dans ce mode, le client de messagerie parcourt tous les paramètres de connexion possibles jusqu'à ce que la connexion soit établie. Serveurs SMTP, IMAP et POP3 en cas de connexion correcte établissant envoyer la chaîne de salutation au client. Les serveurs peuvent utiliser une initiation de connexion SSL/TLS implicite ou explicite (START TLS). Si le mode de connexion ne correspond pas (par exemple, le serveur attend une connexion SSL implicite mais le client essaie d'établir une connexion SSL non sécurisée ou explicite), le serveur n'enverra pas de chaîne de salutation. Dans ce cas, l'utilisateur attendra longtemps jusqu'à ce que le délai d'attente atteigne une chaîne de salutation et le client passe à l'option de connexion suivante. Pour éviter ce problème, la propriété GreetingTimeout a été introduite. Cette propriété vous permet de définir le délai d'attente pour la chaîne de salutation, et de réduire le temps d'établissement de connexion automatique. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Obtient ou définit une chaîne HELO/EHLO. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Obtient ou définit le nom d'hôte. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Obtient ou définit le nom du fichier journal |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Obtient ou définit le mot de passe. Les limitations de mot de passe sont définies par l'implémentation du serveur, auquel le client se connecte. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Obtient ou définit le répertoire dans lequel les applications enregistrent les messages électroniques à traiter par le serveur SMTP local. Veuillez noter : seul le chemin absolu est autorisé. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Obtient ou définit le port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Obtient ou définit le proxy pour le client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Mode de sécurité pour un client de messagerie |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Obtient ou définit le répertoire dans lequel les applications enregistrent les messages électroniques à traiter en les envoyant dans la file d'attente SMTP. Veuillez noter : seul le chemin absolu est autorisé. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Obtient l'énumération des types d'authentification pris en charge par le serveur |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Définit les versions des protocoles de cryptage SSL/TLS à utiliser. VEUILLEZ FAIRE ATTENTION, vous ne pouvez définir que les versions de protocole prises en charge par .net framework. SI CERTAINES VERSIONS DU PROTOCOLE NE SONT PAS PRIS EN CHARGE PAR VOTRE VERSION ACTUELLE DE .NET FRAMEWORK, ILS SERONT IGNORÉS ET Ignorés. IL PEUT ENTRAÎNER UNE RÉTROGRADATION DU NIVEAU DE SÉCURITÉ TLS. DANS CE CAS, L'EXCEPTION NE SERA PAS GÉNÉRÉE !!! Veuillez consulter[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentation pour plus de détails. Veuillez utiliser[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) si vous souhaitez définir les protocoles de chiffrement sans aucune vérification de compatibilité. La valeur par défaut est : Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (au cas où votre version actuelle de .net framework prend en charge ces versions de TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Obtient ou définit le délai d'expiration des opérations de messagerie |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Obtient ou définit TokenProvider permettant de récupérer le jeton d'accès. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indique si l'authentification est utilisée. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Obtient ou définit la valeur qui indique si la date doit être utilisée dans le nom du fichier journal. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Obtient ou définit une valeur booléenne qui contrôle si les DefaultCredentials sont envoyés avec les demandes. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Obtient ou définit la valeur qui indique si le client doit utiliser plusieurs connexions pour les opérations lourdes. Veuillez noter que l'utilisation de ce mode n'est pas nécessaire pour augmenter les performances. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Obtient ou définit l'objet qui indique si le mode pipelining est activé. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Obtient ou définit le nom d'utilisateur. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Obtient ou définit une valeur booléenne qui contrôle si les messages sont envoyés au format TNEF. Notez que maintenant le message est envoyé au format TNEF lors du chargement d'un message contient tnef. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crée une nouvelle connexion indépendante pour les opérations non liées aux threads (pas de connexion par défaut). L'appel de cette méthode est similaire à l'appel de CreateConnection(createAsDefaultConnection = false) Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crée une nouvelle connexion (par défaut ou indépendante) pour les opérations. Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalise toutes les opérations avec un serveur. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Transfère le message spécifié au destinataire |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Transfère le message spécifié au destinataire |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Transfère le message spécifié au destinataire |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Transfère le message spécifié au destinataire |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Transfère le message spécifié au destinataire |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Transfère le message spécifié au destinataire |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Transfère le message spécifié au destinataire |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | Commande 'Aucune opération' |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | Commande 'Aucune opération' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Réinitialise les paramètres de journalisation par défaut. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Envoyer les messages spécifiés. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Envoyer le message spécifié. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Envoyer la collection de messages spécifiée. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Envoyer le message spécifié. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Envoyer les messages spécifiés. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Envoyer le message spécifié. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Envoyer la collection de messages spécifiée. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Envoyer le message spécifié. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Crée et envoie le message spécifié. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Crée et envoie le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Envoyer les messages spécifiés. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Envoyer la collection de messages spécifiée. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Envoyer les messages spécifiés. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Envoyer la collection de messages spécifiée. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Envoyer les messages spécifiés. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Envoyer la collection de messages spécifiée. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Envoyer les messages spécifiés. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Envoyer le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Envoyer la collection de messages spécifiée. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Crée et envoie le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Crée et envoie le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Crée et envoie le message spécifié. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Crée et envoie le message spécifié. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Ajouter des messages à la file d'attente |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Définit les versions des protocoles de chiffrement SSL/TLS à utiliser. Cette méthode n'est pas sûre et définit les protocoles de chiffrement sans aucune vérification de compatibilité. Utilisation[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) pour définir en toute sécurité uniquement les protocoles définitivement pris en charge par .net framework. Veuillez noter que si votre framework .net actuel ne prend pas en charge ce niveau de sécurité, une exception sera levée lors de la tentative d'établissement d'une connexion au serveur. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Exécute la validation des identifiants |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Exécute la validation des identifiants |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crée une nouvelle instance du[`SmtpClient`](../smtpclient) classe |

### Voir également

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* espace de noms [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
