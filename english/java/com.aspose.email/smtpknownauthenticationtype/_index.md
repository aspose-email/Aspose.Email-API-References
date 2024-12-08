---
title: SmtpKnownAuthenticationType
second_title: Aspose.Email for Java API Reference
description: 
type: docs
weight: 668
url: /java/com.aspose.email/smtpknownauthenticationtype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SmtpKnownAuthenticationType extends System.Enum
```
## Fields

| Field | Description |
| --- | --- |
| [Anonymous](#Anonymous) | https://tools.ietf.org/html/rfc4505 |
| [CramMD5](#CramMD5) | https://tools.ietf.org/html/rfc2195 |
| [DigestMD5](#DigestMD5) | https://tools.ietf.org/html/rfc2831 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [External](#External) | https://tools.ietf.org/html/rfc2222 |
| [GSSAPI](#GSSAPI) | GSS-API https://tools.ietf.org/html/rfc2078 https://tools.ietf.org/html/rfc2222 Kerberos V5 https://tools.ietf.org/html/rfc4752 |
| [GSSSPNEGO](#GSSSPNEGO) | GSS-SPNEGO https://tools.ietf.org/html/rfc5801\#section-14 https://tools.ietf.org/html/rfc4178 |
| [KerberosV4](#KerberosV4) | https://tools.ietf.org/html/rfc2222 |
| [Login](#Login) | https://tools.ietf.org/id/draft-murchison-sasl-login-00.txt |
| [NTLM](#NTLM) | http://davenport.sourceforge.net/ntlm.html https://tools.ietf.org/doc/tcllib/html/sasl.html |
| [None](#None) | None |
| [OAUTH2](#OAUTH2) | https://tools.ietf.org/html/rfc7628 |
| [OtpMd4](#OtpMd4) | https://tools.ietf.org/html/rfc2444 |
| [OtpMd5](#OtpMd5) | https://tools.ietf.org/html/rfc2444 |
| [OtpSha1](#OtpSha1) | https://tools.ietf.org/html/rfc2444 |
| [PassDssSha3Des1](#PassDssSha3Des1) | https://tools.ietf.org/html/draft-newman-sasl-passdss-00 |
| [Plain](#Plain) | https://tools.ietf.org/html/rfc4422 |
| [SKEY](#SKEY) | https://tools.ietf.org/html/rfc1760 https://tools.ietf.org/html/rfc2222\#section-7.3 |
| [ScramSha1](#ScramSha1) | https://tools.ietf.org/html/rfc5802 |
| [ScramSha1Plus](#ScramSha1Plus) | https://tools.ietf.org/html/rfc5802 |
| [ScramSha224](#ScramSha224) |  |
| [ScramSha224Plus](#ScramSha224Plus) |  |
| [ScramSha256](#ScramSha256) | https://tools.ietf.org/html/rfc7677 |
| [ScramSha256Plus](#ScramSha256Plus) | https://tools.ietf.org/html/rfc7677 |
| [ScramSha384](#ScramSha384) |  |
| [ScramSha384Plus](#ScramSha384Plus) |  |
| [ScramSha512](#ScramSha512) | https://tools.ietf.org/html/draft-melnikov-scram-sha-512-01 |
| [ScramSha512Plus](#ScramSha512Plus) | https://tools.ietf.org/html/draft-melnikov-scram-sha-512-01 |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Anonymous {#Anonymous}
```
public static final long Anonymous
```


https://tools.ietf.org/html/rfc4505

### CramMD5 {#CramMD5}
```
public static final long CramMD5
```


https://tools.ietf.org/html/rfc2195

### DigestMD5 {#DigestMD5}
```
public static final long DigestMD5
```


https://tools.ietf.org/html/rfc2831

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### External {#External}
```
public static final long External
```


https://tools.ietf.org/html/rfc2222

### GSSAPI {#GSSAPI}
```
public static final long GSSAPI
```


GSS-API https://tools.ietf.org/html/rfc2078 https://tools.ietf.org/html/rfc2222 Kerberos V5 https://tools.ietf.org/html/rfc4752

### GSSSPNEGO {#GSSSPNEGO}
```
public static final long GSSSPNEGO
```


GSS-SPNEGO https://tools.ietf.org/html/rfc5801\#section-14 https://tools.ietf.org/html/rfc4178

### KerberosV4 {#KerberosV4}
```
public static final long KerberosV4
```


https://tools.ietf.org/html/rfc2222

### Login {#Login}
```
public static final long Login
```


https://tools.ietf.org/id/draft-murchison-sasl-login-00.txt

### NTLM {#NTLM}
```
public static final long NTLM
```


http://davenport.sourceforge.net/ntlm.html https://tools.ietf.org/doc/tcllib/html/sasl.html

### None {#None}
```
public static final long None
```


None

### OAUTH2 {#OAUTH2}
```
public static final long OAUTH2
```


https://tools.ietf.org/html/rfc7628

### OtpMd4 {#OtpMd4}
```
public static final long OtpMd4
```


https://tools.ietf.org/html/rfc2444

### OtpMd5 {#OtpMd5}
```
public static final long OtpMd5
```


https://tools.ietf.org/html/rfc2444

### OtpSha1 {#OtpSha1}
```
public static final long OtpSha1
```


https://tools.ietf.org/html/rfc2444

### PassDssSha3Des1 {#PassDssSha3Des1}
```
public static final long PassDssSha3Des1
```


https://tools.ietf.org/html/draft-newman-sasl-passdss-00

### Plain {#Plain}
```
public static final long Plain
```


https://tools.ietf.org/html/rfc4422

### SKEY {#SKEY}
```
public static final long SKEY
```


https://tools.ietf.org/html/rfc1760 https://tools.ietf.org/html/rfc2222\#section-7.3

### ScramSha1 {#ScramSha1}
```
public static final long ScramSha1
```


https://tools.ietf.org/html/rfc5802

### ScramSha1Plus {#ScramSha1Plus}
```
public static final long ScramSha1Plus
```


https://tools.ietf.org/html/rfc5802

### ScramSha224 {#ScramSha224}
```
public static final long ScramSha224
```




### ScramSha224Plus {#ScramSha224Plus}
```
public static final long ScramSha224Plus
```




### ScramSha256 {#ScramSha256}
```
public static final long ScramSha256
```


https://tools.ietf.org/html/rfc7677

### ScramSha256Plus {#ScramSha256Plus}
```
public static final long ScramSha256Plus
```


https://tools.ietf.org/html/rfc7677

### ScramSha384 {#ScramSha384}
```
public static final long ScramSha384
```




### ScramSha384Plus {#ScramSha384Plus}
```
public static final long ScramSha384Plus
```




### ScramSha512 {#ScramSha512}
```
public static final long ScramSha512
```


https://tools.ietf.org/html/draft-melnikov-scram-sha-512-01

### ScramSha512Plus {#ScramSha512Plus}
```
public static final long ScramSha512Plus
```


https://tools.ietf.org/html/draft-melnikov-scram-sha-512-01

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
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

