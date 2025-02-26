---
lang: en
title: 'API docs: express.invokeexpressmiddleware'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/express
permalink: /doc/en/lb4/apidocs.express.invokeexpressmiddleware.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/express](./express.md) &gt; [invokeExpressMiddleware](./express.invokeexpressmiddleware.md)

## invokeExpressMiddleware() function

Invoke a list of Express middleware handler functions

<b>Signature:</b>

```typescript
export declare function invokeExpressMiddleware(middlewareCtx: MiddlewareContext, ...handlers: ExpressRequestHandler[]): ValueOrPromise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  middlewareCtx | [MiddlewareContext](./express.middlewarecontext.md) | Middleware context |
|  handlers | [ExpressRequestHandler](./express.expressrequesthandler.md)<!-- -->\[\] | A list of Express middleware handler functions |

<b>Returns:</b>

[ValueOrPromise](./context.valueorpromise.md)<!-- -->&lt;boolean&gt;

## Example


```ts
import cors from 'cors';
import helmet from 'helmet';
import morgan from 'morgan';
import {MiddlewareContext, invokeExpressMiddleware} from '@loopback/express';

// ... Either an instance of `MiddlewareContext` is passed in or a new one
// can be instantiated from Express request and response objects

const middlewareCtx = new MiddlewareContext(request, response);
const finished = await invokeExpressMiddleware(
  middlewareCtx,
  cors(),
  helmet(),
  morgan('combined'));

if (finished) {
  // Http response is sent by one of the middleware
} else {
  // Http response is yet to be produced
}
```


