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
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is the same e-mail address. |
| [getAddress()](#getAddress--) | Gets the e-mail address, such as  john@example.com . |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of addresses, which is always 1. |
| [getDisplayName()](#getDisplayName--) | Gets the display name, such as  John Smith . |
| [getHost()](#getHost--) | Gets the host part of the address: the part after  @ . |
| [getId()](#getId--) | Gets the identifiers of the address on the server it came from, such as Exchange. |
| [getOriginalAddressString()](#getOriginalAddressString--) | Gets the address exactly as it appeared in the message, before it was parsed. |
| [getParticipationStatus()](#getParticipationStatus--) | Gets the response of the attendee to a meeting request, when the address is a meeting attendee. |
| [getUser()](#getUser--) | Gets the user part of the address: the part before  @ . |
| [getX500Address()](#getX500Address--) | Gets the Exchange (X.500) form of the address, if the message has one. |
| [get_Item(int i)](#get-Item-int-) | Gets the address itself; the index is ignored. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isX500OriginalAddressType()](#isX500OriginalAddressType--) | Indicates whether the original address is of X500 type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | Sets the e-mail address, such as  john@example.com . |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Sets the display name, such as  John Smith . |
| [setOriginalAddressString(String value)](#setOriginalAddressString-java.lang.String-) | Sets the address exactly as it appeared in the message, before it was parsed. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Sets the response of the attendee to a meeting request, when the address is a meeting attendee. |
| [toString()](#toString--) | Returns the address with its display name, as written in a header. |
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
| address | java.lang.String | The e-mail address, optionally with a display name, such as  John Smith  . |
| ignoreSmtpCheck | boolean |  true  to skip the check that the address is a valid SMTP address. |

### MailAddress(String address, String displayName, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-boolean-}
```
public MailAddress(String address, String displayName, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address. |
| displayName | java.lang.String | The display name. |
| ignoreSmtpCheck | boolean |  true  to skip the check that the address is a valid SMTP address. |

### MailAddress(String address, String displayName, Charset displayNameEncoding) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | The encoding of the display name in the headers. |

### MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | The encoding of the display name in the headers. |
| ignoreSmtpCheck | boolean |  true  to skip the check that the address is a valid SMTP address. |

### MailAddress(String address) {#MailAddress-java.lang.String-}
```
public MailAddress(String address)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address, optionally with a display name, such as  John Smith  . |

### MailAddress(String address, String displayName) {#MailAddress-java.lang.String-java.lang.String-}
```
public MailAddress(String address, String displayName)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address. |
| displayName | java.lang.String | The display name. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is the same e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with. |

**Returns:**
boolean -  true  if  obj  is equal to this address; otherwise,  false .
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Gets the e-mail address, such as  john@example.com .

**Returns:**
java.lang.String - The e-mail address.
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


Gets the number of addresses, which is always 1. Together with the indexer it lets an address be used where a list is expected.

**Returns:**
int
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name, such as  John Smith .

**Returns:**
java.lang.String - The display name.
### getHost() {#getHost--}
```
public final String getHost()
```


Gets the host part of the address: the part after  @ .

**Returns:**
java.lang.String - The host.
### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets the identifiers of the address on the server it came from, such as Exchange.

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
### getOriginalAddressString() {#getOriginalAddressString--}
```
public final String getOriginalAddressString()
```


Gets the address exactly as it appeared in the message, before it was parsed.

**Returns:**
java.lang.String - The original address string.
### getParticipationStatus() {#getParticipationStatus--}
```
public final int getParticipationStatus()
```


Gets the response of the attendee to a meeting request, when the address is a meeting attendee.

**Returns:**
int
### getUser() {#getUser--}
```
public final String getUser()
```


Gets the user part of the address: the part before  @ .

**Returns:**
java.lang.String - The user name.
### getX500Address() {#getX500Address--}
```
public final String getX500Address()
```


Gets the Exchange (X.500) form of the address, if the message has one.

**Returns:**
java.lang.String
### get_Item(int i) {#get-Item-int-}
```
public final MailAddress get_Item(int i)
```


Gets the address itself; the index is ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int | Ignored. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - This address.
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


Sets the e-mail address, such as  john@example.com .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The e-mail address. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Sets the display name, such as  John Smith .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name. |

### setOriginalAddressString(String value) {#setOriginalAddressString-java.lang.String-}
```
public final void setOriginalAddressString(String value)
```


Sets the address exactly as it appeared in the message, before it was parsed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The original address string. |

### setParticipationStatus(int value) {#setParticipationStatus-int-}
```
public final void setParticipationStatus(int value)
```


Sets the response of the attendee to a meeting request, when the address is a meeting attendee.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns the address with its display name, as written in a header.

**Returns:**
java.lang.String - The address, such as  "John Smith"  .
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

