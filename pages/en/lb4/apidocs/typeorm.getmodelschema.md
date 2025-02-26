---
lang: en
title: 'API docs: typeorm.getmodelschema'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/extensions/typeorm
permalink: /doc/en/lb4/apidocs.typeorm.getmodelschema.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/typeorm](./typeorm.md) &gt; [getModelSchema](./typeorm.getmodelschema.md)

## getModelSchema() function

Describe the provided Entity as a reference to a definition shared by multiple endpoints. The definition is included in the returned schema.

<b>Signature:</b>

```typescript
export declare function getModelSchema<T extends object>(modelCtor: Function & {
    prototype: T;
}, options?: JsonSchemaOptions<T>): SchemaObject;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelCtor | Function &amp; { prototype: T; } | The entity constructor (e.g. <code>Product</code>) |
|  options | [JsonSchemaOptions](./repository-json-schema.jsonschemaoptions.md)<!-- -->&lt;T&gt; | Additional options |

<b>Returns:</b>

SchemaObject


