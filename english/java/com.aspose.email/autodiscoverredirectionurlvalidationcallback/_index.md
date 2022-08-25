---
title: AutodiscoverRedirectionUrlValidationCallback
second_title: Aspose.Email for Java API Reference
description:  Defines a delegate that is used by the AutodiscoverService to ask whether a redirectionUrl can be used.
type: docs
weight: 70
url: /java/com.aspose.email/autodiscoverredirectionurlvalidationcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AutodiscoverRedirectionUrlValidationCallback extends System.MulticastDelegate
```

Defines a delegate that is used by the AutodiscoverService to ask whether a redirectionUrl can be used.
## Constructors

| Constructor | Description |
| --- | --- |
| [AutodiscoverRedirectionUrlValidationCallback()](#AutodiscoverRedirectionUrlValidationCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(String redirectionUrl)](#invoke-java.lang.String-) |  |
| [beginInvoke(String redirectionUrl, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### AutodiscoverRedirectionUrlValidationCallback() {#AutodiscoverRedirectionUrlValidationCallback--}
```
public AutodiscoverRedirectionUrlValidationCallback()
```


### invoke(String redirectionUrl) {#invoke-java.lang.String-}
```
public abstract boolean invoke(String redirectionUrl)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| redirectionUrl | java.lang.String |  |

**Returns:**
boolean
### beginInvoke(String redirectionUrl, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(String redirectionUrl, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| redirectionUrl | java.lang.String |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
