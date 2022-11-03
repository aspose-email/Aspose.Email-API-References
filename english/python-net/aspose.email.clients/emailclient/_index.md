---
title: EmailClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 30
url: /email/python-net/aspose.email.clients/emailclient/
---

## EmailClient class

Represents the client that creates server connection by using the host credentials.

The EmailClient type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|enable_logger|Gets or sets value which allows enable/disable logger|
|log_file_name|Gets or sets log file name|
|use_date_in_log_file_name|Gets or sets value which indicates if date has to be used in log file name.|
|supported_encryption|Defines the versions of SSL/TLS encryption protocols to be used.<br/>            PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework.<br/>            IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED.<br/>            IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!!<br/>            Please, see|
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
|greeting_timeout|Gets or sets the greeting timeout that is used when establishing a connection.<br/>            Please note, greeting timeout can't be infinite.<br/>            <br/>            Email clients may execute enough long operations. To limit the time of operations users have to use|
|password|Gets or sets the password.<br/>            Password limitations are defined by server implementation, which  client connects.|
|access_token|Gets or sets the access token.|
|token_provider|Gets or sets TokenProvider allowing to retrieve access token.|
|username|Gets or sets the username.|
|connection_state|Gets the current state of the connection.|
|current_connection|Gets current connection according to ConnectionAsgmtMode option|
|connection_asgmt_mode|Gets or sets value which defines mode of connection allocation in multiple threads environment<br/>            <br/>            There are folowing connection types:<br/>            <br/>            - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually.<br/>            <br/>            - Default connection is connection default for some thread.<br/>              If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection.<br/>              Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. <br/>              These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method.<br/>              If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it.<br/>              <br/>            - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. <br/>              These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method.<br/>            <br/>            There are folowing connection allocation types:<br/>            <br/>            - ConnectionAsgmtType.UseMainOrDefault<br/>            <br/>            This mode uses by default in email clients.<br/>            Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User can create default connections for threads with CreateConnection method. <br/>            If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.<br/>            If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread.<br/>            User also can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm.<br/>            To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread.<br/>            <br/>            - ConnectionAsgmtType.UseMain<br/>            <br/>            Email client uses main connection for all operations from multiple threads. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User cann't create default connections.<br/>            User can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. <br/>            <br/>            - ConnectionAsgmtType.UseDefault<br/>            <br/>            Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode.<br/>            If default connection hasn't been created for some thread (first invocation of email client method), <br/>            email client creates default connection implicitly for thread before first operation is executed.<br/>            User can't create default connections for threads with CreateConnection method because they are created automatically. <br/>            When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read.<br/>            User also can create connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm.<br/>            To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.|
|use_multi_connection|Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. <br/>            Please note, using of this mode not necessary has to lead to performance increasing.|
|connections_quantity|Gets or sets quantity of connections in multy-connection mode|
## Methods
| Name | Description |
| :- | :- |
|noop()|  |
|noop(connection)|  |
|create_connection()|  |
|create_connection(create_as_default_connection)|  |
|reset_log_settings()|  |
|set_supported_encryption_unsafe(value)|Defines the versions of SSL/TLS encryption protocols to be used.<br/>            This method is not safe and sets the encryption protocols without any compatibility checks.<br/>            Use|
|get_capabilities()|  |
|validate_credentials()|  |

### See Also

* namespace [aspose.email.clients](/email/python-net/aspose.email.clients/)
* assembly [Aspose.Email](/slides/python-net/)

