---
title: ImapClient.SetQuotaAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Sets quota information
type: docs
weight: 1150
url: /net/aspose.email.clients.imap/imapclient/setquotaasync/
---
## SetQuotaAsync(IConnection, string, string, int) {#setquotaasync}

Sets quota information

```csharp
public Task<ImapQuota[]> SetQuotaAsync(IConnection connection, string quotaRootName, 
    string resourceName, int resourceLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| quotaRootName | String | quota root name |
| resourceName | String | resource name |
| resourceLimit | Int32 | resource limit |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapQuota](../../imapquota/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SetQuotaAsync(string, string, int) {#setquotaasync_2}

Sets quota information

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, int resourceLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| quotaRootName | String | quota root name |
| resourceName | String | resource name |
| resourceLimit | Int32 | resource limit |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapQuota](../../imapquota/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SetQuotaAsync(IConnection, string, string, int, CancellationToken) {#setquotaasync_1}

Sets quota information

```csharp
public Task<ImapQuota[]> SetQuotaAsync(IConnection connection, string quotaRootName, 
    string resourceName, int resourceLimit, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| quotaRootName | String | quota root name |
| resourceName | String | resource name |
| resourceLimit | Int32 | resource limit |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapQuota](../../imapquota/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SetQuotaAsync(string, string, int, CancellationToken) {#setquotaasync_3}

Sets quota information

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, 
    int resourceLimit, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| quotaRootName | String | quota root name |
| resourceName | String | resource name |
| resourceLimit | Int32 | resource limit |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapQuota](../../imapquota/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


