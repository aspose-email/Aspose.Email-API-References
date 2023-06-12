---
title: MailAddress
second_title: Aspose.Email for Java API Reference
description: Represents the address of a message.
type: docs
weight: 365
url: /java/com.aspose.email/mailaddress/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMailAddress](../../com.aspose.email/imailaddress)
```
public class MailAddress implements IMailAddress
```

Represents the address of a message.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailAddress(String address, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-boolean-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
| [MailAddress(String address, String displayName, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-boolean-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
| [MailAddress(String address, String displayName, Charset displayNameEncoding)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
| [MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
| [MailAddress(String address)](#MailAddress-java.lang.String-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
| [MailAddress(String address, String displayName)](#MailAddress-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [getAddress()](#getAddress--) | Gets or sets the e-mail address. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Contains count of mail addresses. |
| [getDisplayName()](#getDisplayName--) | Gets or sets a display name. |
| [getHost()](#getHost--) | Gets the host portion of the address. |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | Gets or sets the original e-mail address string. |
| [getParticipationStatus()](#getParticipationStatus--) | Gets or sets the participation status for the calendar user. |
| [getUser()](#getUser--) | Gets the username. |
| [get_Item(int i)](#get-Item-int-) | Gets the element at the specified index. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | Gets or sets the e-mail address. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets a display name. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Gets or sets the participation status for the calendar user. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | Performs an implicit conversion from [MailAddressCollection](../../com.aspose.email/mailaddresscollection) to [MailAddress](../../com.aspose.email/mailaddress). |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | Performs an implicit conversion from String to [MailAddress](../../com.aspose.email/mailaddress). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailAddress(String address, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-boolean-}
```
public MailAddress(String address, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| ignoreSmtpCheck | boolean | if set to  true  then SMTP check will be omitted. |

### MailAddress(String address, String displayName, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-boolean-}
```
public MailAddress(String address, String displayName, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| displayName | java.lang.String | The display name. |
| ignoreSmtpCheck | boolean | if set to  true  then SMTP check will be omitted. |

### MailAddress(String address, String displayName, Charset displayNameEncoding) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | The display name encoding. |

### MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | The display name encoding. |
| ignoreSmtpCheck | boolean | if set to  true  then SMTP check will be omitted. |

### MailAddress(String address) {#MailAddress-java.lang.String-}
```
public MailAddress(String address)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |

### MailAddress(String address, String displayName) {#MailAddress-java.lang.String-java.lang.String-}
```
public MailAddress(String address, String displayName)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| displayName | java.lang.String | The display name. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Gets or sets the e-mail address.

Value: A String that contains the e-mail address.

**Returns:**
java.lang.String
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


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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

