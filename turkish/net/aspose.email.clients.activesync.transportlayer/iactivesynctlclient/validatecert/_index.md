---
title: ValidateCert
second_title: Aspose.Email for .NET API Referansı
description: ValidateCert komutu istemci tarafından bir S/MIME postası aracılığıyla alınan bir sertifikayı doğrulamak için kullanılır.
type: docs
weight: 250
url: /tr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

ValidateCert komutu, istemci tarafından bir S/MIME postası aracılığıyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificate | X509Certificate | Onaylanması gereken sertifika. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificate | X509Certificate | Onaylanması gereken sertifika. |
| checkCrl | Boolean | Sunucunun doğrulanamayan bir iptal durumunu yoksayması GEREKİR. Sertifika iptal listeleri (CRL'ler) alınamadığında bir sertifikanın iptal durumu doğrulanamaz. CheckCRL değeri DOĞRU olarak ayarlandığında, sunucu bir sertifikanın iptal durumu doğrulanamaz. doğrulanamayan iptal durumu. CheckCRL değeri YANLIŞ olarak ayarlandığında, sunucu doğrulanamayan bir iptal durumunu yok saymalıdır ÖNEMLİDİR. Varsayılan değer YANLIŞ'tır. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificate | X509Certificate | Onaylanması gereken sertifika. |
| certificateChains | IEnumerable`1 | Doğrulanacak sertifikaların listesi. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificate | X509Certificate | Onaylanması gereken sertifika. |
| certificateChains | IEnumerable`1 | Doğrulanması gereken sertifikaların listesi. |
| checkCrl | Boolean | Sunucunun doğrulanamayan bir iptal durumunu yoksayması GEREKİR. Sertifika iptal listeleri (CRL'ler) alınamadığında bir sertifikanın iptal durumu doğrulanamaz. CheckCRL değeri DOĞRU olarak ayarlandığında, sunucu bir sertifikanın iptal durumu doğrulanamaz. doğrulanamayan iptal durumu. CheckCRL değeri YANLIŞ olarak ayarlandığında, sunucu doğrulanamayan bir iptal durumunu yok saymalıdır ÖNEMLİDİR. Varsayılan değer YANLIŞ'tır. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificates | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificates | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |
| checkCrl | Boolean | Sunucunun doğrulanamayan bir iptal durumunu yoksayması GEREKİR. Sertifika iptal listeleri (CRL'ler) alınamadığında bir sertifikanın iptal durumu doğrulanamaz. CheckCRL değeri DOĞRU olarak ayarlandığında, sunucu bir sertifikanın iptal durumu doğrulanamaz. doğrulanamayan iptal durumu. CheckCRL değeri YANLIŞ olarak ayarlandığında, sunucu doğrulanamayan bir iptal durumunu yok saymalıdır ÖNEMLİDİR. Varsayılan değer YANLIŞ'tır. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificates | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |
| certificateChains | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| certificates | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |
| certificateChains | IEnumerable`1 | Doğrulanması gereken sertifikaların numaralandırılması. |
| checkCrl | Boolean | Sunucunun doğrulanamayan bir iptal durumunu yoksayması GEREKİR. Sertifika iptal listeleri (CRL'ler) alınamadığında bir sertifikanın iptal durumu doğrulanamaz. CheckCRL değeri DOĞRU olarak ayarlandığında, sunucu bir sertifikanın iptal durumu doğrulanamaz. doğrulanamayan iptal durumu. CheckCRL değeri YANLIŞ olarak ayarlandığında, sunucu doğrulanamayan bir iptal durumunu yok saymalıdır ÖNEMLİDİR. Varsayılan değer YANLIŞ'tır. |

### Geri dönüş değeri

Doğrulama sertifikası durumlarının listesi

### Ayrıca bakınız

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
