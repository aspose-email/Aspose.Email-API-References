---
title: MapiMessageItemBase.Subject
second_title: Aspose.Email for .NET API Reference
description: MapiMessageItemBase property. Gets or sets the subject of the message
type: docs
weight: 170
url: /net/aspose.email.mapi/mapimessageitembase/subject/
---
## MapiMessageItemBase.Subject property

Gets or sets the subject of the message.

```csharp
public string Subject { get; set; }
```

### Property Value

The string that represents message subject.

## Remarks

When setting a value, the values of SubjectPrefix(PR_SUBJECT_PREFIX) and NormalizedSubject(PR_NORMALIZED_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

### See Also

* class [MapiMessageItemBase](../)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase/)
* assembly [Aspose.Email](../../../)


