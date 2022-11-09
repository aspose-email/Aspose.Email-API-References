---
title: FreebusyQuery
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/aspose.email.clients.google/freebusyquery/
---

## FreebusyQuery class

Request free/busy information for a set of calendars.

The FreebusyQuery type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FreebusyQuery()|Initializes a new instance of the FreebusyQuery class.|
|FreebusyQuery(time_min, time_max, items)|Initializes a new instance of the FreebusyQuery class|
|FreebusyQuery(time_min, time_max, time_zone, items)|Initializes a new instance of the FreebusyQuery class|
|FreebusyQuery(time_min, time_max, time_zone, group_expansion_max, calendar_expansion_max, items)|Initializes a new instance of the FreebusyQuery class|
|FreebusyQuery(time_min, time_max, items)|Initializes a new instance of the FreebusyQuery class|
|FreebusyQuery(time_min, time_max, time_zone, items)|Initializes a new instance of the FreebusyQuery class|
|FreebusyQuery(time_min, time_max, time_zone, group_expansion_max, calendar_expansion_max, items)|Initializes a new instance of the FreebusyQuery class|
## Properties
| Name | Description |
| :- | :- |
|time_min|The start of the interval for the query.|
|time_max|The end of the interval for the query.|
|time_zone|Time zone used in the response. Optional. The default is UTC.|
|group_expansion_max|Maximal number of calendar identifiers to be provided for a single group. Optional. <br/>            An error will be returned for a group with more members than this value.|
|calendar_expansion_max|Maximal number of calendars for which FreeBusy information is to be provided. Optional.|
|items|List of calendars and/or groups to query.<br/>            Contains identifiers of a calendar or a group.|

### See Also

* namespace [aspose.email.clients.google](/python-net/aspose.email.clients.google/)
* assembly [Aspose.Email](/python-net/)

