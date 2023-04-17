---
title: IEWSClient.DelegateAccess
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Delegates access on the principal mailbox to the specified user
type: docs
weight: 570
url: /net/aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/
---
## DelegateAccess(string, ExchangeDelegateFolderPermissionLevel, string) {#delegateaccess_2}

Delegates access on the principal mailbox to the specified user.

```csharp
public void DelegateAccess(string delegateSmtpAddress, 
    ExchangeDelegateFolderPermissionLevel permissionLevel, string mailbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| delegateSmtpAddress | String | A primary smtp address of user. |
| permissionLevel | ExchangeDelegateFolderPermissionLevel | A permission level that is granted to the user on all folders. |
| mailbox | String | A mailbox to grant access on. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *delegateSmtpAddress* or *mailbox* is `null` or `empty`. |

### See Also

* enum [ExchangeDelegateFolderPermissionLevel](../../exchangedelegatefolderpermissionlevel/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DelegateAccess(ExchangeDelegateUser, string) {#delegateaccess}

Delegates access on the specified mailbox to the specified user.

```csharp
public void DelegateAccess(ExchangeDelegateUser delegateUser, string mailbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| delegateUser | ExchangeDelegateUser | A [`ExchangeDelegateUser`](../../exchangedelegateuser/) containing user information and delegation settings. |
| mailbox | String | A mailbox to grant access on. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *delegateUser* is null. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *mailbox* is `null` or `empty`. |

### See Also

* class [ExchangeDelegateUser](../../exchangedelegateuser/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DelegateAccess(ExchangeDelegateUserCollection, string) {#delegateaccess_1}

Delegates access on the mailbox to the specified users.

```csharp
public void DelegateAccess(ExchangeDelegateUserCollection delegateUsers, string mailbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| delegateUsers | ExchangeDelegateUserCollection | A [`ExchangeDelegateUserCollection`](../../exchangedelegateusercollection/) containing the users information and delegation settings. |
| mailbox | String | A mailbox to grant access on. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *delegateUsers* is `null`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *mailbox* is `null` or `empty`. |

### See Also

* class [ExchangeDelegateUserCollection](../../exchangedelegateusercollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


