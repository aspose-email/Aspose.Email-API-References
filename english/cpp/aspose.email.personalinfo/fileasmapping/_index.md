---
title: "FileAsMapping Enum"
linktitle: "FileAsMapping"
articleTitle: "FileAsMapping"
second_title: "Aspose.Email for C++"
description: "Specifies how to generate and recompute the value of the dispidFileAs property when other contact name properties change."
type: docs
weight: 10
url: /cpp/aspose.email.personalinfo/fileasmapping/
---

## FileAsMapping enumeration (20 values)

Specifies how to generate and recompute the value of the dispidFileAs property when other contact name properties change. Coincides MS-OXPROPS revision 16.2 from 7/31/2014

| Value | Description |
| --- | --- |
| Empty | Empty value. |
| DisplayName | DisplayName |
| FirstName | GivenName |
| LastName | Surname |
| Organization | CompanyName |
| FirstMiddleLastGen | GivenName MiddleName Surname Generation |
| LastFirstMiddle | Surname, GivenName MiddleName |
| LastFirstMiddle2 | SurnameGivenName MiddleName |
| LastFirstMiddle3 | Surname GivenName MiddleName |
| OrgLastFirstMiddle | CompanyName\r\nSurname, GivenName MiddleName |
| OrgLastFirstMiddle2 | CompanyName\r\nSurnameGivenName MiddleName |
| OrgLastFirstMiddle3 | CompanyName\r\nSurname GivenName MiddleName |
| LastFirstMiddleOrg | Surname, GivenName MiddleName\r\nCompanyName |
| LastFirstMiddleOrg2 | SurnameGivenName MiddleName\r\nCompanyName |
| LastFirstMiddleOrg3 | Surname GivenName PidTagMiddleName\r\nCompanyName |
| LastFirstMiddleGen | Surname GivenName MiddleName Generation |
| LastFirstMiddleGen2 | SurnameGivenName MiddleName Generation |
| BestMatch | Specifies that, when displaying the contact, the application should attempt to use the current value of dispidFileUnder and other contact properties to find a "best match" for dispidFileUnderId to one of the previous values in this table. |
| AccordingToLocale | Specifies that, when displaying the contact, the application should choose the appropriate default values (according to the language locale) for dispidFileUnderId and update dispidFileUnder to match the choice. |
| None | Specifies that, FileUnder is a user-provided, and should not be changed when another contact name property changes. I.e. value of FileUnder is not constructed from other properties. |

