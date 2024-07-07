---
title: FolderCreationOptions
second_title: Aspose.Email for Java API Reference
description: Represents the options for creating  a subfolder in the Outlook PST message store.
type: docs
weight: 256
url: /java/com.aspose.email/foldercreationoptions/
---

**Inheritance:**
java.lang.Object
```
public class FolderCreationOptions
```

Represents the options for creating a subfolder in the Outlook PST message store. This class serves as a container for configuring specific settings related to the creation of subfolders.
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderCreationOptions()](#FolderCreationOptions--) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with default values. |
| [FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference)](#FolderCreationOptions-boolean-boolean-) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters. |
| [FolderCreationOptions(boolean createHierarchy, boolean allowNameCaseDifference, String containerClass)](#FolderCreationOptions-boolean-boolean-java.lang.String-) | Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with the specified parameters. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNameCaseDifference()](#getAllowNameCaseDifference--) | Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names. |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets or sets the container class for the new subfolder. |
| [getCreateHierarchy()](#getCreateHierarchy--) | Gets or sets a value indicating whether to create the hierarchy of parent folders. |
| [getEnforceContainerClassMatching()](#getEnforceContainerClassMatching--) | Gets or sets a value indicating whether to enforce container class checking. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNameCaseDifference(boolean value)](#setAllowNameCaseDifference-boolean-) | Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names. |
| [setContainerClass(String value)](#setContainerClass-java.lang.String-) | Gets or sets the container class for the new subfolder. |
| [setCreateHierarchy(boolean value)](#setCreateHierarchy-boolean-) | Gets or sets a value indicating whether to create the hierarchy of parent folders. |
| [setEnforceContainerClassMatching(boolean value)](#setEnforceContainerClassMatching-boolean-) | Gets or sets a value indicating whether to enforce container class checking. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderCreationOptions() {#FolderCreationOptions--}
```
public FolderCreationOptions()
```


Initializes a new instance of the [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) class with default values.

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


Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names.

Value:  true  if a difference in name casing should be allowed when comparing folder names; otherwise,  false . The default value is  false .

--------------------

If a folder with the same name already exists when adding a new folder and  AllowNameCaseDifference (\#getAllowNameCaseDifference.getAllowNameCaseDifference/\#setAllowNameCaseDifference(boolean).setAllowNameCaseDifference(boolean)) is set to  true , the folder names will be treated as different even if the casing differs. In this case, no exception will be thrown, and the folder will be added. When  AllowNameCaseDifference (\#getAllowNameCaseDifference.getAllowNameCaseDifference/\#setAllowNameCaseDifference(boolean).setAllowNameCaseDifference(boolean)) is set to  false , the comparison will be case-insensitive, and the folder creation operation will consider folders with the same name but different casing as duplicates, throwing an InvalidOperationException to indicate that a folder with the specified name already exists.

**Returns:**
boolean
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


Gets or sets the container class for the new subfolder.

--------------------

The container class represents the message class of the new subfolder. The default value is "IPF.Note".

**Returns:**
java.lang.String
### getCreateHierarchy() {#getCreateHierarchy--}
```
public final boolean getCreateHierarchy()
```


Gets or sets a value indicating whether to create the hierarchy of parent folders.

Value:  true  if the hierarchy of parent folders should be created. In this case, the name of the subfolder to be created is considered as path;  false  if only the subfolder with specified name should be created. The default value is  false .

--------------------

When specifying the subfolder path, use the backslash (\\) as the separator between folder names. For example, "parent1\\parent2\\subfolder".

**Returns:**
boolean
### getEnforceContainerClassMatching() {#getEnforceContainerClassMatching--}
```
public final boolean getEnforceContainerClassMatching()
```


Gets or sets a value indicating whether to enforce container class checking.

Value: True if container class checking should be enforced; otherwise, false. Default is false.

--------------------

Specifies whether to enforce checking the container class of the folder being added against the container class of the parent folder. If set to true, an exception will be thrown if the container classes do not match.

**Returns:**
boolean
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


Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names.

Value:  true  if a difference in name casing should be allowed when comparing folder names; otherwise,  false . The default value is  false .

--------------------

If a folder with the same name already exists when adding a new folder and  AllowNameCaseDifference (\#getAllowNameCaseDifference.getAllowNameCaseDifference/\#setAllowNameCaseDifference(boolean).setAllowNameCaseDifference(boolean)) is set to  true , the folder names will be treated as different even if the casing differs. In this case, no exception will be thrown, and the folder will be added. When  AllowNameCaseDifference (\#getAllowNameCaseDifference.getAllowNameCaseDifference/\#setAllowNameCaseDifference(boolean).setAllowNameCaseDifference(boolean)) is set to  false , the comparison will be case-insensitive, and the folder creation operation will consider folders with the same name but different casing as duplicates, throwing an InvalidOperationException to indicate that a folder with the specified name already exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setContainerClass(String value) {#setContainerClass-java.lang.String-}
```
public final void setContainerClass(String value)
```


Gets or sets the container class for the new subfolder.

--------------------

The container class represents the message class of the new subfolder. The default value is "IPF.Note".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCreateHierarchy(boolean value) {#setCreateHierarchy-boolean-}
```
public final void setCreateHierarchy(boolean value)
```


Gets or sets a value indicating whether to create the hierarchy of parent folders.

Value:  true  if the hierarchy of parent folders should be created. In this case, the name of the subfolder to be created is considered as path;  false  if only the subfolder with specified name should be created. The default value is  false .

--------------------

When specifying the subfolder path, use the backslash (\\) as the separator between folder names. For example, "parent1\\parent2\\subfolder".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnforceContainerClassMatching(boolean value) {#setEnforceContainerClassMatching-boolean-}
```
public final void setEnforceContainerClassMatching(boolean value)
```


Gets or sets a value indicating whether to enforce container class checking.

Value: True if container class checking should be enforced; otherwise, false. Default is false.

--------------------

Specifies whether to enforce checking the container class of the folder being added against the container class of the parent folder. If set to true, an exception will be thrown if the container classes do not match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

