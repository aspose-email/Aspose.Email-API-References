---
title: MeetingResponse
second_title: Aspose.Email for .NET API Referansı
description: Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder geçici olarak kabul eder veya reddeder.
type: docs
weight: 110
url: /tr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| userResponse | UserResponse | Toplantının kabul edildiğini, geçici olarak kabul edildiğini veya reddedildiğini gösterir. |
| collectionId | String | Toplantı isteğini içeren klasörü belirtir. LongId dahil edilmişse isteğe bağlıdır. CollectionId değeri en fazla 64 karakter uzunluğunda olabilir. |
| requestId | String | Toplantı isteği ileti öğesinin sunucu kimliğini belirtir. Uzun Kimlik dahil edilmişse isteğe bağlıdır. RequestId değeri en fazla 64 karakter uzunluğunda olabilir. |

### Geri dönüş değeri

MeetingResponseResult nesnesini döndürür.

### Ayrıca bakınız

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| userResponse | UserResponse | Toplantının kabul edildiğini, geçici olarak kabul edildiğini veya reddedildiğini gösterir. |
| collectionId | String | Toplantı isteğini içeren klasörü belirtir. LongId dahil edilmişse isteğe bağlıdır. CollectionId değeri en fazla 64 karakter uzunluğunda olabilir. |
| requestId | String | Toplantı isteği ileti öğesinin sunucu kimliğini belirtir. Uzun Kimlik dahil edilmişse isteğe bağlıdır. RequestId değeri en fazla 64 karakter uzunluğunda olabilir. |
| longId | String | Arama komutu yanıt iletisinde döndürülen kaynak toplantı isteğinin uzun kimliğini belirtir. LongId varsa, CollectionId, InstanceId ve RequestId mevcut değildir. LongId değeri en fazla 256 karakter uzunluğunda olabilir. |
| instanceId | String | Değiştirilecek yinelenen toplantı örneğini belirtir. Protokol sürümü 12.1 veya 14.0 olduğunda InstanceId desteklenmez. InstanceId öğesi, protokol sürümünün 12.1 veya 14.0. olduğu isteklerde yer alıyorsa, 2 Durum değeri döndürülür. InstanceId, değiştirilecek randevu veya toplantı örneğinin başlangıç saatini içerir. InstanceId MeetingResponse isteğine dahil edilmemişse, eylem, yinelenen öğenin her örneğinde gerçekleştirilecektir. InstanceId, yinelenen bir randevu veya toplantı için bir istisnanın başlangıç zamanını belirtebilir. InstanceId, bir takvim öğesini tanımlamak için LongId ile kullanılabilir veya bir takvim öğesini tanımlamak için CollectionId ve RequestId ile birlikte kullanılabilir. InstanceId değerinin biçimi, noktalama ayırıcılarıyla birlikte tarihsaat biçiminde bir dizedir. örnek, 2010-04-08T18:16:00.000Z. Belirtilen InstanceId değeri uygun biçimde değilse, sunucu 104 Durum öğesi değeriyle yanıt verir. InstanceId değeri yinelenmeyen bir toplantı belirtiyorsa, sunucu 146 Durum öğesi değeriyle yanıt verir. |

### Geri dönüş değeri

MeetingResponseResult nesnesini döndürür.

### Ayrıca bakınız

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| request | MeetingResponseRequest[] | MeetingResponseRequest nesneleri dizisi |

### Geri dönüş değeri

MeetingResponseResult nesneleri dizisini döndürür.

### Ayrıca bakınız

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| request | IEnumerable`1 | MeetingResponseRequest nesnelerinin numaralandırılması |

### Geri dönüş değeri

MeetingResponseResult nesneleri dizisini döndürür.

### Ayrıca bakınız

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
