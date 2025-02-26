---
lang: en
title: 'API docs: metadata.methodparameterdecoratorfactory.createdecorator'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/metadata
permalink: /doc/en/lb4/apidocs.metadata.methodparameterdecoratorfactory.createdecorator.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/metadata](./metadata.md) &gt; [MethodParameterDecoratorFactory](./metadata.methodparameterdecoratorfactory.md) &gt; [createDecorator](./metadata.methodparameterdecoratorfactory.createdecorator.md)

## MethodParameterDecoratorFactory.createDecorator() method

Create a method decorator function

<b>Signature:</b>

```typescript
static createDecorator<S>(key: MetadataKey<S, MethodDecorator>, spec: S, options?: DecoratorOptions): MethodDecorator;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | [MetadataKey](./metadata.metadatakey.md)<!-- -->&lt;S, MethodDecorator&gt; | Metadata key |
|  spec | S | Metadata object from the decorator function |
|  options | [DecoratorOptions](./metadata.decoratoroptions.md) | Options for the decorator |

<b>Returns:</b>

MethodDecorator


