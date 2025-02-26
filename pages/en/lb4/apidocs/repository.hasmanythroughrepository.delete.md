---
lang: en
title: 'API docs: repository.hasmanythroughrepository.delete'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.hasmanythroughrepository.delete.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [HasManyThroughRepository](./repository.hasmanythroughrepository.md) &gt; [delete](./repository.hasmanythroughrepository.delete.md)

## HasManyThroughRepository.delete() method

Delete multiple target model instances

<b>Signature:</b>

```typescript
delete(where?: Where<Target>, options?: Options & {
        throughOptions?: Options;
    }): Promise<Count>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  where | [Where](./filter.where.md)<!-- -->&lt;Target&gt; | Instances within the where scope are deleted |
|  options | [Options](./repository.options.md) &amp; { throughOptions?: [Options](./repository.options.md)<!-- -->; } |  |

<b>Returns:</b>

Promise&lt;[Count](./repository.count.md)<!-- -->&gt;

A promise which resolves the deleted target model instances


