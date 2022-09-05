---
title: DeliveryNotificationOptions
second_title: Aspose.Email for Java API Reference
description:  Specifies delivery notifications.
type: docs
weight: 154
url: /java/com.aspose.email/deliverynotificationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DeliveryNotificationOptions extends System.Enum
```

Specifies delivery notifications.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No notification information will be sent. |
| [OnSuccess](#OnSuccess) | Notify if the delivery is successful. |
| [OnFailure](#OnFailure) | Notify if the delivery is unsuccessful. |
| [Delay](#Delay) | Notify if the delivery is delayed. |
| [Never](#Never) | A notification should not be generated under any circumstances. |
### None {#None}
```
public static final int None
```


No notification information will be sent. The mail server will utilize its configured behavior to determine whether it should generate a delivery notification.

### OnSuccess {#OnSuccess}
```
public static final int OnSuccess
```


Notify if the delivery is successful.

### OnFailure {#OnFailure}
```
public static final int OnFailure
```


Notify if the delivery is unsuccessful.

### Delay {#Delay}
```
public static final int Delay
```


Notify if the delivery is delayed.

### Never {#Never}
```
public static final int Never
```


A notification should not be generated under any circumstances.

