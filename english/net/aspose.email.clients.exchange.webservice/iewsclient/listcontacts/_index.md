---
title: IEWSClient.ListContacts
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Lists contacts located in the specified folder on server
type: docs
weight: 1090
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listcontacts/
---
## ListContacts(string) {#listcontacts}

Lists contacts located in the specified folder on server

```csharp
public MapiContact[] ListContacts(string folderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The URI of folder |

### Return Value

An array of read [`MapiContact`](../../../aspose.email.mapi/mapicontact/) that represents contact information

### See Also

* class [MapiContact](../../../aspose.email.mapi/mapicontact/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListContacts(string, IEnumerable&lt;PropertyDescriptor&gt;) {#listcontacts_1}

Lists contacts located in the specified folder on server

```csharp
public MapiContact[] ListContacts(string folderUri, IEnumerable<PropertyDescriptor> mapiProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | A folder to search contacts in |
| mapiProperties | IEnumerable`1 | Required additional mapi properties |

### Return Value

An array of read [`MapiContact`](../../../aspose.email.mapi/mapicontact/) that represents contact information

### See Also

* class [MapiContact](../../../aspose.email.mapi/mapicontact/)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


