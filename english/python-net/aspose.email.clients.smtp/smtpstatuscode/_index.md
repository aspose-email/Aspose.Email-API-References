---
title: SmtpStatusCode
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/aspose.email.clients.smtp/smtpstatuscode/
---

## SmtpStatusCode enumeration

Smtp status codes

## Members
| Member name | Description |
| :- | :- |
|NOT_DEFINED|Not defined|
|GENERAL_FAILURE|General failure|
|SYSTEM_STATUS|System status, or system help reply.<br/>            A SMTP status 211 is a message that gives details about the Mail Server status. <br/>            In the case of a System Help reply, it is a message to the user requesting help information.|
|HELP_MESSAGE|A help message for a human reader will follow. <br/>            SMTP 214 is usually provided as a response to the “HELP” command. <br/>            A user will usually receive this as a displays of information about the mail server and it will most likely be in the form of a link to the FAQ page of THAT particular SMTP software that is running on the mail server.<br/>            Due to the nature of this error and how the email server responds, it is normally called a reply, as in SMTP Reply 214.|
|SERVICE_READY|SMTP Service ready.|
|SERVICE_CLOSING_TRANSMISSION_CHANNEL|Service closing transmission channel|
|AUTHENTICATION_SUCCEEDED|Authentication Succeeded|
|OK|Requested action taken and completed.|
|USER_NOT_LOCAL_WILL_FORWARD|The recipient is not local to the server, but the server will accept and forward the message.|
|CANNOT_VERIFY_USER_WILL_ATTEMPT_DELIVERY|The recipient cannot be VRFYed, but the server accepts the message and attempts delivery.|
|BASE_64_RESPONSE|Text part containing the [BASE64] encoded string|
|START_MAIL_INPUT|Start message input and end with. This indicates that the server is ready to accept the message itself|
|SERVICE_NOT_AVAILABLE|The service is not available and the connection will be closed.|
|PASSWORD_TRANSITION_NEEDED|A password transition is needed|
|MAILBOX_BUSY|The requested command failed because the user’s mailbox was unavailable (such as being full). Try again later.|
|LOCAL_ERROR_IN_PROCESSING|The command has been aborted due to a server error. (on their side)|
|INSUFFICIENT_STORAGE|The command has been aborted because the server has insufficient system storage.|
|CLIENT_NOT_PERMITTED|Client does not have permission.<br/>            TLS not available due to temporary reason. <br/>            Encryption required for requested authentication mechanism.|
|COMMAND_UNRECOGNIZED|The server could not recognize the command due to a syntax error.|
|SYNTAX_ERROR|A syntax error was encountered in command arguments.|
|COMMAND_NOT_IMPLEMENTED|This command is not implemented.|
|COMMAND_NOT_PERMITTED|Сommand is not permitted during a mail transaction|
|UNRECOGNIZED_AUTHENTICATION_TYPE|Unrecognized authentication type|
|AUTHENTICATION_REQUIRED|The SMTP server requires a secure connection or the client was not authenticated.<br/>            But sometimes it's about the recipient's server blacklisting yours, or an invalid email address.|
|AUTHENTICATION_MECHANISM_IS_TO_WEAK|Authentication mechanism is to weak|
|CREDENTIALS_INVALID|Authentication credentials invalid|
|ENCRYPTION_REQUIRED_REQUESTED_MECHANISM|Encryption required for requested authentication mechanism|
|MAILBOX_UNAVAILABLE|It usually defines a non-existent email address on the remote side.|
|USER_NOT_LOCAL_TRY_ALTERNATE_PATH|"User not local or invalid address – Relay denied". <br/>            Meaning, if both your address and the recipient's are not locally hosted by the server, a relay can be interrupted.|
|EXCEEDED_STORAGE_ALLOCATION|"Requested mail actions aborted – Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits.|
|MAILBOX_NAME_NOT_ALLOWED|"Requested action not taken – Mailbox name invalid". <br/>            That is, there's an incorrect email address into the recipients line.|
|TRANSACTION_FAILED|This means that the transaction has failed. <br/>            It's a permanent error and the server will not try to send the message again.|

### See Also

* namespace [aspose.email.clients.smtp](/python-net/aspose.email.clients.smtp/)
* assembly [Aspose.Email](/python-net/)

