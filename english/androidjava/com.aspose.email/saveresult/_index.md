---
title: SaveResult
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the result of saving the retrieved item.
type: docs
weight: 376
url: /java/com.aspose.email/saveresult/
---
**Inheritance:**
java.lang.Object
```
public class SaveResult
```

Represents the result of saving the retrieved item.
## Methods

| Method | Description |
| --- | --- |
| [getStatus()](#getStatus--) | Gets the saving status. |
| [getMissedProperties()](#getMissedProperties--) | Gets the collection of missed properties. |
| [getAttachments()](#getAttachments--) | Gets the save results of attachments. |
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets the saving status.

Value: The [SaveStatus](../../com.aspose.email/savestatus).

**Returns:**
int
### getMissedProperties() {#getMissedProperties--}
```
public final List<PropertyDescriptor> getMissedProperties()
```


Gets the collection of missed properties.

Value: The list of [PropertyDescriptor](../../com.aspose.email/propertydescriptor).

**Returns:**
java.util.List<com.aspose.email.PropertyDescriptor>
### getAttachments() {#getAttachments--}
```
public final List<SaveResult> getAttachments()
```


Gets the save results of attachments.

Value: The list of [SaveResult](../../com.aspose.email/saveresult).

**Returns:**
java.util.List<com.aspose.email.SaveResult>
