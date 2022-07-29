---
title: Range
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica el número de entradas coincidentes que se devuelven. El formato del valor del elemento Range tiene la forma de un especificador de índice basado en cero formado por un cero un guión y otro valor numérico mn. La m indica el índice más bajo de una matriz de base cero que contendría los elementos. La n indica el índice más alto de una matriz de base cero que contendría los elementos. Por ejemplo un valor de elemento Rango de 09 indica 10 elementos y 010 indica 11 elementos. Un valor de elemento de Rango de 00 indica 1 elemento. Si Rango es nulo se usa el valor de Rango predeterminado para cada tipo de Tienda. La siguiente tabla identifica los valores de rango predeterminados y los resultados máximos devueltos para cada tipo de tienda Mailbox - Valor de rango predeterminado 0-99 - Resultados máximos devueltos 100 DocumentLibrary - Valor de rango predeterminado 0-999 - Resultados máximos devueltos  1000 GAL - Valor de rango predeterminado 0-99 - Resultados máximos devueltos 100 Si el valor de rango especificado en la solicitud excede el valor de rango predeterminado se devuelve un valor de estado de 12 para indicar que se ha excedido el rango máximo. En la respuesta del comando Buscar la propiedad Total indica una estimación del número total de entradas que coincidieron con el valor de Consulta. Los resultados de la búsqueda se almacenan en una carpeta de búsqueda en el servidor. De esta forma cuando un cliente regresa con la misma consulta pero con un nuevo rango de filas las filas se extraen del conjunto de resultados que está actualmente almacenado en la carpeta de búsqueda. No es necesario reconstruir todo el conjunto de resultados.
type: docs
weight: 20
url: /es/net/aspose.email.clients.activesync.transportlayer/searchresponsestore/range/
---
## SearchResponseStore.Range property

Especifica el número de entradas coincidentes que se devuelven. El formato del valor del elemento Range tiene la forma de un especificador de índice basado en cero, formado por un cero, un guión y otro valor numérico: "mn". La m indica el índice más bajo de una matriz de base cero que contendría los elementos. La n indica el índice más alto de una matriz de base cero que contendría los elementos. Por ejemplo, un valor de elemento Rango de 0–9 indica 10 elementos y 0–10 indica 11 elementos. Un valor de elemento de Rango de 0–0 indica 1 elemento. Si Rango es nulo, se usa el valor de Rango predeterminado para cada tipo de Tienda. La siguiente tabla identifica los valores de rango predeterminados y los resultados máximos devueltos para cada tipo de tienda: Mailbox - Valor de rango predeterminado: 0-99 - Resultados máximos devueltos: 100 DocumentLibrary - Valor de rango predeterminado: 0-999 - Resultados máximos devueltos : 1000 GAL - Valor de rango predeterminado: 0-99 - Resultados máximos devueltos: 100 Si el valor de rango especificado en la solicitud excede el valor de rango predeterminado, se devuelve un valor de estado de 12 para indicar que se ha excedido el rango máximo. En la respuesta del comando Buscar, la propiedad Total indica una estimación del número total de entradas que coincidieron con el valor de Consulta. Los resultados de la búsqueda se almacenan en una carpeta de búsqueda en el servidor. De esta forma, cuando un cliente regresa con la misma consulta pero con un nuevo rango de filas, las filas se extraen del conjunto de resultados que está actualmente almacenado en la carpeta de búsqueda. No es necesario reconstruir todo el conjunto de resultados.

```csharp
public string Range { get; set; }
```

### Ver también

* class [SearchResponseStore](../../searchresponsestore)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchresponsestore)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->