---
title: ValidateCert
second_title: Aspose.Email per riferimento all'API .NET
description: Il comando ValidateCert viene utilizzato dal client per convalidare un certificato ricevuto tramite e-mail S/MIME.
type: docs
weight: 250
url: /it/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

Il comando ValidateCert viene utilizzato dal client per convalidare un certificato ricevuto tramite e-mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificate | X509Certificate | Certificato che deve essere convalidato. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificate | X509Certificate | Certificato che deve essere convalidato. |
| checkCrl | Boolean | Specifica se il server DOVREBBE ignorare uno stato di revoca non verificabile. Lo stato di revoca di un certificato non può essere verificato quando non è possibile recuperare le liste di revoca dei certificati (CRL). Quando il valore CheckCRL è impostato su TRUE, il server NON DEVE ignorare un stato di revoca non verificabile. Quando il valore CheckCRL è impostato su FALSE, il server DOVREBBE ignorare uno stato di revoca non verificabile. Il valore predefinito è FALSE. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificate | X509Certificate | Certificato che deve essere convalidato. |
| certificateChains | IEnumerable`1 | Elenco dei certificati da convalidare. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificate | X509Certificate | Certificato che deve essere convalidato. |
| certificateChains | IEnumerable`1 | Elenco dei certificati da convalidare. |
| checkCrl | Boolean | Specifica se il server DOVREBBE ignorare uno stato di revoca non verificabile. Lo stato di revoca di un certificato non può essere verificato quando non è possibile recuperare le liste di revoca dei certificati (CRL). Quando il valore CheckCRL è impostato su TRUE, il server NON DEVE ignorare un stato di revoca non verificabile. Quando il valore CheckCRL è impostato su FALSE, il server DOVREBBE ignorare uno stato di revoca non verificabile. Il valore predefinito è FALSE. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumerazione dei certificati da convalidare. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumerazione dei certificati da convalidare. |
| checkCrl | Boolean | Specifica se il server DOVREBBE ignorare uno stato di revoca non verificabile. Lo stato di revoca di un certificato non può essere verificato quando non è possibile recuperare le liste di revoca dei certificati (CRL). Quando il valore CheckCRL è impostato su TRUE, il server NON DEVE ignorare un stato di revoca non verificabile. Quando il valore CheckCRL è impostato su FALSE, il server DOVREBBE ignorare uno stato di revoca non verificabile. Il valore predefinito è FALSE. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumerazione dei certificati da convalidare. |
| certificateChains | IEnumerable`1 | Enumerazione dei certificati da convalidare. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumerazione dei certificati da convalidare. |
| certificateChains | IEnumerable`1 | Enumerazione dei certificati da convalidare. |
| checkCrl | Boolean | Specifica se il server DOVREBBE ignorare uno stato di revoca non verificabile. Lo stato di revoca di un certificato non può essere verificato quando non è possibile recuperare le liste di revoca dei certificati (CRL). Quando il valore CheckCRL è impostato su TRUE, il server NON DEVE ignorare un stato di revoca non verificabile. Quando il valore CheckCRL è impostato su FALSE, il server DOVREBBE ignorare uno stato di revoca non verificabile. Il valore predefinito è FALSE. |

### Valore di ritorno

Elenco degli stati dei certificati di convalida

### Guarda anche

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
