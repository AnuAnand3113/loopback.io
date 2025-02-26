---
lang: en
title: 'API docs: context.context.getbinding_1'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.context.getbinding_1.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Context](./context.context.md) &gt; [getBinding](./context.context.getbinding_1.md)

## Context.getBinding() method

Look up a binding by key in the context and its ancestors. If no matching binding is found and `options.optional` is not set to true, an error will be thrown.

<b>Signature:</b>

```typescript
getBinding<ValueType>(key: BindingAddress<ValueType>, options?: {
        optional?: boolean;
    }): Binding<ValueType> | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | [BindingAddress](./context.bindingaddress.md)<!-- -->&lt;ValueType&gt; | Binding key |
|  options | { optional?: boolean; } | Options to control if the binding is optional. If <code>options.optional</code> is set to true, the method will return <code>undefined</code> instead of throwing an error if the binding key is not found. |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;ValueType&gt; \| undefined


