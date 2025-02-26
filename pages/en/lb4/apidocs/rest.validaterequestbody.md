---
lang: en
title: 'API docs: rest.validaterequestbody'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.validaterequestbody.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [validateRequestBody](./rest.validaterequestbody.md)

## validateRequestBody() function

Check whether the request body is valid according to the provided OpenAPI schema. The JSON schema is generated from the OpenAPI schema which is typically defined by `@requestBody()`<!-- -->. The validation leverages AJV schema validator.

<b>Signature:</b>

```typescript
export declare function validateRequestBody(body: RequestBody, requestBodySpec?: RequestBodyObject, globalSchemas?: SchemasObject, options?: ValidationOptions): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  body | [RequestBody](./rest.requestbody.md) | The request body parsed from an HTTP request. |
|  requestBodySpec | RequestBodyObject | The OpenAPI requestBody specification defined in <code>@requestBody()</code>. |
|  globalSchemas | SchemasObject | The referenced schemas generated from <code>OpenAPISpec.components.schemas</code>. |
|  options | [ValidationOptions](./rest.validationoptions.md) | Request body validation options for AJV |

<b>Returns:</b>

Promise&lt;void&gt;


