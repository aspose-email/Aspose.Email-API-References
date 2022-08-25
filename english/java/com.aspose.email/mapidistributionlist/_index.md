---
title: MapiDistributionList
second_title: Aspose.Email for Java API Reference
description:  Represents the Personal Distribution List object.
type: docs
weight: 432
url: /java/com.aspose.email/mapidistributionlist/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiDistributionList extends MapiMessageItemBase
```

Represents the Personal Distribution List object.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiDistributionList()](#MapiDistributionList--) | Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class. |
| [MapiDistributionList(String displayName, MapiDistributionListMemberCollection members)](#MapiDistributionList-java.lang.String-com.aspose.email.MapiDistributionListMemberCollection-) | Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMembers()](#getMembers--) | Gets the list of the members of the personal distribution list. |
| [getDisplayName()](#getDisplayName--) | Gets or sets the user-visible name of the personal distribution list. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets the user-visible name of the personal distribution list. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
### MapiDistributionList() {#MapiDistributionList--}
```
public MapiDistributionList()
```


Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class.

### MapiDistributionList(String displayName, MapiDistributionListMemberCollection members) {#MapiDistributionList-java.lang.String-com.aspose.email.MapiDistributionListMemberCollection-}
```
public MapiDistributionList(String displayName, MapiDistributionListMemberCollection members)
```


Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The display namme. |
| members | [MapiDistributionListMemberCollection](../../com.aspose.email/mapidistributionlistmembercollection) | The recipiens. |

### getMembers() {#getMembers--}
```
public final MapiDistributionListMemberCollection getMembers()
```


Gets the list of the members of the personal distribution list.

Value: The collection of MapiDistributionListMember.

**Returns:**
[MapiDistributionListMemberCollection](../../com.aspose.email/mapidistributionlistmembercollection)
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets the user-visible name of the personal distribution list.

Value: The display name.

**Returns:**
java.lang.String
### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets the user-visible name of the personal distribution list.

Value: The display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves the specified file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

