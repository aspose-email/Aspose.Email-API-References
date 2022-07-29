---
title: AmpForm
second_title: Référence de l'API Aspose.Email pour .NET
description: Lextension amp-form vous permet de créer des formulaires pour soumettre des champs de saisie dans un document AMP.
type: docs
weight: 120
url: /fr/net/aspose.email.amp/ampform/
---
## AmpForm class

L'extension amp-form vous permet de créer des formulaires pour soumettre des champs de saisie dans un document AMP.

```csharp
public class AmpForm : AmpComponent
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AmpForm](ampform)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Action](../../aspose.email.amp/ampform/action) { get; set; } | Spécifie un point de terminaison de serveur pour gérer l'entrée de formulaire. La valeur doit être une URL https (absolue ou relative) et ne doit pas être un lien vers un CDN |
| [ActionXhr](../../aspose.email.amp/ampform/actionxhr) { get; set; } | Spécifie un point de terminaison de serveur pour gérer la saisie du formulaire et soumettre le formulaire via XMLHttpRequest (XHR). |
| [Attributes](../../aspose.email.amp/ampcomponent/attributes) { get; } | AMP fournit un ensemble d'attributs communs qui sont étendus à de nombreux composants AMP. |
| [Fallback](../../aspose.email.amp/ampcomponent/fallback) { get; set; } | Un repli est une convention qui permet à l'élément de communiquer au lecteur que le navigateur ne prend pas en charge l'élément. |
| [Fieldset](../../aspose.email.amp/ampform/fieldset) { get; } | Liste des champs. |
| [Method](../../aspose.email.amp/ampform/method) { get; set; } | L'attribut method indique au serveur la méthode de requête. |
| [Placeholder](../../aspose.email.amp/ampcomponent/placeholder) { get; set; } | L'élément marqué avec l'attribut d'espace réservé agit comme un espace réservé pour l'élément AMP parent. S'il est spécifié, un élément d'espace réservé doit être un enfant direct de l'élément AMP. |
| override [RequiredScript](../../aspose.email.amp/ampform/requiredscript) { get; } | Script requis qui doit être ajouté à la section head. |
| [Target](../../aspose.email.amp/ampform/target) { get; set; } | Indique où afficher la réponse du formulaire après avoir soumis le formulaire. La valeur doit être _blank ou _top. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ToAmpHtml](../../aspose.email.amp/ampform/toamphtml)() | Représente la version amp html du composant. |
| override [ToHtml](../../aspose.email.amp/ampform/tohtml)() | Représente la version html du composant. |

### Voir également

* class [AmpComponent](../ampcomponent)
* espace de noms [Aspose.Email.Amp](../../aspose.email.amp)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->