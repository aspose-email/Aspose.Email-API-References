---
title: MailAddress
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the address of a message.
type: docs
weight: 188
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
| [getDisplayName()](#getDisplayName--) | Gets or sets a display name. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets a display name. |
| [getUser()](#getUser--) | Gets the username. |
| [getHost()](#getHost--) | Gets the host portion of the address. |
| [getAddress()](#getAddress--) | Gets or sets the e-mail address. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Gets or sets the e-mail address. |
| [getOriginalAddressString()](#getOriginalAddressString--) | Gets or sets the original e-mail address string. |
| [getCount()](#getCount--) | Contains count of mail addresses. |
| [get_Item(int i)](#get-Item-int-) | Gets the element at the specified index. |
| [getParticipationStatus()](#getParticipationStatus--) | Gets or sets the participation status for the calendar user. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Gets or sets the participation status for the calendar user. |
| [getId()](#getId--) | Gets object identification information |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | Performs an implicit conversion from String to [MailAddress](../../com.aspose.email/mailaddress). |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | Performs an implicit conversion from [MailAddressCollection](../../com.aspose.email/mailaddresscollection) to [MailAddress](../../com.aspose.email/mailaddress). |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### MailAddress(String address, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-boolean-}
```
public MailAddress(String address, boolean ignoreSmtpCheck)
```


Initializes a new instance of the [MailAddress](../../com.aspose.email/mailaddress) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address. |
| ignoreSmtpCheck | boolean | if set to \`\`\` true \`\`\` then SMTP check will be omitted. |

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
| ignoreSmtpCheck | boolean | if set to \`\`\` true \`\`\` then SMTP check will be omitted. |

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
| ignoreSmtpCheck | boolean | if set to \`\`\` true \`\`\` then SMTP check will be omitted. |

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

### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets a display name.

Value: A String that contains the display name.

**Returns:**
java.lang.String
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

### getUser() {#getUser--}
```
public final String getUser()
```


Gets the username.

Value: A String that contains the user name.

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
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Gets or sets the e-mail address.

Value: A String that contains the e-mail address.

**Returns:**
java.lang.String
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

### getOriginalAddressString() {#getOriginalAddressString--}
```
public final String getOriginalAddressString()
```


Gets or sets the original e-mail address string.

Value: A String that contains the original e-mail address.

**Returns:**
java.lang.String
### getCount() {#getCount--}
```
public final int getCount()
```


Contains count of mail addresses.

**Returns:**
int
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
### getParticipationStatus() {#getParticipationStatus--}
```
public final int getParticipationStatus()
```


Gets or sets the participation status for the calendar user.

**Returns:**
int
### setParticipationStatus(int value) {#setParticipationStatus-int-}
```
public final void setParticipationStatus(int value)
```


Gets or sets the participation status for the calendar user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets object identification information

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
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
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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
boolean - \`\`\` true \`\`\` if the specified Object is equal to this instance; otherwise, \`\`\` false \`\`\`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
