---
title: MapiMessageItemBase.SetBodyRtf
second_title: Aspose.Email for .NET API Reference
description: MapiMessageItemBase method. Sets the body of the item in RTF format optionally compressing it
type: docs
weight: 250
url: /net/aspose.email.mapi/mapimessageitembase/setbodyrtf/
---
## MapiMessageItemBase.SetBodyRtf method

Sets the body of the item in RTF format, optionally compressing it.

```csharp
public void SetBodyRtf(string content, bool compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The body in RTF. |
| compression | Boolean | `true` to store the RTF body compressed. |

## Remarks

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use [`SetBodyContent`](../setbodycontent/). Setting `null` or an empty string clears both bodies.

### See Also

* class [MapiMessageItemBase](../)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase/)
* assembly [Aspose.Email](../../../)


