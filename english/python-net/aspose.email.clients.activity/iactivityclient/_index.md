---
title: IActivityClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/aspose.email.clients.activity/iactivityclient/
---

## IActivityClient class

Represents the interface for Exchange REST client.

The IActivityClient type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|multiple_services_token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|timeout|Gets or sets the number of milliseconds to wait before the operation times out.<br/>            The default value is 100,000 milliseconds (100 seconds).|
|tenant_id|Gets or sets tenant identifier|
|resource_id|Gets or sets resource id.<br/>            For instance for users it may be user principal name (UPN) or user id|
## Methods
| Name | Description |
| :- | :- |
|list_content(content_type)|  |
|list_content(content_type, start_time, end_time)|  |
|list_friendly_names()|  |
|list_subscriptions()|  |
|start_subscription(content_type, webhook)|  |
|stop_subscription(content_type)|  |
|fetch_content(content_id)|  |

### See Also

* namespace [aspose.email.clients.activity](/email/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/email/python-net/)

