---
title: Pop3Client
second_title: Référence de l'API Aspose.Email pour .NET
description: Permet aux applications daccéder aux messages et de les manipuler à laide de Post Office Protocol Version 3 POP3.
type: docs
weight: 16880
url: /fr/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Permet aux applications d'accéder aux messages et de les manipuler à l'aide de Post Office Protocol Version 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_1)(string) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_3)(string, int) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initialise une nouvelle instance du[`Pop3Client`](../pop3client) classe |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Obtient ou définit le jeton d'accès. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Obtient ou définit l'énumération des types d'authentification autorisés par l'utilisateur |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contient une collection de certificats clients |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Obtient ou définit la valeur qui définit le mode d'allocation de connexion dans plusieurs threads environment Il existe les types de connexion suivants : - La connexion principale est une connexion créée et supprimée avec le client de messagerie. Elle ne peut pas être créée ou supprimée manuellement. - La connexion par défaut est la connexion par défaut pour certains threads. Si la connexion par défaut existe et que ConnectionAsgmtMode le permet, toutes les méthodes du client de messagerie exécutées dans ce thread utiliseront implicitement cette connexion. Une seule connexion par défaut peut exister par thread. Il peut être créé manuellement ou automatiquement. Cela dépend de la propriété EmailClient.ConnectionAsgmtMode. Ces connexions peuvent être créées manuellement avec la méthode EmailClient.CreateConnection(createAsDefaultConnection = true). Si la connexion par défaut n'est pas utilisée (dépend du mode d'allocation de la connexion), la connexion principale est implicitement utilisée à sa place. - Les connexions indépendantes sont des connexions qui sont non liés aux threads. Ils peuvent être créés manuellement et doivent être utilisés explicitement comme paramètre de méthode. Ces connexions peuvent être créées manuellement avec la méthode EmailClient.CreateConnection() ou la méthode EmailClient.CreateConnection(createAsDefaultConnection = false). Il existe les types d'allocation de connexion suivants : - ConnectionAsgmtType.UseMainOrDefault Ce mode est utilisé par défaut dans les clients de messagerie. Le client de messagerie utilise la connexion principale pour toutes les opérations à partir de plusieurs threads si la connexion par défaut n'a pas été créée ou si la connexion n'a pas été explicitement transmise en tant que paramètre de méthode. La connexion principale est une connexion qui est créée en même temps que le client de messagerie. L'utilisateur peut créer des connexions par défaut pour les threads avec la méthode CreateConnection. Si la connexion par défaut pour le fil est créée, elle est utilisée implicitement pour toutes les méthodes du client de messagerie qui sont invoquées dans ce fil. Si la connexion par défaut pour le fil n'est pas créée, la connexion principale est utilisée pour toutes les méthodes du client de messagerie qui sont invoquées dans ce fil. thread. L'utilisateur peut également créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. La connexion par défaut ne peut être qu'une par thread. Veuillez noter que les connexions par défaut fonctionnent correctement si l'utilisateur utilise des objets Thread pour la programmation multitâche. Si l'utilisateur utilise ConnectionPool ou utilise des objets de tâche pour la programmation multitâche, ce mode peut entraîner un mauvais comportement d'un programme. Pour éviter ce problème, l'utilisateur doit supprimer manuellement la connexion par défaut (s'il l'utilise) à la fin du code qui s'exécute dans le thread. - ConnectionAsgmtType.UseMain Le client de messagerie utilise la connexion principale pour toutes les opérations à partir de plusieurs threads. La connexion principale est une connexion qui est créée en même temps que le client de messagerie. L'utilisateur ne peut pas créer de connexions par défaut. L'utilisateur peut créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. - ConnectionAsgmtType.UseDefault Le client de messagerie utilise implicitement uniquement les connexions par défaut pour toutes les opérations à partir de plusieurs threads. La connexion principale n'est pas utilisée dans ce mode. Si la connexion par défaut n'a pas été créée pour un thread (première invocation de la méthode du client de messagerie), le client de messagerie crée implicitement une connexion par défaut pour le thread avant l'exécution de la première opération. L'utilisateur ne peut pas créez des connexions par défaut pour les threads avec la méthode CreateConnection car elles sont créées automatiquement. Lorsque la connexion par défaut pour le thread est créée, elle est utilisée implicitement pour toutes les méthodes du client de messagerie qui sont invoquées dans ce thread.read. L'utilisateur peut également créer des connexions non liées à des threads (pas des connexions par défaut) avec la méthode CreateConnection. Si l'utilisateur souhaite utiliser d'autres connexions (non principales et non par défaut), il doit passer explicitement cette connexion en tant que paramètre d'une méthode qu'il souhaite utiliser. L'utilisateur peut en outre créer n'importe quel nombre de connexions. La connexion par défaut ne peut être qu'une par thread. Veuillez noter que les connexions par défaut fonctionnent correctement si l'utilisateur utilise des objets Thread pour la programmation multitâche. Si l'utilisateur utilise ConnectionPool ou utilise des objets Task pour la programmation multitâche, ce mode peut entraîner un mauvais comportement d'un programme. Pour éviter ce problème, l'utilisateur doit supprimer manuellement la connexion par défaut à la fin du code qui s'exécute dans le thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Période de vérification de la connexion en millisecondes. La valeur par défaut est de 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Obtient ou définit la quantité de connexions en mode multi-connexion |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Obtient l'état actuel de la connexion. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Obtient la connexion actuelle selon l'option ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Obtient le port par défaut pour le client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Obtient ou définit la valeur qui permet d'activer/désactiver l'enregistreur |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Obtient ou définit le délai d'expiration du message d'accueil utilisé lors de l'établissement d'une connexion. Veuillez noter que le délai d'expiration du message d'accueil ne peut pas être infini. Les clients de messagerie peuvent exécuter des opérations suffisamment longues. Pour limiter le temps des opérations, les utilisateurs doivent utiliser[`Timeout`](../../aspose.email.clients/emailclient/timeout)propriété. Les valeurs de cette propriété doivent avoir de longs intervalles pour ne pas empêcher les opérations de longue durée. Mais dans certains cas, si EmailClient utilise uniquement la propriété Timeout, l'établissement de la connexion peut prendre beaucoup de temps. Par exemple, le client de messagerie peut utiliser le mode automatique pour établir la connexion. Dans ce mode, le client de messagerie parcourt tous les paramètres de connexion possibles jusqu'à ce que la connexion soit établie. Serveurs SMTP, IMAP et POP3 en cas de connexion correcte établissant envoyer la chaîne de salutation au client. Les serveurs peuvent utiliser une initiation de connexion SSL/TLS implicite ou explicite (START TLS). Si le mode de connexion ne correspond pas (par exemple, le serveur attend une connexion SSL implicite mais le client essaie d'établir une connexion SSL non sécurisée ou explicite), le serveur n'enverra pas de chaîne de salutation. Dans ce cas, l'utilisateur attendra longtemps jusqu'à ce que le délai d'attente atteigne une chaîne de salutation et le client passe à l'option de connexion suivante. Pour éviter ce problème, la propriété GreetingTimeout a été introduite. Cette propriété vous permet de définir le délai d'attente pour la chaîne de salutation, et de réduire le temps d'établissement de connexion automatique. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Obtient ou définit le nom d'hôte. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Obtient ou définit le nom du fichier journal |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Obtient ou définit le mot de passe. Les limitations de mot de passe sont définies par l'implémentation du serveur, auquel le client se connecte. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Obtient ou définit le port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Obtient ou définit le proxy pour le client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Mode de sécurité pour un client de messagerie |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Obtient l'énumération des types d'authentification pris en charge par le serveur |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Définit les versions des protocoles de cryptage SSL/TLS à utiliser. VEUILLEZ FAIRE ATTENTION, vous ne pouvez définir que les versions de protocole prises en charge par .net framework. SI CERTAINES VERSIONS DU PROTOCOLE NE SONT PAS PRIS EN CHARGE PAR VOTRE VERSION ACTUELLE DE .NET FRAMEWORK, ILS SERONT IGNORÉS ET Ignorés. IL PEUT ENTRAÎNER UNE RÉTROGRADATION DU NIVEAU DE SÉCURITÉ TLS. DANS CE CAS, L'EXCEPTION NE SERA PAS GÉNÉRÉE !!! Veuillez consulter[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentation pour plus de détails. Veuillez utiliser[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) si vous souhaitez définir les protocoles de chiffrement sans aucune vérification de compatibilité. La valeur par défaut est : Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (au cas où votre version actuelle de .net framework prend en charge ces versions de TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Obtient ou définit le délai d'expiration des opérations de messagerie |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Obtient ou définit TokenProvider permettant de récupérer le jeton d'accès. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indique si l'authentification est utilisée. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Obtient ou définit la valeur qui indique si la date doit être utilisée dans le nom du fichier journal. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Obtient ou définit une valeur booléenne qui contrôle si les DefaultCredentials sont envoyés avec les demandes. Cette option est utilisée UNIQUEMENT avec l'authentification NTLM ! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Obtient ou définit la valeur qui indique si le client doit utiliser plusieurs connexions pour les opérations lourdes. Veuillez noter que l'utilisation de ce mode n'est pas nécessaire pour augmenter les performances. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Obtient ou définit l'objet qui indique si le mode pipelining est activé. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Obtient ou définit le nom d'utilisateur. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Valider les suppressions |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Valider les suppressions |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Valider les suppressions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Valider les suppressions |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crée une nouvelle connexion indépendante pour les opérations non liées aux threads (pas de connexion par défaut). L'appel de cette méthode est similaire à l'appel de CreateConnection(createAsDefaultConnection = false) Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crée une nouvelle connexion (par défaut ou indépendante) pour les opérations. Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Supprime le message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Supprime le message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Supprime le message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Supprime le message |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Supprime tous les messages |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Supprime tous les messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Supprime tous les messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Supprime tous les messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Supprime tous les messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Supprime tous les messages |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalise toutes les opérations avec un serveur. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Récupère le message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Récupère le message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Récupère le message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Récupère le message |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Récupère les messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Récupère les messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Récupère les messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Récupère les messages |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Récupère les messages de manière asynchrone |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Obtient la taille de la boîte aux lettres |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Obtient la taille de la boîte aux lettres |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Obtient la taille de la boîte aux lettres |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Obtient la taille de la boîte aux lettres |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Obtient la taille de la boîte aux lettres |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Obtient la taille de la boîte aux lettres |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Obtient le nombre de messages |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Obtient le nombre de messages |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Obtient le nombre de messages |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Obtient le nombre de messages |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Obtient le nombre de messages |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Obtient les en-têtes de message |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Obtient les en-têtes de message |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Obtient les en-têtes de message |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Obtient la taille du message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Obtient la taille du message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Obtient la taille du message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Obtient la taille du message |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Obtient l'identifiant unique du message |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Obtient l'identifiant unique du message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Obtient l'identifiant unique du message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Obtient l'identifiant unique du message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Obtient l'identifiant unique du message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Obtient l'identifiant unique du message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Liste les messages. Obtient une information pour chaque message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Liste les messages. Obtient une information pour chaque message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Liste les messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Liste les messages. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Charge la liste de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Charge la liste de Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | Commande 'Aucune opération' |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | Commande 'Aucune opération' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | Commande 'Aucune opération' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Réinitialise les paramètres de journalisation par défaut. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Récupère et enregistre le message dans un fichier |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Récupère et enregistre le message sous forme de flux |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Récupère et enregistre le message dans un fichier |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Définit les versions des protocoles de chiffrement SSL/TLS à utiliser. Cette méthode n'est pas sûre et définit les protocoles de chiffrement sans aucune vérification de compatibilité. Utilisation[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) pour définir en toute sécurité uniquement les protocoles définitivement pris en charge par .net framework. Veuillez noter que si votre framework .net actuel ne prend pas en charge ce niveau de sécurité, une exception sera levée lors de la tentative d'établissement d'une connexion au serveur. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Exécute la validation des identifiants |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Exécute la validation des identifiants |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Exécute la validation des identifiants |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crée une nouvelle instance du[`Pop3Client`](../pop3client) classe |

### Voir également

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
