---
title: MailQuery
second_title: Aspose.Email for Java API Reference
description: Represents the search criteria that are used to match several message properties in the mailbox.
type: docs
weight: 390
url: /java/com.aspose.email/mailquery/
---

**Inheritance:**
java.lang.Object
```
public class MailQuery
```

Represents the search criteria, that are used to match several message properties in the mailbox.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailQuery(String queryString)](#MailQuery-java.lang.String-) | Initializes a new instance of the [MailQuery](../../com.aspose.email/mailquery) class. |
| [MailQuery(String queryString, String orderByString)](#MailQuery-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailQuery](../../com.aspose.email/mailquery) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(MailQuery other)](#equals-com.aspose.email.MailQuery-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object, is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getOrderByString()](#getOrderByString--) | The sort query string. |
| [getSchema()](#getSchema--) | This method is reserved and should not be used. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailQuery(String queryString) {#MailQuery-java.lang.String-}
```
public MailQuery(String queryString)
```


Initializes a new instance of the [MailQuery](../../com.aspose.email/mailquery) class.

--------------------

> ```
> MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| queryString | java.lang.String | The query string.

--------------------

The query string should have the following view.

The example of a simple expression:

'<Field name>' <Comparison operator> '<Field value>',

where <Field Name> - the name of a message field through which filtering is made, <Comparison operator> - comparison operators, as their name implies, allow to compare message field and specified value, <Field value> - value to be compared with a message field.

The number of simple expressions can make a compound one, ex.: (<Simple expression 1> & <Simple expression 2>) | <Simple expression 3>,

where '&' - logical-AND operator, '|' - logical-OR operator

At present the following values are allowed as a field name (<Field name>):

'To' - represents a TO field of message, 'Text' - represents string in the header or body of the message, 'Bcc' - represents a BCC field of message, 'Body' - represents a string in the body of message, 'Cc' - represents a CC field of message, 'From' - represents a From field of message, 'Subject' - represents a string in the subject of message, 'InternalDate' - represents an internal date of message, 'SentDate' - represents a sent date of message

Additionally, the following field names are allowed for IMAP-protocol:

'Answered' - represents an /Answered flag of message 'Seen' - represents a /Seen flag of message 'Flagged' - represents a /Flagged flag of message 'Draft' - represents a /Draft flag of message 'Deleted' - represents a Deleted/ flag of message 'Recent' - represents a Deleted/ flag of message 'MessageSize' - represents a size (in bytes) of message

Additionally, the following field names are allowed for Exchange:

'IsRead' - Indicates whether the message has been read 'HasAttachment' - Indicates whether or not the message has attachments 'IsSubmitted' - Indicates whether the message has been submitted to the Outbox 'ContentClass' - represents a content class of item

Additionally, the following field names are allowed for pst/ost files:

'MessageClass' - Represents a message class 'ContainerClass' - Represents a folder container class 'Importance' - Represents a message importance 'MessageSize' - represents a size (in bytes) of message 'FolderName' - represents a folder name 'ContentsCount' - represents a total number of items in the folder 'UnreadContentsCount' - represents the number of unread items in the folder. 'Subfolders' - Indicates whether or not the folder has subfolders 'Read' - the message is marked as having been read 'HasAttachment' - the message has at least one attachment 'Unsent' - the message is still being composed 'Unmodified' - the message has not been modified since it was first saved (if unsent) or it was delivered (if sent) 'FromMe' - the user receiving the message was also the user who sent the message 'Resend' - the message includes a request for a resend operation with a non-delivery report 'NotifyRead' - the user who sent the message has requested notification when a recipient first reads it 'NotifyUnread' - the user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires 'EverRead' - the message has been read at least once

The field value (<Field value>) can take the following values: For text fields - any string, For date type fields - the string of 'd-MMM-yyy' format, ex. '10-Feb-2009', For flags (fields of boolean type) - either 'True', or 'False' |

### MailQuery(String queryString, String orderByString) {#MailQuery-java.lang.String-java.lang.String-}
```
public MailQuery(String queryString, String orderByString)
```


Initializes a new instance of the [MailQuery](../../com.aspose.email/mailquery) class.

--------------------

> ```
> MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
> ```

--------------------

The sort query string should have the following view.

The example of a simple expression:

'<Field name>' OrderBy ['ASC'|'DESC'],

where <Field Name> - the name of a message field through which sorting is made, ['ASC'|'DESC'] - sorting operators, allow to sort Ascending or Descending,

The number of simple expressions can make a compound one, ex.: (<Simple expression 1> & <Simple expression 2>),

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| queryString | java.lang.String |  |
| orderByString | java.lang.String |  |

### equals(MailQuery other) {#equals-com.aspose.email.MailQuery-}
```
public final boolean equals(MailQuery other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MailQuery](../../com.aspose.email/mailquery) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the  other  parameter; otherwise, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOrderByString() {#getOrderByString--}
```
public final String getOrderByString()
```


The sort query string.

**Returns:**
java.lang.String
### getSchema() {#getSchema--}
```
public final System.Xml.XmlSchema getSchema()
```


This method is reserved and should not be used. When implementing the IXmlSerializable interface, you should return null (Nothing in Visual Basic) from this method, and instead, if specifying a custom schema is required, apply the XmlSchemaProviderAttribute to the class.

**Returns:**
com.aspose.ms.System.Xml.XmlSchema - An XmlSchema that describes the XML representation of the object that is produced by the  M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)  method and consumed by the  M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)  method.
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




### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A query string that represents this instance.
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

