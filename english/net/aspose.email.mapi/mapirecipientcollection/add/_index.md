---
title: MapiRecipientCollection.Add
second_title: Aspose.Email for .NET API Reference
description: MapiRecipientCollection method. Adds a recipient
type: docs
weight: 20
url: /net/aspose.email.mapi/mapirecipientcollection/add/
---
## Add(string, string, MapiRecipientType) {#add}

Adds a recipient.

```csharp
public MapiRecipient Add(string address, string displayName, MapiRecipientType recipientType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The e-mail address. |
| displayName | String | The display name. |
| recipientType | MapiRecipientType | The type: To, CC or BCC. |

### Return Value

The new [`MapiRecipient`](../../mapirecipient/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *address* is `null` or empty. |
| ArgumentException | *address* is not valid. |

## Remarks

Adding a recipient also updates [`DisplayTo`](../../mapimessage/displayto/), [`DisplayCc`](../../mapimessage/displaycc/) or [`DisplayBcc`](../../mapimessage/displaybcc/) of the message, depending on the type of the recipient.

### See Also

* class [MapiRecipient](../../mapirecipient/)
* enum [MapiRecipientType](../../mapirecipienttype/)
* class [MapiRecipientCollection](../)
* namespace [Aspose.Email.Mapi](../../mapirecipientcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, string, string, MapiRecipientType) {#add_1}

Adds a recipient with an address of the specified type.

```csharp
public MapiRecipient Add(string address, string addressType, string displayName, 
    MapiRecipientType recipientType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The address. |
| addressType | String | The type of the address, such as `SMTP` or `EX`. |
| displayName | String | The display name. |
| recipientType | MapiRecipientType | The type: To, CC or BCC. |

### Return Value

The new [`MapiRecipient`](../../mapirecipient/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *address* is `null` or empty. |
| ArgumentException | *address* is not valid. |

## Remarks

Adding a recipient also updates [`DisplayTo`](../../mapimessage/displayto/), [`DisplayCc`](../../mapimessage/displaycc/) or [`DisplayBcc`](../../mapimessage/displaybcc/) of the message, depending on the type of the recipient.

### See Also

* class [MapiRecipient](../../mapirecipient/)
* enum [MapiRecipientType](../../mapirecipienttype/)
* class [MapiRecipientCollection](../)
* namespace [Aspose.Email.Mapi](../../mapirecipientcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(MapiRecipient) {#add_2}

Adds an existing recipient to the end of the collection.

```csharp
public void Add(MapiRecipient item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | MapiRecipient | The recipient to add. |

### See Also

* class [MapiRecipient](../../mapirecipient/)
* class [MapiRecipientCollection](../)
* namespace [Aspose.Email.Mapi](../../mapirecipientcollection/)
* assembly [Aspose.Email](../../../)


