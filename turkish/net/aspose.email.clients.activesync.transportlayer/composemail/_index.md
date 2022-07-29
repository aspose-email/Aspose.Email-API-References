---
title: ComposeMail
second_title: Aspose.Email for .NET API Referansı
description: ActiveSync protokolünün ComposeMail ad alanı
type: docs
weight: 1120
url: /tr/net/aspose.email.clients.activesync.transportlayer/composemail/
---
## ComposeMail enumeration

ActiveSync protokolünün ComposeMail ad alanı

```csharp
public enum ComposeMail
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| SendMail | `5` | SendMail öğesi, HTTP POST'un gövdesinin SendMail komutunu içerdiğini tanımlayan SendMail komut istekleri ve yanıtlarında gerekli bir öğedir (bölüm 2.2.2.15). |
| SmartForward | `6` | SmartForward öğesi, SmartForward komut isteklerinde ve HTTP POST gövdesinin bir SmartForward komutu içerdiğini tanımlayan yanıtlarda gerekli bir öğedir (bölüm 2.2.2.17). |
| SmartReply | `7` | SmartReply öğesi, SmartReply komut isteklerinde ve HTTP POST gövdesinin bir SmartReply komutu içerdiğini tanımlayan yanıtlarda gerekli bir öğedir (bölüm 2.2.2.18). |
| SaveInSentItems | `8` | SaveInSentItems öğesi, mesajın bir kopyasının Gönderilmiş Öğeler klasöründe saklanıp saklanmayacağını belirtir. |
| ReplaceMime | `9` | İstemcinin tüm mesajı gönderip göndermediğini belirtir. |
| Source | `11` | Kaynak mesajla ilgili bilgileri içerir. |
| FolderId | `12` | FolderSync komut yanıt mesajında (bölüm 2.2.2.4.2) döndürülen kaynak mesajın klasör kimliğini belirtir. |
| ItemId | `13` | Senkronizasyon komutu yanıt mesajında (bölüm 2.2.2.19.2) döndürülen kaynak mesaj için öğe kimliğini belirtir. |
| LongId | `14` | Bu öğe, Arama komutu yanıt mesajında (bölüm 2.2.2.14.2) döndürülen kaynak toplantı isteği için uzun kimliği belirtir. |
| InstanceId | `15` | InstanceId öğesi, kaynak öğe için bir yineleme örneğini belirten SmartForward komut istekleri ve SmartReply komut isteklerindeki Source öğesinin isteğe bağlı bir alt öğesidir. |
| Mime | `16` | MIME kodlu mesajı içerir. |
| ClientId | `17` | İstemcinin benzersiz ileti kimliğini (MID) belirtir. |
| Status | `18` | Bir komut isteğinin başarısızlığının nedenini belirtir. |
| AccountId | `19` | Bir e-postanın gönderildiği hesabı tanımlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->