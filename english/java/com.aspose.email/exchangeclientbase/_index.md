---
title: ExchangeClientBase
second_title: Aspose.Email for Java API Reference
description:  Provides the abstract base class to MS Exchange Server access.
type: docs
weight: 196
url: /java/com.aspose.email/exchangeclientbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IExchangeClientBase](../../com.aspose.email/iexchangeclientbase)
```
public abstract class ExchangeClientBase implements IExchangeClientBase
```

Provides the abstract base class to MS Exchange Server access.
## Methods

| Method | Description |
| --- | --- |
| [setCommonLogFileName(String value)](#setCommonLogFileName-java.lang.String-) | Sets log file name for all sessions. |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [setProxy(System.Net.WebProxy value)](#setProxy-com.aspose.ms.System.Net.WebProxy-) | Gets or sets the proxy. |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials |
| [getMailboxUri()](#getMailboxUri--) | Gets or sets the mailbox uri |
| [setMailboxUri(String value)](#setMailboxUri-java.lang.String-) | Gets or sets the mailbox uri |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### setCommonLogFileName(String value) {#setCommonLogFileName-java.lang.String-}
```
public static void setCommonLogFileName(String value)
```


Sets log file name for all sessions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The log file name. |

### getProxy() {#getProxy--}
```
public System.Net.WebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.WebProxy
### setProxy(System.Net.WebProxy value) {#setProxy-com.aspose.ms.System.Net.WebProxy-}
```
public void setProxy(System.Net.WebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.WebProxy |  |

### getCredentials() {#getCredentials--}
```
public System.Net.ICredentials getCredentials()
```


Gets or sets the credentials

Value: ICredentials

**Returns:**
com.aspose.ms.System.Net.ICredentials
### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public void setCredentials(System.Net.ICredentials value)
```


Gets or sets the credentials

Value: ICredentials

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

### getMailboxUri() {#getMailboxUri--}
```
public String getMailboxUri()
```


Gets or sets the mailbox uri

Value: Uri of the mailbox

**Returns:**
java.lang.String
### setMailboxUri(String value) {#setMailboxUri-java.lang.String-}
```
public void setMailboxUri(String value)
```


Gets or sets the mailbox uri

Value: Uri of the mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

Value: Timeout in milliseconds

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

Value: Timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### resetLogSettings() {#resetLogSettings--}
```
public final void resetLogSettings()
```


Resets logging settings to default.

### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




