---
title: MailServerValidatingEventArgs
second_title: Aspose.Email for Android via Java API Reference
description:  Provides data for the MailServerValidatingEvent event.
type: docs
weight: 198
url: /java/com.aspose.email/mailservervalidatingeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs), [com.aspose.email.DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs)
```
public class MailServerValidatingEventArgs extends DomainValidatingEventArgs
```

Provides data for the MailServerValidatingEvent event.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)](#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
## Methods

| Method | Description |
| --- | --- |
| [getMailExchangeServers_MailServerValidatingEventArgs_New()](#getMailExchangeServers-MailServerValidatingEventArgs-New--) | Gets the mail exchange server list. |
| [getMailExchangeServers()](#getMailExchangeServers--) | Gets the mail exchange server list. |
### MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList) {#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---}
```
public MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | A string contains the original copy of the mail address. |
| mailaddress | [MailAddress](../../com.aspose.email/mailaddress) | The MailAddress. |
| mailExchangeList | java.lang.String[] | A set of mail exchange server list. |

### getMailExchangeServers_MailServerValidatingEventArgs_New() {#getMailExchangeServers-MailServerValidatingEventArgs-New--}
```
public final String[] getMailExchangeServers_MailServerValidatingEventArgs_New()
```


Gets the mail exchange server list.

**Returns:**
java.lang.String[]
### getMailExchangeServers() {#getMailExchangeServers--}
```
public final String[] getMailExchangeServers()
```


Gets the mail exchange server list.

**Returns:**
java.lang.String[]
