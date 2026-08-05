---
title: "Aspose::Email::Clients::Smtp::SmtpClient class"
linktitle: "SmtpClient"
articleTitle: "SmtpClient"
second_title: "Aspose.Email for C++"
description: "Allows applications to send messages by using the Simple Mail Transfer Protocol (SMTP)."
type: docs
weight: 10
url: /cpp/aspose.email.clients.smtp/smtpclient/
---

## SmtpClient class

**Inherits:** Aspose::Email::Clients::EmailClient, Aspose::Email::Clients::Smtp::IMailTransferAgent

Allows applications to send messages by using the Simple Mail Transfer Protocol (SMTP).

## Constructors

| Name | Description |
| --- | --- |
| [SmtpClient (17 overloads)](./smtpclient/) | Initializes a new instance of the SmtpClient class. |

## Methods

| Name | Description |
| --- | --- |
| [BeginForward (13 overloads)](./beginforward/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [BeginNoop (6 overloads)](./beginnoop/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [BeginSend (26 overloads)](./beginsend/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [BeginSendQueue (3 overloads)](./beginsendqueue/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [BeginValidateCredentials (6 overloads)](./beginvalidatecredentials/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [EndBeginSendQueue](./endbeginsendqueue/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [EndForward](./endforward/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [EndNoop](./endnoop/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [EndSend](./endsend/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [EndValidateCredentials](./endvalidatecredentials/) | Please note: this method is used only for the .NET framework with versions earlier than 4.5. |
| [Forward (6 overloads)](./forward/) | Forwards specified message to recipient |
| [get_AllowedAuthentication](./get_allowedauthentication/) | Gets enumeration of allowed by user authentication types |
| [get_DefaultPort](./get_defaultport/) | Gets default port for client |
| [get_DeliveryMethod](./get_deliverymethod/) | Gets the delivery method. |
| [get_HelloMessage](./get_hellomessage/) | Gets a HELO/EHLO string. |
| [get_PickupDirectoryLocation](./get_pickupdirectorylocation/) | Gets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed. |
| [get_Pool](./get_pool/) | Gets connection pool for the client |
| [get_SmtpQueueLocation](./get_smtpqueuelocation/) | Gets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed. |
| [get_SupportedAuthentication](./get_supportedauthentication/) | Gets enumeration of supported by server authentication types |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/) | Gets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [get_UseTnef](./get_usetnef/) | Gets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef. |
| [Noop (3 overloads)](./noop/) | 'No operation' command |
| [Send (10 overloads)](./send/) | Send the specified message. |
| [SendToQueue](./sendtoqueue/) | Append messages to queue |
| [set_AllowedAuthentication](./set_allowedauthentication/) | Sets enumeration of allowed by user authentication types |
| [set_DeliveryMethod](./set_deliverymethod/) | Sets the delivery method. |
| [set_HelloMessage](./set_hellomessage/) | Sets a HELO/EHLO string. |
| [set_PickupDirectoryLocation](./set_pickupdirectorylocation/) | Sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed. |
| [set_SmtpQueueLocation](./set_smtpqueuelocation/) | Sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/) | Sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [set_UseTnef](./set_usetnef/) | Sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef. |
| [ValidateCredentials (2 overloads)](./validatecredentials/) | Executes credentials validation |

