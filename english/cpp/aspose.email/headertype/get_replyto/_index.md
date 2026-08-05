---
title: "Aspose::Email::HeaderType::get_ReplyTo method"
linktitle: "get_ReplyTo"
articleTitle: "get_ReplyTo"
second_title: "Aspose.Email for C++"
description: "This header field is meant to indicate where the sender wants replies to go."
type: docs
weight: 200
url: /cpp/aspose.email/headertype/get_replyto/
---

## get_ReplyTo {#get_replyto}

This header field is meant to indicate where the sender wants replies to go. Unfortunately, this is ambiguous, since there are different kinds of replies, which the sender may wish to go to different addresses. In particular, there are personal replies intended for only one person, and group replies, intended for the whole group of people who read the replied-to message (often a mailing list, anewsgroup name cannot appear here because of different syntax, see "FollowupTo" .).

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_ReplyTo()
```

