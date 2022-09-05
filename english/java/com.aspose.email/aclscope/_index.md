---
title: AclScope
second_title: Aspose.Email for Java API Reference
description:  The scope of the access rule.
type: docs
weight: 12
url: /java/com.aspose.email/aclscope/
---
**Inheritance:**
java.lang.Object
```
public class AclScope
```

The scope of the access rule.
## Constructors

| Constructor | Description |
| --- | --- |
| [AclScope()](#AclScope--) | Initializes a new instance of the AclScope class. |
| [AclScope(int type, String value)](#AclScope-int-java.lang.String-) | Initializes a new instance of the AclScope class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the ACL scope. |
| [setType(int value)](#setType-int-) | The type of the ACL scope. |
| [getValue()](#getValue--) | The email address of a user or group, or the name of a domain, depending on the scope type. |
| [setValue(String value)](#setValue-java.lang.String-) | The email address of a user or group, or the name of a domain, depending on the scope type. |
### AclScope() {#AclScope--}
```
public AclScope()
```


Initializes a new instance of the AclScope class.

### AclScope(int type, String value) {#AclScope-int-java.lang.String-}
```
public AclScope(int type, String value)
```


Initializes a new instance of the AclScope class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of the ACL scope. |
| value | java.lang.String | The email address of a user or group, or the name of a domain, depending on the scope type. |

### getType() {#getType--}
```
public final int getType()
```


The type of the ACL scope.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


The type of the ACL scope.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final String getValue()
```


The email address of a user or group, or the name of a domain, depending on the scope type. Omitted for type "default".

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


The email address of a user or group, or the name of a domain, depending on the scope type. Omitted for type "default".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

