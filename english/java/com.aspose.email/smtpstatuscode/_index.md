---
title: SmtpStatusCode
second_title: Aspose.Email for Java API Reference
description: Smtp status codes
type: docs
weight: 639
url: /java/com.aspose.email/smtpstatuscode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SmtpStatusCode extends System.Enum
```

Smtp status codes
## Fields

| Field | Description |
| --- | --- |
| [AuthenticationMechanismIsToWeak](#AuthenticationMechanismIsToWeak) | Authentication mechanism is to weak |
| [AuthenticationRequired](#AuthenticationRequired) | The SMTP server requires a secure connection or the client was not authenticated. |
| [AuthenticationSucceeded](#AuthenticationSucceeded) | Authentication Succeeded |
| [Base64Response](#Base64Response) | Text part containing the [BASE64] encoded string |
| [CannotVerifyUserWillAttemptDelivery](#CannotVerifyUserWillAttemptDelivery) | The recipient cannot be VRFYed, but the server accepts the message and attempts delivery. |
| [ClientNotPermitted](#ClientNotPermitted) | Client does not have permission. |
| [CommandNotImplemented](#CommandNotImplemented) | This command is not implemented. |
| [CommandNotPermitted](#CommandNotPermitted) | \\u0421ommand is not permitted during a mail transaction |
| [CommandUnrecognized](#CommandUnrecognized) | The server could not recognize the command due to a syntax error. |
| [CredentialsInvalid](#CredentialsInvalid) | Authentication credentials invalid |
| [EncryptionRequiredRequestedMechanism](#EncryptionRequiredRequestedMechanism) | Encryption required for requested authentication mechanism |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExceededStorageAllocation](#ExceededStorageAllocation) | "Requested mail actions aborted \\u2013 Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits. |
| [GeneralFailure](#GeneralFailure) | General failure |
| [HelpMessage](#HelpMessage) | A help message for a human reader will follow. |
| [InsufficientStorage](#InsufficientStorage) | The command has been aborted because the server has insufficient system storage. |
| [LocalErrorInProcessing](#LocalErrorInProcessing) | The command has been aborted due to a server error. |
| [MailboxBusy](#MailboxBusy) | The requested command failed because the user\\u2019s mailbox was unavailable (such as being full). |
| [MailboxNameNotAllowed](#MailboxNameNotAllowed) | "Requested action not taken \\u2013 Mailbox name invalid". |
| [MailboxUnavailable](#MailboxUnavailable) | It usually defines a non-existent email address on the remote side. |
| [NotDefined](#NotDefined) | Not defined |
| [Ok](#Ok) | Requested action taken and completed. |
| [PasswordTransitionNeeded](#PasswordTransitionNeeded) | A password transition is needed |
| [ServiceClosingTransmissionChannel](#ServiceClosingTransmissionChannel) | Service closing transmission channel |
| [ServiceNotAvailable](#ServiceNotAvailable) | The service is not available and the connection will be closed. |
| [ServiceReady](#ServiceReady) | SMTP Service ready. |
| [StartMailInput](#StartMailInput) | Start message input and end with. |
| [SyntaxError](#SyntaxError) | A syntax error was encountered in command arguments. |
| [SystemStatus](#SystemStatus) | System status, or system help reply. |
| [TransactionFailed](#TransactionFailed) | This means that the transaction has failed. |
| [UnrecognizedAuthenticationType](#UnrecognizedAuthenticationType) | Unrecognized authentication type |
| [UserNotLocalTryAlternatePath](#UserNotLocalTryAlternatePath) | "User not local or invalid address \\u2013 Relay denied". |
| [UserNotLocalWillForward](#UserNotLocalWillForward) | The recipient is not local to the server, but the server will accept and forward the message. |
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
### AuthenticationMechanismIsToWeak {#AuthenticationMechanismIsToWeak}
```
public static final int AuthenticationMechanismIsToWeak
```


Authentication mechanism is to weak

### AuthenticationRequired {#AuthenticationRequired}
```
public static final int AuthenticationRequired
```


The SMTP server requires a secure connection or the client was not authenticated. But sometimes it's about the recipient's server blacklisting yours, or an invalid email address.

### AuthenticationSucceeded {#AuthenticationSucceeded}
```
public static final int AuthenticationSucceeded
```


Authentication Succeeded

### Base64Response {#Base64Response}
```
public static final int Base64Response
```


Text part containing the [BASE64] encoded string

### CannotVerifyUserWillAttemptDelivery {#CannotVerifyUserWillAttemptDelivery}
```
public static final int CannotVerifyUserWillAttemptDelivery
```


The recipient cannot be VRFYed, but the server accepts the message and attempts delivery.

### ClientNotPermitted {#ClientNotPermitted}
```
public static final int ClientNotPermitted
```


Client does not have permission. TLS not available due to temporary reason. Encryption required for requested authentication mechanism.

### CommandNotImplemented {#CommandNotImplemented}
```
public static final int CommandNotImplemented
```


This command is not implemented.

### CommandNotPermitted {#CommandNotPermitted}
```
public static final int CommandNotPermitted
```


\\u0421ommand is not permitted during a mail transaction

### CommandUnrecognized {#CommandUnrecognized}
```
public static final int CommandUnrecognized
```


The server could not recognize the command due to a syntax error.

### CredentialsInvalid {#CredentialsInvalid}
```
public static final int CredentialsInvalid
```


Authentication credentials invalid

### EncryptionRequiredRequestedMechanism {#EncryptionRequiredRequestedMechanism}
```
public static final int EncryptionRequiredRequestedMechanism
```


Encryption required for requested authentication mechanism

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExceededStorageAllocation {#ExceededStorageAllocation}
```
public static final int ExceededStorageAllocation
```


"Requested mail actions aborted \\u2013 Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits.

### GeneralFailure {#GeneralFailure}
```
public static final int GeneralFailure
```


General failure

### HelpMessage {#HelpMessage}
```
public static final int HelpMessage
```


A help message for a human reader will follow. SMTP 214 is usually provided as a response to the \\u201cHELP\\u201d command. A user will usually receive this as a displays of information about the mail server and it will most likely be in the form of a link to the FAQ page of THAT particular SMTP software that is running on the mail server. Due to the nature of this error and how the email server responds, it is normally called a reply, as in SMTP Reply 214.

### InsufficientStorage {#InsufficientStorage}
```
public static final int InsufficientStorage
```


The command has been aborted because the server has insufficient system storage.

### LocalErrorInProcessing {#LocalErrorInProcessing}
```
public static final int LocalErrorInProcessing
```


The command has been aborted due to a server error. (on their side)

### MailboxBusy {#MailboxBusy}
```
public static final int MailboxBusy
```


The requested command failed because the user\\u2019s mailbox was unavailable (such as being full). Try again later.

### MailboxNameNotAllowed {#MailboxNameNotAllowed}
```
public static final int MailboxNameNotAllowed
```


"Requested action not taken \\u2013 Mailbox name invalid". That is, there's an incorrect email address into the recipients line.

### MailboxUnavailable {#MailboxUnavailable}
```
public static final int MailboxUnavailable
```


It usually defines a non-existent email address on the remote side.

### NotDefined {#NotDefined}
```
public static final int NotDefined
```


Not defined

### Ok {#Ok}
```
public static final int Ok
```


Requested action taken and completed.

### PasswordTransitionNeeded {#PasswordTransitionNeeded}
```
public static final int PasswordTransitionNeeded
```


A password transition is needed

### ServiceClosingTransmissionChannel {#ServiceClosingTransmissionChannel}
```
public static final int ServiceClosingTransmissionChannel
```


Service closing transmission channel

### ServiceNotAvailable {#ServiceNotAvailable}
```
public static final int ServiceNotAvailable
```


The service is not available and the connection will be closed.

### ServiceReady {#ServiceReady}
```
public static final int ServiceReady
```


SMTP Service ready.

### StartMailInput {#StartMailInput}
```
public static final int StartMailInput
```


Start message input and end with. This indicates that the server is ready to accept the message itself

### SyntaxError {#SyntaxError}
```
public static final int SyntaxError
```


A syntax error was encountered in command arguments.

### SystemStatus {#SystemStatus}
```
public static final int SystemStatus
```


System status, or system help reply. A SMTP status 211 is a message that gives details about the Mail Server status. In the case of a System Help reply, it is a message to the user requesting help information.

### TransactionFailed {#TransactionFailed}
```
public static final int TransactionFailed
```


This means that the transaction has failed. It's a permanent error and the server will not try to send the message again.

### UnrecognizedAuthenticationType {#UnrecognizedAuthenticationType}
```
public static final int UnrecognizedAuthenticationType
```


Unrecognized authentication type

### UserNotLocalTryAlternatePath {#UserNotLocalTryAlternatePath}
```
public static final int UserNotLocalTryAlternatePath
```


"User not local or invalid address \\u2013 Relay denied". Meaning, if both your address and the recipient's are not locally hosted by the server, a relay can be interrupted.

### UserNotLocalWillForward {#UserNotLocalWillForward}
```
public static final int UserNotLocalWillForward
```


The recipient is not local to the server, but the server will accept and forward the message.

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

