---
title: CallInformation
second_title: Aspose.Email for Java API Reference
description:  Phone call information
type: docs
weight: 99
url: /java/com.aspose.email/callinformation/
---
**Inheritance:**
java.lang.Object
```
public class CallInformation
```

Phone call information
## Methods

| Method | Description |
| --- | --- |
| [getFailureCause()](#getFailureCause--) | Connection failure cause |
| [getCallState()](#getCallState--) | Phone call statuses. |
| [getSIPResponse()](#getSIPResponse--) | SIP response |
| [getSIPResponseCode()](#getSIPResponseCode--) | SIP response code This list details all the SIP response codes defined in IETF RFCs and registered with the IANA as of 18 April 2013. |
### getFailureCause() {#getFailureCause--}
```
public final int getFailureCause()
```


Connection failure cause

**Returns:**
int
### getCallState() {#getCallState--}
```
public final int getCallState()
```


Phone call statuses.

**Returns:**
int
### getSIPResponse() {#getSIPResponse--}
```
public final String getSIPResponse()
```


SIP response

**Returns:**
java.lang.String
### getSIPResponseCode() {#getSIPResponseCode--}
```
public final int getSIPResponseCode()
```


SIP response code This list details all the SIP response codes defined in IETF RFCs and registered with the IANA as of 18 April 2013. It also includes SIP response codes defined in obsolete SIP RFCs (specifically, RFC 2543), which are therefore not registered with the IANA; these are explicitly noted as such. 1xx\\u2014Provisional Responses 2xx\\u2014Successful Responses 3xx\\u2014Redirection Responses 4xx\\u2014Client Failure Responses 5xx\\u2014Server Failure Responses 6xx\\u2014Global Failure Responses

**Returns:**
int
