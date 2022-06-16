---
title: ValidateCert
second_title: Справочник по Aspose.Email для .NET API
description: Команда ValidateCert используется клиентом для проверки сертификата полученного по почте S/MIME.
type: docs
weight: 250
url: /ru/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

Команда ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate | Сертификат, который необходимо проверить. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate | Сертификат, который необходимо проверить. |
| checkCrl | Boolean | Указывает, ДОЛЖЕН ли сервер игнорировать неподдающийся проверке статус отзыва. Статус отзыва сертификата не может быть проверен, если невозможно получить списки отзыва сертификатов (CRL). Когда значение CheckCRL установлено в TRUE, сервер НЕ ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Когда значение CheckCRL установлено в FALSE, сервер ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Значение по умолчанию - FALSE. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate | Сертификат, который необходимо проверить. |
| certificateChains | IEnumerable`1 | Список сертификатов, подлежащих проверке. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate | Сертификат, который необходимо проверить. |
| certificateChains | IEnumerable`1 | Список сертификатов, которые необходимо проверить. |
| checkCrl | Boolean | Указывает, ДОЛЖЕН ли сервер игнорировать неподдающийся проверке статус отзыва. Статус отзыва сертификата не может быть проверен, если невозможно получить списки отзыва сертификатов (CRL). Когда значение CheckCRL установлено в TRUE, сервер НЕ ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Когда значение CheckCRL установлено в FALSE, сервер ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Значение по умолчанию - FALSE. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificates | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificates | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |
| checkCrl | Boolean | Указывает, ДОЛЖЕН ли сервер игнорировать неподдающийся проверке статус отзыва. Статус отзыва сертификата не может быть проверен, если невозможно получить списки отзыва сертификатов (CRL). Когда значение CheckCRL установлено в TRUE, сервер НЕ ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Когда значение CheckCRL установлено в FALSE, сервер ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Значение по умолчанию - FALSE. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificates | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |
| certificateChains | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificates | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |
| certificateChains | IEnumerable`1 | Перечень сертификатов, которые необходимо проверить. |
| checkCrl | Boolean | Указывает, ДОЛЖЕН ли сервер игнорировать неподдающийся проверке статус отзыва. Статус отзыва сертификата не может быть проверен, если невозможно получить списки отзыва сертификатов (CRL). Когда значение CheckCRL установлено в TRUE, сервер НЕ ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Когда значение CheckCRL установлено в FALSE, сервер ДОЛЖЕН игнорировать неподдающийся проверке статус отзыва. Значение по умолчанию - FALSE. |

### Возвращаемое значение

Список статусов сертификатов проверки

### Смотрите также

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
