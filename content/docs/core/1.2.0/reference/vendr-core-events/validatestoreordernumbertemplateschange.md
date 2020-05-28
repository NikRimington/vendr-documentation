---
title: ValidateStoreOrderNumberTemplatesChange
description: API reference for ValidateStoreOrderNumberTemplatesChange in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateStoreOrderNumberTemplatesChange

```csharp
public class ValidateStoreOrderNumberTemplatesChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateStoreOrderNumberTemplatesChange

```csharp
public ValidateStoreOrderNumberTemplatesChange(StoreReadOnly store, 
    ChangingValue<string> cartNumberTemplate, ChangingValue<string> orderNumberTemplate)
```


### Properties

#### CartNumberTemplate

```csharp
public ChangingValue<string> CartNumberTemplate { get; }
```


---

#### OrderNumberTemplate

```csharp
public ChangingValue<string> OrderNumberTemplate { get; }
```


---

#### Store

```csharp
public StoreReadOnly Store { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->