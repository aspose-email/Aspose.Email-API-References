---
title: IGraphClientAsync.ListCalendarItemsAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists MapiCalendar items from the calendar
type: docs
weight: 310
url: /net/aspose.email.clients.graph/igraphclientasync/listcalendaritemsasync/
---
## IGraphClientAsync.ListCalendarItemsAsync method

Asynchronously lists MapiCalendar items from the calendar.

```csharp
public Task<MapiCalendarCollection> ListCalendarItemsAsync(string id, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Calendar id. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering calendars. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of MapiCalendar of the calendar.

### See Also

* class [MapiCalendarCollection](../../../aspose.email.mapi/mapicalendarcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


