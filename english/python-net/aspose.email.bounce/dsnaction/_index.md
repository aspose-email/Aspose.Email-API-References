---
title: DSNAction
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 20
url: /python-net/aspose.email.bounce/dsnaction/
---

## DSNAction enumeration

Indicates the action performed by the Reporting-MTA as a result of its attempt to deliver the message.

## Members
| Member name | Description |
| :- | :- |
|NONE|None of actions.|
|DELAYED|Indicates that the Reporting MTA has so far been unable to deliver or relay the message, but it will continue to attempt to do so. Additional notification messages may be issued as the message is further delayed or successfully delivered, or if delivery attempts are later abandoned.|
|DELIVERED|Indicates that the message was successfully delivered to the recipient address specified by the sender, which includes "delivery" to a mailing list exploder. It does not indicate that the message has been read. This is a terminal state and no further DSN for this recipient should be expected.|
|EXPANDED|Indicates that the message has been successfully delivered to the recipient address as specified by the sender, and forwarded by the Reporting-MTA beyond that destination to multiple additional recipient addresses. An action-value of "expanded" differs from Delivered in that "expanded" is not a terminal state. Further "failed" and/or "delayed" notifications may be provided.|
|FAILED|Indicates that the message could not be delivered to the recipient. The Reporting MTA has abandoned any attempts to deliver the message to this recipient. No further notifications should be expected.|
|RELAYED|Indicates that the message has been relayed or gatewayed into an environment that does not accept responsibility for generating DSNs upon successful delivery. This action-value SHOULD NOT be used unless the sender has requested notification of successful delivery for this recipient.|

### See Also

* namespace [aspose.email.bounce](/email/python-net/aspose.email.bounce/)
* assembly [Aspose.Email](/email/python-net/)

