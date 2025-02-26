---
lang: en
title: 'API docs: metadata.decoratorfactory.mergewithinherited'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/metadata
permalink: /doc/en/lb4/apidocs.metadata.decoratorfactory.mergewithinherited.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/metadata](./metadata.md) &gt; [DecoratorFactory](./metadata.decoratorfactory.md) &gt; [mergeWithInherited](./metadata.decoratorfactory.mergewithinherited.md)

## DecoratorFactory.mergeWithInherited() method

This method is called by the default implementation of the decorator function to merge the spec argument from the decoration with the inherited metadata for a class, all properties, all methods, or all method parameters that are decorated by this decorator.

It MUST be overridden by subclasses to process inherited metadata.

<b>Signature:</b>

```typescript
protected mergeWithInherited(inheritedMetadata: M, target: Object, member?: string | symbol, descriptorOrIndex?: TypedPropertyDescriptor<any> | number): M;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  inheritedMetadata | M | Metadata inherited from the base classes |
|  target | Object | Decoration target |
|  member | string \| symbol | Optional property or method |
|  descriptorOrIndex | TypedPropertyDescriptor&lt;any&gt; \| number | Optional parameter index or method descriptor |

<b>Returns:</b>

M


