---
title: GetHtmlBodyText
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupère le corps du message HTML en texte brut. Cette méthode analyse la propriété HtmlBody et renvoie le contenu en texte brut en ignorant le balisage html.
type: docs
weight: 500
url: /fr/net/aspose.email/mailmessage/gethtmlbodytext/
---
## GetHtmlBodyText(bool) {#gethtmlbodytext_1}

Récupère le corps du message HTML en texte brut. Cette méthode analyse la propriété HtmlBody et renvoie le contenu en texte brut en ignorant le balisage html.

```csharp
public virtual string GetHtmlBodyText(bool showUrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| showUrl | Boolean | Définit le besoin d'afficher l'URL dans le texte. |

### Voir également

* class [MailMessage](../../mailmessage)
* espace de noms [Aspose.Email](../../mailmessage)
* Assemblée [Aspose.Email](../../../)

---

## GetHtmlBodyText(HyperlinkRenderingCallback) {#gethtmlbodytext}

Obtient le message htmlbody en texte brut.

```csharp
public virtual string GetHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| hyperlinkRenderingCallback | HyperlinkRenderingCallback | Référence à une méthode personnalisée pour gérer le rendu du lien hypertexte. |

### Return_Value

Chaîne de résultat de la gestion personnalisée du rendu du lien hypertexte.

### Voir également

* delegate [HyperlinkRenderingCallback](../../hyperlinkrenderingcallback)
* class [MailMessage](../../mailmessage)
* espace de noms [Aspose.Email](../../mailmessage)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->