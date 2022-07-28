---
title: DataContainer
second_title: Aspose.Email for .NET API Referansı
description: Kişi e-posta iletisi takvim randevusu veya görev öğesi gibi belirli bir nesneye ilişkin verileri içerir. DataContainer öğeleri değiştirmek öğeleri eklemek veya istemci cihaz veya sunucudaki öğeleri almak için kullanılabilir.
type: docs
weight: 1150
url: /tr/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Kişi, e-posta iletisi, takvim randevusu veya görev öğesi gibi belirli bir nesneye ilişkin verileri içerir. DataContainer, öğeleri değiştirmek, öğeleri eklemek veya istemci cihaz veya sunucudaki öğeleri almak için kullanılabilir.

```csharp
public class DataContainer : IEnumerable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | DataContainer sınıfının yeni bir örneğini başlatır. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | DataContainer sınıfının yeni bir örneğini başlatır. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | DataContainer sınıfının yeni bir örneğini başlatır. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | DataContainer sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Verinin ikili olup olmadığını belirtir. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Verileri veri kapsayıcısında bulunan öğenin adı. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Seçilen element için DataContainer alır DataContainer miktarı birden fazlaysa AsposeException yükselir. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | Verileri veri kapsayıcısında bulunan öğenin Ad Alanı. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Ana DataContainer |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | element için xml düğümünde önek |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | ApplicationData öğesinin alt öğelerini yeni bir Listeye kopyalar. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | element değeri |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Öğenin verilerini xml biçiminde DataContainer'a ekler. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Öğenin verilerini xml biçiminde DataContainer'a ekler. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | element için boş DataContainer ekler. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Öğenin verilerini DataContainer'a ekler. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Öğenin verilerini DataContainer'a ekler. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Seçili element için DataContainers listesini alır |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Seçili element için DataContainers listesini alır |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Koleksiyon boyunca yinelenen bir Numaralandırıcı döndürür. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
