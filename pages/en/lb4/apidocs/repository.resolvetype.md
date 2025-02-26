---
lang: en
title: 'API docs: repository.resolvetype'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.resolvetype.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [resolveType](./repository.resolvetype.md)

## resolveType() function

Resolve a type value that may have been provided via TypeResolver.

<b>Signature:</b>

```typescript
export declare function resolveType<T extends Object>(fn: TypeResolver<T> | Class<T>): Class<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | [TypeResolver](./repository.typeresolver.md)<!-- -->&lt;T&gt; \| [Class](./repository.class.md)<!-- -->&lt;T&gt; | A type class or a type provider. |

<b>Returns:</b>

[Class](./repository.class.md)<!-- -->&lt;T&gt;

The resolved type.


