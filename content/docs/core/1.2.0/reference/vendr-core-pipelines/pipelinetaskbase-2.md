---
title: PipelineTaskBase<T,TResult>
description: API reference for PipelineTaskBase<T,TResult> in Vendr, the eCommerce solution for Umbraco v8+
---
## PipelineTaskBase&lt;T,TResult&gt;

```csharp
public abstract class PipelineTaskBase<T, TResult> : PipelineTaskBase, IPipelineAction<T>, 
    IPipelineTask<T, TResult>
```

**Inheritance**

* class [PipelineTaskBase](../pipelinetaskbase/)
* interface [IPipelineAction&lt;T&gt;](../ipipelineaction-1/)
* interface [IPipelineTask&lt;T,TResult&gt;](../ipipelinetask-2/)

**Namespace**
* [Vendr.Core.Pipelines](../)

### Methods

#### Execute

Executes the pipeline task.

```csharp
public override PipelineResult Execute(PipelineArgs input)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| input | The pipeline args. |

**Returns**

A pipeline result.


---

#### Execute

Executes the pipeline task.

```csharp
public abstract PipelineResult<TResult> Execute(PipelineArgs<T> args)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| input | The pipeline args. |

**Returns**

A pipeline result.


---

#### Fail

Creates a fail pipeline result.

```csharp
public virtual PipelineResult<TResult> Fail()
```

**Returns**

A fail pipeline result.


---

#### Fail (1 of 2)

Creates a fail pipeline result.

```csharp
public override PipelineResult Fail(object result)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |

**Returns**

A fail pipeline result.

---

#### Fail (2 of 2)

Creates a fail pipeline result.

```csharp
public override PipelineResult Fail(object result, Exception exception)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |
| exception | An exception message. |

**Returns**

A fail pipeline result.


---

#### Fail (1 of 3)

Creates a fail pipeline result.

```csharp
public virtual PipelineResult<TResult> Fail(TResult result)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |

**Returns**

A fail pipeline result.

---

#### Fail (2 of 3)

Creates a fail pipeline result.

```csharp
public virtual PipelineResult<TResult> Fail(Exception exception)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| exception | An exception message. |

**Returns**

A fail pipeline result.

---

#### Fail (3 of 3)

Creates a fail pipeline result.

```csharp
public virtual PipelineResult<TResult> Fail(TResult result, Exception exception)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |
| exception | An exception message. |

**Returns**

A fail pipeline result.


---

#### Ok

Creates a success pipeline result.

```csharp
public virtual PipelineResult<TResult> Ok()
```

**Returns**

A success pipeline result.


---

#### Ok

Creates a success pipeline result.

```csharp
public override PipelineResult Ok(object result)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |

**Returns**

A success pipeline result.


---

#### Ok

Creates a success pipeline result.

```csharp
public virtual PipelineResult<TResult> Ok(TResult result)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| result | The result data. |

**Returns**

A success pipeline result.


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->