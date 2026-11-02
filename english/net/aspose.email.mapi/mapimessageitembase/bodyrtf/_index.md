---
title: MapiMessageItemBase.BodyRtf
second_title: Aspose.Email for .NET API Reference
description: MapiMessageItemBase property. Gets or sets the body of the item in RTF format
type: docs
weight: 50
url: /net/aspose.email.mapi/mapimessageitembase/bodyrtf/
---
## MapiMessageItemBase.BodyRtf property

Gets or sets the body of the item in RTF format.

```csharp
public string BodyRtf { get; set; }
```

### Property Value

The RTF body.

## Remarks

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use [`SetBodyContent`](../setbodycontent/), which encapsulates HTML in RTF as Outlook does. Setting `null` or an empty string clears both bodies.

### See Also

* class [MapiMessageItemBase](../)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase/)
* assembly [Aspose.Email](../../../)


