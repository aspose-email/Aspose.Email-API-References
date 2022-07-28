---
title: FreebusyQuery
second_title: Référence de l'API Aspose.Email pour .NET
description: Initialise une nouvelle instance de la classe FreebusyQuery.
type: docs
weight: 10
url: /fr/net/aspose.email.clients.google/freebusyquery/freebusyquery/
---
## FreebusyQuery() {#constructor}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery()
```

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, IEnumerable&lt;string&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, IEnumerable<string> items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| items | IEnumerable`1 | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, string, IEnumerable&lt;string&gt;) {#constructor_2}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, string timeZone, IEnumerable<string> items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| timeZone | String | Fuseau horaire utilisé dans la réponse. Optionnel. La valeur par défaut est UTC. |
| items | IEnumerable`1 | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, string, int?, int?, IEnumerable&lt;string&gt;) {#constructor_3}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, string timeZone, int? groupExpansionMax, 
    int? calendarExpansionMax, IEnumerable<string> items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| timeZone | String | Fuseau horaire utilisé dans la réponse. Optionnel. La valeur par défaut est UTC. |
| groupExpansionMax | Nullable`1 | Nombre maximal d'identifiants de calendrier à fournir pour un seul groupe. Optionnel. Une erreur sera renvoyée pour un groupe avec plus de membres que cette valeur. |
| calendarExpansionMax | Nullable`1 | Nombre maximal d'agendas pour lesquels des informations FreeBusy doivent être fournies. Facultatif. |
| items | IEnumerable`1 | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, params string[]) {#constructor_6}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, params string[] items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| items | String[] | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, string, params string[]) {#constructor_5}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, string timeZone, params string[] items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| timeZone | String | Fuseau horaire utilisé dans la réponse. Optionnel. La valeur par défaut est UTC. |
| items | String[] | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

---

## FreebusyQuery(DateTime, DateTime, string, int?, int?, params string[]) {#constructor_4}

Initialise une nouvelle instance de la classe FreebusyQuery.

```csharp
public FreebusyQuery(DateTime timeMin, DateTime timeMax, string timeZone, int? groupExpansionMax, 
    int? calendarExpansionMax, params string[] items)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| timeMin | DateTime | La fin de l'intervalle pour la requête. |
| timeMax | DateTime | La fin de l'intervalle pour la requête. |
| timeZone | String | Fuseau horaire utilisé dans la réponse. Optionnel. La valeur par défaut est UTC. |
| groupExpansionMax | Nullable`1 | Nombre maximal d'identifiants de calendrier à fournir pour un seul groupe. Optionnel. Une erreur sera renvoyée pour un groupe avec plus de membres que cette valeur. |
| calendarExpansionMax | Nullable`1 | Nombre maximal d'agendas pour lesquels des informations FreeBusy doivent être fournies. Facultatif. |
| items | String[] | Liste des agendas et/ou groupes à interroger. Contient les identifiants d'un agenda ou d'un groupe. |

### Voir également

* class [FreebusyQuery](../../freebusyquery)
* espace de noms [Aspose.Email.Clients.Google](../../freebusyquery)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
