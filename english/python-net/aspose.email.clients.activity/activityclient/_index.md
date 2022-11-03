---
title: ActivityClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /email/python-net/aspose.email.clients.activity/activityclient/
---

## ActivityClient class

Provides access to MS Exchange Server (Office365) by using REST API.

The ActivityClient type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|timeout|Gets or sets the number of milliseconds to wait before the operation times out.<br/>            The default value is 100,000 milliseconds (100 seconds).|
|multiple_services_token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|tenant_id|Gets or sets tenant identifier|
|resource_id|Gets or sets resource id.<br/>            For instance for users it may be user principal name (UPN) or user id|
## Methods
| Name | Description |
| :- | :- |
|get_client(token_provider, tenant_id)|Initializes a new instance of the|
|get_client(token_provider, tenant_id)|Initializes a new instance of the|
|list_content(content_type)|  |
|list_content(content_type, start_time, end_time)|  |
|list_friendly_names()|  |
|list_subscriptions()|  |
|start_subscription(content_type, webhook)|  |
|stop_subscription(content_type)|  |
|fetch_content(content_id)|  |

### See Also

* namespace [aspose.email.clients.activity](/email/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/slides/python-net/)

