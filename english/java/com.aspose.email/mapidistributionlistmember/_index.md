---
title: MapiDistributionListMember
second_title: Aspose.Email for Java API Reference
description: A member of a personal distribution list.
type: docs
weight: 459
url: /java/com.aspose.email/mapidistributionlistmember/
---

**Inheritance:**
java.lang.Object
```
public final class MapiDistributionListMember
```

A member of a personal distribution list.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiDistributionListMember(String displayName, String emailAddress)](#MapiDistributionListMember-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiDistributionListMember](../../com.aspose.email/mapidistributionlistmember) class with a name and an e-mail address. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressType()](#getAddressType--) | Gets the type of the e-mail address, such as  SMTP . |
| [getClass()](#getClass--) |  |
| [getContactAddressType()](#getContactAddressType--) | Gets which address of the contact the member refers to, when \#getEntryId().getEntryId() points to a contact. |
| [getDisplayName()](#getDisplayName--) | Gets the name shown for the member. |
| [getEmailAddress()](#getEmailAddress--) | Gets the e-mail address of the member. |
| [getEntryId()](#getEntryId--) | Gets the EntryID of the member: of a contact, of another list, or of a one-off address. |
| [getEntryIdType()](#getEntryIdType--) | Gets what \#getEntryId().getEntryId() refers to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressType(String value)](#setAddressType-java.lang.String-) | Sets the type of the e-mail address, such as  SMTP . |
| [setContactAddressType(int value)](#setContactAddressType-int-) | Sets which address of the contact the member refers to, when \#getEntryId().getEntryId() points to a contact. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Sets the name shown for the member. |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | Sets the e-mail address of the member. |
| [setEntryId(byte[] value)](#setEntryId-byte---) | Sets the EntryID of the member: of a contact, of another list, or of a one-off address. |
| [setEntryIdType(int value)](#setEntryIdType-int-) | Sets what \#getEntryId().getEntryId() refers to. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiDistributionListMember(String displayName, String emailAddress) {#MapiDistributionListMember-java.lang.String-java.lang.String-}
```
public MapiDistributionListMember(String displayName, String emailAddress)
```


Initializes a new instance of the [MapiDistributionListMember](../../com.aspose.email/mapidistributionlistmember) class with a name and an e-mail address.

Outlook does not show a member whose  displayName  is  null  or empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The name shown for the member. |
| emailAddress | java.lang.String | The e-mail address. |

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
### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


Gets the type of the e-mail address, such as  SMTP .

**Returns:**
java.lang.String - The address type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContactAddressType() {#getContactAddressType--}
```
public final int getContactAddressType()
```


Gets which address of the contact the member refers to, when \#getEntryId().getEntryId() points to a contact.

**Returns:**
int - The address of the contact.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the name shown for the member.

Outlook does not show a member whose display name is  null  or empty.

**Returns:**
java.lang.String - The display name.
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


Gets the e-mail address of the member.

**Returns:**
java.lang.String - The e-mail address.
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the EntryID of the member: of a contact, of another list, or of a one-off address.

**Returns:**
byte[] - The EntryID.
### getEntryIdType() {#getEntryIdType--}
```
public final int getEntryIdType()
```


Gets what \#getEntryId().getEntryId() refers to.

**Returns:**
int - The type of the EntryID.
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




### setAddressType(String value) {#setAddressType-java.lang.String-}
```
public final void setAddressType(String value)
```


Sets the type of the e-mail address, such as  SMTP .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The address type. |

### setContactAddressType(int value) {#setContactAddressType-int-}
```
public final void setContactAddressType(int value)
```


Sets which address of the contact the member refers to, when \#getEntryId().getEntryId() points to a contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The address of the contact. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Sets the name shown for the member.

Outlook does not show a member whose display name is  null  or empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name. |

### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


Sets the e-mail address of the member.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The e-mail address. |

### setEntryId(byte[] value) {#setEntryId-byte---}
```
public final void setEntryId(byte[] value)
```


Sets the EntryID of the member: of a contact, of another list, or of a one-off address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The EntryID. |

### setEntryIdType(int value) {#setEntryIdType-int-}
```
public final void setEntryIdType(int value)
```


Sets what \#getEntryId().getEntryId() refers to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The type of the EntryID. |

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

