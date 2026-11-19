---
title: MapiContactElectronicAddress
second_title: Aspose.Email for Java API Reference
description: An e-mail address or fax number of a contact.
type: docs
weight: 440
url: /java/com.aspose.email/mapicontactelectronicaddress/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiContactAddress](../../com.aspose.email/mapicontactaddress)
```
public final class MapiContactElectronicAddress extends MapiContactAddress
```

An e-mail address or fax number of a contact.

A string converts to this class with \#to\_MapiContactElectronicAddress(String).to\_MapiContactElectronicAddress(String), so an e-mail address can be assigned to  getElectronicAddresses()  as  setEmail1(MapiContactElectronicAddress.to\_MapiContactElectronicAddress("alice@example.com")) .
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiContactElectronicAddress()](#MapiContactElectronicAddress--) | Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class. |
| [MapiContactElectronicAddress(String displayName, String addressType, String emailAddress)](#MapiContactElectronicAddress-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class. |
| [MapiContactElectronicAddress(String emailAddress)](#MapiContactElectronicAddress-java.lang.String-) | Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class with an e-mail address. |
| [MapiContactElectronicAddress(String faxNumber, String emailAddress)](#MapiContactElectronicAddress-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class with a fax number and an e-mail address. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [getAddressType()](#getAddressType--) | Gets the type of the address, such as  SMTP  or  EX  (Exchange). |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | Gets the name shown for the address. |
| [getEmailAddress()](#getEmailAddress--) | Gets the e-mail address. |
| [getFaxNumber()](#getFaxNumber--) | Gets the fax number. |
| [getOriginalDisplayName()](#getOriginalDisplayName--) | Gets the SMTP form of the address, used when the address itself is of another type. |
| [hashCode()](#hashCode--) | Returns the hash code of the address. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether no field of the address is set. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressType(String value)](#setAddressType-java.lang.String-) | Sets the type of the address, such as  SMTP  or  EX  (Exchange). |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Sets the name shown for the address. |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | Sets the e-mail address. |
| [setFaxNumber(String value)](#setFaxNumber-java.lang.String-) | Sets the fax number. |
| [setOriginalDisplayName(String value)](#setOriginalDisplayName-java.lang.String-) | Sets the SMTP form of the address, used when the address itself is of another type. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [to_MapiContactElectronicAddress(String emailAddress)](#to-MapiContactElectronicAddress-java.lang.String-) | Performs an implicit conversion from String to [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiContactElectronicAddress() {#MapiContactElectronicAddress--}
```
public MapiContactElectronicAddress()
```


Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class.

### MapiContactElectronicAddress(String displayName, String addressType, String emailAddress) {#MapiContactElectronicAddress-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContactElectronicAddress(String displayName, String addressType, String emailAddress)
```


Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The name shown for the address. |
| addressType | java.lang.String | The type of the address, such as  SMTP . |
| emailAddress | java.lang.String | The e-mail address. |

### MapiContactElectronicAddress(String emailAddress) {#MapiContactElectronicAddress-java.lang.String-}
```
public MapiContactElectronicAddress(String emailAddress)
```


Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class with an e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emailAddress | java.lang.String | The e-mail address. |

### MapiContactElectronicAddress(String faxNumber, String emailAddress) {#MapiContactElectronicAddress-java.lang.String-java.lang.String-}
```
public MapiContactElectronicAddress(String faxNumber, String emailAddress)
```


Initializes a new instance of the [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) class with a fax number and an e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| faxNumber | java.lang.String | The fax number. |
| emailAddress | java.lang.String | The e-mail address. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


Gets the type of the address, such as  SMTP  or  EX  (Exchange).

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the name shown for the address.

**Returns:**
java.lang.String
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


Gets the e-mail address.

**Returns:**
java.lang.String
### getFaxNumber() {#getFaxNumber--}
```
public final String getFaxNumber()
```


Gets the fax number.

**Returns:**
java.lang.String
### getOriginalDisplayName() {#getOriginalDisplayName--}
```
public final String getOriginalDisplayName()
```


Gets the SMTP form of the address, used when the address itself is of another type.

**Returns:**
java.lang.String - The SMTP address.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code of the address.

**Returns:**
int - The hash code.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Gets a value indicating whether no field of the address is set.

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




### setAddressType(String value) {#setAddressType-java.lang.String-}
```
public final void setAddressType(String value)
```


Sets the type of the address, such as  SMTP  or  EX  (Exchange).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Sets the name shown for the address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


Sets the e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFaxNumber(String value) {#setFaxNumber-java.lang.String-}
```
public final void setFaxNumber(String value)
```


Sets the fax number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOriginalDisplayName(String value) {#setOriginalDisplayName-java.lang.String-}
```
public final void setOriginalDisplayName(String value)
```


Sets the SMTP form of the address, used when the address itself is of another type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The SMTP address. |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
### to_MapiContactElectronicAddress(String emailAddress) {#to-MapiContactElectronicAddress-java.lang.String-}
```
public static MapiContactElectronicAddress to_MapiContactElectronicAddress(String emailAddress)
```


Performs an implicit conversion from String to [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emailAddress | java.lang.String | The email address. |

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) - The result of the conversion.
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

