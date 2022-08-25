---
title: DomainValidatingEventArgs
second_title: Aspose.Email for Java API Reference
description:  Provides data for the DomainValidating event.
type: docs
weight: 159
url: /java/com.aspose.email/domainvalidatingeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs)
```
public class DomainValidatingEventArgs extends SyntaxValidatingEventArgs
```

Provides data for the DomainValidating event.
## Constructors

| Constructor | Description |
| --- | --- |
| [DomainValidatingEventArgs(String mail, MailAddress mailaddress)](#DomainValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
## Methods

| Method | Description |
| --- | --- |
| [getDomain()](#getDomain--) | Gets the domain. |
| [getMailAddress()](#getMailAddress--) | Gets the mail address. |
### DomainValidatingEventArgs(String mail, MailAddress mailaddress) {#DomainValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-}
```
public DomainValidatingEventArgs(String mail, MailAddress mailaddress)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | The mail address. |
| mailaddress | [MailAddress](../../com.aspose.email/mailaddress) | The mail address. |

### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets the domain.

**Returns:**
java.lang.String
### getMailAddress() {#getMailAddress--}
```
public final MailAddress getMailAddress()
```


Gets the mail address.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
