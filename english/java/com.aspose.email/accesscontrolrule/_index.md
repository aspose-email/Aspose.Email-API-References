---
title: AccessControlRule
second_title: Aspose.Email for Java API Reference
description: Access control rule.
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getETag()](#getETag--) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [getId()](#getId--) | Identifier of the resource. |
| [getKind()](#getKind--) | Type of the resource |
| [getRole()](#getRole--) | The role assigned to the scope. |
| [getScope()](#getScope--) | The scope of the rule. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setETag(String value)](#setETag-java.lang.String-) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [setId(String value)](#setId-java.lang.String-) | Identifier of the resource. |
| [setRole(int value)](#setRole-int-) | The role assigned to the scope. |
| [setScope(AclScope value)](#setScope-com.aspose.email.AclScope-) | The scope of the rule. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getETag() {#getETag--}
```
public String getETag()
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public String getId()
```


Identifier of the resource.

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public String getKind()
```


Type of the resource

**Returns:**
java.lang.String
### getRole() {#getRole--}
```
public final int getRole()
```


The role assigned to the scope.

**Returns:**
int
### getScope() {#getScope--}
```
public final AclScope getScope()
```


The scope of the rule.

**Returns:**
[AclScope](../../com.aspose.email/aclscope)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setETag(String value) {#setETag-java.lang.String-}
```
public void setETag(String value)
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


Identifier of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRole(int value) {#setRole-int-}
```
public final void setRole(int value)
```


The role assigned to the scope.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setScope(AclScope value) {#setScope-com.aspose.email.AclScope-}
```
public final void setScope(AclScope value)
```


The scope of the rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AclScope](../../com.aspose.email/aclscope) |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
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

