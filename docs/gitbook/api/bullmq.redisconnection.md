<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [RedisConnection](./bullmq.redisconnection.md)

## RedisConnection class

<b>Signature:</b>

```typescript
export declare class RedisConnection extends EventEmitter 
```
<b>Extends:</b> EventEmitter

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(opts)](./bullmq.redisconnection._constructor_.md) |  | Constructs a new instance of the <code>RedisConnection</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [client](./bullmq.redisconnection.client.md) |  | Promise&lt;IORedis.Redis&gt; |  |
|  [minimumVersion](./bullmq.redisconnection.minimumversion.md) | <code>static</code> | string |  |
|  [redisVersion](./bullmq.redisconnection.redisversion.md) |  | string |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [close()](./bullmq.redisconnection.close.md) |  |  |
|  [disconnect()](./bullmq.redisconnection.disconnect.md) |  |  |
|  [reconnect()](./bullmq.redisconnection.reconnect.md) |  |  |
|  [waitUntilReady(client)](./bullmq.redisconnection.waituntilready.md) | <code>static</code> | Waits for a redis client to be ready. |

