---
title: ExchangeAdvancedSyntaxQueryBuilder
second_title: Aspose.Email for Java API Reference
description:  Represents the builder of search expression based on
 the Advanced Query Syntax AQS that used by Exchange protocol.
type: docs
weight: 186
url: /java/com.aspose.email/exchangeadvancedsyntaxquerybuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ExchangeAdvancedSyntaxQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression based on the Advanced Query Syntax (AQS) that used by Exchange protocol. AQS is an alternative to search filters for expressing search criteria.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeAdvancedSyntaxQueryBuilder()](#ExchangeAdvancedSyntaxQueryBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAttachment()](#getAttachment--) | Gets the field that allows to find items with a specified attachment name. |
| [getParticipants()](#getParticipants--) |  |
| [getCategory()](#getCategory--) |  |
| [getImportance()](#getImportance--) |  |
| [getKind()](#getKind--) |  |
| [hasAttachment()](#hasAttachment--) |  |
| [getIsflagged()](#getIsflagged--) |  |
| [isRead()](#isRead--) |  |
| [getSize()](#getSize--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [getQuery()](#getQuery--) | Gets the query. |
### ExchangeAdvancedSyntaxQueryBuilder() {#ExchangeAdvancedSyntaxQueryBuilder--}
```
public ExchangeAdvancedSyntaxQueryBuilder()
```




### getAttachment() {#getAttachment--}
```
public final StringComparisonField getAttachment()
```


Gets the field that allows to find items with a specified attachment name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getParticipants() {#getParticipants--}
```
public final StringComparisonField getParticipants()
```




**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCategory() {#getCategory--}
```
public final StringComparisonField getCategory()
```




**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getImportance() {#getImportance--}
```
public final StringComparisonField getImportance()
```




**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getKind() {#getKind--}
```
public final EnumComparisonField getKind()
```




**Returns:**
[EnumComparisonField](../../com.aspose.email/enumcomparisonfield)
### hasAttachment() {#hasAttachment--}
```
public final BoolComparisonField hasAttachment()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getIsflagged() {#getIsflagged--}
```
public final BoolComparisonField getIsflagged()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### isRead() {#isRead--}
```
public final BoolComparisonField isRead()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getSize() {#getSize--}
```
public final IntComparisonField getSize()
```




**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### or(MailQuery query1, MailQuery query2) {#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-}
```
public final MailQuery or(MailQuery query1, MailQuery query2)
```


Search messages that match either search key. Provides disjunction between two expressions (OR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | The query1. |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | The query2. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### getQuery() {#getQuery--}
```
public final MailQuery getQuery()
```


Gets the query.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
