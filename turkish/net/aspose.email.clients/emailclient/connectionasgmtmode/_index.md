---
title: ConnectionAsgmtMode
second_title: Aspose.Email for .NET API Referansı
description: Birden çok iş parçacığı ortamında bağlantı ayırma modunu tanımlayan değeri alır veya ayarlar Aşağıdaki bağlantı türleri vardır - Ana bağlantı posta istemcisi ile birlikte oluşturulan ve atılan bağlantıdır.Manuel olarak oluşturulamaz veya atılamaz. - Varsayılan bağlantı bazı iş parçacıkları için varsayılan bağlantıdır. Varsayılan bağlantı varsa ve ConnectionAsgmtMode izin veriyorsa bu iş parçacığında yürütülen tüm e-posta istemcisi yöntemleri örtük olarak bu bağlantıyı kullanır. İş parçacığı başına yalnızca bir varsayılan bağlantı olabilir. Manuel veya otomatik olarak oluşturulabilir. EmailClient.ConnectionAsgmtMode özelliğine bağlıdır. Bu bağlantılar EmailClient.CreateConnectioncreateAsDefaultConnection  true yöntemiyle manuel olarak oluşturulabilir. Varsayılan bağlantı kullanılmazsa bağlantı ayırma moduna bağlıdır bunun yerine dolaylı olarak ana bağlantı kullanılır. - Bağımsız bağlantılar iş parçacıklarına bağlı değiller. Elle oluşturulabilirler ve açıkça yöntem parametresi olarak kullanılmaları gerekir. Bu bağlantılar EmailClient.CreateConnection yöntemiyle veya EmailClient.CreateConnectioncreateAsDefaultConnection  false yöntemiyle manuel olarak oluşturulabilir. Aşağıdaki bağlantı ayırma türleri vardır - ConnectionAsgmtType. Bu e-posta kipinde ConnectionAsgmtType.UseMainOrDefault varsayılan olarak kullanılır. E-posta istemcisi varsayılan bağlantı oluşturulmamışsa veya bağlantı açıkça yöntem parametresi olarak geçirilmemişse birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı CreateConnection yöntemi ile threadler için varsayılan bağlantılar oluşturabilir. Dizi için varsayılan bağlantı oluşturulursa bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Dizi için varsayılan bağlantı oluşturulmazsa bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için ana bağlantı kullanılır. thread. Kullanıcı ayrıca CreateConnection yöntemiyle threadlerle bağlantılı olmayan varsayılan bağlantılar değil bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa ana değil ve varsayılan değil bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı iş parçacığı başına yalnızca bir olabilir. Kullanıcı çoklu görev programlaması için Thread nesnelerini kullanıyorsa varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının varsayılan bağlantıyı kullanıyorsa çalıştıran kodun sonuna manuel olarak atması gerekir. thread. - ConnectionAsgmtType.UseMain E-posta istemcisi birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı varsayılan bağlantılar oluşturamaz. Kullanıcı CreateConnection yöntemiyle iş parçacıklarına bağlı olmayan varsayılan bağlantılar değil bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa ana değil ve varsayılan değil bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. - ConnectionAsgmtType.UseDefault E-posta istemcisi birden çok iş parçacığından gelen tüm işlemler için örtük olarak yalnızca varsayılan bağlantıları kullanır. Bu modda ana bağlantı kullanılmaz. Bir dizi için varsayılan bağlantı oluşturulmamışsa e-posta istemcisi yönteminin ilk çağrılması e-posta istemcisi ilk işlem yürütülmeden önce örtük olarak dizi için varsayılan bağlantı oluşturur. Kullanıcı yapamaz otomatik olarak oluşturuldukları için CreateConnection yöntemiyle iş parçacıkları için varsayılan bağlantılar oluşturun. İş parçacığı için varsayılan bağlantı oluşturulduğunda bu thread.read. içinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Kullanıcı ayrıca CreateConnection yöntemiyle iş parçacıklarıyla bağlantılı olmayan varsayılan bağlantılar değil bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa ana değil ve varsayılan değil bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı iş parçacığı başına yalnızca bir olabilir. Kullanıcı çoklu görev programlaması için Thread nesnelerini kullanıyorsa varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının iş parçacığında yürütülen kodun sonundaki varsayılan bağlantıyı manuel olarak atması gerekir.
type: docs
weight: 30
url: /tr/net/aspose.email.clients/emailclient/connectionasgmtmode/
---
## EmailClient.ConnectionAsgmtMode property

