---
title: EmailAddress
second_title: Aspose.Email for Android via Java API Reference
description: Represents an email address
type: docs
weight: 114
url: /androidjava/com.aspose.email/emailaddress/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailAddress](../../com.aspose.email/mailaddress)

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class EmailAddress extends MailAddress implements Comparable<EmailAddress>, System.IEquatable<EmailAddress>
```

Represents an email address
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailAddress()](#EmailAddress--) | Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class. |
| [EmailAddress(String address)](#EmailAddress-java.lang.String-) | Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class. |
| [EmailAddress(String address, String displayName)](#EmailAddress-java.lang.String-java.lang.String-) | Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class. |
## Methods

| Method | Description |
| --- | --- |
| [compareTo(EmailAddress obj)](#compareTo-com.aspose.email.EmailAddress-) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [equals(EmailAddress obj)](#equals-com.aspose.email.EmailAddress-) | Determines whether the specified Object is equal to the current Object. |
| [equals(EmailAddress x, EmailAddress y)](#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified object instances are considered equal. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [getAddress()](#getAddress--) | Gets or sets the e-mail address. |
| [getCategory()](#getCategory--) | Gets or sets an object category |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Contains count of mail addresses. |
| [getDisplayName()](#getDisplayName--) | Gets or sets a display name. |
| [getHost()](#getHost--) | Gets the host portion of the address. |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | Gets or sets the original e-mail address string. |
| [getParticipationStatus()](#getParticipationStatus--) | Gets or sets the participation status for the calendar user. |
| [getPrefered()](#getPrefered--) | Gets or sets a value which defines whether email address is preferred. |
| [getRoutingType()](#getRoutingType--) | Gets or sets a routing type for an email |
| [getUser()](#getUser--) | Gets the username. |
| [get_Item(int i)](#get-Item-int-) | Gets the element at the specified index. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [hashCode(EmailAddress obj)](#hashCode-com.aspose.email.EmailAddress-) | GetHashCode returns a hash function for specified object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(EmailAddress a, EmailAddress b)](#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified objects are equal. |
| [op_Inequality(EmailAddress a, EmailAddress b)](#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified objects are not equal. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Gets or sets the e-mail address. |
| [setCategory(EmailAddressCategory value)](#setCategory-com.aspose.email.EmailAddressCategory-) | Gets or sets an object category |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets a display name. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Gets or sets the participation status for the calendar user. |
| [setPrefered(boolean value)](#setPrefered-boolean-) | Gets or sets a value which defines whether email address is preferred. |
| [setRoutingType(String value)](#setRoutingType-java.lang.String-) | Gets or sets a routing type for an email |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | Performs an implicit conversion from [MailAddressCollection](../../com.aspose.email/mailaddresscollection) to [MailAddress](../../com.aspose.email/mailaddress). |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | Performs an implicit conversion from String to [MailAddress](../../com.aspose.email/mailaddress). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailAddress() {#EmailAddress--}
```
public EmailAddress()
```


Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class.

### EmailAddress(String address) {#EmailAddress-java.lang.String-}
```
public EmailAddress(String address)
```


Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |

### EmailAddress(String address, String displayName) {#EmailAddress-java.lang.String-java.lang.String-}
```
public EmailAddress(String address, String displayName)
```


Initializes a new instance of the [EmailAddress](../../com.aspose.email/emailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| displayName | java.lang.String | The display name. |

### compareTo(EmailAddress obj) {#compareTo-com.aspose.email.EmailAddress-}
```
public int compareTo(EmailAddress obj)
```


Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | An object to compare with this instance, or null. |

**Returns:**
int - This method returns: a value less than 0 if this is less than value 0 if this is equal to value a value greater than 0 if this is greater than value
### equals(EmailAddress obj) {#equals-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### equals(EmailAddress x, EmailAddress y) {#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress x, EmailAddress y)
```


Determines whether the specified object instances are considered equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | [EmailAddress](../../com.aspose.email/emailaddress) | The first object to compare. |
| y | [EmailAddress](../../com.aspose.email/emailaddress) | The second object to compare. |

**Returns:**
boolean - true if the objects are considered equal; otherwise, false. If both objA and objB are null, the method returns true.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Gets or sets the e-mail address.

Value: A String that contains the e-mail address.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public final EmailAddressCategory getCategory()
```


Gets or sets an object category

**Returns:**
[EmailAddressCategory](../../com.aspose.email/emailaddresscategory)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Contains count of mail addresses.

**Returns:**
int
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets a display name.

Value: A String that contains the display name.

**Returns:**
java.lang.String
### getHost() {#getHost--}
```
public final String getHost()
```


Gets the host portion of the address.

Value: A String that contains the name of the host.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets object identification information

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
### getOriginalAddressString() {#getOriginalAddressString--}
```
public final String getOriginalAddressString()
```


Gets or sets the original e-mail address string.

Value: A String that contains the original e-mail address.

**Returns:**
java.lang.String
### getParticipationStatus() {#getParticipationStatus--}
```
public final int getParticipationStatus()
```


Gets or sets the participation status for the calendar user.

**Returns:**
int
### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


Gets or sets a value which defines whether email address is preferred.

**Returns:**
boolean
### getRoutingType() {#getRoutingType--}
```
public final String getRoutingType()
```


Gets or sets a routing type for an email

**Returns:**
java.lang.String
### getUser() {#getUser--}
```
public final String getUser()
```


Gets the username.

Value: A String that contains the user name.

**Returns:**
java.lang.String
### get_Item(int i) {#get-Item-int-}
```
public final MailAddress get_Item(int i)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int | The zero-based index of the element to get or set. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - Returns the element at the specified index.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### hashCode(EmailAddress obj) {#hashCode-com.aspose.email.EmailAddress-}
```
public final int hashCode(EmailAddress obj)
```


GetHashCode returns a hash function for specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | The Object for which a hash code is to be returned. |

**Returns:**
int - Returns a hash function for specified object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(EmailAddress a, EmailAddress b) {#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Equality(EmailAddress a, EmailAddress b)
```


Determines whether the specified objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | First object to compare |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | Second object to compare |

**Returns:**
boolean - Returns true if objects are equal, otherwise false.
### op_Inequality(EmailAddress a, EmailAddress b) {#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Inequality(EmailAddress a, EmailAddress b)
```


Determines whether the specified objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | First object to compare |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | Second object to compare |

**Returns:**
boolean - Returns true if objects are not equal, otherwise false.
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Gets or sets the e-mail address.

Value: A String that contains the e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCategory(EmailAddressCategory value) {#setCategory-com.aspose.email.EmailAddressCategory-}
```
public final void setCategory(EmailAddressCategory value)
```


Gets or sets an object category

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets a display name.

Value: A String that contains the display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setParticipationStatus(int value) {#setParticipationStatus-int-}
```
public final void setParticipationStatus(int value)
```


Gets or sets the participation status for the calendar user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


Gets or sets a value which defines whether email address is preferred.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRoutingType(String value) {#setRoutingType-java.lang.String-}
```
public final void setRoutingType(String value)
```


Gets or sets a routing type for an email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
### to_MailAddress(MailAddressCollection addresses) {#to-MailAddress-com.aspose.email.MailAddressCollection-}
```
public static MailAddress to_MailAddress(MailAddressCollection addresses)
```


Performs an implicit conversion from [MailAddressCollection](../../com.aspose.email/mailaddresscollection) to [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The address collection. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
### to_MailAddress(String address) {#to-MailAddress-java.lang.String-}
```
public static MailAddress to_MailAddress(String address)
```


Performs an implicit conversion from String to [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The address. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
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

