---
title: EmailAddress
second_title: Aspose.Email for Java API Reference
description:  Represents an email address
type: docs
weight: 165
url: /java/com.aspose.email/emailaddress/
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
| [getPrefered()](#getPrefered--) | Gets or sets a value which defines whether email address is preferred. |
| [setPrefered(boolean value)](#setPrefered-boolean-) | Gets or sets a value which defines whether email address is preferred. |
| [getCategory()](#getCategory--) | Gets or sets an object category |
| [setCategory(EmailAddressCategory value)](#setCategory-com.aspose.email.EmailAddressCategory-) | Gets or sets an object category |
| [getRoutingType()](#getRoutingType--) | Gets or sets a routing type for an email |
| [setRoutingType(String value)](#setRoutingType-java.lang.String-) | Gets or sets a routing type for an email |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [hashCode(EmailAddress obj)](#hashCode-com.aspose.email.EmailAddress-) | GetHashCode returns a hash function for specified object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [equals(EmailAddress obj)](#equals-com.aspose.email.EmailAddress-) | Determines whether the specified Object is equal to the current Object. |
| [equals(EmailAddress x, EmailAddress y)](#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified object instances are considered equal. |
| [op_Equality(EmailAddress a, EmailAddress b)](#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified objects are equal. |
| [op_Inequality(EmailAddress a, EmailAddress b)](#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Determines whether the specified objects are not equal. |
| [compareTo(EmailAddress obj)](#compareTo-com.aspose.email.EmailAddress-) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
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

### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


Gets or sets a value which defines whether email address is preferred.

**Returns:**
boolean
### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


Gets or sets a value which defines whether email address is preferred.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCategory() {#getCategory--}
```
public final EmailAddressCategory getCategory()
```


Gets or sets an object category

**Returns:**
[EmailAddressCategory](../../com.aspose.email/emailaddresscategory)
### setCategory(EmailAddressCategory value) {#setCategory-com.aspose.email.EmailAddressCategory-}
```
public final void setCategory(EmailAddressCategory value)
```


Gets or sets an object category

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) |  |

### getRoutingType() {#getRoutingType--}
```
public final String getRoutingType()
```


Gets or sets a routing type for an email

**Returns:**
java.lang.String
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
