---
title: TgzBackupBuilder
second_title: Aspose.Email for Java API Reference
description: Scans a directory tree of EML files and writes them into a GZip-compressed TAR archive in the format required by Zimbras mailbox import tool zmmailbox importMailbox.
type: docs
weight: 717
url: /java/com.aspose.email/tgzbackupbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TgzBackupBuilder
```

Scans a directory tree of EML files and writes them into a GZip-compressed TAR archive in the format required by Zimbra's mailbox import tool ( zmmailbox importMailbox ).

--------------------

Each EML file is stored together with a companion  .meta  JSON file that carries the Zimbra-specific metadata (item id, folder path, flags, sender, digest, etc.). The relative sub-folder structure of the source directory is preserved inside the archive so that messages end up in the correct Zimbra folders after import.
## Constructors

| Constructor | Description |
| --- | --- |
| [TgzBackupBuilder()](#TgzBackupBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [build(String inputDirectory, String outputArchive, String rootFolderName)](#build-java.lang.String-java.lang.String-java.lang.String-) | Scans  inputDirectory  recursively for  \*.eml  files and packages them into a Zimbra-importable TGZ archive at  outputArchive . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TgzBackupBuilder() {#TgzBackupBuilder--}
```
public TgzBackupBuilder()
```


### build(String inputDirectory, String outputArchive, String rootFolderName) {#build-java.lang.String-java.lang.String-java.lang.String-}
```
public static BuildResult build(String inputDirectory, String outputArchive, String rootFolderName)
```


Scans  inputDirectory  recursively for  \*.eml  files and packages them into a Zimbra-importable TGZ archive at  outputArchive .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputDirectory | java.lang.String | Absolute or relative path to the folder that contains the source EML files. Sub-folders are included and their relative paths are preserved inside the archive. |
| outputArchive | java.lang.String | Path of the  .tgz  file to create. The file is overwritten if it already exists. The parent directory must exist before calling this method. |
| rootFolderName | java.lang.String | Name of the top-level folder inside the archive (e.g.  "Imported" ). This becomes the Zimbra mailbox root that all messages are imported under.

--------------------

For every EML file the method writes two entries into the TAR stream in this order:

1.  A  .meta  JSON file with Zimbra metadata (date, subject, sender, digest, etc.).
2.  The normalised EML file itself.

Files that cannot be parsed are skipped; the error is recorded in  BuildResult.Errors ([BuildResult.getErrors](../../com.aspose.email/buildresult\#getErrors)/ ). |

**Returns:**
[BuildResult](../../com.aspose.email/buildresult) - A [BuildResult](../../com.aspose.email/buildresult) with the count of successfully written messages and a list of any per-file errors.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

