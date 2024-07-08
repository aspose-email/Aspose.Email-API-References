---
title: ExchangeClientBase
second_title: Aspose.Email for Java API Reference
description: Provides the abstract base class to MS Exchange Server access.
type: docs
weight: 198
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getMailboxUri()](#getMailboxUri--) | Gets or sets the mailbox uri |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [setCommonLogFileName(String value)](#setCommonLogFileName-java.lang.String-) | Sets log file name for all sessions. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setMailboxUri(String value)](#setMailboxUri-java.lang.String-) | Gets or sets the mailbox uri |
| [setProxy(System.Net.WebProxy value)](#setProxy-com.aspose.ms.System.Net.WebProxy-) | Gets or sets the proxy. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCredentials() {#getCredentials--}
```
public System.Net.ICredentials getCredentials()
```


Gets or sets the credentials

Value: ICredentials

**Returns:**
com.aspose.ms.System.Net.ICredentials
### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getMailboxUri() {#getMailboxUri--}
```
public String getMailboxUri()
```


Gets or sets the mailbox uri

Value: Uri of the mailbox

**Returns:**
java.lang.String
### getProxy() {#getProxy--}
```
public System.Net.WebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.WebProxy
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

Value: Timeout in milliseconds

**Returns:**
int
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetLogSettings() {#resetLogSettings--}
```
public final void resetLogSettings()
```


Resets logging settings to default.

### setCommonLogFileName(String value) {#setCommonLogFileName-java.lang.String-}
```
public static void setCommonLogFileName(String value)
```


Sets log file name for all sessions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The log file name. |

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

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setProxy(System.Net.WebProxy value) {#setProxy-com.aspose.ms.System.Net.WebProxy-}
```
public void setProxy(System.Net.WebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.WebProxy |  |

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

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

