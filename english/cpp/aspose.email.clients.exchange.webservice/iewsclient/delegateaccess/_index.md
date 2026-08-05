---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::DelegateAccess method"
linktitle: "DelegateAccess"
articleTitle: "DelegateAccess"
second_title: "Aspose.Email for C++"
description: "Delegates access on the specified mailbox to the specified user."
type: docs
weight: 230
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/
---

## DelegateAccess (1 of 3) {#delegateaccess_1}

Delegates access on the specified mailbox to the specified user.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
DelegateAccess(System::SharedPtr < ExchangeDelegateUser > delegateUser, System::String mailbox)
```

| Parameter | Description |
| --- | --- |
| delegateUser | A ExchangeDelegateUser containing user information and delegation settings. |
| mailbox | A mailbox to grant access on. |

---

## DelegateAccess (2 of 3) {#delegateaccess_2}

Delegates access on the mailbox to the specified users.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
DelegateAccess(System::SharedPtr < ExchangeDelegateUserCollection > delegateUsers, System::String mailbox)
```

| Parameter | Description |
| --- | --- |
| delegateUsers | A ExchangeDelegateUserCollection containing the users information and delegation settings. |
| mailbox | A mailbox to grant access on. |

---

## DelegateAccess (3 of 3) {#delegateaccess_3}

Delegates access on the principal mailbox to the specified user.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
DelegateAccess(System::String delegateSmtpAddress, ExchangeDelegateFolderPermissionLevel permissionLevel, System::String mailbox)
```

| Parameter | Description |
| --- | --- |
| delegateSmtpAddress | A primary smtp address of user. |
| permissionLevel | A permission level that is granted to the user on all folders. |
| mailbox | A mailbox to grant access on. |

