---
title: FileAsMapping
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 460
url: /python-net/aspose.email.personalinfo/fileasmapping/
---

## FileAsMapping enumeration

Specifies how to generate and recompute the value of the dispidFileAs property when other contact name properties change.<br/>            Coincides MS-OXPROPS revision 16.2 from 7/31/2014

## Members
| Member name | Description |
| :- | :- |
|EMPTY|Empty value.|
|DISPLAY_NAME|DisplayName|
|FIRST_NAME|GivenName|
|LAST_NAME|Surname|
|ORGANIZATION|CompanyName|
|FIRST_MIDDLE_LAST_GEN|GivenName MiddleName Surname Generation|
|LAST_FIRST_MIDDLE|Surname, GivenName MiddleName|
|LAST_FIRST_MIDDLE2|SurnameGivenName MiddleName|
|LAST_FIRST_MIDDLE3|Surname GivenName MiddleName|
|ORG_LAST_FIRST_MIDDLE|CompanyName\r\nSurname, GivenName MiddleName|
|ORG_LAST_FIRST_MIDDLE2|CompanyName\r\nSurnameGivenName MiddleName|
|ORG_LAST_FIRST_MIDDLE3|CompanyName\r\nSurname GivenName MiddleName|
|LAST_FIRST_MIDDLE_ORG|Surname, GivenName MiddleName\r\nCompanyName|
|LAST_FIRST_MIDDLE_ORG2|SurnameGivenName MiddleName\r\nCompanyName|
|LAST_FIRST_MIDDLE_ORG3|Surname GivenName PidTagMiddleName\r\nCompanyName|
|LAST_FIRST_MIDDLE_GEN|Surname GivenName MiddleName Generation|
|LAST_FIRST_MIDDLE_GEN2|SurnameGivenName MiddleName Generation|
|BEST_MATCH|Specifies that, when displaying the contact, <br/>            the application should attempt to use the current value of dispidFileUnder and other contact properties <br/>            to find a "best match" for dispidFileUnderId to one of the previous values in this table.|
|ACCORDING_TO_LOCALE|Specifies that, when displaying the contact, <br/>            the application should choose the appropriate default values (according to the language locale) <br/>            for dispidFileUnderId and update dispidFileUnder to match the choice.|
|NONE|Specifies that, FileUnder is a user-provided, and should not be changed when another contact name property changes.<br/>            I.e. value of FileUnder is not constructed from other properties.|

### See Also

* namespace [aspose.email.personalinfo](/email/python-net/aspose.email.personalinfo/)
* assembly [Aspose.Email](/email/python-net/)

