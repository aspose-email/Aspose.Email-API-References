---
title: ConnectionAsgmtMode
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft den Wert ab oder legt ihn fest der den Modus der Verbindungszuweisung in der Umgebung mit mehreren Threads definiert Es gibt folgende Verbindungstypen - Die Hauptverbindung ist eine Verbindung die zusammen mit dem E-Mail-Client erstellt und verworfen wird. Sie kann nicht manuell erstellt oder verworfen werden. - Standardverbindung ist Standardverbindung für einige Threads. Wenn eine Standardverbindung existiert und ConnectionAsgmtMode erlaubt werden alle Methoden des E-Mail-Clients die in diesem Thread ausgeführt werden implizit diese Verbindung verwenden. Pro Thread kann nur eine Standardverbindung existieren. Es kann manuell oder automatisch erstellt werden. Dies hängt von der Eigenschaft EmailClient.ConnectionAsgmtMode ab. Diese Verbindungen können manuell mit der Methode EmailClient.CreateConnectioncreateAsDefaultConnection  true erstellt werden. Wenn die Standardverbindung nicht verwendet wird abhängig vom Verbindungszuweisungsmodus wird stattdessen implizit die Hauptverbindung verwendet. - Unabhängige Verbindungen sind Verbindungen die vorhanden sind nicht mit Threads verknüpft. Sie können manuell erstellt werden und müssen explizit als Methodenparameter verwendet werden. Diese Verbindungen können manuell mit der EmailClient.CreateConnection-Methode oder der EmailClient.CreateConnectioncreateAsDefaultConnection  false-Methode erstellt werden. Es gibt folgende Verbindungszuweisungstypen - ConnectionAsgmtType.UseMainOrDefault Dieser Modus wird standardmäßig in E-Mail-Clients verwendet. Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads wenn keine Standardverbindung erstellt wurde oder die Verbindung nicht explizit als Methodenparameter übergeben wurde. Die Hauptverbindung ist eine Verbindung die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann Standardverbindungen für Threads mit der CreateConnection-Methode erstellen. Wenn die Standardverbindung für Thread erstellt wird wird sie implizit für alle Methoden des E-Mail-Clients verwendet die in diesem Thread aufgerufen werden. Wenn die Standardverbindung für Thread nicht erstellt wird wird die Hauptverbindung für alle Methoden des E-Mail-Clients verwendet die in diesem Thread aufgerufen werden thread. Der Benutzer kann mit der CreateConnection-Methode auch Verbindungen erstellen die nicht mit Threads verknüpft sind keine Standardverbindungen. Wenn der Benutzer andere Verbindungen verwenden möchte nicht main und nicht default muss er diese Verbindung explizit als Parameter einer Methode übergeben die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie dass Standardverbindungen korrekt funktionieren wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden muss der Benutzer die Standardverbindung falls er sie verwendet am Ende des Codes der ausgeführt wird manuell entfernen the thread. - ConnectionAsgmtType.UseMain Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads. Die Hauptverbindung ist eine Verbindung die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann keine Standardverbindungen erstellen. Der Benutzer kann mit der CreateConnection-Methode Verbindungen erstellen die nicht mit Threads verknüpft sind keine Standardverbindungen. Wenn der Benutzer andere Verbindungen verwenden möchte nicht main und nicht default muss er diese Verbindung explizit als Parameter einer Methode übergeben die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. - ConnectionAsgmtType.UseDefault Der E-Mail-Client verwendet implizit nur Standardverbindungen für alle Vorgänge aus mehreren Threads. Die Hauptverbindung wird in diesem Modus nicht verwendet. Wenn für einen Thread keine Standardverbindung erstellt wurde erster Aufruf der E-Mail-Client-Methode erstellt der E-Mail-Client implizit eine Standardverbindung für den Thread bevor die erste Operation ausgeführt wird. Der Benutzer kann dies nicht Erstellen Sie Standardverbindungen für Threads mit der CreateConnection-Methode da sie automatisch erstellt werden. Wenn die Standardverbindung für Thread erstellt wird wird sie implizit für alle Methoden des E-Mail-Clients verwendet die in diesem Thread aufgerufen werden.read. Der Benutzer kann auch Verbindungen erstellen die nicht mit Threads verknüpft sind keine Standardverbindungen mit der CreateConnection-Methode. Wenn der Benutzer andere Verbindungen verwenden möchte nicht main und nicht default muss er diese Verbindung explizit als Parameter einer Methode übergeben die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie dass Standardverbindungen korrekt funktionieren wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden muss der Benutzer die Standardverbindung manuell am Ende des Codes entfernen der im Thread ausgeführt wird.
type: docs
weight: 30
url: /de/net/aspose.email.clients/emailclient/connectionasgmtmode/
---
## EmailClient.ConnectionAsgmtMode property

