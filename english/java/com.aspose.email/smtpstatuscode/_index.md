---
title: SmtpStatusCode
second_title: Aspose.Email for Java API Reference
description:  Smtp status codes
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
| [NotDefined](#NotDefined) | Not defined |
| [GeneralFailure](#GeneralFailure) | General failure |
| [SystemStatus](#SystemStatus) | System status, or system help reply. |
| [HelpMessage](#HelpMessage) | A help message for a human reader will follow. |
| [ServiceReady](#ServiceReady) | SMTP Service ready. |
| [ServiceClosingTransmissionChannel](#ServiceClosingTransmissionChannel) | Service closing transmission channel |
| [AuthenticationSucceeded](#AuthenticationSucceeded) | Authentication Succeeded |
| [Ok](#Ok) | Requested action taken and completed. |
| [UserNotLocalWillForward](#UserNotLocalWillForward) | The recipient is not local to the server, but the server will accept and forward the message. |
| [CannotVerifyUserWillAttemptDelivery](#CannotVerifyUserWillAttemptDelivery) | The recipient cannot be VRFYed, but the server accepts the message and attempts delivery. |
| [Base64Response](#Base64Response) | Text part containing the [BASE64] encoded string |
| [StartMailInput](#StartMailInput) | Start message input and end with. |
| [ServiceNotAvailable](#ServiceNotAvailable) | The service is not available and the connection will be closed. |
| [PasswordTransitionNeeded](#PasswordTransitionNeeded) | A password transition is needed |
| [MailboxBusy](#MailboxBusy) | The requested command failed because the user\\u2019s mailbox was unavailable (such as being full). |
| [LocalErrorInProcessing](#LocalErrorInProcessing) | The command has been aborted due to a server error. |
| [InsufficientStorage](#InsufficientStorage) | The command has been aborted because the server has insufficient system storage. |
| [ClientNotPermitted](#ClientNotPermitted) | Client does not have permission. |
| [CommandUnrecognized](#CommandUnrecognized) | The server could not recognize the command due to a syntax error. |
| [SyntaxError](#SyntaxError) | A syntax error was encountered in command arguments. |
| [CommandNotImplemented](#CommandNotImplemented) | This command is not implemented. |
| [CommandNotPermitted](#CommandNotPermitted) | \\u0421ommand is not permitted during a mail transaction |
| [UnrecognizedAuthenticationType](#UnrecognizedAuthenticationType) | Unrecognized authentication type |
| [AuthenticationRequired](#AuthenticationRequired) | The SMTP server requires a secure connection or the client was not authenticated. |
| [AuthenticationMechanismIsToWeak](#AuthenticationMechanismIsToWeak) | Authentication mechanism is to weak |
| [CredentialsInvalid](#CredentialsInvalid) | Authentication credentials invalid |
| [EncryptionRequiredRequestedMechanism](#EncryptionRequiredRequestedMechanism) | Encryption required for requested authentication mechanism |
| [MailboxUnavailable](#MailboxUnavailable) | It usually defines a non-existent email address on the remote side. |
| [UserNotLocalTryAlternatePath](#UserNotLocalTryAlternatePath) | "User not local or invalid address \\u2013 Relay denied". |
| [ExceededStorageAllocation](#ExceededStorageAllocation) | "Requested mail actions aborted \\u2013 Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits. |
| [MailboxNameNotAllowed](#MailboxNameNotAllowed) | "Requested action not taken \\u2013 Mailbox name invalid". |
| [TransactionFailed](#TransactionFailed) | This means that the transaction has failed. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```


Not defined

### GeneralFailure {#GeneralFailure}
```
public static final int GeneralFailure
```


General failure

### SystemStatus {#SystemStatus}
```
public static final int SystemStatus
```


System status, or system help reply. A SMTP status 211 is a message that gives details about the Mail Server status. In the case of a System Help reply, it is a message to the user requesting help information.

### HelpMessage {#HelpMessage}
```
public static final int HelpMessage
```


A help message for a human reader will follow. SMTP 214 is usually provided as a response to the \\u201cHELP\\u201d command. A user will usually receive this as a displays of information about the mail server and it will most likely be in the form of a link to the FAQ page of THAT particular SMTP software that is running on the mail server. Due to the nature of this error and how the email server responds, it is normally called a reply, as in SMTP Reply 214.

### ServiceReady {#ServiceReady}
```
public static final int ServiceReady
```


SMTP Service ready.

### ServiceClosingTransmissionChannel {#ServiceClosingTransmissionChannel}
```
public static final int ServiceClosingTransmissionChannel
```


Service closing transmission channel

### AuthenticationSucceeded {#AuthenticationSucceeded}
```
public static final int AuthenticationSucceeded
```


Authentication Succeeded

### Ok {#Ok}
```
public static final int Ok
```


Requested action taken and completed.

### UserNotLocalWillForward {#UserNotLocalWillForward}
```
public static final int UserNotLocalWillForward
```


The recipient is not local to the server, but the server will accept and forward the message.

### CannotVerifyUserWillAttemptDelivery {#CannotVerifyUserWillAttemptDelivery}
```
public static final int CannotVerifyUserWillAttemptDelivery
```


The recipient cannot be VRFYed, but the server accepts the message and attempts delivery.

### Base64Response {#Base64Response}
```
public static final int Base64Response
```


Text part containing the [BASE64] encoded string

### StartMailInput {#StartMailInput}
```
public static final int StartMailInput
```


Start message input and end with. This indicates that the server is ready to accept the message itself

### ServiceNotAvailable {#ServiceNotAvailable}
```
public static final int ServiceNotAvailable
```


The service is not available and the connection will be closed.

### PasswordTransitionNeeded {#PasswordTransitionNeeded}
```
public static final int PasswordTransitionNeeded
```


A password transition is needed

### MailboxBusy {#MailboxBusy}
```
public static final int MailboxBusy
```


The requested command failed because the user\\u2019s mailbox was unavailable (such as being full). Try again later.

### LocalErrorInProcessing {#LocalErrorInProcessing}
```
public static final int LocalErrorInProcessing
```


The command has been aborted due to a server error. (on their side)

### InsufficientStorage {#InsufficientStorage}
```
public static final int InsufficientStorage
```


The command has been aborted because the server has insufficient system storage.

### ClientNotPermitted {#ClientNotPermitted}
```
public static final int ClientNotPermitted
```


Client does not have permission. TLS not available due to temporary reason. Encryption required for requested authentication mechanism.

### CommandUnrecognized {#CommandUnrecognized}
```
public static final int CommandUnrecognized
```


The server could not recognize the command due to a syntax error.

### SyntaxError {#SyntaxError}
```
public static final int SyntaxError
```


A syntax error was encountered in command arguments.

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

### UnrecognizedAuthenticationType {#UnrecognizedAuthenticationType}
```
public static final int UnrecognizedAuthenticationType
```


Unrecognized authentication type

### AuthenticationRequired {#AuthenticationRequired}
```
public static final int AuthenticationRequired
```


The SMTP server requires a secure connection or the client was not authenticated. But sometimes it's about the recipient's server blacklisting yours, or an invalid email address.

### AuthenticationMechanismIsToWeak {#AuthenticationMechanismIsToWeak}
```
public static final int AuthenticationMechanismIsToWeak
```


Authentication mechanism is to weak

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

### MailboxUnavailable {#MailboxUnavailable}
```
public static final int MailboxUnavailable
```


It usually defines a non-existent email address on the remote side.

### UserNotLocalTryAlternatePath {#UserNotLocalTryAlternatePath}
```
public static final int UserNotLocalTryAlternatePath
```


"User not local or invalid address \\u2013 Relay denied". Meaning, if both your address and the recipient's are not locally hosted by the server, a relay can be interrupted.

### ExceededStorageAllocation {#ExceededStorageAllocation}
```
public static final int ExceededStorageAllocation
```


"Requested mail actions aborted \\u2013 Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits.

### MailboxNameNotAllowed {#MailboxNameNotAllowed}
```
public static final int MailboxNameNotAllowed
```


"Requested action not taken \\u2013 Mailbox name invalid". That is, there's an incorrect email address into the recipients line.

### TransactionFailed {#TransactionFailed}
```
public static final int TransactionFailed
```


This means that the transaction has failed. It's a permanent error and the server will not try to send the message again.

