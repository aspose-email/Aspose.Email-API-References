---
title: MailAddress
second_title: Aspose.Email for Java API Reference
description: Represents an email address with support for display names encoding and address parsing.
type: docs
weight: 385
url: /java/com.aspose.email/mailaddress/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMailAddress](../../com.aspose.email/imailaddress)
```
public class MailAddress implements IMailAddress
```

Represents an email address with support for display names, encoding, and address parsing. This class provides functionality for working with email addresses in email messages, including properties for the display name, user name, host, and raw address. It supports proper encoding of international characters in display names and validates email addresses against SMTP standards.

The [MailAddress](../../com.aspose.email/mailaddress) class can represent both simple email addresses (e.g., "user@example.com") and addresses with display names (e.g., "John Elias <john@example.com>"). It automatically handles encoding of non-ASCII characters in display names and validates addresses to ensure they comply with SMTP standards.

The following example shows how to create mail addresses with and without display names.

```

 // Create a simple email address
 MailAddress address1 = new MailAddress("user@example.com");

 // Create an address with display name
 MailAddress address2 = new MailAddress("john@example.com", "John Doe");

 // Create an address with encoded display name (international characters)
 MailAddress address3 = new MailAddress("user@example.com", "\u0410\u043d\u0434\u0440\u0435\u0439 \u0418\u0432\u0430\u043d\u043e\u0432",
         StandardCharsets.UTF_8);

 // Access address properties
 System.out.println("Address: " + address1.getAddress());
 System.out.println("Display Name: " + address2.getDisplayName());
 System.out.println("User: " + address2.getUser());
 System.out.println("Host: " + address2.getHost());
 
```
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
| [getX500Address()](#getX500Address--) | Gets the email address in Exchange format, if it exists. |
| [get_Item(int i)](#get-Item-int-) | Gets the element at the specified index. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isX500OriginalAddressType()](#isX500OriginalAddressType--) | Indicates whether the original address is of X500 type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | Gets or sets the e-mail address. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets a display name. |
| [setOriginalAddressString(String value)](#setOriginalAddressString-java.lang.String-) | Gets or sets the original e-mail address string. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Gets or sets the participation status for the calendar user. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [toX500String()](#toX500String--) | Returns a String that represents this instance in Exchange format. |
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
### getX500Address() {#getX500Address--}
```
public final String getX500Address()
```


Gets the email address in Exchange format, if it exists.

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
### isX500OriginalAddressType() {#isX500OriginalAddressType--}
```
public final boolean isX500OriginalAddressType()
```


Indicates whether the original address is of X500 type.

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

### setOriginalAddressString(String value) {#setOriginalAddressString-java.lang.String-}
```
public final void setOriginalAddressString(String value)
```


Gets or sets the original e-mail address string.

Value: A String that contains the original e-mail address.

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
### toX500String() {#toX500String--}
```
public String toX500String()
```


Returns a String that represents this instance in Exchange format.

**Returns:**
java.lang.String - A String that represents this instance in Exchange format.
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

