---
title: ConnectionAsgmtType
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 1610
url: /python-net/aspose.email.clients/connectionasgmttype/
---

## ConnectionAsgmtType enumeration

Defines algorithm of connection allocation in multiple threads environment

## Members
| Member name | Description |
| :- | :- |
|USE_MAIN_OR_DEFAULT|This mode uses by default in email clients.<br/>            <br/>            Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User can create default connections for threads with CreateConnection method. <br/>            If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.<br/>            If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread.<br/>            User also can create independent connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            <br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm because of thread may be reused in this case.<br/>            To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread.|
|USE_MAIN|Email client uses main connection for all operations from multiple threads. <br/>            Main connection is connection which is created in the same time like email client.<br/>            User cann't create default connections.<br/>            User can create independent connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections.|
|USE_DEFAULT|Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode.<br/>            If default connection hasn't been created for some thread (first invocation of email client method), <br/>            email client creates default connection implicitly for thread before first operation is executed.<br/>            User can't create default connections for threads with CreateConnection method because they are created automatically. <br/>            When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read.<br/>            User also can create independent connections not linked with threads (not default connections) with CreateConnection method. <br/>            If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use.<br/>            User can additionally create any number of connections. Default connection can be only one per thread.<br/>            <br/>            Please note default connections works correctly if user uses Thread objects for multitasking programming. <br/>            If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm because of thread may be reused in this case.<br/>            To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.|

### See Also

* namespace [aspose.email.clients](/email/python-net/aspose.email.clients/)
* assembly [Aspose.Email](/email/python-net/)

