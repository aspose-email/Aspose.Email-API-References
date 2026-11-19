---
title: ReferenceAttachmentOptions
second_title: Aspose.Email for Java API Reference
description: Options of a reference attachment a link to a file in a cloud storage such as OneDrive instead of the file itself.
type: docs
weight: 628
url: /java/com.aspose.email/referenceattachmentoptions/
---

**Inheritance:**
java.lang.Object
```
public class ReferenceAttachmentOptions
```

Options of a reference attachment: a link to a file in a cloud storage, such as OneDrive, instead of the file itself.

Pass an instance to [MapiAttachmentCollection.add(String, MapiMessage)](../../com.aspose.email/mapiattachmentcollection\#add-String--MapiMessage-).
## Constructors

| Constructor | Description |
| --- | --- |
| [ReferenceAttachmentOptions(String sharedLink, String url, String providerName)](#ReferenceAttachmentOptions-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [ReferenceAttachmentOptions](../../com.aspose.email/referenceattachmentoptions) class with a link, a URL and a provider. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalPermissionType()](#getOriginalPermissionType--) | Gets the original permission type for the reference attachment. |
| [getPermissionType()](#getPermissionType--) | Gets the permission type for the reference attachment. |
| [getPreviewUrl()](#getPreviewUrl--) | Gets the preview URL of the reference attachment. |
| [getProviderEndpointUrl()](#getProviderEndpointUrl--) | Gets the provider endpoint URL. |
| [getProviderName()](#getProviderName--) | Gets the name of the storage provider, such as  OneDrive . |
| [getSharedLink()](#getSharedLink--) | Gets the shared link of the file in the cloud storage. |
| [getThumbnailUrl()](#getThumbnailUrl--) | Gets the thumbnail URL of the reference attachment. |
| [getUrl()](#getUrl--) | Gets the direct URL of the file. |
| [hashCode()](#hashCode--) |  |
| [isFolder()](#isFolder--) | Gets a value indicating whether the reference attachment is a folder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFolder(boolean value)](#setFolder-boolean-) | Sets a value indicating whether the reference attachment is a folder. |
| [setOriginalPermissionType(int value)](#setOriginalPermissionType-int-) | Sets the original permission type for the reference attachment. |
| [setPermissionType(int value)](#setPermissionType-int-) | Sets the permission type for the reference attachment. |
| [setPreviewUrl(String value)](#setPreviewUrl-java.lang.String-) | Sets the preview URL of the reference attachment. |
| [setProviderEndpointUrl(String value)](#setProviderEndpointUrl-java.lang.String-) | Sets the provider endpoint URL. |
| [setProviderName(String value)](#setProviderName-java.lang.String-) | Sets the name of the storage provider, such as  OneDrive . |
| [setSharedLink(String value)](#setSharedLink-java.lang.String-) | Sets the shared link of the file in the cloud storage. |
| [setThumbnailUrl(String value)](#setThumbnailUrl-java.lang.String-) | Sets the thumbnail URL of the reference attachment. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Sets the direct URL of the file. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReferenceAttachmentOptions(String sharedLink, String url, String providerName) {#ReferenceAttachmentOptions-java.lang.String-java.lang.String-java.lang.String-}
```
public ReferenceAttachmentOptions(String sharedLink, String url, String providerName)
```


Initializes a new instance of the [ReferenceAttachmentOptions](../../com.aspose.email/referenceattachmentoptions) class with a link, a URL and a provider.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sharedLink | java.lang.String | The shared link of the file. |
| url | java.lang.String | The direct URL of the file. |
| providerName | java.lang.String | The name of the storage provider, such as  OneDrive . |

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
### getOriginalPermissionType() {#getOriginalPermissionType--}
```
public final int getOriginalPermissionType()
```


Gets the original permission type for the reference attachment. Used to specify the original permission level before any modifications. The default value is None.

**Returns:**
int
### getPermissionType() {#getPermissionType--}
```
public final int getPermissionType()
```


Gets the permission type for the reference attachment. Indicates the level of access granted. The default value is AnyoneCanEdit.

**Returns:**
int
### getPreviewUrl() {#getPreviewUrl--}
```
public final String getPreviewUrl()
```


Gets the preview URL of the reference attachment. This URL can be used to generate a preview of the resource, if supported by the provider. The default value is Empty.

**Returns:**
java.lang.String
### getProviderEndpointUrl() {#getProviderEndpointUrl--}
```
public final String getProviderEndpointUrl()
```


Gets the provider endpoint URL. Typically used for specifying the base URL of the cloud provider API. The default value is Empty.

**Returns:**
java.lang.String
### getProviderName() {#getProviderName--}
```
public final String getProviderName()
```


Gets the name of the storage provider, such as  OneDrive .

**Returns:**
java.lang.String
### getSharedLink() {#getSharedLink--}
```
public final String getSharedLink()
```


Gets the shared link of the file in the cloud storage.

**Returns:**
java.lang.String
### getThumbnailUrl() {#getThumbnailUrl--}
```
public final String getThumbnailUrl()
```


Gets the thumbnail URL of the reference attachment. The URL points to a thumbnail image of the resource for visual representation. The default value is Empty.

**Returns:**
java.lang.String
### getUrl() {#getUrl--}
```
public final String getUrl()
```


Gets the direct URL of the file.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFolder() {#isFolder--}
```
public final boolean isFolder()
```


Gets a value indicating whether the reference attachment is a folder. The default value is  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFolder(boolean value) {#setFolder-boolean-}
```
public final void setFolder(boolean value)
```


Sets a value indicating whether the reference attachment is a folder. The default value is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setOriginalPermissionType(int value) {#setOriginalPermissionType-int-}
```
public final void setOriginalPermissionType(int value)
```


Sets the original permission type for the reference attachment. Used to specify the original permission level before any modifications. The default value is None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPermissionType(int value) {#setPermissionType-int-}
```
public final void setPermissionType(int value)
```


Sets the permission type for the reference attachment. Indicates the level of access granted. The default value is AnyoneCanEdit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreviewUrl(String value) {#setPreviewUrl-java.lang.String-}
```
public final void setPreviewUrl(String value)
```


Sets the preview URL of the reference attachment. This URL can be used to generate a preview of the resource, if supported by the provider. The default value is Empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setProviderEndpointUrl(String value) {#setProviderEndpointUrl-java.lang.String-}
```
public final void setProviderEndpointUrl(String value)
```


Sets the provider endpoint URL. Typically used for specifying the base URL of the cloud provider API. The default value is Empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setProviderName(String value) {#setProviderName-java.lang.String-}
```
public final void setProviderName(String value)
```


Sets the name of the storage provider, such as  OneDrive .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSharedLink(String value) {#setSharedLink-java.lang.String-}
```
public final void setSharedLink(String value)
```


Sets the shared link of the file in the cloud storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setThumbnailUrl(String value) {#setThumbnailUrl-java.lang.String-}
```
public final void setThumbnailUrl(String value)
```


Sets the thumbnail URL of the reference attachment. The URL points to a thumbnail image of the resource for visual representation. The default value is Empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


Sets the direct URL of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

