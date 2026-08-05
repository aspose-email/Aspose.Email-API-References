---
title: "DSNAction Enum"
linktitle: "DSNAction"
articleTitle: "DSNAction"
second_title: "Aspose.Email for C++"
description: "Indicates the action performed by the Reporting-MTA as a result of its attempt to deliver the message."
type: docs
weight: 10
url: /cpp/aspose.email.bounce/dsnaction/
---

## DSNAction enumeration (6 values)

Indicates the action performed by the Reporting-MTA as a result of its attempt to deliver the message.

| Value | Description |
| --- | --- |
| None | None of actions. |
| Delayed | Indicates that the Reporting MTA has so far been unable to deliver or relay the message, but it will continue to attempt to do so. Additional notification messages may be issued as the message is further delayed or successfully delivered, or if delivery attempts are later abandoned. |
| Delivered | Indicates that the message was successfully delivered to the recipient address specified by the sender, which includes "delivery" to a mailing list exploder. It does not indicate that the message has been read. This is a terminal state and no further DSN for this recipient should be expected. |
| Expanded | Indicates that the message has been successfully delivered to the recipient address as specified by the sender, and forwarded by the Reporting-MTA beyond that destination to multiple additional recipient addresses. An action-value of "expanded" differs from Delivered in that "expanded" is not a terminal state. Further "failed" and/or "delayed" notifications may be provided. |
| Failed | Indicates that the message could not be delivered to the recipient. The Reporting MTA has abandoned any attempts to deliver the message to this recipient. No further notifications should be expected. |
| Relayed | Indicates that the message has been relayed or gatewayed into an environment that does not accept responsibility for generating DSNs upon successful delivery. This action-value SHOULD NOT be used unless the sender has requested notification of successful delivery for this recipient. |

