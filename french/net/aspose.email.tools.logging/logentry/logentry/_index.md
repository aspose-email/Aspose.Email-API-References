---
title: LogEntry
second_title: Référence de l'API Aspose.Email pour .NET
description: Initialiser une nouvelle instance dunLogEntryaspose.email.tools.logging/logentry classe.
type: docs
weight: 10
url: /fr/net/aspose.email.tools.logging/logentry/logentry/
---
## LogEntry() {#constructor}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry()
```

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string) {#constructor_5}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry(string message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Le message. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, DateTime) {#constructor_9}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry(string message, DateTime time)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Le message. |
| time | DateTime | Le temps. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, Exception) {#constructor_10}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry(string message, Exception innerException)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| innerException | Exception | L'exception interne à enregistrer. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel) {#constructor_6}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry(string message, LogLevel severity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| severity | LogLevel | Gravité des entrées de journal en tant que[`Severity`](../severity) énumération. (Non spécifié, Information, Avertissement ou Erreur). |

### Voir également

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel) {#constructor_11}

Initialiser une nouvelle instance d'un[`LogEntry`](../../logentry) classe.

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| innerException | Exception | L'exception interne à enregistrer. |
| severity | LogLevel | Gravité des entrées de journal en tant que[`Severity`](../severity) énumération. (Non spécifié, Information, Avertissement ou Erreur). |

### Voir également

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, IDictionary&lt;string, string&gt;) {#constructor_8}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(string message, IDictionary<string, string> properties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| properties | IDictionary`2 | Dictionnaire des couples clé/valeur à enregistrer. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(byte[]) {#constructor_1}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(byte[] binaryDataMessage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Corps du message binaire à consigner. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding) {#constructor_3}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Corps du message binaire à consigner. |
| messageEncoding | Encoding | Encodage pour message binaire |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(byte[], IDictionary&lt;string, string&gt;) {#constructor_2}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(byte[] binaryDataMessage, IDictionary<string, string> properties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Corps du message binaire à consigner. |
| properties | IDictionary`2 | Dictionnaire des couples clé/valeur à enregistrer. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding, IDictionary&lt;string, string&gt;) {#constructor_4}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding, 
    IDictionary<string, string> properties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Corps du message binaire à consigner. |
| messageEncoding | Encoding | Encodage pour message binaire |
| properties | IDictionary`2 | Dictionnaire des couples clé/valeur à enregistrer. |

### Voir également

* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_7}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(string message, LogLevel severity, string category, int eventId, string title, 
    IDictionary<string, string> properties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| severity | LogLevel | Gravité des entrées de journal en tant que[`Severity`](../severity) énumération. (Non spécifié, Information, Avertissement ou Erreur). |
| category | String | Nom de catégorie utilisé pour acheminer l'entrée de journal vers un ou plusieurs récepteurs. |
| eventId | Int32 | Numéro d'événement ou identifiant. |
| title | String | Description supplémentaire du message d'entrée de journal. |
| properties | IDictionary`2 | Dictionnaire des couples clé/valeur à enregistrer. |

### Voir également

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_12}

Créer une nouvelle instance de[`LogEntry`](../../logentry) avec un ensemble complet de paramètres de constructeur

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity, string category, 
    int eventId, string title, IDictionary<string, string> properties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | String | Corps du message à enregistrer. Valeur de la méthode ToString() de l'objet message. |
| innerException | Exception | L'exception interne à enregistrer. |
| severity | LogLevel | Gravité des entrées de journal en tant que[`Severity`](../severity) énumération. (Non spécifié, Information, Avertissement ou Erreur). |
| category | String | Nom de catégorie utilisé pour acheminer l'entrée de journal vers un ou plusieurs récepteurs. |
| eventId | Int32 | Numéro d'événement ou identifiant. |
| title | String | Description supplémentaire du message d'entrée de journal. |
| properties | IDictionary`2 | Dictionnaire des couples clé/valeur à enregistrer. |

### Voir également

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espace de noms [Aspose.Email.Tools.Logging](../../logentry)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
