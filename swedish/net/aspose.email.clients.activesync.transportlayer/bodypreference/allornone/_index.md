---
title: AllOrNone
second_title: Aspose.Email för .NET API-referens
description: En klient kan inkludera flera BodyPreference-element i en kommandobegäran med olika värden för Type-elementet avsnitt 2.2.2.22.4. Som standard returnerar servern data trunkerad till den storlek som begärts av TruncationSize för det Type-element som matchar det ursprungliga lagringsformatet för objektets Body-element. Men om klienten också inkluderar elementet AllOrNone med värdet TRUE tillsammans med TruncationSize-elementet instruerar den servern att inte returnera ett trunkerat svar för den typen när storleken i byte på tillgänglig data överstiger värdet av TruncationSize-elementet. Till exempel kan en klient använda dessa två element för att indikera att den inte kan bearbeta partiell Rich Text Format RTF-data ett Type-elementvärde på 3. I det här fallet om klienten har specificerat flera BodyPreference-element väljer servern nästa BodyPreference-element som kommer att returnera den maximala mängden brödtext till klienten. Antag att klienten anger två BodyPreference-element. Om elementet AllOrNone inte är definierat söks synkroniseras eller hämtas det trunkerade eller icke-trunkerade innehållet som om värdet var inställt på FALSE.
type: docs
weight: 20
url: /sv/net/aspose.email.clients.activesync.transportlayer/bodypreference/allornone/
---
## BodyPreference.AllOrNone property

En klient kan inkludera flera BodyPreference-element i en kommandobegäran med olika värden för Type-elementet (avsnitt 2.2.2.22.4). Som standard returnerar servern data trunkerad till den storlek som begärts av TruncationSize för det Type-element som matchar det ursprungliga lagringsformatet för objektets Body-element. Men om klienten också inkluderar elementet AllOrNone med värdet TRUE tillsammans med TruncationSize-elementet, instruerar den servern att inte returnera ett trunkerat svar för den typen när storleken (i byte) på tillgänglig data överstiger värdet av TruncationSize-elementet. Till exempel kan en klient använda dessa två element för att indikera att den inte kan bearbeta partiell Rich Text Format (RTF)-data (ett Type-elementvärde på 3). I det här fallet, om klienten har specificerat flera BodyPreference-element, väljer servern nästa BodyPreference-element som kommer att returnera den maximala mängden brödtext till klienten. Antag att klienten anger två BodyPreference-element. Om elementet AllOrNone inte är definierat, söks, synkroniseras eller hämtas det trunkerade eller icke-trunkerade innehållet som om värdet var inställt på FALSE.

```csharp
public bool? AllOrNone { get; set; }
```

### Se även

* class [BodyPreference](../../bodypreference)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../bodypreference)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->