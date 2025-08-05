---
title: GraphNotebook
second_title: Aspose.Email for Java API Reference
description: ... A OneNote notebook.
type: docs
weight: 295
url: /java/com.aspose.email/graphnotebook/
---

**Inheritance:**
java.lang.Object
```
public class GraphNotebook
```

[...][] A OneNote notebook.


[...]: https://docs.microsoft.com/en-us/graph/api/resources/notebook?view=graph-rest-1.0
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphNotebook()](#GraphNotebook--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJsonArray(JSONObject jsonValue, int resource, String resourceId)](#fromJsonArray-com.aspose.json.JSONObject-int-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getCreatedBy()](#getCreatedBy--) | Identity of the user, device, and application which created the item. |
| [getCreatedDateTime()](#getCreatedDateTime--) | The date and time when the notebook was created. |
| [getDisplayName()](#getDisplayName--) | The name of the notebook. |
| [getId()](#getId--) | The unique identifier of the notebook. |
| [getLastModifiedBy()](#getLastModifiedBy--) | Identity of the user, device, and application which created the item. |
| [getLastModifiedDateTime()](#getLastModifiedDateTime--) | The date and time when the notebook was last modified. |
| [getLinks()](#getLinks--) | Links for opening the notebook. |
| [getSectionGroupsUrl()](#getSectionGroupsUrl--) | The URL for the sectionGroups navigation property, which returns all the section groups in the notebook. |
| [getSectionsUrl()](#getSectionsUrl--) | The URL for the sections navigation property, which returns all the sections in the notebook. |
| [getSelf()](#getSelf--) | The endpoint where you can get details about the notebook. |
| [getUserRole()](#getUserRole--) | Possible values are: Owner, Contributor, Reader, None. |
| [hashCode()](#hashCode--) |  |
| [isDefault()](#isDefault--) | Indicates whether this is the user's default notebook. |
| [isShared()](#isShared--) | Indicates whether the notebook is shared. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | The name of the notebook. |
| [setLinks(GraphNotebookLinks value)](#setLinks-com.aspose.email.GraphNotebookLinks-) | Links for opening the notebook. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphNotebook() {#GraphNotebook--}
```
public GraphNotebook()
```


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
### fromJsonArray(JSONObject jsonValue, int resource, String resourceId) {#fromJsonArray-com.aspose.json.JSONObject-int-java.lang.String-}
```
public static GraphNotebookCollection fromJsonArray(JSONObject jsonValue, int resource, String resourceId)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonValue | com.aspose.json.JSONObject |  |
| resource | int |  |
| resourceId | java.lang.String |  |

**Returns:**
[GraphNotebookCollection](../../com.aspose.email/graphnotebookcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreatedBy() {#getCreatedBy--}
```
public final GraphIdentitySet getCreatedBy()
```


Identity of the user, device, and application which created the item. Read-only.

**Returns:**
[GraphIdentitySet](../../com.aspose.email/graphidentityset)
### getCreatedDateTime() {#getCreatedDateTime--}
```
public final System.DateTimeOffset getCreatedDateTime()
```


The date and time when the notebook was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Read-only.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


The name of the notebook.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final String getId()
```


The unique identifier of the notebook. Read-only.

**Returns:**
java.lang.String
### getLastModifiedBy() {#getLastModifiedBy--}
```
public final GraphIdentitySet getLastModifiedBy()
```


Identity of the user, device, and application which created the item. Read-only.

**Returns:**
[GraphIdentitySet](../../com.aspose.email/graphidentityset)
### getLastModifiedDateTime() {#getLastModifiedDateTime--}
```
public final System.DateTimeOffset getLastModifiedDateTime()
```


The date and time when the notebook was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Read-only.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### getLinks() {#getLinks--}
```
public final GraphNotebookLinks getLinks()
```


Links for opening the notebook. The oneNoteClientURL link opens the notebook in the OneNote native client if it's installed. The oneNoteWebURL link opens the notebook in OneNote on the web.

**Returns:**
[GraphNotebookLinks](../../com.aspose.email/graphnotebooklinks)
### getSectionGroupsUrl() {#getSectionGroupsUrl--}
```
public final String getSectionGroupsUrl()
```


The URL for the sectionGroups navigation property, which returns all the section groups in the notebook. Read-only.

**Returns:**
java.lang.String
### getSectionsUrl() {#getSectionsUrl--}
```
public final String getSectionsUrl()
```


The URL for the sections navigation property, which returns all the sections in the notebook. Read-only.

**Returns:**
java.lang.String
### getSelf() {#getSelf--}
```
public final String getSelf()
```


The endpoint where you can get details about the notebook. Read-only.

**Returns:**
java.lang.String
### getUserRole() {#getUserRole--}
```
public final int getUserRole()
```


Possible values are: Owner, Contributor, Reader, None. Owner represents owner-level access to the notebook. Contributor represents read/write access to the notebook. Reader represents read-only access to the notebook. Read-only.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefault() {#isDefault--}
```
public final Boolean isDefault()
```


Indicates whether this is the user's default notebook. Read-only.

**Returns:**
java.lang.Boolean
### isShared() {#isShared--}
```
public final Boolean isShared()
```


Indicates whether the notebook is shared. If true, the contents of the notebook can be seen by people other than the owner. Read-only.

**Returns:**
java.lang.Boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


The name of the notebook.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLinks(GraphNotebookLinks value) {#setLinks-com.aspose.email.GraphNotebookLinks-}
```
public final void setLinks(GraphNotebookLinks value)
```


Links for opening the notebook. The oneNoteClientURL link opens the notebook in the OneNote native client if it's installed. The oneNoteWebURL link opens the notebook in OneNote on the web.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphNotebookLinks](../../com.aspose.email/graphnotebooklinks) |  |

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

