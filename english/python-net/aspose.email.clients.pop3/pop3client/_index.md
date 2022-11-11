---
title: Pop3Client
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 20
url: /python-net/aspose.email.clients.pop3/pop3client/
---

## Pop3Client class

Allows applications to access and manipulate <br/>            messages by using the Post Office Protocol Version 3 (POP3).

The Pop3Client type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Pop3Client()|Initializes a new instance of the [Pop3Client](/email/python-net/aspose.email.clients.pop3/pop3client/) class|
|Pop3Client(host)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, security_options)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port, security_options)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, username, password)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, username, password, security_options)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port, username, password)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port, username, password, security_options)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port, username, auth_info, use_o_auth, security_options)|Initializes a new instance of the Pop3Client class|
|Pop3Client(host, port, username, token_provider, security_options)|Initializes a new instance of the Pop3Client class|
## Properties
| Name | Description |
| :- | :- |
|enable_logger|Gets or sets value which allows enable/disable logger|
|log_file_name|Gets or sets log file name|
|use_date_in_log_file_name|Gets or sets value which indicates if date has to be used in log file name.|
|supported_encryption|Defines the versions of SSL/TLS encryption protocols to be used.<br/>            PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework.<br/>            IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED.<br/>            IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!!<br/>            Please, see [EncryptionProtocols](/email/python-net/aspose.email.clients.base/encryptionprotocols/) documentation for more details.<br/>            Please use|
|use_pipelining|Gets or sets object which indicates whether the pipelining mode is enabled.|
|host|Gets or sets the host name.|
|default_port|Gets default port for client|
|port|Gets or sets the port.|
|security_options|Security mode for a mail client|
|use_authentication|Indicates whether authentication is used.|
|connection_checkup_period|Period of connection checking up in milliseconds.<br/>            Default value is 5 min.|
|use_default_credentials|Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests.<br/>            This option is used with NTLM authentication ONLY!|
|proxy|Gets or sets proxy for the client|
|timeout|Gets or sets the timeout for mail operations|
|greeting_timeout|Gets or sets the greeting timeout that is used when establishing a connection.<br/>            Please note, greeting timeout can't be infinite.<br/>            <br/>            Email clients may execute enough long operations. To limit the time of operations users have to use [timeout](/email/python-net/aspose.email.clients/emailclient/) property. <br/>            Values for this property have to have long intervals to not prevent long-time operations. <br/>            But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. <br/>            For instance, the mail client may use the automatic mode to connection establishing. <br/>            In this mode, the email client goes through all possible connection parameters until the connection is established. <br/>            SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. <br/>            Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. <br/>            If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish <br/>            a non-secured or explicit SSL connection), the server won't send a greeting string. <br/>            In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. <br/>            To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, <br/>            and reduce the time of automatic connection establishment.|
|password|Gets or sets the password.<br/>            Password limitations are defined by server implementation, which  client connects.|
|access_token|Gets or sets the access token.|
|token_provider|Gets or sets TokenProvider allowing to retrieve access token.|
|username|Gets or sets the username.|
|connection_state|Gets the current state of the connection.|
|current_connection|Gets current connection according to ConnectionAsgmtMode option|
|connection_asgmt_mode|Gets or sets value which defines mode of connection allocation in multiple threads environment<br/>            <br/>            There are folowing connection types:<br/>            <br/>            - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually.<br/>            <br/>            - Default connection is connection default for some thread.<br/>              If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection.<br/>              Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. <br/>              These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method.<br/>              If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it.<br/>              <br/>            - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. <br/>              These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method.<br/>            <br/>            There are folowing connection allocation types:<br/>            <br/>            - ConnectionAsgmtType.UseMainOrDefault<br/>            <br/>            This mode uses by default in email clients.<br/>            Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User can create default connections for threads with CreateConnection method. <br/>            If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.<br/>            If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread.<br/>            User also can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm.<br/>            To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread.<br/>            <br/>            - ConnectionAsgmtType.UseMain<br/>            <br/>            Email client uses main connection for all operations from multiple threads. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User cann't create default connections.<br/>            User can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. <br/>            <br/>            - ConnectionAsgmtType.UseDefault<br/>            <br/>            Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode.<br/>            If default connection hasn't been created for some thread (first invocation of email client method), <br/>            email client creates default connection implicitly for thread before first operation is executed.<br/>            User can't create default connections for threads with CreateConnection method because they are created automatically. <br/>            When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read.<br/>            User also can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm.<br/>            To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.|
|use_multi_connection|Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. <br/>            Please note, using of this mode not necessary has to lead to performance increasing.|
|connections_quantity|Gets or sets quantity of connections in multy-connection mode|
|allowed_authentication|Gets or sets enumeration of allowed by user authentication types|
|supported_authentication|Gets enumeration of supported by server authentication types|
## Methods
| Name | Description |
| :- | :- |
|noop(connection)|  |
|noop()|  |
|validate_credentials(connection)|  |
|validate_credentials()|  |
|create_connection()|  |
|create_connection(create_as_default_connection)|  |
|commit_deletes(sleep)|  |
|commit_deletes(connection)|  |
|commit_deletes()|  |
|delete_message(connection, sequence_number)|  |
|delete_message(connection, unique_id)|  |
|delete_message(sequence_number)|  |
|delete_message(unique_id)|  |
|delete_messages(connection)|  |
|delete_messages()|  |
|fetch_message(connection, unique_id)|  |
|fetch_message(connection, sequence_number)|  |
|fetch_message(unique_id)|  |
|fetch_message(sequence_number)|  |
|fetch_messages(sequence_numbers)|  |
|fetch_messages(uids)|  |
|fetch_messages(connection, sequence_numbers)|  |
|fetch_messages(connection, uids)|  |
|get_mailbox_info(connection)|  |
|get_mailbox_info(connection, close_transaction)|  |
|get_mailbox_info(close_transaction)|  |
|get_mailbox_info()|  |
|get_mailbox_size(connection)|  |
|get_mailbox_size()|  |
|get_message_count(connection)|  |
|get_message_count(connection, close_transaction)|  |
|get_message_count()|  |
|get_message_count(close_transaction)|  |
|get_message_headers(connection, sequence_number)|  |
|get_message_headers(sequence_number)|  |
|get_message_headers(connection, unique_id)|  |
|get_message_headers(unique_id)|  |
|get_message_size(connection, unique_id)|  |
|get_message_size(unique_id)|  |
|get_message_size(connection, sequence_number)|  |
|get_message_size(sequence_number)|  |
|get_message_unique_id(connection, sequence_number)|  |
|get_message_unique_id(sequence_number)|  |
|get_message_info(connection, unique_id, fields)|  |
|get_message_info(connection, unique_id)|  |
|get_message_info(unique_id)|  |
|get_message_info(unique_id, fields)|  |
|get_message_info(connection, sequence_number, fields)|  |
|get_message_info(connection, sequence_number)|  |
|get_message_info(sequence_number)|  |
|get_message_info(sequence_number, fields)|  |
|list_messages(unique_id_lst)|  |
|list_messages(sequence_number_lst)|  |
|list_messages(connection, unique_id_lst)|  |
|list_messages(connection, sequence_number_lst)|  |
|list_messages(connection)|  |
|list_messages(connection, close_transaction)|  |
|list_messages(connection, query)|  |
|list_messages(connection, fields)|  |
|list_messages(connection, fields, close_transaction, query)|  |
|list_messages()|  |
|list_messages(close_transaction)|  |
|list_messages(query)|  |
|list_messages(fields)|  |
|list_messages(fields, close_transaction, query)|  |
|load_message_info_list(sequence_number_list)|  |
|load_message_info_list(connection, sequence_number_list)|  |
|load_message_info_list(message_info_list)|  |
|load_message_info_list(connection, message_info_list)|  |
|save_message(connection, unique_id, output_stream)|  |
|save_message(connection, unique_id, file_name)|  |
|save_message(connection, sequence_number, output_stream)|  |
|save_message(connection, sequence_number, file_name)|  |
|save_message(unique_id, output_stream)|  |
|save_message(unique_id, file_name)|  |
|save_message(sequence_number, output_stream)|  |
|save_message(sequence_number, file_name)|  |
|undelete_messages(connection)|  |
|undelete_messages()|  |
|reset_log_settings()|  |
|set_supported_encryption_unsafe(value)|  |
|get_capabilities()|  |

### See Also

* namespace [aspose.email.clients.pop3](/email/python-net/aspose.email.clients.pop3/)
* assembly [Aspose.Email](/email/python-net/)