Ruft den Wert ab oder legt ihn fest, der den Modus der Verbindungszuweisung in der Umgebung mit mehreren Threads definiert Es gibt folgende Verbindungstypen: - Die Hauptverbindung ist eine Verbindung, die zusammen mit dem E-Mail-Client erstellt und verworfen wird. Sie kann nicht manuell erstellt oder verworfen werden. - Standardverbindung ist Standardverbindung für einige Threads. Wenn eine Standardverbindung existiert und ConnectionAsgmtMode erlaubt, werden alle Methoden des E-Mail-Clients, die in diesem Thread ausgeführt werden, implizit diese Verbindung verwenden. Pro Thread kann nur eine Standardverbindung existieren. Es kann manuell oder automatisch erstellt werden. Dies hängt von der Eigenschaft EmailClient.ConnectionAsgmtMode ab. Diese Verbindungen können manuell mit der Methode EmailClient.CreateConnection(createAsDefaultConnection = true) erstellt werden. Wenn die Standardverbindung nicht verwendet wird (abhängig vom Verbindungszuweisungsmodus), wird stattdessen implizit die Hauptverbindung verwendet. - Unabhängige Verbindungen sind Verbindungen, die vorhanden sind nicht mit Threads verknüpft. Sie können manuell erstellt werden und müssen explizit als Methodenparameter verwendet werden. Diese Verbindungen können manuell mit der EmailClient.CreateConnection()-Methode oder der EmailClient.CreateConnection(createAsDefaultConnection = false)-Methode erstellt werden. Es gibt folgende Verbindungszuweisungstypen: - ConnectionAsgmtType.UseMainOrDefault Dieser Modus wird standardmäßig in E-Mail-Clients verwendet. Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads, wenn keine Standardverbindung erstellt wurde oder die Verbindung nicht explizit als Methodenparameter übergeben wurde. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann Standardverbindungen für Threads mit der CreateConnection-Methode erstellen. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden. Wenn die Standardverbindung für Thread nicht erstellt wird, wird die Hauptverbindung für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden thread. Der Benutzer kann mit der CreateConnection-Methode auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung (falls er sie verwendet) am Ende des Codes, der ausgeführt wird, manuell entfernen the thread. - ConnectionAsgmtType.UseMain Der E-Mail-Client verwendet die Hauptverbindung für alle Vorgänge aus mehreren Threads. Die Hauptverbindung ist eine Verbindung, die gleichzeitig mit dem E-Mail-Client erstellt wird. Der Benutzer kann keine Standardverbindungen erstellen. Der Benutzer kann mit der CreateConnection-Methode Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen). Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. - ConnectionAsgmtType.UseDefault Der E-Mail-Client verwendet implizit nur Standardverbindungen für alle Vorgänge aus mehreren Threads. Die Hauptverbindung wird in diesem Modus nicht verwendet. Wenn für einen Thread keine Standardverbindung erstellt wurde (erster Aufruf der E-Mail-Client-Methode), erstellt der E-Mail-Client implizit eine Standardverbindung für den Thread, bevor die erste Operation ausgeführt wird. Der Benutzer kann dies nicht Erstellen Sie Standardverbindungen für Threads mit der CreateConnection-Methode, da sie automatisch erstellt werden. Wenn die Standardverbindung für Thread erstellt wird, wird sie implizit für alle Methoden des E-Mail-Clients verwendet, die in diesem Thread aufgerufen werden.read. Der Benutzer kann auch Verbindungen erstellen, die nicht mit Threads verknüpft sind (keine Standardverbindungen) mit der CreateConnection-Methode. Wenn der Benutzer andere Verbindungen verwenden möchte (nicht main und nicht default), muss er diese Verbindung explizit als Parameter einer Methode übergeben, die er verwenden möchte. Der Benutzer kann zusätzlich beliebig viele Verbindungen erstellen. Die Standardverbindung kann nur eine pro Thread sein. Bitte beachten Sie, dass Standardverbindungen korrekt funktionieren, wenn der Benutzer Thread-Objekte für die Multitasking-Programmierung verwendet. Wenn der Benutzer ConnectionPool oder Task-Objekte für die Multitasking-Programmierung verwendet, kann dieser Modus zu einem falschen Verhalten eines Programms führen. Um dieses Problem zu vermeiden, muss der Benutzer die Standardverbindung manuell am Ende des Codes entfernen, der im Thread ausgeführt wird.

```csharp
public virtual ConnectionAsgmtType ConnectionAsgmtMode { get; set; }
```

### Siehe auch

* enum [ConnectionAsgmtType](../../connectionasgmttype)
* class [EmailClient](../../emailclient)
* namensraum [Aspose.Email.Clients](../../emailclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->