---
title: ListFoldersOptions
second_title: Référence de l'API Aspose.Email pour .NET
description: Les options de sélection de liste de dossiers Veuillez noter que ces options sont prises en charge si le serveur prend en charge RFC 5258 IMAP LIST Command Extensions Voir plus de détails dans https//tools.ietf.org/html/rfc5258
type: docs
weight: 16510
url: /fr/net/aspose.email.clients.imap/listfoldersoptions/
---
## ListFoldersOptions enumeration

Les options de sélection de liste de dossiers Veuillez noter que ces options sont prises en charge si le serveur prend en charge RFC 5258 "IMAP LIST Command Extensions" Voir plus de détails dans https://tools.ietf.org/html/rfc5258

```csharp
[Flags]
public enum ListFoldersOptions
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Non défini |
| Subscribed | `1` | SUBSCRIBED - oblige la commande LIST à répertorier les noms souscrits, plutôt que les boîtes aux lettres existantes. Il s'agira souvent d'un sous-ensemble des boîtes aux lettres réelles. Il est également possible que cette liste contienne des noms de boîtes aux lettres qui n'existent pas. Dans tous les cas, la liste DOIT inclure exactement les noms de boîtes aux lettres qui correspondent au modèle de liste canonique et auxquels vous êtes abonné. Cette option est destinée à compléter la commande LSUB. Il convient de noter en particulier les attributs de boîte aux lettres renvoyés par cette option, par rapport à ce qui est renvoyé par LSUB. Avec ce dernier, les attributs renvoyés peuvent ne pas refléter l'état réel de l'attribut sur le nom de la boîte aux lettres, et l'attribut \NoSelect a une deuxième signification particulière (il indique que cette boîte aux lettres n'est pas elle-même abonnée, mais qu'elle a des boîtes aux lettres descendantes qui sont). Avec l'option de sélection SUBSCRIBED décrite ici, les attributs sont précis et complets, et n'ont aucune signification particulière. "LSUB" et "LIST (ABONNE)" ne sont donc pas la même chose, et certains serveurs doivent faire un travail supplémentaire important pour répondre à "LIST (ABONNE)". Pour cette raison, les clients DEVRAIENT continuer à utiliser "LSUB" à moins qu'ils ne souhaitent spécifiquement les informations supplémentaires offertes par "LIST (SUBSCRIBED)". Cette option définit un nouvel attribut de boîte aux lettres, "\Subscribe", qui indique qu'un nom de boîte aux lettres est abonné à. L'attribut "\Subscribed" DOIT être pris en charge et DOIT être calculé avec précision lorsque l'option de sélection SUBSCRIBED est spécifiée. Notez que l'option de sélection SUBSCRIBED implique l'option de retour SUBSCRIBED (voir ci-dessous). |
| Remote | `2` | REMOTE - force la commande LIST à afficher les boîtes aux lettres distantes ainsi que les locales, comme décrit dans [MBRef]. Cette option est destinée à remplacer la commande RLIST et, en conjonction avec l'option de sélection SUBSCRIBED, la commande RLSUB. Cette option définit un nouvel attribut de boîte aux lettres, "\Remote", qui indique qu'une boîte aux lettres est une boîte aux lettres distante. Le L'attribut "\Remote" DOIT être calculé avec précision lorsque l'option REMOTE est spécifiée. L'option de sélection REMOTE n'a aucune interaction avec les autres options. Son effet est de dire au serveur d'appliquer les autres options, le cas échéant, aux boîtes aux lettres distantes, dans en plus des locaux. En particulier, il n'a aucune interaction avec RECURSIVEMATCH (voir ci-dessous). Une demande pour (REMOTE RECURSIVEMATCH) n'est pas valide, car une demande pour (RECURSIVEMATCH) l'est. Une requête pour (REMOTE RECURSIVEMATCH SUBSCRIBED) demande toutes les boîtes aux lettres abonnées, à la fois locales et distantes. |
| RecursiveMatch | `4` | RECURSIVEMATCH - cette option force le serveur à renvoyer des informations sur les boîtes aux lettres parentes qui ne correspondent pas aux autres options de sélection, mais qui ont des sous-boîtes aux lettres qui le font. Les informations sur les enfants sont renvoyées dans l'élément de données étendu CHILDINFO. Remarque 1 : pour qu'une boîte aux lettres parente soit renvoyée, elle doit toujours correspondre au modèle canonique de LISTE. Remarque 2 : lors du renvoi de l'élément de données étendu CHILDINFO, peu importe si la sous-boîte aux lettres correspond ou non à la LISTE canonique. motif. L'option RECURSIVEMATCH NE DOIT PAS être la seule option de sélection (ou uniquement avec REMOTE), car elle n'a de sens que lorsque d'autres options de sélection sont également utilisées. Le serveur DOIT renvoyer une réponse étiquetée BAD dans ce cas. Notez que même si l'option RECURSIVEMATCH est spécifiée, le client DOIT toujours être en mesure de gérer un cas lorsqu'un élément de données étendu CHILDINFO est renvoyé et qu'il n'y a pas de sous-boîtes aux lettres qui répondent aux critères de sélection de la commande LIST suivante, car ils peut être supprimé/renommé après l'envoi de la réponse LIST, mais avant que le client n'ait eu la possibilité d'y accéder. |

### Voir également

* espace de noms [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
