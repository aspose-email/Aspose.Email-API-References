---
title: BackupSettings
second_title: Aspose.Email for Java API Reference
description:  Class contains options for backup operation
type: docs
weight: 76
url: /java/com.aspose.email/backupsettings/
---
**Inheritance:**
java.lang.Object
```
public class BackupSettings
```

Class contains options for backup operation
## Constructors

| Constructor | Description |
| --- | --- |
| [BackupSettings()](#BackupSettings--) | Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class |
| [BackupSettings(int options)](#BackupSettings-int-) | Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class |
| [BackupSettings(boolean executeRecursively, boolean restoreConnection, int numberOfAttempts, int timeoutBetweenAttempts)](#BackupSettings-boolean-boolean-int-int-) | Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class |
## Methods

| Method | Description |
| --- | --- |
| [getDefault()](#getDefault--) | Gets [BackupSettings](../../com.aspose.email/backupsettings) class with settings by default |
| [to_BackupSettings(int options)](#to-BackupSettings-int-) | Converts enumerable options to class |
| [getExecuteRecursively()](#getExecuteRecursively--) | Gets or sets value which defines if backup should be executed recursively |
| [setExecuteRecursively(boolean value)](#setExecuteRecursively-boolean-) | Gets or sets value which defines if backup should be executed recursively |
| [getRestoreConnection()](#getRestoreConnection--) | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [setRestoreConnection(boolean value)](#setRestoreConnection-boolean-) | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [getNumberOfAttemptsToRrepeat()](#getNumberOfAttemptsToRrepeat--) | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. |
| [setNumberOfAttemptsToRrepeat(int value)](#setNumberOfAttemptsToRrepeat-int-) | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. |
| [getTimeoutBetweenAttempts()](#getTimeoutBetweenAttempts--) | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [setTimeoutBetweenAttempts(int value)](#setTimeoutBetweenAttempts-int-) | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
### BackupSettings() {#BackupSettings--}
```
public BackupSettings()
```


Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class

### BackupSettings(int options) {#BackupSettings-int-}
```
public BackupSettings(int options)
```


Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | int | enumerates backup options |

### BackupSettings(boolean executeRecursively, boolean restoreConnection, int numberOfAttempts, int timeoutBetweenAttempts) {#BackupSettings-boolean-boolean-int-int-}
```
public BackupSettings(boolean executeRecursively, boolean restoreConnection, int numberOfAttempts, int timeoutBetweenAttempts)
```


Initializes a new instance of the [BackupSettings](../../com.aspose.email/backupsettings) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| executeRecursively | boolean | defines if backup should be executed recursively |
| restoreConnection | boolean | defines if connection has to be restored in case if server closes connection forcibly |
| numberOfAttempts | int | defines number of attempts to repeat failed operation |
| timeoutBetweenAttempts | int | defines timeout (in milliseconds) between attemptions to execute operation again |

### getDefault() {#getDefault--}
```
public static BackupSettings getDefault()
```


Gets [BackupSettings](../../com.aspose.email/backupsettings) class with settings by default

**Returns:**
[BackupSettings](../../com.aspose.email/backupsettings)
### to_BackupSettings(int options) {#to-BackupSettings-int-}
```
public static BackupSettings to_BackupSettings(int options)
```


Converts enumerable options to class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | int | Options to convert |

**Returns:**
[BackupSettings](../../com.aspose.email/backupsettings)
### getExecuteRecursively() {#getExecuteRecursively--}
```
public final boolean getExecuteRecursively()
```


Gets or sets value which defines if backup should be executed recursively

**Returns:**
boolean
### setExecuteRecursively(boolean value) {#setExecuteRecursively-boolean-}
```
public final void setExecuteRecursively(boolean value)
```


Gets or sets value which defines if backup should be executed recursively

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRestoreConnection() {#getRestoreConnection--}
```
public final boolean getRestoreConnection()
```


Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option.

**Returns:**
boolean
### setRestoreConnection(boolean value) {#setRestoreConnection-boolean-}
```
public final void setRestoreConnection(boolean value)
```


Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberOfAttemptsToRrepeat() {#getNumberOfAttemptsToRrepeat--}
```
public final int getNumberOfAttemptsToRrepeat()
```


Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE\_1\_1\_0243 FETCH 219 (BODY) AE\_1\_1\_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Returns:**
int
### setNumberOfAttemptsToRrepeat(int value) {#setNumberOfAttemptsToRrepeat-int-}
```
public final void setNumberOfAttemptsToRrepeat(int value)
```


Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE\_1\_1\_0243 FETCH 219 (BODY) AE\_1\_1\_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTimeoutBetweenAttempts() {#getTimeoutBetweenAttempts--}
```
public final int getTimeoutBetweenAttempts()
```


Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option.

**Returns:**
int
### setTimeoutBetweenAttempts(int value) {#setTimeoutBetweenAttempts-int-}
```
public final void setTimeoutBetweenAttempts(int value)
```


Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

