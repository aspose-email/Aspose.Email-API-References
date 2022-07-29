---
title: DelegateAccess
second_title: Aspose.Email für .NET-API-Referenz
description: Delegiert den Zugriff auf das Hauptpostfach an den angegebenen Benutzer.
type: docs
weight: 570
url: /de/net/aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/
---
## DelegateAccess(string, ExchangeDelegateFolderPermissionLevel, string) {#delegateaccess_2}

Delegiert den Zugriff auf das Hauptpostfach an den angegebenen Benutzer.

```csharp
public void DelegateAccess(string delegateSmtpAddress, 
    ExchangeDelegateFolderPermissionLevel permissionLevel, string mailbox)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| delegateSmtpAddress | String | Eine primäre SMTP-Adresse des Benutzers. |
| permissionLevel | ExchangeDelegateFolderPermissionLevel | Eine Berechtigungsstufe, die dem Benutzer für alle Ordner gewährt wird. |
| mailbox | String | Ein Postfach, auf das Zugriff gewährt werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *delegateSmtpAddress*oder*mailbox* ist`Null`oder`leer`. |

### Siehe auch

* enum [ExchangeDelegateFolderPermissionLevel](../../exchangedelegatefolderpermissionlevel)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## DelegateAccess(ExchangeDelegateUser, string) {#delegateaccess}

Delegiert den Zugriff auf das angegebene Postfach an den angegebenen Benutzer.

```csharp
public void DelegateAccess(ExchangeDelegateUser delegateUser, string mailbox)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| delegateUser | ExchangeDelegateUser | EIN[`ExchangeDelegateUser`](../../exchangedelegateuser) enthält Benutzerinformationen und Delegierungseinstellungen. |
| mailbox | String | Ein Postfach, auf das Zugriff gewährt werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *delegateUser* ist Null. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *mailbox* ist`Null`oder`leer`. |

### Siehe auch

* class [ExchangeDelegateUser](../../exchangedelegateuser)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## DelegateAccess(ExchangeDelegateUserCollection, string) {#delegateaccess_1}

Delegiert den Zugriff auf das Postfach an die angegebenen Benutzer.

```csharp
public void DelegateAccess(ExchangeDelegateUserCollection delegateUsers, string mailbox)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| delegateUsers | ExchangeDelegateUserCollection | EIN[`ExchangeDelegateUserCollection`](../../exchangedelegateusercollection) enthält die Benutzerinformationen und Delegierungseinstellungen. |
| mailbox | String | Ein Postfach, auf das Zugriff gewährt werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *delegateUsers* ist`Null`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *mailbox* ist`Null`oder`leer`. |

### Siehe auch

* class [ExchangeDelegateUserCollection](../../exchangedelegateusercollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->