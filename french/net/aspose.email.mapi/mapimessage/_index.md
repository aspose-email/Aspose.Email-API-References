---
title: MapiMessage
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un document au format de message Outlook qui peut être analysé.
type: docs
weight: 18450
url: /fr/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Représente un document au format de message Outlook qui peut être analysé.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Initialise une nouvelle instance du[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Initialise une nouvelle instance du[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Initialise une nouvelle instance du[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Initialise une nouvelle instance du[`MapiMessage`](../mapimessage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Obtient les pièces jointes dans le message. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contient les informations de facturation associées à un article. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Obtient le texte du message. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtient le[`BodyRtf`](../mapimessageitembase/bodyrtf) du message converti en HTML, si présent, sinon une chaîne vide. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtient ou définit le texte du message au format RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtient le type du corps. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contient des mots-clés ou des catégories pour l'objet de message. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'expéditeur du message a envoyé un message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contient les noms des sociétés associées à un article. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Obtient le sujet du premier message dans un fil de conversation. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Obtient ou définit la date et l'heure d'envoi d'un message. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Obtient une liste des noms d'affichage de tous les destinataires de messages en copie carbone invisible (Cci), séparés par des points-virgules (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Obtient une liste des noms d'affichage de tous les destinataires de messages en copie carbone (CC), séparés par des points-virgules (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Obtient le nom d'affichage du message. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Obtient un préfixe du nom d'affichage. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Obtient une liste des noms d'affichage des destinataires principaux du message (À), séparés par des points-virgules (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Obtient les indicateurs de message. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Obtient les en-têtes du message de transport |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Obtient l'ID de message du message. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtient une chaîne sensible à la casse qui identifie la classe de message définie par l'expéditeur, telle que IPM.Note. La classe de message spécifie le type, l'objectif ou le contenu du message. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Obtient le format du message Outlook. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contient les informations de kilométrage associées à un article. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtient le mappage de propriété nommé. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Obtient le sujet normalisé du message. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtient le flux de propriété. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Obtient ou définit une valeur indiquant si la confirmation de lecture est demandée. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtient les destinataires du message. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Obtient ou définit la réponse aux noms. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Obtient le type d'adresse e-mail de l'expéditeur du message. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Obtient ou définit l'adresse e-mail de l'expéditeur du message. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Obtient ou définit le nom d'affichage de l'expéditeur du message. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Obtient ou définit l'adresse e-mail de l'expéditeur du message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtient la sensibilité. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Obtient le type d'adresse pour l'utilisateur de messagerie représenté par l'expéditeur. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Obtient ou définit l'adresse e-mail de l'utilisateur de messagerie représenté par l'expéditeur. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Obtient ou définit le nom d'affichage de l'utilisateur de messagerie représenté par l'expéditeur. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Obtient ou définit l'adresse e-mail de l'utilisateur de messagerie représenté par l'expéditeur. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtient ou définit l'objet du message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtient un préfixe d'objet qui indique généralement une action sur un message, tel que "FW : " pour le transfert. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtient les sous-stockages. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Obtient les informations d'enveloppe de message spécifiques au transport. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Crée une instance de MapiMessage à partir du MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Crée une instance de MapiMessage à partir du MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Crée une instance de MapiMessage à partir du MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Crée une instance de MapiMessage à partir d'une collection de propriétés Mapi. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Charge le message du flux. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Charge le message à partir du fichier. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Charge le message du flux avec des options supplémentaires. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Charge le message du fichier avec des options supplémentaires. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Charge le message à partir de la structure de données TNEF (Transport Neutral Encapsulation Format) |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Charge le message à partir de la structure de données TNEF (Transport Neutral Encapsulation Format) |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Ajoute la propriété personnalisée. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Ajoute la propriété personnalisée. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Vérifie si ce message peut être traité comme un message de rebond. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Obtient une collection de MapiProperties personnalisées. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Obtient la propriété MAPI par descripteur de propriété. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type booléen. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtient la valeur int32 de la propriété spécifiée par tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type court. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Détermine si les propriétés de chaîne sont codées en Unicode ou non. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fournit la suppression correcte de la propriété de toutes les collections. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Enregistre dans le flux spécifié en tant que Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Enregistre dans le fichier spécifié en tant que Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Enregistre le message sous forme de flux avec des options supplémentaires. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Enregistre le message dans un fichier avec des options supplémentaires. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Enregistre dans le flux spécifié en tant que modèle de fichier Outlook (format OFT). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Enregistre dans le fichier spécifié en tant que modèle de fichier Outlook (format OFT). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Enregistrer le message au format TNEF. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Enregistrer le message au format TNEF. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Définit le contenu du corps. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Définit le contenu du corps. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Obtient ou définit le texte du message au format RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Définit les indicateurs de message. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Définit la propriété. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Définit la propriété MAPI. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Définit la valeur de la propriété de chaîne. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Crée une instance de MailMessage à partir de ce MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Convertir MapiMessage en objet IMapiMessageItem en dépendance avec MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Essayez d'obtenir les données de propriété avec la clé de balise spécifiée. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtient la valeur de la propriété spécifiée en tant que type DateTime. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtient la valeur de la propriété spécifiée en tant que type Int32. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtient la valeur de la propriété spécifiée en tant que type Long. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec la balise spécifiée. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec une balise et une page de code spécifiées. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Détruit les pièces jointes dans les fichiers de messages Outlook spécifiés. DestroyAttachments ignorera l'analyse des pièces jointes. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Détermine si le flux spécifié a un format MSG. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Détermine si le fichier spécifié a un format MSG. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Supprime toutes les pièces jointes des fichiers de messages Outlook spécifiés. |

### Remarques

Les instances de la classe MapiMessage sont utilisées pour représenter les fichiers de document de message Microsoft Outlook qui sont analysés par la classe MapiMessageReader. Pour accéder à l'expéditeur, au destinataire et au contenu d'un message électronique, utilisez les propriétés associées de la classe MapiMessage.

### Exemples

L'exemple suivant montre comment lire les fichiers de messages Outlook.

[C#]

[Visual Basic]

```csharp
//Ouvrir les fichiers de messages Outlook
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/lire le sujet
onsole.WriteLine("Subject:" + msg.Subject);

/nom de l'expéditeur
onsole.WriteLine("From:" + msg.SenderName);

/Corps du message
onsole.WriteLine("Body:" + msg.Body);

/Pièces jointes
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Ouvrir les fichiers de messages Outlook 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'lire le sujet 
Console.WriteLine("Subject:" + msg.Subject) 

'nom de l'expéditeur 
Console.WriteLine("From:" + msg.SenderName) 

'Corps du message 
Console.WriteLine("Body:" + msg.Body) 

'Pièces jointes 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Voir également

* class [MapiMessageItemBase](../mapimessageitembase)
* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
