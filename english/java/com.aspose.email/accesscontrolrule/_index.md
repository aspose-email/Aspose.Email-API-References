---
title: AccessControlRule
second_title: Aspose.Email for Java API Reference
description:  Access control rule.
type: docs
weight: 10
url: /java/com.aspose.email/accesscontrolrule/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.BaseDataObject](../../com.aspose.email/basedataobject)
```
public class AccessControlRule extends BaseDataObject
```

Access control rule.
## Constructors

| Constructor | Description |
| --- | --- |
| [AccessControlRule()](#AccessControlRule--) | Initializes a new instance of the AccessControlRule class. |
| [AccessControlRule(AclScope scope, int role)](#AccessControlRule-com.aspose.email.AclScope-int-) | Initializes a new instance of the AccessControlRule class. |
| [AccessControlRule(String id, AclScope scope, int role)](#AccessControlRule-java.lang.String-com.aspose.email.AclScope-int-) | Initializes a new instance of the AccessControlRule class. |
| [AccessControlRule(String id, String eTag, AclScope scope, int role)](#AccessControlRule-java.lang.String-java.lang.String-com.aspose.email.AclScope-int-) | Initializes a new instance of the AccessControlRule class. |
## Fields

| Field | Description |
| --- | --- |
| [ACCESS_CONTROL_RULE_KIND](#ACCESS-CONTROL-RULE-KIND) | Type of the resource ("calendar\#calendar"). |
## Methods

| Method | Description |
| --- | --- |
| [getScope()](#getScope--) | The scope of the rule. |
| [setScope(AclScope value)](#setScope-com.aspose.email.AclScope-) | The scope of the rule. |
| [getRole()](#getRole--) | The role assigned to the scope. |
| [setRole(int value)](#setRole-int-) | The role assigned to the scope. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
### AccessControlRule() {#AccessControlRule--}
```
public AccessControlRule()
```


Initializes a new instance of the AccessControlRule class.

### AccessControlRule(AclScope scope, int role) {#AccessControlRule-com.aspose.email.AclScope-int-}
```
public AccessControlRule(AclScope scope, int role)
```


Initializes a new instance of the AccessControlRule class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scope | [AclScope](../../com.aspose.email/aclscope) | The scope of the rule. |
| role | int | The role assigned to the scope. |

### AccessControlRule(String id, AclScope scope, int role) {#AccessControlRule-java.lang.String-com.aspose.email.AclScope-int-}
```
public AccessControlRule(String id, AclScope scope, int role)
```


Initializes a new instance of the AccessControlRule class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| scope | [AclScope](../../com.aspose.email/aclscope) | The scope of the rule. |
| role | int | The role assigned to the scope. |

### AccessControlRule(String id, String eTag, AclScope scope, int role) {#AccessControlRule-java.lang.String-java.lang.String-com.aspose.email.AclScope-int-}
```
public AccessControlRule(String id, String eTag, AclScope scope, int role)
```


Initializes a new instance of the AccessControlRule class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| eTag | java.lang.String | An entity tag |
| scope | [AclScope](../../com.aspose.email/aclscope) | The scope of the rule. |
| role | int | The role assigned to the scope. |

### ACCESS_CONTROL_RULE_KIND {#ACCESS-CONTROL-RULE-KIND}
```
public static final String ACCESS_CONTROL_RULE_KIND
```


Type of the resource ("calendar\#calendar").

### getScope() {#getScope--}
```
public final AclScope getScope()
```


The scope of the rule.

**Returns:**
[AclScope](../../com.aspose.email/aclscope)
### setScope(AclScope value) {#setScope-com.aspose.email.AclScope-}
```
public final void setScope(AclScope value)
```


The scope of the rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AclScope](../../com.aspose.email/aclscope) |  |

### getRole() {#getRole--}
```
public final int getRole()
```


The role assigned to the scope.

**Returns:**
int
### setRole(int value) {#setRole-int-}
```
public final void setRole(int value)
```


The role assigned to the scope.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
