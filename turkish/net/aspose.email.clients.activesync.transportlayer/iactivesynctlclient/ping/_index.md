---
title: Ping
second_title: Aspose.Email for .NET API Referansı
description: Ping komutu istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.
type: docs
weight: 140
url: /tr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| serverId | String | Id öğesi, izlenecek klasörün sunucu kimliğini belirten Ping komut isteklerindeki Klasör öğesinin gerekli bir alt öğesidir. |
| fClass | FolderClass | Class öğesi, izlenecek klasörün içerik sınıfını belirten Ping komut isteklerindeki Klasör öğesinin gerekli bir alt öğesidir. |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval, belirtilen klasör kümesine yeni öğe eklenmemişse sunucunun yanıt göndermeden önce beklemesi gereken süreyi saniye cinsinden belirtir. |
| serverId | String | Id öğesi, izlenecek klasörün sunucu kimliğini belirten Ping komut isteklerindeki Klasör öğesinin gerekli bir alt öğesidir. |
| fClass | FolderClass | Class öğesi, izlenecek klasörün içerik sınıfını belirten Ping komut isteklerindeki Klasör öğesinin gerekli bir alt öğesidir. |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pingParameters | PingParameter[] | Ping parametreleri |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval, belirtilen klasör kümesine yeni öğe eklenmemişse sunucunun yanıt göndermeden önce beklemesi gereken süreyi saniye cinsinden belirtir. |
| pingParameters | PingParameter[] | Ping parametreleri |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Ping parametreleri |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval, belirtilen klasör kümesine yeni öğe eklenmemişse sunucunun yanıt göndermeden önce beklemesi gereken süreyi saniye cinsinden belirtir. |
| pingParameters | IEnumerable`1 | Ping parametreleri |

### Geri dönüş değeri

Değişikliklerin keşfedildiği klasörler dizisi

### Ayrıca bakınız

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
