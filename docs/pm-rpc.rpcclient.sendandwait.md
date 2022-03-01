<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [pm-rpc](./pm-rpc.md) &gt; [RpcClient](./pm-rpc.rpcclient.md) &gt; [sendAndWait](./pm-rpc.rpcclient.sendandwait.md)

## RpcClient.sendAndWait() method

Execute a message exchange and \*wait\* for the response. \*\*\*This will block the main thread\*\*\*.

<b>Signature:</b>

```typescript
sendAndWait<ReturnData = any, SendData = any>(opcode: string, payload?: SendData, timeout?: number): Promise<MaybeProps<ReturnData>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  opcode | string | An opcode indicating the procedure being executed. |
|  payload | SendData | The request payload. |
|  timeout | number | Duration in milliseconds after which the wait period times out unless a message is received. For an indefinite wait-period, set this to -1 (not recommended). |

<b>Returns:</b>

Promise&lt;MaybeProps&lt;ReturnData&gt;&gt;
