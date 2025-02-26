---
lang: en
title: 'API docs: filter.condition'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/filter
permalink: /doc/en/lb4/apidocs.filter.condition.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/filter](./filter.md) &gt; [Condition](./filter.condition.md)

## Condition type

Condition clause

<b>Signature:</b>

```typescript
export declare type Condition<MT extends object> = {
    [P in KeyOf<MT>]?: PredicateComparison<MT[P]> | (MT[P] & ShortHandEqualType);
};
```
<b>References:</b> [KeyOf](./filter.keyof.md)<!-- -->, [PredicateComparison](./filter.predicatecomparison.md)<!-- -->, [ShortHandEqualType](./filter.shorthandequaltype.md)

## Example


```ts
{
  name: {inq: ['John', 'Mary']},
  status: 'ACTIVE',
  age: {gte: 40}
}
```


