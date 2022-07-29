---
title: NthOccurrence
second_title: Référence de l'API Aspose.Email pour .NET
description: Obtient ou définit la nième occurrence du jour de la semaine.
type: docs
weight: 40
url: /fr/net/aspose.email.calendar.recurrences/byday/nthoccurrence/
---
## ByDay.NthOccurrence property

Obtient ou définit la nième occurrence du jour de la semaine.

```csharp
public int NthOccurrence { get; set; }
```

### Remarques

La plage valide pour cette propriété est de -53 à 53.

Les valeurs positives représentent la Nème occurrence depuis le début de la période, par exemple NthOccurrence = 1, représente la 1ère occurrence du jour de la semaine.

Les valeurs négatives représentent la Nième occurrence à partir de la fin de la période, par exemple NthOccurrence = -1, représente la dernière occurrence du jour de la semaine.

Lorsque NthOccurrence est égal à zéro, il représente toutes les occurrences du jour de la semaine spécifié. Par exemple, BYDAY=MO a NthOccurrence zéro et représente tous les lundis de l'ensemble.

### Voir également

* class [ByDay](../../byday)
* espace de noms [Aspose.Email.Calendar.Recurrences](../../byday)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->