---
title: PersonalStorageLoadOptions
second_title: Aspose.Email for Java API Reference
description:  Specifies additional options when loading a PST storage.
type: docs
weight: 553
url: /java/com.aspose.email/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object
```
public class PersonalStorageLoadOptions
```

Specifies additional options when loading a PST storage.
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWritable()](#getWritable--) | Gets or sets a value indicating whether the pst is writable. |
| [setWritable(boolean value)](#setWritable-boolean-) | Gets or sets a value indicating whether the pst is writable. |
| [getLeaveStreamOpen()](#getLeaveStreamOpen--) | Leave stream open when PersonalStorage is disposed. |
| [setLeaveStreamOpen(boolean value)](#setLeaveStreamOpen-boolean-) | Leave stream open when PersonalStorage is disposed. |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


### getWritable() {#getWritable--}
```
public final boolean getWritable()
```


Gets or sets a value indicating whether the pst is writable. By default the value is true.

Value: \`\`\` true \`\`\` if writable; otherwise, \`\`\` false \`\`\`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public final void setWritable(boolean value)
```


Gets or sets a value indicating whether the pst is writable. By default the value is true.

Value: \`\`\` true \`\`\` if writable; otherwise, \`\`\` false \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLeaveStreamOpen() {#getLeaveStreamOpen--}
```
public final boolean getLeaveStreamOpen()
```


Leave stream open when PersonalStorage is disposed. Should always be false when [PersonalStorage\#fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String-PersonalStorageLoadOptions-) method is used. By default the value is false.

**Returns:**
boolean
### setLeaveStreamOpen(boolean value) {#setLeaveStreamOpen-boolean-}
```
public final void setLeaveStreamOpen(boolean value)
```


Leave stream open when PersonalStorage is disposed. Should always be false when [PersonalStorage\#fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String-PersonalStorageLoadOptions-) method is used. By default the value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

