---
title: MailQuery
second_title: Référence de l'API Aspose.Email pour .NET
description: Initialise une nouvelle instance duMailQueryaspose.email.tools.search/mailquery classer.
type: docs
weight: 10
url: /fr/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Initialise une nouvelle instance du[`MailQuery`](../../mailquery) classer.

```csharp
public MailQuery(string queryString)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| queryString | String | La chaîne de requête. |

### Remarques

La chaîne de requête doit avoir la vue suivante.

L'exemple d'une expression simple :

'&lt;Nom du champ&gt;' &lt;Opérateur de comparaison&gt; '&lt;Valeur du champ&gt;',

où &lt;Field Name&gt; - le nom d'un champ de message à travers lequel le filtrage est effectué, &lt;Comparison operator&gt; - les opérateurs de comparaison, comme leur nom l'indique, permettent de comparer le champ de message et la valeur spécifiée, &lt;Field value&gt; - la valeur à être comparé à un champ de message.

Le nombre d'expressions simples peut en faire une composée, ex. : (&lt;Expression simple 1&gt; &amp; &lt;Expression simple 2&gt;) &#x7C; &lt;Expression simple 3&gt;,

où "&amp;" - opérateur logique ET, "&#x7C;" - opérateur logique OU

Actuellement, les valeurs suivantes sont autorisées comme nom de champ (&lt;Nom du champ&gt;) :

"To" - représente un champ TO du message, "Text" - représente une chaîne dans l'en-tête ou le corps du message, "Cci" - représente un champ BCC du message, "Body" - représente une chaîne dans le corps du message, "Cc" - représente un champ CC du message, "From" - représente un champ From du message, "Subject" - représente une chaîne dans l'objet du message, "InternalDate" - représente une date interne date du message, "SentDate" - représente une date d'envoi du message

De plus, les noms de champs suivants sont autorisés pour le protocole IMAP :

"Répondu" - représente un drapeau /Répondu du message "Vu" - représente un drapeau /Vu du message "Marqué" - représente un drapeau /Flagged du message "Brouillon" - représente un drapeau /Brouillon du message "Supprimé" - représente un indicateur Supprimé/ de message "Récent" - représente un indicateur Supprimé/ de message "MessageSize" - représente une taille (en octets) de message

De plus, les noms de champs suivants sont autorisés pour Exchange :

"IsRead" - Indique si le message a été lu "HasAttachment" - Indique si le message contient ou non des pièces jointes "IsSubmitted" - Indique si le message a été soumis à la boîte d'envoi "ContentClass" - représente une classe de contenu de item

De plus, les noms de champs suivants sont autorisés pour les fichiers pst/ost :

"MessageClass" - Représente une classe de message "ContainerClass" - Représente une classe de conteneur de dossier "Importance" - Représente une importance de message "MessageSize" - représente une taille (en octets) de message "FolderName" - représente un nom de dossier "ContentsCount" - représente un nombre total d'éléments dans le dossier "UnreadContentsCount" - représente le nombre d'éléments non lus dans le dossier. "Subfolders" - Indique si le dossier contient ou non des sous-dossiers "Read" - le message est marqué comme ayant été lu " HasAttachment" - le message a au moins une pièce jointe "Unsent" - le message est toujours en cours de composition "Unmodified" - le message n'a pas été modifié depuis qu'il a été enregistré pour la première fois (si non envoyé) ou qu'il a été remis (si envoyé) "FromMe " - l'utilisateur recevant le message était également l'utilisateur qui a envoyé le message "Renvoyer" - le message inclut une demande d'opération de renvoi avec un rapport de non-remise_x000 d_ "NotifyRead" - l'utilisateur qui a envoyé le message a demandé une notification lorsqu'un destinataire le lit pour la première fois "NotifyUnread" - l'utilisateur qui a envoyé le message a demandé une notification lorsqu'un destinataire le supprime avant de le lire ou que l'objet Message expire "EverRead" - le le message a été lu au moins une fois

La valeur du champ (&lt;Valeur du champ&gt;) peut prendre les valeurs suivantes : Pour les champs de texte - n'importe quelle chaîne, Pour les champs de type date - la chaîne au format "j-MMM-aaa", ex. "10-Feb-2009", Pour les flags (champs de type booléen) - soit "True", soit "False"

### Exemples

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Voir également

* class [MailQuery](../../mailquery)
* espace de noms [Aspose.Email.Tools.Search](../../mailquery)
* Assemblée [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Initialise une nouvelle instance du[`MailQuery`](../../mailquery) classer.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Remarques

La chaîne de requête de tri doit avoir la vue suivante.

L'exemple d'une expression simple :

'&lt;Nom du champ&gt;' OrderBy ['ASC'&#x7C;'DESC'],

où &lt;Field Name&gt; - le nom d'un champ de message à travers lequel le tri est effectué, ['ASC'&#x7C;'DESC'] - les opérateurs de tri, permettent de trier par ordre croissant ou décroissant,

Le nombre d'expressions simples peut en faire une composée, ex. : (&lt;Expression simple 1&gt; &amp; &lt;Expression simple 2&gt;),

### Exemples

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Voir également

* class [MailQuery](../../mailquery)
* espace de noms [Aspose.Email.Tools.Search](../../mailquery)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
