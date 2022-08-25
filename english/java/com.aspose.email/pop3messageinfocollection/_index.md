---
title: Pop3MessageInfoCollection
second_title: Aspose.Email for Java API Reference
description:  Represents the information of a mail message from Pop3 server.
type: docs
weight: 570
url: /java/com.aspose.email/pop3messageinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList, com.aspose.ms.System.Collections.Generic.IGenericCollection, com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class Pop3MessageInfoCollection extends System.Collections.ObjectModel.Collection<Pop3MessageInfo> implements System.Collections.Generic.IGenericList<Pop3MessageInfo>, System.Collections.Generic.IGenericCollection<Pop3MessageInfo>, System.Collections.Generic.IGenericEnumerable<Pop3MessageInfo>
```

Represents the information of a mail message from Pop3 server.
## Constructors

| Constructor | Description |
| --- | --- |
| [Pop3MessageInfoCollection()](#Pop3MessageInfoCollection--) | Initializes a new instance of the Pop3MessageInfoCollection class. |
## Methods

| Method | Description |
| --- | --- |
| [getMessage(String uniqueId)](#getMessage-java.lang.String-) | Gets the [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) of the E-Mail message. |
| [getMessage(int sequenceNumber)](#getMessage-int-) | Gets the [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) of the E-Mail message. |
### Pop3MessageInfoCollection() {#Pop3MessageInfoCollection--}
```
public Pop3MessageInfoCollection()
```


Initializes a new instance of the Pop3MessageInfoCollection class.

### getMessage(String uniqueId) {#getMessage-java.lang.String-}
```
public final Pop3MessageInfo getMessage(String uniqueId)
```


Gets the [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) of the E-Mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | Unique Id of the E-Mail message. |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Returns [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) if exists, otherwise returns null.
### getMessage(int sequenceNumber) {#getMessage-int-}
```
public final Pop3MessageInfo getMessage(int sequenceNumber)
```


Gets the [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) of the E-Mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | Sequence number of the E-Mail message. |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Returns [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) if exists, otherwise returns null.
