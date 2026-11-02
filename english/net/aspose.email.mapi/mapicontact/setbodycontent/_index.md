---
title: MapiContact.SetBodyContent
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Sets the content of the body
type: docs
weight: 180
url: /net/aspose.email.mapi/mapicontact/setbodycontent/
---
## MapiContact.SetBodyContent method

Sets the content of the body.

```csharp
public override void SetBodyContent(string content, BodyContentType contentType)
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

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR_RTF_COMPRESSED, PR_RTF_DECOMPRESSES, PR_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF.

### See Also

* enum [BodyContentType](../../bodycontenttype/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


