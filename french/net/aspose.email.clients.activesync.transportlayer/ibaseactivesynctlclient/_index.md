---
title: IBaseActiveSyncTLClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Interface client ActiveSync de base
type: docs
weight: 1320
url: /fr/net/aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/
---
## IBaseActiveSyncTLClient interface

Interface client ActiveSync de base

```csharp
public interface IBaseActiveSyncTLClient : IDisposable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/authenticationtype) { get; set; } | Obtient ou définit le type d'authentification utilisé par le client ActiveSync. |
| [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscoveruri) { get; set; } | Obtient l'uri de découverte automatique |
| [Credentials](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/credentials) { get; } | Informations d'identification de l'utilisateur pour le serveur Exchange |
| [DeviceID](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/deviceid) { get; set; } | Un GUID qui identifie le périphérique. L'ID de périphérique est spécifié par la partie de règle ABNF device-id-spec de la valeur de requête en texte brut. La valeur, représentée par la règle ABNF device-id, est une chaîne qui spécifie le périphérique. Chaque appareil DOIT avoir une chaîne d'ID d'appareil unique. Chaque demande de l'appareil DOIT inclure la même chaîne d'ID d'appareil. |
| [DeviceType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/devicetype) { get; set; } | Le type de périphérique est spécifié par la partie de règle ABNF de spécification de type de périphérique de la valeur de requête en texte brut. La valeur, représentée par la règle ABNF de type de périphérique, est toute chaîne qui spécifie un type de périphérique. "SP" spécifie un SmartPhone et "PPC" spécifie un PocketPC. D'autres appareils clients envoient des chaînes uniques pour leur type d'appareil spécifique. Chaque demande d'un appareil client DOIT inclure la même chaîne de type d'appareil. |
| [PolicyState](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/policystate) { get; set; } | Un entier non signé qui indique l'état des paramètres de stratégie sur le périphérique client, comme spécifié dans [MS-ASPROV] section 2.2.2.41. |
| [Proxy](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/proxy) { get; set; } | Obtient ou définit le proxy. |
| [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedservercommands) { get; } | Obtient les versions des commandes ActiveSync prises en charge par le serveur |
| [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedserverprotocols) { get; } | Obtient les versions des protocoles ActiveSync qui sont pris en charge par le serveur |
| [Timeout](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| [Uri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/uri) { get; } | Obtient l'uri du serveur |
| [UserAgent](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/useragent) { get; set; } | Le champ d'en-tête de demande User-Agent contient des informations sur l'agent utilisateur à l'origine de la demande. Ceci est à des fins statistiques, de traçage des violations de protocole et de reconnaissance automatisée des agents utilisateurs dans le but d'adapter les réponses pour éviter les limitations particulières des agents utilisateurs. Les agents utilisateurs DEVRAIENT inclure ce champ avec les requêtes. Le champ peut contenir plusieurs jetons de produit (section 3.8) et des commentaires identifiant l'agent et tous les sous-produits qui constituent une partie importante de l'agent utilisateur. Par convention, les tokens produits sont listés dans l'ordre de leur importance pour l'identification de l'application. Exemple : User-Agent : CERN-LineMode/2.15 libwww/2.17b3 |
| [Version](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/version) { get; } | Obtient la version du protocole utilisé dans le client ActiveSync. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Autodiscover](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscover)(string) | La commande de découverte automatique facilite la découverte des informations de configuration du compte principal en utilisant l'adresse SMTP (Simple Mail Transfer Protocol) de l'utilisateur comme entrée principale. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
