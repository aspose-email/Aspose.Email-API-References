---
title: SpamAnalyzer
second_title: Aspose.Email for Java API Reference
description: Class which allows applications to detect spam e-mails with self-learning Bayesian filter.
type: docs
weight: 653
url: /java/com.aspose.email/spamanalyzer/
---

**Inheritance:**
java.lang.Object
```
public class SpamAnalyzer
```

Class which allows applications to detect spam e-mails with self-learning Bayesian filter.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpamAnalyzer()](#SpamAnalyzer--) | Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class. |
| [SpamAnalyzer(InputStream stream)](#SpamAnalyzer-java.io.InputStream-) | Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class. |
| [SpamAnalyzer(String filePath)](#SpamAnalyzer-java.lang.String-) | Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [loadDatabase(InputStream stream)](#loadDatabase-java.io.InputStream-) | Loads Bayesian database from stream. |
| [loadDatabase(String filePath)](#loadDatabase-java.lang.String-) | Loads Bayesian database from file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Clears all statistics (Bayesian database). |
| [saveDatabase(OutputStream stream)](#saveDatabase-java.io.OutputStream-) | Saves the Bayesian database to stream. |
| [saveDatabase(String filePath)](#saveDatabase-java.lang.String-) | Saves the Bayesian database to file. |
| [test(MailMessage message)](#test-com.aspose.email.MailMessage-) | Analyses the message and returns the probability of the message being spam. |
| [toString()](#toString--) |  |
| [trainFilter(MailMessage message, boolean isSpam)](#trainFilter-com.aspose.email.MailMessage-boolean-) | Learns from the specified message as from spam or non-spam source. |
| [trainFilter(MailMessage[] ham, MailMessage[] spam)](#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---) | Learns from the specified messages as from spam or non-spam source. |
| [trainFilter(String text, boolean isSpam)](#trainFilter-java.lang.String-boolean-) | Learns from the specified string as from spam or non-spam source. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SpamAnalyzer() {#SpamAnalyzer--}
```
public SpamAnalyzer()
```


Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class.

### SpamAnalyzer(InputStream stream) {#SpamAnalyzer-java.io.InputStream-}
```
public SpamAnalyzer(InputStream stream)
```


Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | An input stream containing Bayesian database. |

### SpamAnalyzer(String filePath) {#SpamAnalyzer-java.lang.String-}
```
public SpamAnalyzer(String filePath)
```


Initialize a new instance of the [SpamAnalyzer](../../com.aspose.email/spamanalyzer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full or relative path to the file containing Bayesian database. |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadDatabase(InputStream stream) {#loadDatabase-java.io.InputStream-}
```
public final void loadDatabase(InputStream stream)
```


Loads Bayesian database from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | An input stream containing Bayesian database. |

### loadDatabase(String filePath) {#loadDatabase-java.lang.String-}
```
public final void loadDatabase(String filePath)
```


Loads Bayesian database from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full or relative path to the file containing Bayesian database. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public final void reset()
```


Clears all statistics (Bayesian database).

### saveDatabase(OutputStream stream) {#saveDatabase-java.io.OutputStream-}
```
public final void saveDatabase(OutputStream stream)
```


Saves the Bayesian database to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | An output stream containing Bayesian database. |

### saveDatabase(String filePath) {#saveDatabase-java.lang.String-}
```
public final void saveDatabase(String filePath)
```


Saves the Bayesian database to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full or relative path to the file containing Bayesian database. |

### test(MailMessage message) {#test-com.aspose.email.MailMessage-}
```
public final double test(MailMessage message)
```


Analyses the message and returns the probability of the message being spam.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | MailMessage for test the probability of the message being spam. |

**Returns:**
double - A double value in 0-1 range, where 0 corresponds to "definitely non-spam" (0% spam probability) and 1 corresponds to "definitely spam" (100% spam probability).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trainFilter(MailMessage message, boolean isSpam) {#trainFilter-com.aspose.email.MailMessage-boolean-}
```
public final void trainFilter(MailMessage message, boolean isSpam)
```


Learns from the specified message as from spam or non-spam source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A reference to the MailMessage object representing the message to train the Bayesian filter. |
| isSpam | boolean | True if the message is a spam; false if it's a legitimate message. |

### trainFilter(MailMessage[] ham, MailMessage[] spam) {#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---}
```
public final void trainFilter(MailMessage[] ham, MailMessage[] spam)
```


Learns from the specified messages as from spam or non-spam source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ham | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage objects that is non-spam for training the Bayesian filter. |
| spam | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage objects that is spam for training the Bayesian filter. |

### trainFilter(String text, boolean isSpam) {#trainFilter-java.lang.String-boolean-}
```
public final void trainFilter(String text, boolean isSpam)
```


Learns from the specified string as from spam or non-spam source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | A string value to train the Bayesian filter. |
| isSpam | boolean | True if specified text is a spam; false if it's a legitimate text. |

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

