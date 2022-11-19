---
title: ExchangeAdvancedSyntaxMailQuery
second_title: Aspose.Email for Java API Reference
description: Represents the search criteria that are used to match several message properties in the mailbox.
type: docs
weight: 185
url: /java/com.aspose.email/exchangeadvancedsyntaxmailquery/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQuery](../../com.aspose.email/mailquery)
```
public class ExchangeAdvancedSyntaxMailQuery extends MailQuery
```

Represents the search criteria, that are used to match several message properties in the mailbox. Implements an Advanced Query Syntax (AQS) search that is used by EWS. AQS described at https://docs.microsoft.com/exchange/client-developer/exchange-web-services/how-to-perform-an-aqs-search-by-using-ews-in-exchange.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeAdvancedSyntaxMailQuery(String advancedSyntaxQueryString)](#ExchangeAdvancedSyntaxMailQuery-java.lang.String-) | Initializes a new instance of the [ExchangeAdvancedSyntaxMailQuery](../../com.aspose.email/exchangeadvancedsyntaxmailquery) class. |
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
| [readXml(System.Xml.XmlReader reader)](#readXml-com.aspose.ms.System.Xml.XmlReader-) | Generates an object from its XML representation. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeXml(System.Xml.XmlWriter writer)](#writeXml-com.aspose.ms.System.Xml.XmlWriter-) | Converts an object into its XML representation. |
### ExchangeAdvancedSyntaxMailQuery(String advancedSyntaxQueryString) {#ExchangeAdvancedSyntaxMailQuery-java.lang.String-}
```
public ExchangeAdvancedSyntaxMailQuery(String advancedSyntaxQueryString)
```


Initializes a new instance of the [ExchangeAdvancedSyntaxMailQuery](../../com.aspose.email/exchangeadvancedsyntaxmailquery) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| advancedSyntaxQueryString | java.lang.String | The advanced syntax query string. |

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




### readXml(System.Xml.XmlReader reader) {#readXml-com.aspose.ms.System.Xml.XmlReader-}
```
public void readXml(System.Xml.XmlReader reader)
```


Generates an object from its XML representation. Not implemented for the ExchangeAdvancedMailQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reader | com.aspose.ms.System.Xml.XmlReader | The XmlReader stream from which the object is deserialized. |

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

### writeXml(System.Xml.XmlWriter writer) {#writeXml-com.aspose.ms.System.Xml.XmlWriter-}
```
public void writeXml(System.Xml.XmlWriter writer)
```


Converts an object into its XML representation. Not implemented for the ExchangeAdvancedMailQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| writer | com.aspose.ms.System.Xml.XmlWriter | The XmlWriter stream to which the object is serialized. |

