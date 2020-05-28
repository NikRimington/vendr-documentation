---
title: CalculateOrderLineTotalPriceTotalDiscountTask
description: API reference for CalculateOrderLineTotalPriceTotalDiscountTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CalculateOrderLineTotalPriceTotalDiscountTask

```csharp
public class CalculateOrderLineTotalPriceTotalDiscountTask : 
    PipelineTaskWithTypedArgsBase<OrderLineCalculationPipelineArgs, OrderLineCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.OrderLine.Tasks](../)

### Constructors

#### CalculateOrderLineTotalPriceTotalDiscountTask

The default constructor.

```csharp
public CalculateOrderLineTotalPriceTotalDiscountTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderLineCalculation> Execute(OrderLineCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->