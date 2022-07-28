---
title: MarkAsJunk
second_title: Référence de l'API Aspose.Email pour .NET
description: La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque lexpéditeur du message.
type: docs
weight: 1270
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| isJunk | Boolean | Indique si les messages sont marqués comme courrier indésirable. Si la valeur true ajoute l'expéditeur du message à la liste de blocage. Si la valeur est false, l'expéditeur du message est supprimé de la liste de blocage. |
| messageUriEn | String[] | Tableau d'URI de message |

### Return_Value

Renvoie le tableau des ID de message qui sont déplacés vers le dossier de courrier indésirable.

### Voir également

* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| isJunk | Boolean | Indique si les messages sont marqués comme courrier indésirable. Si la valeur true ajoute l'expéditeur du message à la liste de blocage. Si la valeur est false, l'expéditeur du message est supprimé de la liste de blocage. |
| moveItem | Boolean | Indique si les messages sont déplacés vers le dossier de courrier indésirable. |
| messageUriEn | String[] | Tableau d'URI de message |

### Return_Value

Renvoie le tableau des ID de message qui sont déplacés vers le dossier de courrier indésirable.

### Voir également

* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| isJunk | Boolean | Indique si les messages sont marqués comme courrier indésirable. Si la valeur true ajoute l'expéditeur du message à la liste de blocage. Si la valeur est false, l'expéditeur du message est supprimé de la liste de blocage. |
| messageUriEn | IEnumerable`1 | Énumération des uri de message |

### Return_Value

Renvoie l'ID d'élément du message marqué comme courrier indésirable.

### Voir également

* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| isJunk | Boolean | Indique si les messages sont marqués comme courrier indésirable. Si la valeur true ajoute l'expéditeur du message à la liste de blocage. Si la valeur est false, l'expéditeur du message est supprimé de la liste de blocage. |
| moveItem | Boolean | Indique si les messages sont déplacés vers le dossier de courrier indésirable. |
| messageUriEn | IEnumerable`1 | Énumération des uri de message |

### Return_Value

Renvoie le tableau des ID de message qui sont déplacés vers le dossier de courrier indésirable.

### Voir également

* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| isJunk | Boolean | Indique si les messages sont marqués comme courrier indésirable. Si la valeur true ajoute l'expéditeur du message à la liste de blocage. Si la valeur est false, l'expéditeur du message est supprimé de la liste de blocage. |
| moveItem | Boolean | Indique si les messages sont déplacés vers le dossier de courrier indésirable. |
| messageUriEn | IEnumerable`1 | Énumération des uri de message |
| movedMessageIds | String[]& | Renvoie le tableau des ID de message qui sont déplacés vers le dossier de courrier indésirable. |
| failedMessageIds | String[]& | Renvoie le tableau des ID de message qui n'ont pas été déplacés vers le dossier de courrier indésirable. |
| errorMessages | String[]& | Messages d'erreur pour les opérations ayant échoué |

### Voir également

* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
