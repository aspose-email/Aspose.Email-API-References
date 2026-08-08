---
title: MapiContactTelephonePropertySet
second_title: Aspose.Email for Android via Java API 参考
description: 指定联系人的可选电话号码
type: docs
weight: 247
url: /zh/androidjava/com.aspose.email/mapicontacttelephonepropertyset/
---

**Inheritance:**
java.lang.Object
```
public final class MapiContactTelephonePropertySet
```

为联系人指定可选的电话号码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiContactTelephonePropertySet()](#MapiContactTelephonePropertySet--) | 初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例 |
| [MapiContactTelephonePropertySet(String primaryTelephoneNumber)](#MapiContactTelephonePropertySet-java.lang.String-) | 初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例。 |
| [MapiContactTelephonePropertySet(MapiPropertyCollection properties)](#MapiContactTelephonePropertySet-com.aspose.email.MapiPropertyCollection-) | 初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssistantTelephoneNumber()](#getAssistantTelephoneNumber--) | 获取或设置联系人的助理电话号码 |
| [getBusiness2TelephoneNumber()](#getBusiness2TelephoneNumber--) | 获取或设置第二个商务电话号码 |
| [getBusinessTelephoneNumber()](#getBusinessTelephoneNumber--) | 获取或设置商务电话号码 |
| [getCallbackTelephoneNumber()](#getCallbackTelephoneNumber--) | 获取或设置回拨电话号码 |
| [getCarTelephoneNumber()](#getCarTelephoneNumber--) | 获取或设置车载电话号码 |
| [getClass()](#getClass--) |  |
| [getCompanyMainTelephoneNumber()](#getCompanyMainTelephoneNumber--) | 获取或设置公司电话号码 |
| [getDefaultTelephoneNumber()](#getDefaultTelephoneNumber--) | 当 UseAutocomplete 属性设置为 'true' 且用户未设置任何电子地址时，电子地址的默认值将被使用。 |
| [getHome2TelephoneNumber()](#getHome2TelephoneNumber--) | 获取或设置第二个住宅电话号码 |
| [getHomeTelephoneNumber()](#getHomeTelephoneNumber--) | 获取或设置住宅电话号码 |
| [getIsdnNumber()](#getIsdnNumber--) | 获取或设置综合业务数字网 (ISDN) 号码 |
| [getMobileTelephoneNumber()](#getMobileTelephoneNumber--) | 获取或设置移动电话号码 |
| [getOtherTelephoneNumber()](#getOtherTelephoneNumber--) | 获取或设置备用电话号码 |
| [getPagerTelephoneNumber()](#getPagerTelephoneNumber--) | 获取或设置传呼机电话号码 |
| [getPrimaryTelephoneNumber()](#getPrimaryTelephoneNumber--) | 获取或设置主要电话号码 |
| [getRadioTelephoneNumber()](#getRadioTelephoneNumber--) | 获取或设置无线电话号码 |
| [getTelexNumber()](#getTelexNumber--) | 获取或设置电传号码 |
| [getTtyTddPhoneNumber()](#getTtyTddPhoneNumber--) | 获取或设置联系人的文字电话 (TTY) 或聋人通信设备 (TDD) 号码 |
| [getUseAutocomplete()](#getUseAutocomplete--) | 指示如果用户未设置任何电子地址，则会自动完成一个电子地址。 |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | 显示 MapiContactTelephonePropertySet 是否为空 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAssistantTelephoneNumber(String value)](#setAssistantTelephoneNumber-java.lang.String-) | 获取或设置联系人的助理电话号码 |
| [setBusiness2TelephoneNumber(String value)](#setBusiness2TelephoneNumber-java.lang.String-) | 获取或设置第二个商务电话号码 |
| [setBusinessTelephoneNumber(String value)](#setBusinessTelephoneNumber-java.lang.String-) | 获取或设置商务电话号码 |
| [setCallbackTelephoneNumber(String value)](#setCallbackTelephoneNumber-java.lang.String-) | 获取或设置回拨电话号码 |
| [setCarTelephoneNumber(String value)](#setCarTelephoneNumber-java.lang.String-) | 获取或设置车载电话号码 |
| [setCompanyMainTelephoneNumber(String value)](#setCompanyMainTelephoneNumber-java.lang.String-) | 获取或设置公司电话号码 |
| [setDefaultTelephoneNumber(String value)](#setDefaultTelephoneNumber-java.lang.String-) | 当 UseAutocomplete 属性设置为 'true' 且用户未设置任何电子地址时，电子地址的默认值将被使用。 |
| [setHome2TelephoneNumber(String value)](#setHome2TelephoneNumber-java.lang.String-) | 获取或设置第二个住宅电话号码 |
| [setHomeTelephoneNumber(String value)](#setHomeTelephoneNumber-java.lang.String-) | 获取或设置住宅电话号码 |
| [setIsdnNumber(String value)](#setIsdnNumber-java.lang.String-) | 获取或设置综合业务数字网 (ISDN) 号码 |
| [setMobileTelephoneNumber(String value)](#setMobileTelephoneNumber-java.lang.String-) | 获取或设置移动电话号码 |
| [setOtherTelephoneNumber(String value)](#setOtherTelephoneNumber-java.lang.String-) | 获取或设置备用电话号码 |
| [setPagerTelephoneNumber(String value)](#setPagerTelephoneNumber-java.lang.String-) | 获取或设置传呼机电话号码 |
| [setPrimaryTelephoneNumber(String value)](#setPrimaryTelephoneNumber-java.lang.String-) | 获取或设置主要电话号码 |
| [setRadioTelephoneNumber(String value)](#setRadioTelephoneNumber-java.lang.String-) | 获取或设置无线电话号码 |
| [setTelexNumber(String value)](#setTelexNumber-java.lang.String-) | 获取或设置电传号码 |
| [setTtyTddPhoneNumber(String value)](#setTtyTddPhoneNumber-java.lang.String-) | 获取或设置联系人的文字电话 (TTY) 或聋人通信设备 (TDD) 号码 |
| [setUseAutocomplete(boolean value)](#setUseAutocomplete-boolean-) | 指示如果用户未设置任何电子地址，则会自动完成一个电子地址。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiContactTelephonePropertySet() {#MapiContactTelephonePropertySet--}
```
public MapiContactTelephonePropertySet()
```


初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例

### MapiContactTelephonePropertySet(String primaryTelephoneNumber) {#MapiContactTelephonePropertySet-java.lang.String-}
```
public MapiContactTelephonePropertySet(String primaryTelephoneNumber)
```


初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| primaryTelephoneNumber | java.lang.String | 主要电话号码。 |

### MapiContactTelephonePropertySet(MapiPropertyCollection properties) {#MapiContactTelephonePropertySet-com.aspose.email.MapiPropertyCollection-}
```
public MapiContactTelephonePropertySet(MapiPropertyCollection properties)
```


初始化一个新的 [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) 类实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | 一个包含联系人电话属性的 [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssistantTelephoneNumber() {#getAssistantTelephoneNumber--}
```
public final String getAssistantTelephoneNumber()
```


获取或设置联系人的助理电话号码

**Returns:**
java.lang.String
### getBusiness2TelephoneNumber() {#getBusiness2TelephoneNumber--}
```
public final String getBusiness2TelephoneNumber()
```


获取或设置第二个商务电话号码

**Returns:**
java.lang.String
### getBusinessTelephoneNumber() {#getBusinessTelephoneNumber--}
```
public final String getBusinessTelephoneNumber()
```


获取或设置商务电话号码

**Returns:**
java.lang.String
### getCallbackTelephoneNumber() {#getCallbackTelephoneNumber--}
```
public final String getCallbackTelephoneNumber()
```


获取或设置回拨电话号码

**Returns:**
java.lang.String
### getCarTelephoneNumber() {#getCarTelephoneNumber--}
```
public final String getCarTelephoneNumber()
```


获取或设置车载电话号码

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompanyMainTelephoneNumber() {#getCompanyMainTelephoneNumber--}
```
public final String getCompanyMainTelephoneNumber()
```


获取或设置公司电话号码

**Returns:**
java.lang.String
### getDefaultTelephoneNumber() {#getDefaultTelephoneNumber--}
```
public final String getDefaultTelephoneNumber()
```


当 UseAutocomplete 属性设置为 'true' 且用户未设置任何电子地址时，电子地址的默认值将被使用。

**Returns:**
java.lang.String
### getHome2TelephoneNumber() {#getHome2TelephoneNumber--}
```
public final String getHome2TelephoneNumber()
```


获取或设置第二个住宅电话号码

**Returns:**
java.lang.String
### getHomeTelephoneNumber() {#getHomeTelephoneNumber--}
```
public final String getHomeTelephoneNumber()
```


获取或设置住宅电话号码

**Returns:**
java.lang.String
### getIsdnNumber() {#getIsdnNumber--}
```
public final String getIsdnNumber()
```


获取或设置综合业务数字网 (ISDN) 号码

**Returns:**
java.lang.String
### getMobileTelephoneNumber() {#getMobileTelephoneNumber--}
```
public final String getMobileTelephoneNumber()
```


获取或设置移动电话号码

**Returns:**
java.lang.String
### getOtherTelephoneNumber() {#getOtherTelephoneNumber--}
```
public final String getOtherTelephoneNumber()
```


获取或设置备用电话号码

**Returns:**
java.lang.String
### getPagerTelephoneNumber() {#getPagerTelephoneNumber--}
```
public final String getPagerTelephoneNumber()
```


获取或设置传呼机电话号码

**Returns:**
java.lang.String
### getPrimaryTelephoneNumber() {#getPrimaryTelephoneNumber--}
```
public final String getPrimaryTelephoneNumber()
```


获取或设置主要电话号码

**Returns:**
java.lang.String
### getRadioTelephoneNumber() {#getRadioTelephoneNumber--}
```
public final String getRadioTelephoneNumber()
```


获取或设置无线电话号码

**Returns:**
java.lang.String
### getTelexNumber() {#getTelexNumber--}
```
public final String getTelexNumber()
```


获取或设置电传号码

**Returns:**
java.lang.String
### getTtyTddPhoneNumber() {#getTtyTddPhoneNumber--}
```
public final String getTtyTddPhoneNumber()
```


获取或设置联系人的文字电话 (TTY) 或聋人通信设备 (TDD) 号码

**Returns:**
java.lang.String
### getUseAutocomplete() {#getUseAutocomplete--}
```
public final boolean getUseAutocomplete()
```


指示如果用户未设置任何电子地址，则会自动完成一个电子地址。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


显示 MapiContactTelephonePropertySet 是否为空

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAssistantTelephoneNumber(String value) {#setAssistantTelephoneNumber-java.lang.String-}
```
public final void setAssistantTelephoneNumber(String value)
```


获取或设置联系人的助理电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBusiness2TelephoneNumber(String value) {#setBusiness2TelephoneNumber-java.lang.String-}
```
public final void setBusiness2TelephoneNumber(String value)
```


获取或设置第二个商务电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBusinessTelephoneNumber(String value) {#setBusinessTelephoneNumber-java.lang.String-}
```
public final void setBusinessTelephoneNumber(String value)
```


获取或设置商务电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCallbackTelephoneNumber(String value) {#setCallbackTelephoneNumber-java.lang.String-}
```
public final void setCallbackTelephoneNumber(String value)
```


获取或设置回拨电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCarTelephoneNumber(String value) {#setCarTelephoneNumber-java.lang.String-}
```
public final void setCarTelephoneNumber(String value)
```


获取或设置车载电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompanyMainTelephoneNumber(String value) {#setCompanyMainTelephoneNumber-java.lang.String-}
```
public final void setCompanyMainTelephoneNumber(String value)
```


获取或设置公司电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultTelephoneNumber(String value) {#setDefaultTelephoneNumber-java.lang.String-}
```
public final void setDefaultTelephoneNumber(String value)
```


当 UseAutocomplete 属性设置为 'true' 且用户未设置任何电子地址时，电子地址的默认值将被使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHome2TelephoneNumber(String value) {#setHome2TelephoneNumber-java.lang.String-}
```
public final void setHome2TelephoneNumber(String value)
```


获取或设置第二个住宅电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHomeTelephoneNumber(String value) {#setHomeTelephoneNumber-java.lang.String-}
```
public final void setHomeTelephoneNumber(String value)
```


获取或设置住宅电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setIsdnNumber(String value) {#setIsdnNumber-java.lang.String-}
```
public final void setIsdnNumber(String value)
```


获取或设置综合业务数字网 (ISDN) 号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMobileTelephoneNumber(String value) {#setMobileTelephoneNumber-java.lang.String-}
```
public final void setMobileTelephoneNumber(String value)
```


获取或设置移动电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setOtherTelephoneNumber(String value) {#setOtherTelephoneNumber-java.lang.String-}
```
public final void setOtherTelephoneNumber(String value)
```


获取或设置备用电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPagerTelephoneNumber(String value) {#setPagerTelephoneNumber-java.lang.String-}
```
public final void setPagerTelephoneNumber(String value)
```


获取或设置传呼机电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrimaryTelephoneNumber(String value) {#setPrimaryTelephoneNumber-java.lang.String-}
```
public final void setPrimaryTelephoneNumber(String value)
```


获取或设置主要电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setRadioTelephoneNumber(String value) {#setRadioTelephoneNumber-java.lang.String-}
```
public final void setRadioTelephoneNumber(String value)
```


获取或设置无线电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTelexNumber(String value) {#setTelexNumber-java.lang.String-}
```
public final void setTelexNumber(String value)
```


获取或设置电传号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTtyTddPhoneNumber(String value) {#setTtyTddPhoneNumber-java.lang.String-}
```
public final void setTtyTddPhoneNumber(String value)
```


获取或设置联系人的文字电话 (TTY) 或聋人通信设备 (TDD) 号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setUseAutocomplete(boolean value) {#setUseAutocomplete-boolean-}
```
public final void setUseAutocomplete(boolean value)
```


指示如果用户未设置任何电子地址，则会自动完成一个电子地址。

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

