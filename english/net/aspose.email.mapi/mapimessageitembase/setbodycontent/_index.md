---
title: MapiMessageItemBase.SetBodyContent
second_title: Aspose.Email for .NET API Reference
description: MapiMessageItemBase method. Sets the body of the item in the specified format
type: docs
weight: 240
url: /net/aspose.email.mapi/mapimessageitembase/setbodycontent/
---
## SetBodyContent(string, BodyContentType) {#setbodycontent}

Sets the body of the item in the specified format.

```csharp
public virtual void SetBodyContent(string content, BodyContentType contentType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The text of the body. |
| contentType | BodyContentType | The format of *content*. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *content* is `null` or empty. |

## Remarks

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, [`BodyRtf`](../bodyrtf/) returns that HTML encapsulated in RTF.

### See Also

* enum [BodyContentType](../../bodycontenttype/)
* class [MapiMessageItemBase](../)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase/)
* assembly [Aspose.Email](../../../)

---

## SetBodyContent(string, BodyContentType, bool) {#setbodycontent_1}

Sets the body of the item in the specified format, optionally compressing it.

```csharp
public virtual void SetBodyContent(string content, BodyContentType contentType, bool compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The text of the body. |
| contentType | BodyContentType | The format of *content*. |
| compression | Boolean | `true` to store the RTF body compressed. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *content* is `null` or empty. |

## Remarks

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, [`BodyRtf`](../bodyrtf/) returns that HTML encapsulated in RTF.

### See Also

* enum [BodyContentType](../../bodycontenttype/)
* class [MapiMessageItemBase](../)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase/)
* assembly [Aspose.Email](../../../)