Birden çok iş parçacığı ortamında bağlantı ayırma modunu tanımlayan değeri alır veya ayarlar Aşağıdaki bağlantı türleri vardır: - Ana bağlantı, posta istemcisi ile birlikte oluşturulan ve atılan bağlantıdır.Manuel olarak oluşturulamaz veya atılamaz. - Varsayılan bağlantı, bazı iş parçacıkları için varsayılan bağlantıdır. Varsayılan bağlantı varsa ve ConnectionAsgmtMode izin veriyorsa, bu iş parçacığında yürütülen tüm e-posta istemcisi yöntemleri örtük olarak bu bağlantıyı kullanır. İş parçacığı başına yalnızca bir varsayılan bağlantı olabilir. Manuel veya otomatik olarak oluşturulabilir. EmailClient.ConnectionAsgmtMode özelliğine bağlıdır. Bu bağlantılar EmailClient.CreateConnection(createAsDefaultConnection = true) yöntemiyle manuel olarak oluşturulabilir. Varsayılan bağlantı kullanılmazsa (bağlantı ayırma moduna bağlıdır), bunun yerine dolaylı olarak ana bağlantı kullanılır. - Bağımsız bağlantılar, iş parçacıklarına bağlı değiller. Elle oluşturulabilirler ve açıkça yöntem parametresi olarak kullanılmaları gerekir. Bu bağlantılar, EmailClient.CreateConnection() yöntemiyle veya EmailClient.CreateConnection(createAsDefaultConnection = false) yöntemiyle manuel olarak oluşturulabilir. Aşağıdaki bağlantı ayırma türleri vardır: - ConnectionAsgmtType. Bu e-posta kipinde ConnectionAsgmtType.UseMainOrDefault varsayılan olarak kullanılır. E-posta istemcisi, varsayılan bağlantı oluşturulmamışsa veya bağlantı açıkça yöntem parametresi olarak geçirilmemişse, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı, CreateConnection yöntemi ile threadler için varsayılan bağlantılar oluşturabilir. Dizi için varsayılan bağlantı oluşturulursa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Dizi için varsayılan bağlantı oluşturulmazsa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için ana bağlantı kullanılır. thread. Kullanıcı ayrıca CreateConnection yöntemiyle threadlerle bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının varsayılan bağlantıyı (kullanıyorsa) çalıştıran kodun sonuna manuel olarak atması gerekir. thread. - ConnectionAsgmtType.UseMain E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı varsayılan bağlantılar oluşturamaz. Kullanıcı, CreateConnection yöntemiyle iş parçacıklarına bağlı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. - ConnectionAsgmtType.UseDefault E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için örtük olarak yalnızca varsayılan bağlantıları kullanır. Bu modda ana bağlantı kullanılmaz. Bir dizi için varsayılan bağlantı oluşturulmamışsa (e-posta istemcisi yönteminin ilk çağrılması), e-posta istemcisi, ilk işlem yürütülmeden önce örtük olarak dizi için varsayılan bağlantı oluşturur. Kullanıcı yapamaz otomatik olarak oluşturuldukları için CreateConnection yöntemiyle iş parçacıkları için varsayılan bağlantılar oluşturun. İş parçacığı için varsayılan bağlantı oluşturulduğunda, bu thread.read. içinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Kullanıcı ayrıca CreateConnection yöntemiyle iş parçacıklarıyla bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının iş parçacığında yürütülen kodun sonundaki varsayılan bağlantıyı manuel olarak atması gerekir.

```csharp
public virtual ConnectionAsgmtType ConnectionAsgmtMode { get; set; }
```

### Ayrıca bakınız

* enum [ConnectionAsgmtType](../../connectionasgmttype)
* class [EmailClient](../../emailclient)
* ad alanı [Aspose.Email.Clients](../../emailclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->