---
title: "SmtpStatusCode Enum"
linktitle: "SmtpStatusCode"
articleTitle: "SmtpStatusCode"
second_title: "Aspose.Email for C++"
description: "Smtp status codes"
type: docs
weight: 10
url: /cpp/aspose.email.clients.smtp/smtpstatuscode/
---

## SmtpStatusCode enumeration (32 values)

Smtp status codes

| Value | Description |
| --- | --- |
| NotDefined | Not defined |
| GeneralFailure | General failure |
| SystemStatus | System status, or system help reply. A SMTP status 211 is a message that gives details about the Mail Server status. In the case of a System Help reply, it is a message to the user requesting help information. |
| HelpMessage | A help message for a human reader will follow. SMTP 214 is usually provided as a response to the “HELP” command. A user will usually receive this as a displays of information about the mail server and it will most likely be in the form of a link to the FAQ page of THAT particular SMTP software that is running on the mail server. Due to the nature of this error and how the email server responds, it is normally called a reply, as in SMTP Reply 214. |
| ServiceReady | SMTP Service ready. |
| ServiceClosingTransmissionChannel | Service closing transmission channel |
| AuthenticationSucceeded | Authentication Succeeded |
| Ok | Requested action taken and completed. |
| UserNotLocalWillForward | The recipient is not local to the server, but the server will accept and forward the message. |
| CannotVerifyUserWillAttemptDelivery | The recipient cannot be VRFYed, but the server accepts the message and attempts delivery. |
| Base64Response | Text part containing the [BASE64] encoded string |
| StartMailInput | Start message input and end with. This indicates that the server is ready to accept the message itself |
| ServiceNotAvailable | The service is not available and the connection will be closed. |
| PasswordTransitionNeeded | A password transition is needed |
| MailboxBusy | The requested command failed because the user’s mailbox was unavailable (such as being full). Try again later. |
| LocalErrorInProcessing | The command has been aborted due to a server error. (on their side) |
| InsufficientStorage | The command has been aborted because the server has insufficient system storage. |
| ClientNotPermitted | Client does not have permission. TLS not available due to temporary reason. Encryption required for requested authentication mechanism. |
| CommandUnrecognized | The server could not recognize the command due to a syntax error. |
| SyntaxError | A syntax error was encountered in command arguments. |
| CommandNotImplemented | This command is not implemented. |
| CommandNotPermitted | Сommand is not permitted during a mail transaction |
| UnrecognizedAuthenticationType | Unrecognized authentication type |
| AuthenticationRequired | The SMTP server requires a secure connection or the client was not authenticated. But sometimes it's about the recipient's server blacklisting yours, or an invalid email address. |
| AuthenticationMechanismIsToWeak | Authentication mechanism is to weak |
| CredentialsInvalid | Authentication credentials invalid |
| EncryptionRequiredRequestedMechanism | Encryption required for requested authentication mechanism |
| MailboxUnavailable | It usually defines a non-existent email address on the remote side. |
| UserNotLocalTryAlternatePath | "User not local or invalid address – Relay denied". Meaning, if both your address and the recipient's are not locally hosted by the server, a relay can be interrupted. |
| ExceededStorageAllocation | "Requested mail actions aborted – Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits. |
| MailboxNameNotAllowed | "Requested action not taken – Mailbox name invalid". That is, there's an incorrect email address into the recipients line. |
| TransactionFailed | This means that the transaction has failed. It's a permanent error and the server will not try to send the message again. |

