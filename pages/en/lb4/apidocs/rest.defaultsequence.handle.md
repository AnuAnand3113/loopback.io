---
lang: en
title: 'API docs: rest.defaultsequence.handle'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.defaultsequence.handle.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [DefaultSequence](./rest.defaultsequence.md) &gt; [handle](./rest.defaultsequence.handle.md)

## DefaultSequence.handle() method

Runs the default sequence. Given a handler context (request and response), running the sequence will produce a response or an error.

Default sequence executes these steps - Executes middleware for CORS, OpenAPI spec endpoints - Finds the appropriate controller method, swagger spec and args for invocation - Parses HTTP request to get API argument list - Invokes the API which is defined in the Application Controller - Writes the result from API into the HTTP response - Error is caught and logged using 'logError' if any of the above steps in the sequence fails with an error.

<b>Signature:</b>

```typescript
handle(context: RequestContext): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  context | [RequestContext](./rest.requestcontext.md) | The request context: HTTP request and response objects, per-request IoC container and more. |

<b>Returns:</b>

Promise&lt;void&gt;


