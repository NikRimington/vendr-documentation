---
title: IPriceExtensions
description: API reference for IPriceExtensions in Vendr, the eCommerce solution for Umbraco v8+
---
## IPriceExtensions

Extensions methods for [`IPrice`](../../vendr-core-models/iprice/) entities

```csharp
public static class IPriceExtensions
```

**Namespace**
* [Vendr.Core](../)

### Methods

#### Formatted

Formats the [`IPrice`](../../vendr-core-models/iprice/) values for the given prices [`Currency`](../../vendr-core-models/currency/)

```csharp
public static FormattedPrice Formatted(this IPrice value)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| value | The [`IPrice`](../../vendr-core-models/iprice/) to format |

**Returns**

A [`FormattedPrice`](../../vendr-core-models/formattedprice/) instance


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->