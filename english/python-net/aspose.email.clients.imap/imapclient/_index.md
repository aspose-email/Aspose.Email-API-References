---
title: ImapClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /email/python-net/aspose.email.clients.imap/imapclient/
---

## ImapClient class

Allows applications to access and manipulate <br/>            messages by using the Internet Message Access Protocol (IMAP).

The ImapClient type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ImapClient()|Initializes a new instance of the|
|ImapClient(host)|Initializes a new instance of the ImapClient class|
|ImapClient(host, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, password)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, password, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, password)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, password, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, auth_info, use_o_auth)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, auth_info, use_o_auth, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, auth_info, use_o_auth)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, auth_info, use_o_auth, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, token_provider)|Initializes a new instance of the ImapClient class|
|ImapClient(host, username, token_provider, security_options)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, token_provider)|Initializes a new instance of the ImapClient class|
|ImapClient(host, port, username, token_provider, security_options)|Initializes a new instance of the ImapClient class|
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
|delimiter|Gets or sets delimiter of folders hierarhy.|
|auto_commit|Indicates, whether commit operation are executed automatically <br/>            when folder is changed or before connection is closed.|
|read_only|Gets or sets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted.|
|gm_ext_1_supported|Defines if Google X-GM-EXT-1 extension is supported|
|thread_algorithms|Gets supported thread algorithms|
|thread_supported|Gets information whether Thread command are supported|
|sort_supported|Gets information whether Sort command are supported|
|quota_supported|Gets information whether quota is supported|
|extended_list_supported|Gets information whether LIST Command Extension is supported<br/>            See more https://tools.ietf.org/html/rfc5258|
|special_use_supported|Gets information whether Special-Use Mailboxes is supported<br/>            See more: https://tools.ietf.org/html/rfc6154|
|id_supported|Gets information whether ID extension is supported<br/>            See more: https://tools.ietf.org/html/rfc2971|
|namespace_supported|Gets information whether NAMESPACE extension is supported<br/>            See more: https://tools.ietf.org/html/rfc2342|
|unselect_supported|Gets information whether UNSELECT extension is supported<br/>            See more: https://tools.ietf.org/html/rfc2342|
|sasl_ir_supported|Gets information whether SASL Initial Client Response extension is supported<br/>            See more: https://tools.ietf.org/html/rfc4959|
|move_supported|Gets information whether MOVE extension is supported<br/>            See more: https://tools.ietf.org/html/rfc6851|
|condstore_supported|Gets information whether CONDSTORE extension is supported<br/>            See more: https://tools.ietf.org/html/rfc7162|
|qresync_supported|Gets information whether QRESYNC extension is supported<br/>            See more: https://tools.ietf.org/html/rfc7162|
|annotate_supported|Gets information whether ANNOTATE extension is supported<br/>            See more: https://tools.ietf.org/html/rfc5257|
|uid_plus_supported|Gets information whether UIDPLUS extension is supported<br/>            See more: https://tools.ietf.org/html/rfc4315|
|enable_supported|Gets information whether ENABLE extension is supported<br/>            See more: https://tools.ietf.org/html/rfc5161|
|children_supported|Gets information whether CHILDREN extension is supported<br/>            See more: https://tools.ietf.org/html/rfc3348|
|e_search_supported|Gets information whether ESEARCH extension is supported<br/>            See more: https://tools.ietf.org/html/rfc4731|
|compress_supported|Gets information whether COMPRESS extension is supported<br/>            See more: https://tools.ietf.org/html/rfc4978|
|server_supported_compression|Gets information which compression types are supported by a server.<br/>            See more: https://tools.ietf.org/html/rfc4978|
|exchange_id_automatically|Gets or sets value which indicates whether client should to introduce information about itself to a server automatically. <br/>            See more: https://tools.ietf.org/html/rfc2971|
|client_identification_info|Gets or sets client identification information<br/>            See more: https://tools.ietf.org/html/rfc2971|
|server_identification_info|Gets server identification information<br/>            See more: https://tools.ietf.org/html/rfc2971|
|mailbox_info|Gets set of special-use mailboxes<br/>            See more: http://tools.ietf.org/html/rfc6154 and https://tools.ietf.org/html/rfc8457|
|default_folder|Default folder for ImapClients|
|current_folder|Gets the current folder|
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
|add_message_flags(connection, sequence_number, flags)|  |
|add_message_flags(connection, unique_id, flags)|  |
|add_message_flags(sequence_number, flags)|  |
|add_message_flags(unique_id, flags)|  |
|add_message_flags(connection, sequence_number, flags, modification_sequence)|  |
|add_message_flags(connection, unique_id, flags, modification_sequence)|  |
|add_message_flags(sequence_number, flags, modification_sequence)|  |
|add_message_flags(unique_id, flags, modification_sequence)|  |
|add_message_flags(start_uid, end_uid, flags)|  |
|add_message_flags(start_sequence, end_sequence, flags)|  |
|add_message_flags(connection, start_uid, end_uid, flags)|  |
|add_message_flags(connection, start_sequence, end_sequence, flags)|  |
|add_message_flags(start_uid, end_uid, flags, modification_sequence)|  |
|add_message_flags(start_sequence, end_sequence, flags, modification_sequence)|  |
|add_message_flags(connection, start_uid, end_uid, flags, modification_sequence)|  |
|add_message_flags(connection, start_sequence, end_sequence, flags, modification_sequence)|  |
|add_message_flags(uid_set, flags)|  |
|add_message_flags(sequence_set, flags)|  |
|add_message_flags(connection, uid_set, flags)|  |
|add_message_flags(connection, sequence_set, flags)|  |
|add_message_flags(uid_set, flags, modification_sequence)|  |
|add_message_flags(sequence_set, flags, modification_sequence)|  |
|add_message_flags(connection, uid_set, flags, modification_sequence)|  |
|add_message_flags(connection, sequence_set, flags, modification_sequence)|  |
|add_message_flags(message_info_set, flags)|  |
|add_message_flags(connection, message_info_set, flags)|  |
|add_message_flags(message_info_set, flags, modification_sequence)|  |
|add_message_flags(connection, message_info_set, flags, modification_sequence)|  |
|append_message(connection, message)|  |
|append_message(connection, folder_name, message)|  |
|append_message(connection, file_name)|  |
|append_message(connection, folder_name, file_name)|  |
|append_message(message)|  |
|append_message(folder_name, message)|  |
|append_message(file_name)|  |
|append_message(folder_name, file_name)|  |
|append_messages(connection, messages)|  |
|append_messages(connection, folder_name, messages)|  |
|append_messages(messages)|  |
|append_messages(folder_name, messages)|  |
|backup(connection, folders, file_name, options)|  |
|backup(connection, folders, stream, options)|  |
|backup(folders, file_name, options)|  |
|backup(folders, stream, options)|  |
|change_message_flags(unique_id, flags)|  |
|change_message_flags(sequence_number, flags)|  |
|change_message_flags(connection, unique_id, flags)|  |
|change_message_flags(connection, sequence_number, flags)|  |
|change_message_flags(unique_id, flags, modification_sequence)|  |
|change_message_flags(sequence_number, flags, modification_sequence)|  |
|change_message_flags(connection, unique_id, flags, modification_sequence)|  |
|change_message_flags(connection, sequence_number, flags, modification_sequence)|  |
|change_message_flags(start_uid, end_uid, flags)|  |
|change_message_flags(start_sequence, end_sequence, flags)|  |
|change_message_flags(connection, start_uid, end_uid, flags)|  |
|change_message_flags(connection, start_sequence, end_sequence, flags)|  |
|change_message_flags(start_uid, end_uid, flags, modification_sequence)|  |
|change_message_flags(start_sequence, end_sequence, flags, modification_sequence)|  |
|change_message_flags(connection, start_uid, end_uid, flags, modification_sequence)|  |
|change_message_flags(connection, start_sequence, end_sequence, flags, modification_sequence)|  |
|change_message_flags(uid_set, flags)|  |
|change_message_flags(sequence_set, flags)|  |
|change_message_flags(connection, uid_set, flags)|  |
|change_message_flags(connection, sequence_set, flags)|  |
|change_message_flags(uid_set, flags, modification_sequence)|  |
|change_message_flags(sequence_set, flags, modification_sequence)|  |
|change_message_flags(connection, uid_set, flags, modification_sequence)|  |
|change_message_flags(connection, sequence_set, flags, modification_sequence)|  |
|change_message_flags(message_info_set, flags)|  |
|change_message_flags(connection, message_info_set, flags)|  |
|change_message_flags(message_info_set, flags, modification_sequence)|  |
|change_message_flags(connection, message_info_set, flags, modification_sequence)|  |
|client_capabilities(capability_names)|  |
|client_capabilities(connection, capability_names)|  |
|commit_deletes(connection)|  |
|commit_deletes(connection, sleep)|  |
|commit_deletes()|  |
|commit_deletes(sleep)|  |
|commit_deletes(uid_set)|  |
|commit_deletes(unique_id)|  |
|commit_deletes(start_uid, end_uid)|  |
|commit_deletes(connection, uid_set)|  |
|commit_deletes(connection, unique_id)|  |
|commit_deletes(connection, start_uid, end_uid)|  |
|copy_message(connection, sequence_number, folder_name)|  |
|copy_message(connection, unique_id, folder_name)|  |
|copy_message(sequence_number, folder_name)|  |
|copy_message(unique_id, folder_name)|  |
|copy_messages(connection, start_sequence, end_sequence, folder_name)|  |
|copy_messages(start_sequence, end_sequence, folder_name)|  |
|copy_messages(connection, start_uid, end_uid, folder_name)|  |
|copy_messages(start_uid, end_uid, folder_name)|  |
|copy_messages(sequence_set, folder_name, commit_deletions)|  |
|copy_messages(connection, sequence_set, folder_name)|  |
|copy_messages(sequence_set, folder_name)|  |
|copy_messages(connection, uid_set, folder_name)|  |
|copy_messages(uid_set, folder_name)|  |
|copy_messages(connection, message_info_set, folder_name)|  |
|copy_messages(message_info_set, folder_name)|  |
|create_folder(connection, folder_name)|  |
|create_folder(folder_name)|  |
|delete_folder(connection, folder_name)|  |
|delete_folder(folder_name)|  |
|delete_message(connection, sequence_number)|  |
|delete_message(connection, unique_id)|  |
|delete_message(sequence_number)|  |
|delete_message(unique_id)|  |
|delete_message(connection, sequence_number, modification_sequence)|  |
|delete_message(connection, unique_id, modification_sequence)|  |
|delete_message(sequence_number, modification_sequence)|  |
|delete_message(unique_id, modification_sequence)|  |
|delete_message(unique_id, commit_now)|  |
|delete_message(connection, unique_id, commit_now)|  |
|delete_message(unique_id, modification_sequence, commit_now)|  |
|delete_message(connection, unique_id, modification_sequence, commit_now)|  |
|delete_messages(connection, sequence_set)|  |
|delete_messages(connection, uid_set)|  |
|delete_messages(sequence_set)|  |
|delete_messages(uid_set)|  |
|delete_messages(connection, sequence_set, modification_sequence)|  |
|delete_messages(connection, uid_set, modification_sequence)|  |
|delete_messages(sequence_set, modification_sequence)|  |
|delete_messages(uid_set, modification_sequence)|  |
|delete_messages(uid_set, commit_now)|  |
|delete_messages(connection, uid_set, commit_now)|  |
|delete_messages(uid_set, modification_sequence, commit_now)|  |
|delete_messages(connection, uid_set, modification_sequence, commit_now)|  |
|delete_messages(connection, start_sequence, end_sequence)|  |
|delete_messages(connection, start_uid, end_uid)|  |
|delete_messages(start_sequence, end_sequence)|  |
|delete_messages(start_uid, end_uid)|  |
|delete_messages(connection, start_sequence, end_sequence, modification_sequence)|  |
|delete_messages(connection, start_uid, end_uid, modification_sequence)|  |
|delete_messages(start_sequence, end_sequence, modification_sequence)|  |
|delete_messages(start_uid, end_uid, modification_sequence)|  |
|delete_messages(start_uid, end_uid, commit_now)|  |
|delete_messages(connection, start_uid, end_uid, commit_now)|  |
|delete_messages(start_uid, end_uid, modification_sequence, commit_now)|  |
|delete_messages(connection, start_uid, end_uid, modification_sequence, commit_now)|  |
|delete_messages(connection, message_info_set)|  |
|delete_messages(message_info_set)|  |
|delete_messages(connection, message_info_set, modification_sequence)|  |
|delete_messages(message_info_set, modification_sequence)|  |
|delete_messages(message_info_set, commit_now)|  |
|delete_messages(connection, message_info_set, commit_now)|  |
|delete_messages(message_info_set, modification_sequence, commit_now)|  |
|delete_messages(connection, message_info_set, modification_sequence, commit_now)|  |
|exist_folder(folder_name)|  |
|exist_folder(folder_name, folder_info)|  |
|exist_folder(connection, folder_name)|  |
|exist_folder(connection, folder_name, folder_info)|  |
|fetch_attachment(connection, sequence_number, attachment_name)|  |
|fetch_attachment(sequence_number, attachment_name)|  |
|fetch_message(connection, sequence_number)|  |
|fetch_message(connection, sequence_number, ignore_attachment)|  |
|fetch_message(sequence_number)|  |
|fetch_message(sequence_number, ignore_attachment)|  |
|fetch_message(connection, unique_id)|  |
|fetch_message(unique_id)|  |
|fetch_messages(sequence_numbers)|  |
|fetch_messages(uids)|  |
|fetch_messages(connection, sequence_numbers)|  |
|fetch_messages(connection, uids)|  |
|get_folder_info(connection, folder_name)|  |
|get_folder_info(folder_name)|  |
|get_message_threads(conditions)|  |
|get_message_threads(connection, conditions)|  |
|get_namespaces()|  |
|get_namespaces(connection)|  |
|get_quota(connection, quota_root_name)|  |
|get_quota(quota_root_name)|  |
|get_quota_root(connection, mailbox_name)|  |
|get_quota_root(mailbox_name)|  |
|stop_monitoring(folder_name)|  |
|stop_monitoring()|  |
|introduce_client()|  |
|introduce_client(connection)|  |
|introduce_client(client_identification_info)|  |
|introduce_client(connection, client_identification_info)|  |
|list_folders(connection)|  |
|list_folders(connection, parent_folder)|  |
|list_folders(connection, load_full_info)|  |
|list_folders()|  |
|list_folders(parent_folder)|  |
|list_folders(load_full_info)|  |
|list_folders(parent_folder, load_full_info)|  |
|list_folders(connection, parent_folder, load_full_info)|  |
|list_folders(parent_folder, load_full_info, options, return_options)|  |
|list_folders(connection, parent_folder, load_full_info, options, return_options)|  |
|list_message(connection, sequence_number, message_extra_fields)|  |
|list_message(connection, sequence_number)|  |
|list_message(sequence_number, message_extra_fields)|  |
|list_message(sequence_number)|  |
|list_message(connection, unique_id, message_extra_fields)|  |
|list_message(connection, unique_id)|  |
|list_message(unique_id)|  |
|list_message(unique_id, message_extra_fields)|  |
|list_messages(folder_name, fields_list, max_number_of_messages)|  |
|list_messages(connection, folder_name, fields_list, max_number_of_messages)|  |
|list_messages(folder_name, unique_id_lst)|  |
|list_messages(folder_name, sequence_number_lst)|  |
|list_messages(connection, folder_name, unique_id_lst)|  |
|list_messages(connection, folder_name, sequence_number_lst)|  |
|list_messages(connection, folder_name, modification_sequence, retrieve_recursively, message_extra_fields)|  |
|list_messages(connection)|  |
|list_messages(connection, folder_name)|  |
|list_messages(connection, retrieve_recursively)|  |
|list_messages(connection, modification_sequence)|  |
|list_messages(connection, folder_name, retrieve_recursively)|  |
|list_messages()|  |
|list_messages(message_extra_fields)|  |
|list_messages(retrieve_recursively)|  |
|list_messages(folder_name)|  |
|list_messages(folder_name, retrieve_recursively)|  |
|list_messages(folder_name, retrieve_recursively, message_extra_fields)|  |
|list_messages(modification_sequence)|  |
|list_messages(connection, folder_name, query, max_number_of_messages)|  |
|list_messages(connection, query)|  |
|list_messages(connection, query, max_number_of_messages)|  |
|list_messages(query)|  |
|list_messages(folder_name, query, max_number_of_messages)|  |
|list_messages(query, max_number_of_messages)|  |
|list_messages(connection, max_number_of_messages)|  |
|list_messages(max_number_of_messages)|  |
|list_messages_by_page(items_per_page, settings)|  |
|list_messages_by_page(items_per_page, page_offset, settings)|  |
|list_messages_by_page(page_info, settings)|  |
|list_messages_by_page(query, page_info, settings)|  |
|move_folder(new_parent_folder, folder_name)|  |
|move_folder(connection, new_parent_folder, folder_name)|  |
|move_message(connection, sequence_number, folder_name, commit_deletions)|  |
|move_message(connection, unique_id, folder_name, commit_deletions)|  |
|move_message(sequence_number, folder_name, commit_deletions)|  |
|move_message(unique_id, folder_name, commit_deletions)|  |
|move_message(connection, sequence_number, folder_name)|  |
|move_message(connection, unique_id, folder_name)|  |
|move_message(sequence_number, folder_name)|  |
|move_message(unique_id, folder_name)|  |
|move_messages(connection, start_sequence, end_sequence, folder_name, commit_deletions)|  |
|move_messages(start_sequence, end_sequence, folder_name, commit_deletions)|  |
|move_messages(connection, start_sequence, end_sequence, folder_name)|  |
|move_messages(start_sequence, end_sequence, folder_name)|  |
|move_messages(connection, sequence_set, folder_name, commit_deletions)|  |
|move_messages(sequence_set, folder_name, commit_deletions)|  |
|move_messages(connection, sequence_set, folder_name)|  |
|move_messages(sequence_set, folder_name)|  |
|move_messages(connection, start_uid, end_uid, folder_name, commit_deletions)|  |
|move_messages(start_uid, end_uid, folder_name, commit_deletions)|  |
|move_messages(connection, start_uid, end_uid, folder_name)|  |
|move_messages(start_uid, end_uid, folder_name)|  |
|move_messages(connection, uid_set, folder_name, commit_deletions)|  |
|move_messages(uid_set, folder_name, commit_deletions)|  |
|move_messages(connection, uid_set, folder_name)|  |
|move_messages(uid_set, folder_name)|  |
|move_messages(connection, message_info_set, folder_name, commit_deletions)|  |
|move_messages(message_info_set, folder_name, commit_deletions)|  |
|move_messages(connection, message_info_set, folder_name)|  |
|move_messages(message_info_set, folder_name)|  |
|remove_message_flags(connection, sequence_number, flags)|  |
|remove_message_flags(connection, unique_id, flags)|  |
|remove_message_flags(sequence_number, flags)|  |
|remove_message_flags(unique_id, flags)|  |
|remove_message_flags(connection, sequence_number, flags, modification_sequence)|  |
|remove_message_flags(connection, unique_id, flags, modification_sequence)|  |
|remove_message_flags(sequence_number, flags, modification_sequence)|  |
|remove_message_flags(unique_id, flags, modification_sequence)|  |
|remove_message_flags(start_uid, end_uid, flags)|  |
|remove_message_flags(start_sequence, end_sequence, flags)|  |
|remove_message_flags(connection, start_uid, end_uid, flags)|  |
|remove_message_flags(connection, start_sequence, end_sequence, flags)|  |
|remove_message_flags(start_uid, end_uid, flags, modification_sequence)|  |
|remove_message_flags(start_sequence, end_sequence, flags, modification_sequence)|  |
|remove_message_flags(connection, start_uid, end_uid, flags, modification_sequence)|  |
|remove_message_flags(connection, start_sequence, end_sequence, flags, modification_sequence)|  |
|remove_message_flags(uid_set, flags)|  |
|remove_message_flags(sequence_set, flags)|  |
|remove_message_flags(connection, uid_set, flags)|  |
|remove_message_flags(connection, sequence_set, flags)|  |
|remove_message_flags(uid_set, flags, modification_sequence)|  |
|remove_message_flags(sequence_set, flags, modification_sequence)|  |
|remove_message_flags(connection, uid_set, flags, modification_sequence)|  |
|remove_message_flags(connection, sequence_set, flags, modification_sequence)|  |
|remove_message_flags(message_info_set, flags)|  |
|remove_message_flags(connection, message_info_set, flags)|  |
|remove_message_flags(message_info_set, flags, modification_sequence)|  |
|remove_message_flags(connection, message_info_set, flags, modification_sequence)|  |
|rename_folder(connection, folder_name, new_folder_name)|  |
|rename_folder(folder_name, new_folder_name)|  |
|request_checkpoint(connection)|  |
|request_checkpoint()|  |
|save_message(connection, sequence_number, result_stream)|  |
|save_message(connection, unique_id, result_stream)|  |
|save_message(connection, unique_id, file_name)|  |
|save_message(connection, sequence_number, file_name)|  |
|save_message(sequence_number, result_stream)|  |
|save_message(unique_id, result_stream)|  |
|save_message(unique_id, file_name)|  |
|save_message(sequence_number, file_name)|  |
|select_folder(connection, folder_name)|  |
|select_folder(connection, folder_name, read_only)|  |
|select_folder(folder_name)|  |
|select_folder(folder_name, read_only)|  |
|set_quota(connection, quota_root_name, resource_name, resource_limit)|  |
|set_quota(quota_root_name, resource_name, resource_limit)|  |
|sort_message_threads(conditions)|  |
|sort_message_threads(connection, conditions)|  |
|subscribe_folder(connection, folder_name)|  |
|subscribe_folder(folder_name)|  |
|undelete_message(connection, sequence_number)|  |
|undelete_message(connection, unique_id)|  |
|undelete_message(sequence_number)|  |
|undelete_message(unique_id)|  |
|undelete_message(connection, sequence_number, modification_sequence)|  |
|undelete_message(connection, unique_id, modification_sequence)|  |
|undelete_message(sequence_number, modification_sequence)|  |
|undelete_message(unique_id, modification_sequence)|  |
|unselect_folder(connection)|  |
|unselect_folder()|  |
|unselect_folder(connection, do_not_expunge)|  |
|unselect_folder(do_not_expunge)|  |
|unsubscribe_folder(connection, folder_name)|  |
|unsubscribe_folder(folder_name)|  |
|reset_log_settings()|  |
|set_supported_encryption_unsafe(value)|Defines the versions of SSL/TLS encryption protocols to be used.<br/>            This method is not safe and sets the encryption protocols without any compatibility checks.<br/>            Use|
|get_capabilities()|  |
|list_attachments(sequence_number)|  |
|restore(pst, settings)|  |

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/slides/python-net/)

