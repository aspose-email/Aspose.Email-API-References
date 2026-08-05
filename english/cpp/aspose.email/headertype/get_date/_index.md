---
title: "Aspose::Email::HeaderType::get_Date method"
linktitle: "get_Date"
articleTitle: "get_Date"
second_title: "Aspose.Email for C++"
description: "This header specifies a date (and time), normally the date the message was composed and sent."
type: docs
weight: 90
url: /cpp/aspose.email/headertype/get_date/
---

## get_Date {#get_date}

This header specifies a date (and time), normally the date the message was composed and sent. In X.400 mail systems, the time a message was submitted. Some Internet mail systems also use the date when the message was submitted. If this header is omitted by the sender's computer, it might conceivably be added by a mail server or even by some other machine along the route. What you may not know is that the information in the "Date:" line is supplied by the time on the sender's computer, which may or may not be set correctly. Also, the "Date:" header does not normally indicate when the message was sent, but only when it was composed. The date is in the form 3 character day-of-week (Sun - Sat), day number (1-31) dd, 3-character month name, 4-digit year yyyy, followed by time (24-hour) hh:mm:ss and zone zzz format. Time Zone (zzz) is either the 3-character time zone or the local differential in hours and minutes offset from UTC (Universal Time Coordinated - old Greenwich Mean Time). "-" indicates west and "+" indicates east of UTC. No standard Time Zone definitions seem to exist. Many UNIX versions understand a great range of abbreviations, but the most exhaustive list I found was the GNU tar manual Timezone item and documentation for the Perl date manipulation module TIMEZONES.

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_Date()
```

