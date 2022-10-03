---
title: StorageProcessedEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event
type: docs
weight: 648
url: /java/com.aspose.email/storageprocessedeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class StorageProcessedEventArgs extends System.EventArgs
```

Provides data for the [PersonalStorage.StorageProcessedDelegate](../../com.aspose.email/personalstorage\#StorageProcessedDelegate) event
## Methods

| Method | Description |
| --- | --- |
| [getChunk()](#getChunk--) | Gets the pst that represents the chunk. |
| [getFileName()](#getFileName--) | Gets the name of the pst file, that represents the chunk. |
### getChunk() {#getChunk--}
```
public final PersonalStorage getChunk()
```


Gets the pst that represents the chunk.

Value: The chunk.

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage)
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the name of the pst file, that represents the chunk.

Value: The name of the file.

**Returns:**
java.lang.String
