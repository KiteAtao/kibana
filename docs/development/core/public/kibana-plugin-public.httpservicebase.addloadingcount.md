<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-public](./kibana-plugin-public.md) &gt; [HttpServiceBase](./kibana-plugin-public.httpservicebase.md) &gt; [addLoadingCount](./kibana-plugin-public.httpservicebase.addloadingcount.md)

## HttpServiceBase.addLoadingCount() method

Adds a new source of loading counts. Used to show the global loading indicator when sum of all observed counts are more than 0.

<b>Signature:</b>

```typescript
addLoadingCount(countSource$: Observable<number>): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  countSource$ | <code>Observable&lt;number&gt;</code> |  |

<b>Returns:</b>

`void`

