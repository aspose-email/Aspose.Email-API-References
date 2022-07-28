---
title: MailMessage
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un message électronique. Il permet daccéder aux propriétés du message ex. objet corps adresses de lexpéditeur et des destinataires etc. Il peut également être envoyé et livré au moyen de protocoles de messagerie pris en charge.
type: docs
weight: 17710
url: /fr/net/aspose.email/mailmessage/
---
## MailMessage class

Représente un message électronique. Il permet d'accéder aux propriétés du message, ex. objet, corps, adresses de l'expéditeur et des destinataires, etc. Il peut également être envoyé et livré au moyen de protocoles de messagerie pris en charge.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider, ISerializable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MailMessage](mailmessage#constructor)() | Initialise une nouvelle instance du[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_2)(bool) | Initialise une nouvelle instance du[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_1)(MailAddress, MailAddress) | Initialise une nouvelle instance du[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_3)(string, string) | Initialise une nouvelle instance du[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_4)(string, string, string, string) | Initialise une nouvelle instance du[`MailMessage`](../mailmessage) classe |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Obtient la collection de vues alternatives de message |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Obtient la collection de pièces jointes du message |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Obtient ou définit la collection d'adresses qui contient les destinataires BCC du message |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Obtient ou définit la représentation en texte brut du corps du message. Si la partie text/plain est présente dans un message, la propriété renvoie ses données textuelles. Sinon, la propriété renvoie le contenu textuel de la propriété HtmlBody sans balisage html. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Obtient ou définit l'encodage de body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Obtient le type du corps. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Obtient ou définit la collection d'adresses qui contient les destinataires CC |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Obtient ou définit la date du message |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Obtient ou définit les notifications de livraison |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Obtient ou définit un texte d'épilogue. Il est situé après la dernière limite. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Obtient ou définit l'adresse de provenance |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Obtient la collection d'en-têtes de message |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Récupère ou définit le corps html |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Obtient ou définit une valeur indiquant si le corps du message est au format Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Obtient ou définit la valeur qui indique si un message a été envoyé ou non. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Obtient une valeur indiquant si le message est chiffré. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Obtient une valeur indiquant si le message est en lecture seule |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Obtient une valeur indiquant si le message est signé. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Obtient la collection de ressources liées de message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Obtient ou définit l'identifiant du message |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Obtient une valeur indiquant si le message EML d'origine est au format TNEF. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Obtient ou définit un texte de préambule. Il est situé avant la première limite et inclut généralement une note explicative pour les lecteurs non conformes à MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Obtient ou définit l'encodage préféré pour toutes les propriétés de texte |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Obtient ou définit la priorité du message |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Obtient ou définit l'adresse de confirmation de lecture. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Obtient ou définit la liste des adresses auxquelles répondre pour le message électronique |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Obtient ou définit l'adresse ReversePath |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Obtient ou définit l'adresse de l'expéditeur |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Obtient ou définit la sensibilité du message |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Obtient ou définit la ligne d'objet |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Obtient ou définit l'encodage de subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Obtient ou définit le décalage UTC (Coordinated Universal Time) pour les dates des messages. Cette propriété définit la différence de fuseau horaire, entre l'heure locale et UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Obtient ou définit la collection d'adresses qui contient les destinataires du message |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Obtient ou définit le X-Mailer le logiciel qui a créé le message électronique |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Load](../../aspose.email/mailmessage/load#load)(Stream) | Charger le message du flux |
| static [Load](../../aspose.email/mailmessage/load#load_2)(string) | Charger le message du fichier |
| static [Load](../../aspose.email/mailmessage/load#load_1)(Stream, LoadOptions) | Charger le message du flux avec des options supplémentaires. |
| static [Load](../../aspose.email/mailmessage/load#load_3)(string, LoadOptions) | Charger le message du fichier avec des options supplémentaires. |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Ajouter une autre vue au message |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Ajouter une pièce jointe au message |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature)(CmsSigner) | Crée un message signé. Crée une copie en lecture seule du MailMessage spécifié et y ajoute une signature numérique. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_2)(X509Certificate2) | Crée un message signé. Crée une copie en lecture seule du MailMessage spécifié et y ajoute une signature numérique. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_1)(CmsSigner, bool) | Crée un message signé. Crée une copie en lecture seule du MailMessage spécifié et y ajoute une signature numérique. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_3)(X509Certificate2, bool) | Crée un message signé. Crée une copie en lecture seule du MailMessage spécifié et y ajoute une signature numérique. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Vérifie si ce message peut être traité comme un message de rebond. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Vérification de la signature existante MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Clone cette instance |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Crée la confirmation de lecture. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt)() | décrypte ce message |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt_1)(X509Certificate2) | décrypte ce message |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Libère toutes les ressources utilisées par le MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | signe ce message à l'aide de la signature DKIM (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt)(X509Certificate2) | Crypte ce message |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt_1)(X509Certificate2[]) | Crypte ce message |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Renvoie un énumérateur qui parcourt une collection. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Renvoie un code de hachage pour object |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext_1)(bool) | Récupère le corps du message HTML en texte brut. Cette méthode analyse la propriété HtmlBody et renvoie le contenu en texte brut en ignorant le balisage html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext)(HyperlinkRenderingCallback) | Obtient le message htmlbody en texte brut. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | Remplit unSerializationInfo avec les données nécessaires pour sérialiser l'objet cible. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Importe le message du stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Compose le contenu TNEF. Notez que la pièce jointe tnef est composée si un message contenait initialement TNEF et a été chargé sans l'indicateur FileCompatibilityMode.PreserveTnefAttachments, C'est-à-dire que cette méthode ne crée pas de message tnef à partir du message normal. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Supprimer la signature |
| virtual [Save](../../aspose.email/mailmessage/save#save)(Stream) | Enregistrer le message en tant que flux |
| virtual [Save](../../aspose.email/mailmessage/save#save_2)(string) | Enregistrer le message en tant que fichier |
| virtual [Save](../../aspose.email/mailmessage/save#save_1)(Stream, SaveOptions) | Enregistrer le message sous forme de flux avec des options supplémentaires. |
| virtual [Save](../../aspose.email/mailmessage/save#save_3)(string, SaveOptions) | Enregistrer le message dans un fichier avec des options supplémentaires. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Définit le corps html. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature)(Stream) | Vérifie la signature du message eml spécifié. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature_1)(string) | Vérifie la signature du fichier eml spécifié. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage)(Stream) | Valider le message eml correspondant à la spécification mime. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage_1)(string) | Valider le message eml correspondant à la spécification mime. |

### Voir également

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* espace de noms [Aspose.Email](../../aspose.email)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
