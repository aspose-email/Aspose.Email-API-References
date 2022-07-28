---
title: ActiveSyncTLClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Classe de base pour les implémentations de client ActiveSync
type: docs
weight: 950
url: /fr/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Classe de base pour les implémentations de client ActiveSync

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Obtient ou définit le type d'authentification utilisé par le client ActiveSync. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Obtient ou définit le service de découverte automatique uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Informations d'identification de l'utilisateur pour le serveur Exchange |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | Un GUID qui identifie le périphérique. L'ID de périphérique est spécifié par la partie de règle ABNF device-id-spec de la valeur de requête en texte brut. La valeur, représentée par la règle ABNF device-id, est une chaîne qui spécifie le périphérique. Chaque appareil DOIT avoir une chaîne d'ID d'appareil unique. Chaque demande de l'appareil DOIT inclure la même chaîne d'ID d'appareil. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Le type de périphérique est spécifié par la partie de règle ABNF de spécification de type de périphérique de la valeur de requête en texte brut. La valeur, représentée par la règle ABNF de type de périphérique, est toute chaîne qui spécifie un type de périphérique. "SP" spécifie un SmartPhone et "PPC" spécifie un PocketPC. D'autres appareils clients envoient des chaînes uniques pour leur type d'appareil spécifique. Chaque demande d'un appareil client DOIT inclure la même chaîne de type d'appareil. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Un entier non signé qui indique l'état des paramètres de stratégie sur le périphérique client, comme spécifié dans [MS-ASPROV] section 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Obtient ou définit le proxy. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Obtient les versions des commandes ActiveSync qui sont prises en charge |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Obtient les versions des protocoles ActiveSync qui sont pris en charge |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Obtient l'URL du service ActiveSync |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Le champ d'en-tête de demande User-Agent contient des informations sur l'agent utilisateur à l'origine de la demande. Ceci est à des fins statistiques, de traçage des violations de protocole et de reconnaissance automatisée des agents utilisateurs dans le but d'adapter les réponses pour éviter les limitations particulières des agents utilisateurs. Les agents utilisateurs DEVRAIENT inclure ce champ avec les requêtes. Le champ peut contenir plusieurs jetons de produit (section 3.8) et des commentaires identifiant l'agent et tous les sous-produits qui constituent une partie importante de l'agent utilisateur. Par convention, les tokens produits sont listés dans l'ordre de leur importance pour l'identification de l'application. Exemple : User-Agent : CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Obtient la version du protocole utilisé dans le client ActiveSync. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Obtient ou définit la valeur de délai d'expiration par défaut pour les instances de client ActiveSync La valeur par défaut est de 100 000 millisecondes (100 secondes). |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | La commande de découverte automatique facilite la découverte des informations de configuration du compte principal en utilisant l'adresse SMTP (Simple Mail Transfer Protocol) de l'utilisateur comme entrée principale. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Effectue les tâches associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | La commande de découverte automatique facilite la découverte des informations de configuration du compte principal en utilisant l'adresse SMTP (Simple Mail Transfer Protocol) de l'utilisateur comme entrée principale. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Obtient une instance du client ActiveSync La version du protocole ActiveSync est sélectionnée automatiquement en fonction de la réponse du serveur. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Obtient une instance du client ActiveSync |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | La méthode statique GetOptions est utilisée pour découvrir quelles versions de protocole sont prises en charge et quelles commandes de protocole sont prises en charge sur le serveur. Le client utilise la méthode statique GetOptions pour déterminer si le serveur prend en charge les mêmes versions du protocole que le client prend en charge. |

### Voir également

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
