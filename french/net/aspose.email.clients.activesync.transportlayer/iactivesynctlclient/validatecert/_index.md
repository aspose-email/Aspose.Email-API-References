---
title: ValidateCert
second_title: Référence de l'API Aspose.Email pour .NET
description: La commande ValidateCert est utilisée par le client pour valider un certificat qui a été reçu via un courrier S/MIME.
type: docs
weight: 250
url: /fr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

La commande ValidateCert est utilisée par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificate | X509Certificate | Certificat qui doit être validé. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificate | X509Certificate | Certificat qui doit être validé. |
| checkCrl | Boolean | Spécifie si le serveur DEVRAIT ignorer un état de révocation invérifiable. L'état de révocation d'un certificat ne peut pas être vérifié lorsque les listes de révocation de certificats (CRL) ne peuvent pas être récupérées. Lorsque la valeur CheckCRL est définie sur TRUE, le serveur NE DOIT PAS ignorer un statut de révocation invérifiable. Lorsque la valeur CheckCRL est définie sur FALSE, le serveur DEVRAIT ignorer un état de révocation invérifiable. La valeur par défaut est FALSE. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificate | X509Certificate | Certificat qui doit être validé. |
| certificateChains | IEnumerable`1 | Liste des certificats à valider. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificate | X509Certificate | Certificat qui doit être validé. |
| certificateChains | IEnumerable`1 | Liste des certificats qui doivent être validés. |
| checkCrl | Boolean | Spécifie si le serveur DEVRAIT ignorer un état de révocation invérifiable. L'état de révocation d'un certificat ne peut pas être vérifié lorsque les listes de révocation de certificats (CRL) ne peuvent pas être récupérées. Lorsque la valeur CheckCRL est définie sur TRUE, le serveur NE DOIT PAS ignorer un statut de révocation invérifiable. Lorsque la valeur CheckCRL est définie sur FALSE, le serveur DEVRAIT ignorer un état de révocation invérifiable. La valeur par défaut est FALSE. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumération des certificats qui doivent être validés. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumération des certificats qui doivent être validés. |
| checkCrl | Boolean | Spécifie si le serveur DEVRAIT ignorer un état de révocation invérifiable. L'état de révocation d'un certificat ne peut pas être vérifié lorsque les listes de révocation de certificats (CRL) ne peuvent pas être récupérées. Lorsque la valeur CheckCRL est définie sur TRUE, le serveur NE DOIT PAS ignorer un statut de révocation invérifiable. Lorsque la valeur CheckCRL est définie sur FALSE, le serveur DEVRAIT ignorer un état de révocation invérifiable. La valeur par défaut est FALSE. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumération des certificats qui doivent être validés. |
| certificateChains | IEnumerable`1 | Enumération des certificats qui doivent être validés. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumération des certificats qui doivent être validés. |
| certificateChains | IEnumerable`1 | Enumération des certificats qui doivent être validés. |
| checkCrl | Boolean | Spécifie si le serveur DEVRAIT ignorer un état de révocation invérifiable. L'état de révocation d'un certificat ne peut pas être vérifié lorsque les listes de révocation de certificats (CRL) ne peuvent pas être récupérées. Lorsque la valeur CheckCRL est définie sur TRUE, le serveur NE DOIT PAS ignorer un statut de révocation invérifiable. Lorsque la valeur CheckCRL est définie sur FALSE, le serveur DEVRAIT ignorer un état de révocation invérifiable. La valeur par défaut est FALSE. |

### Return_Value

Liste des statuts des certificats de validation

### Voir également

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
