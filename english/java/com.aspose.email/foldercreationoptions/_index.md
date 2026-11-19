---
title: FolderCreationOptions
second_title: Aspose.Email for Java API Reference
description: Options for creating a subfolder with FolderInfo.addSubFolder whether the name is a path how names are compared and the container class of the new folder.
type: docs
weight: 259
url: /java/com.aspose.email/foldercreationoptions/
---

**Inheritance:**
java.lang.Object
```
public class FolderCreationOptions
```

Options for creating a subfolder with  FolderInfo.addSubFolder : whether the name is a path, how names are compared, and the container class of the new folder.
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderCreationOptions()](#FolderCreationOptions--) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the default settings: the name is not a path, names are compared case-insensitively, and the container class is  IPF.Note . |
| [FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference)](#FolderCreationOptions-boolean-boolean-) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters. |
| [FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference, String containerClass)](#FolderCreationOptions-boolean-boolean-java.lang.String-) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNameCaseDifference()](#getAllowNameCaseDifference--) | Gets a value indicating whether to allow a difference in name casing when comparing folder names. |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets the container class of the new folder, which defines the kind of items it holds, for example  IPF.Note  for mail or  IPF.Appointment  for a calendar. |
| [getCreateHierarchy()](#getCreateHierarchy--) | Gets a value indicating whether to create the hierarchy of parent folders. |
| [getEnforceContainerClassMatching()](#getEnforceContainerClassMatching--) | Gets a value indicating whether the container class of the new folder must match the container class of its parent folder. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNameCaseDifference(boolean value)](#setAllowNameCaseDifference-boolean-) | Sets a value indicating whether to allow a difference in name casing when comparing folder names. |
| [setContainerClass(String value)](#setContainerClass-java.lang.String-) | Sets the container class of the new folder, which defines the kind of items it holds, for example  IPF.Note  for mail or  IPF.Appointment  for a calendar. |
| [setCreateHierarchy(boolean value)](#setCreateHierarchy-boolean-) | Sets a value indicating whether to create the hierarchy of parent folders. |
| [setEnforceContainerClassMatching(boolean value)](#setEnforceContainerClassMatching-boolean-) | Sets a value indicating whether the container class of the new folder must match the container class of its parent folder. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderCreationOptions() {#FolderCreationOptions--}
```
public FolderCreationOptions()
```


Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the default settings: the name is not a path, names are compared case-insensitively, and the container class is  IPF.Note .

### FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference) {#FolderCreationOptions-boolean-boolean-}
```
public FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference)
```


Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createHierarchy | boolean | A value indicating whether to create the hierarchy of parent folders if they don't exist. |
| allowNameCaseDifference | boolean | A value indicating whether to allow a difference in name casing when comparing folder names. |

### FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference, String containerClass) {#FolderCreationOptions-boolean-boolean-java.lang.String-}
```
public FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference, String containerClass)
```


Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createHierarchy | boolean | A value indicating whether to create the hierarchy of parent folders if they don't exist. |
| allowNameCaseDifference | boolean | A value indicating whether to allow a difference in name casing when comparing folder names. |
| containerClass | java.lang.String | The container class for the new subfolder. |

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
### getAllowNameCaseDifference() {#getAllowNameCaseDifference--}
```
public final boolean getAllowNameCaseDifference()
```


Gets a value indicating whether to allow a difference in name casing when comparing folder names.

When  true , a folder whose name differs from an existing one only in case is created as a separate folder. When  false , names are compared case-insensitively, and adding a folder whose name matches an existing one throws  IllegalStateException .

**Returns:**
boolean -  true  if a difference in name casing should be allowed when comparing folder names; otherwise,  false . The default value is  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerClass() {#getContainerClass--}
```
public final String getContainerClass()
```


Gets the container class of the new folder, which defines the kind of items it holds, for example  IPF.Note  for mail or  IPF.Appointment  for a calendar.

The default is  IPF.Note .

**Returns:**
java.lang.String
### getCreateHierarchy() {#getCreateHierarchy--}
```
public final boolean getCreateHierarchy()
```


Gets a value indicating whether to create the hierarchy of parent folders.

Separate the folder names in the path with a backslash, for example  Parent1\\Parent2\\Subfolder .

**Returns:**
boolean -  true  if the hierarchy of parent folders should be created. In this case, the name of the subfolder to be created is considered as path;  false  if only the subfolder with specified name should be created. The default value is  false .
### getEnforceContainerClassMatching() {#getEnforceContainerClassMatching--}
```
public final boolean getEnforceContainerClassMatching()
```


Gets a value indicating whether the container class of the new folder must match the container class of its parent folder.

When  true , adding a folder whose container class differs from that of the parent folder throws  IllegalStateException .

**Returns:**
boolean -  true  to require matching container classes; otherwise,  false . The default is  false .
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




### setAllowNameCaseDifference(boolean value) {#setAllowNameCaseDifference-boolean-}
```
public final void setAllowNameCaseDifference(boolean value)
```


Sets a value indicating whether to allow a difference in name casing when comparing folder names.

When  true , a folder whose name differs from an existing one only in case is created as a separate folder. When  false , names are compared case-insensitively, and adding a folder whose name matches an existing one throws  IllegalStateException .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if a difference in name casing should be allowed when comparing folder names; otherwise,  false . The default value is  false . |

### setContainerClass(String value) {#setContainerClass-java.lang.String-}
```
public final void setContainerClass(String value)
```


Sets the container class of the new folder, which defines the kind of items it holds, for example  IPF.Note  for mail or  IPF.Appointment  for a calendar.

The default is  IPF.Note .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCreateHierarchy(boolean value) {#setCreateHierarchy-boolean-}
```
public final void setCreateHierarchy(boolean value)
```


Sets a value indicating whether to create the hierarchy of parent folders.

Separate the folder names in the path with a backslash, for example  Parent1\\Parent2\\Subfolder .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if the hierarchy of parent folders should be created. In this case, the name of the subfolder to be created is considered as path;  false  if only the subfolder with specified name should be created. The default value is  false . |

### setEnforceContainerClassMatching(boolean value) {#setEnforceContainerClassMatching-boolean-}
```
public final void setEnforceContainerClassMatching(boolean value)
```


Sets a value indicating whether the container class of the new folder must match the container class of its parent folder.

When  true , adding a folder whose container class differs from that of the parent folder throws  IllegalStateException .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to require matching container classes; otherwise,  false . The default is  false . |

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

