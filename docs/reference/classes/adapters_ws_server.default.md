[@asyncapi/glee](../README.md) / [adapters/ws/server](../modules/adapters_ws_server.md) / default

# Class: default

[adapters/ws/server](../modules/adapters_ws_server.md).default

## Hierarchy

- [`default`](lib_adapter.default.md)

  ↳ **`default`**

## Table of contents

### Constructors

- [constructor](adapters_ws_server.default.md#constructor)

### Properties

- [config](adapters_ws_server.default.md#config)
- [customHttpServer](adapters_ws_server.default.md#customhttpserver)
- [serverUrl](adapters_ws_server.default.md#serverurl)
- [websocketServers](adapters_ws_server.default.md#websocketservers)
- [wsHttpServer](adapters_ws_server.default.md#wshttpserver)
- [captureRejectionSymbol](adapters_ws_server.default.md#capturerejectionsymbol)
- [captureRejections](adapters_ws_server.default.md#capturerejections)
- [defaultMaxListeners](adapters_ws_server.default.md#defaultmaxlisteners)
- [errorMonitor](adapters_ws_server.default.md#errormonitor)

### Accessors

- [AsyncAPIServer](adapters_ws_server.default.md#asyncapiserver)
- [channelAddresses](adapters_ws_server.default.md#channeladdresses)
- [channelNames](adapters_ws_server.default.md#channelnames)
- [connections](adapters_ws_server.default.md#connections)
- [glee](adapters_ws_server.default.md#glee)
- [operationIds](adapters_ws_server.default.md#operationids)
- [parsedAsyncAPI](adapters_ws_server.default.md#parsedasyncapi)
- [serverName](adapters_ws_server.default.md#servername)
- [serverUrlExpanded](adapters_ws_server.default.md#serverurlexpanded)

### Methods

- [\_connect](adapters_ws_server.default.md#_connect)
- [\_createMessage](adapters_ws_server.default.md#_createmessage)
- [\_createServers](adapters_ws_server.default.md#_createservers)
- [\_endRequest](adapters_ws_server.default.md#_endrequest)
- [\_extractPathname](adapters_ws_server.default.md#_extractpathname)
- [\_getChannel](adapters_ws_server.default.md#_getchannel)
- [\_getPort](adapters_ws_server.default.md#_getport)
- [\_handleBroadcastMessage](adapters_ws_server.default.md#_handlebroadcastmessage)
- [\_handleDirectMessage](adapters_ws_server.default.md#_handledirectmessage)
- [\_handleInvalidChannel](adapters_ws_server.default.md#_handleinvalidchannel)
- [\_handleRequest](adapters_ws_server.default.md#_handlerequest)
- [\_initializeServerEvents](adapters_ws_server.default.md#_initializeserverevents)
- [\_send](adapters_ws_server.default.md#_send)
- [\_validateDirectMessage](adapters_ws_server.default.md#_validatedirectmessage)
- [\_validateHeaders](adapters_ws_server.default.md#_validateheaders)
- [\_validateMethod](adapters_ws_server.default.md#_validatemethod)
- [\_validatePort](adapters_ws_server.default.md#_validateport)
- [\_validateQueries](adapters_ws_server.default.md#_validatequeries)
- [\_validateRequest](adapters_ws_server.default.md#_validaterequest)
- [\_validateRequestAgainstBindings](adapters_ws_server.default.md#_validaterequestagainstbindings)
- [\_verifyClientFunc](adapters_ws_server.default.md#_verifyclientfunc)
- [\_wrapCallbackDecorator](adapters_ws_server.default.md#_wrapcallbackdecorator)
- [addListener](adapters_ws_server.default.md#addlistener)
- [connect](adapters_ws_server.default.md#connect)
- [emit](adapters_ws_server.default.md#emit)
- [eventNames](adapters_ws_server.default.md#eventnames)
- [getAuthConfig](adapters_ws_server.default.md#getauthconfig)
- [getMaxListeners](adapters_ws_server.default.md#getmaxlisteners)
- [getSubscribedChannels](adapters_ws_server.default.md#getsubscribedchannels)
- [listenerCount](adapters_ws_server.default.md#listenercount)
- [listeners](adapters_ws_server.default.md#listeners)
- [name](adapters_ws_server.default.md#name)
- [off](adapters_ws_server.default.md#off)
- [on](adapters_ws_server.default.md#on)
- [once](adapters_ws_server.default.md#once)
- [prependListener](adapters_ws_server.default.md#prependlistener)
- [prependOnceListener](adapters_ws_server.default.md#prependoncelistener)
- [rawListeners](adapters_ws_server.default.md#rawlisteners)
- [removeAllListeners](adapters_ws_server.default.md#removealllisteners)
- [removeListener](adapters_ws_server.default.md#removelistener)
- [resolveProtocolConfig](adapters_ws_server.default.md#resolveprotocolconfig)
- [send](adapters_ws_server.default.md#send)
- [setMaxListeners](adapters_ws_server.default.md#setmaxlisteners)
- [getEventListeners](adapters_ws_server.default.md#geteventlisteners)
- [listenerCount](adapters_ws_server.default.md#listenercount-1)
- [on](adapters_ws_server.default.md#on-1)
- [once](adapters_ws_server.default.md#once-1)
- [setMaxListeners](adapters_ws_server.default.md#setmaxlisteners-1)

## Constructors

### constructor

• **new default**(`options`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`GleeAdapterOptions`](../interfaces/lib_adapter.GleeAdapterOptions.md) |

#### Overrides

[default](lib_adapter.default.md).[constructor](lib_adapter.default.md#constructor)

#### Defined in

[src/adapters/ws/server.ts:21](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L21)

## Properties

### config

• `Private` **config**: [`WebsocketServerAdapterConfig`](../modules/lib.md#websocketserveradapterconfig)

#### Defined in

[src/adapters/ws/server.ts:13](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L13)

___

### customHttpServer

• `Private` **customHttpServer**: `Server`<typeof `IncomingMessage`, typeof `ServerResponse`\>

#### Defined in

[src/adapters/ws/server.ts:16](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L16)

___

### serverUrl

• `Private` **serverUrl**: `URL`

#### Defined in

[src/adapters/ws/server.ts:14](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L14)

___

### websocketServers

• `Private` **websocketServers**: `Map`<`string`, `Server`<`WebSocket`\>\>

#### Defined in

[src/adapters/ws/server.ts:18](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L18)

___

### wsHttpServer

• `Private` **wsHttpServer**: `Server`<typeof `IncomingMessage`, typeof `ServerResponse`\>

#### Defined in

[src/adapters/ws/server.ts:15](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L15)

___

### captureRejectionSymbol

▪ `Static` `Readonly` **captureRejectionSymbol**: typeof [`captureRejectionSymbol`](adapters_cluster_redis.default.md#capturerejectionsymbol)

#### Inherited from

[default](lib_adapter.default.md).[captureRejectionSymbol](lib_adapter.default.md#capturerejectionsymbol)

#### Defined in

node_modules/@types/node/events.d.ts:328

___

### captureRejections

▪ `Static` **captureRejections**: `boolean`

Sets or gets the default captureRejection value for all emitters.

#### Inherited from

[default](lib_adapter.default.md).[captureRejections](lib_adapter.default.md#capturerejections)

#### Defined in

node_modules/@types/node/events.d.ts:333

___

### defaultMaxListeners

▪ `Static` **defaultMaxListeners**: `number`

#### Inherited from

[default](lib_adapter.default.md).[defaultMaxListeners](lib_adapter.default.md#defaultmaxlisteners)

#### Defined in

node_modules/@types/node/events.d.ts:334

___

### errorMonitor

▪ `Static` `Readonly` **errorMonitor**: typeof [`errorMonitor`](adapters_cluster_redis.default.md#errormonitor)

This symbol shall be used to install a listener for only monitoring `'error'`
events. Listeners installed using this symbol are called before the regular
`'error'` listeners are called.

Installing a listener using this symbol does not change the behavior once an
`'error'` event is emitted, therefore the process will still crash if no
regular `'error'` listener is installed.

#### Inherited from

[default](lib_adapter.default.md).[errorMonitor](lib_adapter.default.md#errormonitor)

#### Defined in

node_modules/@types/node/events.d.ts:327

## Accessors

### AsyncAPIServer

• `get` **AsyncAPIServer**(): `ServerInterface`

#### Returns

`ServerInterface`

#### Inherited from

Adapter.AsyncAPIServer

#### Defined in

[src/lib/adapter.ts:184](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L184)

___

### channelAddresses

• `get` **channelAddresses**(): `string`[]

#### Returns

`string`[]

#### Inherited from

Adapter.channelAddresses

#### Defined in

[src/lib/adapter.ts:200](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L200)

___

### channelNames

• `get` **channelNames**(): `string`[]

#### Returns

`string`[]

#### Inherited from

Adapter.channelNames

#### Defined in

[src/lib/adapter.ts:192](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L192)

___

### connections

• `get` **connections**(): [`default`](lib_connection.default.md)[]

#### Returns

[`default`](lib_connection.default.md)[]

#### Inherited from

Adapter.connections

#### Defined in

[src/lib/adapter.ts:204](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L204)

___

### glee

• `get` **glee**(): [`default`](lib_glee.default.md)

#### Returns

[`default`](lib_glee.default.md)

#### Inherited from

Adapter.glee

#### Defined in

[src/lib/adapter.ts:176](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L176)

___

### operationIds

• `get` **operationIds**(): `string`[]

#### Returns

`string`[]

#### Inherited from

Adapter.operationIds

#### Defined in

[src/lib/adapter.ts:196](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L196)

___

### parsedAsyncAPI

• `get` **parsedAsyncAPI**(): `AsyncAPIDocumentInterface`

#### Returns

`AsyncAPIDocumentInterface`

#### Inherited from

Adapter.parsedAsyncAPI

#### Defined in

[src/lib/adapter.ts:188](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L188)

___

### serverName

• `get` **serverName**(): `string`

#### Returns

`string`

#### Inherited from

Adapter.serverName

#### Defined in

[src/lib/adapter.ts:180](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L180)

___

### serverUrlExpanded

• `get` **serverUrlExpanded**(): `string`

#### Returns

`string`

#### Inherited from

Adapter.serverUrlExpanded

#### Defined in

[src/lib/adapter.ts:208](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L208)

## Methods

### \_connect

▸ `Private` **_connect**(): `Promise`<[`default`](adapters_ws_server.default.md)\>

#### Returns

`Promise`<[`default`](adapters_ws_server.default.md)\>

#### Defined in

[src/adapters/ws/server.ts:68](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L68)

___

### \_createMessage

▸ `Private` **_createMessage**(`eventName`, `payload`): [`default`](lib_message.default.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` |
| `payload` | `any` |

#### Returns

[`default`](lib_message.default.md)

#### Defined in

[src/adapters/ws/server.ts:282](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L282)

___

### \_createServers

▸ `Private` **_createServers**(): `void`

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:45](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L45)

___

### \_endRequest

▸ `Private` **_endRequest**(`code`, `message`, `socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `code` | `number` |
| `message` | `string` |
| `socket` | `Duplex` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:100](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L100)

___

### \_extractPathname

▸ `Private` **_extractPathname**(`req`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |

#### Returns

`string`

#### Defined in

[src/adapters/ws/server.ts:183](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L183)

___

### \_getChannel

▸ `Private` **_getChannel**(`req`): `ChannelInterface`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |

#### Returns

`ChannelInterface`

#### Defined in

[src/adapters/ws/server.ts:95](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L95)

___

### \_getPort

▸ `Private` **_getPort**(): `string` \| `number`

#### Returns

`string` \| `number`

#### Defined in

[src/adapters/ws/server.ts:90](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L90)

___

### \_handleBroadcastMessage

▸ `Private` **_handleBroadcastMessage**(`message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | [`default`](lib_message.default.md) |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:250](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L250)

___

### \_handleDirectMessage

▸ `Private` **_handleDirectMessage**(`message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | [`default`](lib_message.default.md) |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:269](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L269)

___

### \_handleInvalidChannel

▸ `Private` **_handleInvalidChannel**(`res`, `pathName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `res` | `Duplex` |
| `pathName` | `string` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:104](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L104)

___

### \_handleRequest

▸ `Private` **_handleRequest**(`request`, `socket`, `head`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | `IncomingMessage` |
| `socket` | `Duplex` |
| `head` | `Buffer` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:171](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L171)

___

### \_initializeServerEvents

▸ `Private` **_initializeServerEvents**(`«destructured»`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `«destructured»` | `Object` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:190](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L190)

___

### \_send

▸ `Private` **_send**(`message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | [`default`](lib_message.default.md) |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:274](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L274)

___

### \_validateDirectMessage

▸ `Private` **_validateDirectMessage**(`message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | [`default`](lib_message.default.md) |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:260](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L260)

___

### \_validateHeaders

▸ `Private` **_validateHeaders**(`req`, `socket`, `channelBindings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |
| `socket` | `Duplex` |
| `channelBindings` | `any` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:128](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L128)

___

### \_validateMethod

▸ `Private` **_validateMethod**(`req`, `socket`, `channelBindings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |
| `socket` | `Duplex` |
| `channelBindings` | `any` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:162](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L162)

___

### \_validatePort

▸ `Private` **_validatePort**(): `void`

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:207](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L207)

___

### \_validateQueries

▸ `Private` **_validateQueries**(`req`, `socket`, `channelBindings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |
| `socket` | `Duplex` |
| `channelBindings` | `any` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:146](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L146)

___

### \_validateRequest

▸ `Private` **_validateRequest**(`request`, `socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | `IncomingMessage` |
| `socket` | `Duplex` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:110](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L110)

___

### \_validateRequestAgainstBindings

▸ `Private` **_validateRequestAgainstBindings**(`req`, `socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `req` | `IncomingMessage` |
| `socket` | `Duplex` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:119](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L119)

___

### \_verifyClientFunc

▸ `Private` **_verifyClientFunc**(`gleeAuth`, `info`, `cb`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `gleeAuth` | `any` |
| `info` | `any` |
| `cb` | `any` |

#### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:229](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L229)

___

### \_wrapCallbackDecorator

▸ `Private` **_wrapCallbackDecorator**(`cb`): (`val`: `boolean`) => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | `any` |

#### Returns

`fn`

▸ (`val`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `boolean` |

##### Returns

`void`

#### Defined in

[src/adapters/ws/server.ts:219](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L219)

___

### addListener

▸ **addListener**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Alias for `emitter.on(eventName, listener)`.

**`Since`**

v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[addListener](lib_adapter.default.md#addlistener)

#### Defined in

node_modules/@types/node/events.d.ts:354

___

### connect

▸ **connect**(): `Promise`<[`default`](adapters_ws_server.default.md)\>

Connects to the remote server.

#### Returns

`Promise`<[`default`](adapters_ws_server.default.md)\>

#### Overrides

[default](lib_adapter.default.md).[connect](lib_adapter.default.md#connect)

#### Defined in

[src/adapters/ws/server.ts:35](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L35)

___

### emit

▸ **emit**(`eventName`, `...args`): `boolean`

Synchronously calls each of the listeners registered for the event named`eventName`, in the order they were registered, passing the supplied arguments
to each.

Returns `true` if the event had listeners, `false` otherwise.

```js
const EventEmitter = require('events');
const myEmitter = new EventEmitter();

// First listener
myEmitter.on('event', function firstListener() {
  console.log('Helloooo! first listener');
});
// Second listener
myEmitter.on('event', function secondListener(arg1, arg2) {
  console.log(`event with parameters ${arg1}, ${arg2} in second listener`);
});
// Third listener
myEmitter.on('event', function thirdListener(...args) {
  const parameters = args.join(', ');
  console.log(`event with parameters ${parameters} in third listener`);
});

console.log(myEmitter.listeners('event'));

myEmitter.emit('event', 1, 2, 3, 4, 5);

// Prints:
// [
//   [Function: firstListener],
//   [Function: secondListener],
//   [Function: thirdListener]
// ]
// Helloooo! first listener
// event with parameters 1, 2 in second listener
// event with parameters 1, 2, 3, 4, 5 in third listener
```

**`Since`**

v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Inherited from

[default](lib_adapter.default.md).[emit](lib_adapter.default.md#emit)

#### Defined in

node_modules/@types/node/events.d.ts:610

___

### eventNames

▸ **eventNames**(): (`string` \| `symbol`)[]

Returns an array listing the events for which the emitter has registered
listeners. The values in the array are strings or `Symbol`s.

```js
const EventEmitter = require('events');
const myEE = new EventEmitter();
myEE.on('foo', () => {});
myEE.on('bar', () => {});

const sym = Symbol('symbol');
myEE.on(sym, () => {});

console.log(myEE.eventNames());
// Prints: [ 'foo', 'bar', Symbol(symbol) ]
```

**`Since`**

v6.0.0

#### Returns

(`string` \| `symbol`)[]

#### Inherited from

[default](lib_adapter.default.md).[eventNames](lib_adapter.default.md#eventnames)

#### Defined in

node_modules/@types/node/events.d.ts:669

___

### getAuthConfig

▸ **getAuthConfig**(`auth`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `auth` | `any` |

#### Returns

`Promise`<`any`\>

#### Inherited from

[default](lib_adapter.default.md).[getAuthConfig](lib_adapter.default.md#getauthconfig)

#### Defined in

[src/lib/adapter.ts:221](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L221)

___

### getMaxListeners

▸ **getMaxListeners**(): `number`

Returns the current max listener value for the `EventEmitter` which is either
set by `emitter.setMaxListeners(n)` or defaults to [defaultMaxListeners](adapters_ws_server.default.md#defaultmaxlisteners).

**`Since`**

v1.0.0

#### Returns

`number`

#### Inherited from

[default](lib_adapter.default.md).[getMaxListeners](lib_adapter.default.md#getmaxlisteners)

#### Defined in

node_modules/@types/node/events.d.ts:526

___

### getSubscribedChannels

▸ **getSubscribedChannels**(): `string`[]

Returns a list of the channels a given adapter has to subscribe to.

#### Returns

`string`[]

#### Inherited from

[default](lib_adapter.default.md).[getSubscribedChannels](lib_adapter.default.md#getsubscribedchannels)

#### Defined in

[src/lib/adapter.ts:237](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L237)

___

### listenerCount

▸ **listenerCount**(`eventName`): `number`

Returns the number of listeners listening to the event named `eventName`.

**`Since`**

v3.2.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event being listened for |

#### Returns

`number`

#### Inherited from

[default](lib_adapter.default.md).[listenerCount](lib_adapter.default.md#listenercount)

#### Defined in

node_modules/@types/node/events.d.ts:616

___

### listeners

▸ **listeners**(`eventName`): `Function`[]

Returns a copy of the array of listeners for the event named `eventName`.

```js
server.on('connection', (stream) => {
  console.log('someone connected!');
});
console.log(util.inspect(server.listeners('connection')));
// Prints: [ [Function] ]
```

**`Since`**

v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |

#### Returns

`Function`[]

#### Inherited from

[default](lib_adapter.default.md).[listeners](lib_adapter.default.md#listeners)

#### Defined in

node_modules/@types/node/events.d.ts:539

___

### name

▸ **name**(): `string`

#### Returns

`string`

#### Defined in

[src/adapters/ws/server.ts:31](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L31)

___

### off

▸ **off**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Alias for `emitter.removeListener()`.

**`Since`**

v10.0.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[off](lib_adapter.default.md#off)

#### Defined in

node_modules/@types/node/events.d.ts:499

___

### on

▸ **on**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Adds the `listener` function to the end of the listeners array for the
event named `eventName`. No checks are made to see if the `listener` has
already been added. Multiple calls passing the same combination of `eventName`and `listener` will result in the `listener` being added, and called, multiple
times.

```js
server.on('connection', (stream) => {
  console.log('someone connected!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

By default, event listeners are invoked in the order they are added. The`emitter.prependListener()` method can be used as an alternative to add the
event listener to the beginning of the listeners array.

```js
const myEE = new EventEmitter();
myEE.on('foo', () => console.log('a'));
myEE.prependListener('foo', () => console.log('b'));
myEE.emit('foo');
// Prints:
//   b
//   a
```

**`Since`**

v0.1.101

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[on](lib_adapter.default.md#on)

#### Defined in

node_modules/@types/node/events.d.ts:385

___

### once

▸ **once**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Adds a **one-time**`listener` function for the event named `eventName`. The
next time `eventName` is triggered, this listener is removed and then invoked.

```js
server.once('connection', (stream) => {
  console.log('Ah, we have our first user!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

By default, event listeners are invoked in the order they are added. The`emitter.prependOnceListener()` method can be used as an alternative to add the
event listener to the beginning of the listeners array.

```js
const myEE = new EventEmitter();
myEE.once('foo', () => console.log('a'));
myEE.prependOnceListener('foo', () => console.log('b'));
myEE.emit('foo');
// Prints:
//   b
//   a
```

**`Since`**

v0.3.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[once](lib_adapter.default.md#once)

#### Defined in

node_modules/@types/node/events.d.ts:414

___

### prependListener

▸ **prependListener**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Adds the `listener` function to the _beginning_ of the listeners array for the
event named `eventName`. No checks are made to see if the `listener` has
already been added. Multiple calls passing the same combination of `eventName`and `listener` will result in the `listener` being added, and called, multiple
times.

```js
server.prependListener('connection', (stream) => {
  console.log('someone connected!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`Since`**

v6.0.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[prependListener](lib_adapter.default.md#prependlistener)

#### Defined in

node_modules/@types/node/events.d.ts:634

___

### prependOnceListener

▸ **prependOnceListener**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Adds a **one-time**`listener` function for the event named `eventName` to the _beginning_ of the listeners array. The next time `eventName` is triggered, this
listener is removed, and then invoked.

```js
server.prependOnceListener('connection', (stream) => {
  console.log('Ah, we have our first user!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`Since`**

v6.0.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[prependOnceListener](lib_adapter.default.md#prependoncelistener)

#### Defined in

node_modules/@types/node/events.d.ts:650

___

### rawListeners

▸ **rawListeners**(`eventName`): `Function`[]

Returns a copy of the array of listeners for the event named `eventName`,
including any wrappers (such as those created by `.once()`).

```js
const emitter = new EventEmitter();
emitter.once('log', () => console.log('log once'));

// Returns a new Array with a function `onceWrapper` which has a property
// `listener` which contains the original listener bound above
const listeners = emitter.rawListeners('log');
const logFnWrapper = listeners[0];

// Logs "log once" to the console and does not unbind the `once` event
logFnWrapper.listener();

// Logs "log once" to the console and removes the listener
logFnWrapper();

emitter.on('log', () => console.log('log persistently'));
// Will return a new Array with a single function bound by `.on()` above
const newListeners = emitter.rawListeners('log');

// Logs "log persistently" twice
newListeners[0]();
emitter.emit('log');
```

**`Since`**

v9.4.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |

#### Returns

`Function`[]

#### Inherited from

[default](lib_adapter.default.md).[rawListeners](lib_adapter.default.md#rawlisteners)

#### Defined in

node_modules/@types/node/events.d.ts:569

___

### removeAllListeners

▸ **removeAllListeners**(`event?`): [`default`](adapters_ws_server.default.md)

Removes all listeners, or those of the specified `eventName`.

It is bad practice to remove listeners added elsewhere in the code,
particularly when the `EventEmitter` instance was created by some other
component or module (e.g. sockets or file streams).

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`Since`**

v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `event?` | `string` \| `symbol` |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[removeAllListeners](lib_adapter.default.md#removealllisteners)

#### Defined in

node_modules/@types/node/events.d.ts:510

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): [`default`](adapters_ws_server.default.md)

Removes the specified `listener` from the listener array for the event named`eventName`.

```js
const callback = (stream) => {
  console.log('someone connected!');
};
server.on('connection', callback);
// ...
server.removeListener('connection', callback);
```

`removeListener()` will remove, at most, one instance of a listener from the
listener array. If any single listener has been added multiple times to the
listener array for the specified `eventName`, then `removeListener()` must be
called multiple times to remove each instance.

Once an event is emitted, all listeners attached to it at the
time of emitting are called in order. This implies that any`removeListener()` or `removeAllListeners()` calls _after_ emitting and _before_ the last listener finishes execution
will not remove them from`emit()` in progress. Subsequent events behave as expected.

```js
const myEmitter = new MyEmitter();

const callbackA = () => {
  console.log('A');
  myEmitter.removeListener('event', callbackB);
};

const callbackB = () => {
  console.log('B');
};

myEmitter.on('event', callbackA);

myEmitter.on('event', callbackB);

// callbackA removes listener callbackB but it will still be called.
// Internal listener array at time of emit [callbackA, callbackB]
myEmitter.emit('event');
// Prints:
//   A
//   B

// callbackB is now removed.
// Internal listener array [callbackA]
myEmitter.emit('event');
// Prints:
//   A
```

Because listeners are managed using an internal array, calling this will
change the position indices of any listener registered _after_ the listener
being removed. This will not impact the order in which listeners are called,
but it means that any copies of the listener array as returned by
the `emitter.listeners()` method will need to be recreated.

When a single function has been added as a handler multiple times for a single
event (as in the example below), `removeListener()` will remove the most
recently added instance. In the example the `once('ping')`listener is removed:

```js
const ee = new EventEmitter();

function pong() {
  console.log('pong');
}

ee.on('ping', pong);
ee.once('ping', pong);
ee.removeListener('ping', pong);

ee.emit('ping');
ee.emit('ping');
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`Since`**

v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[removeListener](lib_adapter.default.md#removelistener)

#### Defined in

node_modules/@types/node/events.d.ts:494

___

### resolveProtocolConfig

▸ **resolveProtocolConfig**(`protocol`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `protocol` | `string` |

#### Returns

`Promise`<`any`\>

#### Inherited from

[default](lib_adapter.default.md).[resolveProtocolConfig](lib_adapter.default.md#resolveprotocolconfig)

#### Defined in

[src/lib/adapter.ts:212](https://github.com/asyncapi/glee/blob/80679df/src/lib/adapter.ts#L212)

___

### send

▸ **send**(`message`): `Promise`<`void`\>

Sends a message to the remote server.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | [`default`](lib_message.default.md) | The message to send. |

#### Returns

`Promise`<`void`\>

#### Overrides

[default](lib_adapter.default.md).[send](lib_adapter.default.md#send)

#### Defined in

[src/adapters/ws/server.ts:241](https://github.com/asyncapi/glee/blob/80679df/src/adapters/ws/server.ts#L241)

___

### setMaxListeners

▸ **setMaxListeners**(`n`): [`default`](adapters_ws_server.default.md)

By default `EventEmitter`s will print a warning if more than `10` listeners are
added for a particular event. This is a useful default that helps finding
memory leaks. The `emitter.setMaxListeners()` method allows the limit to be
modified for this specific `EventEmitter` instance. The value can be set to`Infinity` (or `0`) to indicate an unlimited number of listeners.

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`Since`**

v0.3.5

#### Parameters

| Name | Type |
| :------ | :------ |
| `n` | `number` |

#### Returns

[`default`](adapters_ws_server.default.md)

#### Inherited from

[default](lib_adapter.default.md).[setMaxListeners](lib_adapter.default.md#setmaxlisteners)

#### Defined in

node_modules/@types/node/events.d.ts:520

___

### getEventListeners

▸ `Static` **getEventListeners**(`emitter`, `name`): `Function`[]

Returns a copy of the array of listeners for the event named `eventName`.

For `EventEmitter`s this behaves exactly the same as calling `.listeners` on
the emitter.

For `EventTarget`s this is the only way to get the event listeners for the
event target. This is useful for debugging and diagnostic purposes.

```js
const { getEventListeners, EventEmitter } = require('events');

{
  const ee = new EventEmitter();
  const listener = () => console.log('Events are fun');
  ee.on('foo', listener);
  getEventListeners(ee, 'foo'); // [listener]
}
{
  const et = new EventTarget();
  const listener = () => console.log('Events are fun');
  et.addEventListener('foo', listener);
  getEventListeners(et, 'foo'); // [listener]
}
```

**`Since`**

v15.2.0, v14.17.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `emitter` | `EventEmitter` \| `_DOMEventTarget` |
| `name` | `string` \| `symbol` |

#### Returns

`Function`[]

#### Inherited from

[default](lib_adapter.default.md).[getEventListeners](lib_adapter.default.md#geteventlisteners)

#### Defined in

node_modules/@types/node/events.d.ts:299

___

### listenerCount

▸ `Static` **listenerCount**(`emitter`, `eventName`): `number`

A class method that returns the number of listeners for the given `eventName`registered on the given `emitter`.

```js
const { EventEmitter, listenerCount } = require('events');
const myEmitter = new EventEmitter();
myEmitter.on('event', () => {});
myEmitter.on('event', () => {});
console.log(listenerCount(myEmitter, 'event'));
// Prints: 2
```

**`Since`**

v0.9.12

**`Deprecated`**

Since v3.2.0 - Use `listenerCount` instead.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `emitter` | `EventEmitter` | The emitter to query |
| `eventName` | `string` \| `symbol` | The event name |

#### Returns

`number`

#### Inherited from

[default](lib_adapter.default.md).[listenerCount](lib_adapter.default.md#listenercount-1)

#### Defined in

node_modules/@types/node/events.d.ts:271

___

### on

▸ `Static` **on**(`emitter`, `eventName`, `options?`): `AsyncIterableIterator`<`any`\>

```js
const { on, EventEmitter } = require('events');

(async () => {
  const ee = new EventEmitter();

  // Emit later on
  process.nextTick(() => {
    ee.emit('foo', 'bar');
    ee.emit('foo', 42);
  });

  for await (const event of on(ee, 'foo')) {
    // The execution of this inner block is synchronous and it
    // processes one event at a time (even with await). Do not use
    // if concurrent execution is required.
    console.log(event); // prints ['bar'] [42]
  }
  // Unreachable here
})();
```

Returns an `AsyncIterator` that iterates `eventName` events. It will throw
if the `EventEmitter` emits `'error'`. It removes all listeners when
exiting the loop. The `value` returned by each iteration is an array
composed of the emitted event arguments.

An `AbortSignal` can be used to cancel waiting on events:

```js
const { on, EventEmitter } = require('events');
const ac = new AbortController();

(async () => {
  const ee = new EventEmitter();

  // Emit later on
  process.nextTick(() => {
    ee.emit('foo', 'bar');
    ee.emit('foo', 42);
  });

  for await (const event of on(ee, 'foo', { signal: ac.signal })) {
    // The execution of this inner block is synchronous and it
    // processes one event at a time (even with await). Do not use
    // if concurrent execution is required.
    console.log(event); // prints ['bar'] [42]
  }
  // Unreachable here
})();

process.nextTick(() => ac.abort());
```

**`Since`**

v13.6.0, v12.16.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `emitter` | `EventEmitter` | - |
| `eventName` | `string` | The name of the event being listened for |
| `options?` | `StaticEventEmitterOptions` | - |

#### Returns

`AsyncIterableIterator`<`any`\>

that iterates `eventName` events emitted by the `emitter`

#### Inherited from

[default](lib_adapter.default.md).[on](lib_adapter.default.md#on-1)

#### Defined in

node_modules/@types/node/events.d.ts:254

___

### once

▸ `Static` **once**(`emitter`, `eventName`, `options?`): `Promise`<`any`[]\>

Creates a `Promise` that is fulfilled when the `EventEmitter` emits the given
event or that is rejected if the `EventEmitter` emits `'error'` while waiting.
The `Promise` will resolve with an array of all the arguments emitted to the
given event.

This method is intentionally generic and works with the web platform [EventTarget](https://dom.spec.whatwg.org/#interface-eventtarget) interface, which has no special`'error'` event
semantics and does not listen to the `'error'` event.

```js
const { once, EventEmitter } = require('events');

async function run() {
  const ee = new EventEmitter();

  process.nextTick(() => {
    ee.emit('myevent', 42);
  });

  const [value] = await once(ee, 'myevent');
  console.log(value);

  const err = new Error('kaboom');
  process.nextTick(() => {
    ee.emit('error', err);
  });

  try {
    await once(ee, 'myevent');
  } catch (err) {
    console.log('error happened', err);
  }
}

run();
```

The special handling of the `'error'` event is only used when `events.once()`is used to wait for another event. If `events.once()` is used to wait for the
'`error'` event itself, then it is treated as any other kind of event without
special handling:

```js
const { EventEmitter, once } = require('events');

const ee = new EventEmitter();

once(ee, 'error')
  .then(([err]) => console.log('ok', err.message))
  .catch((err) => console.log('error', err.message));

ee.emit('error', new Error('boom'));

// Prints: ok boom
```

An `AbortSignal` can be used to cancel waiting for the event:

```js
const { EventEmitter, once } = require('events');

const ee = new EventEmitter();
const ac = new AbortController();

async function foo(emitter, event, signal) {
  try {
    await once(emitter, event, { signal });
    console.log('event emitted!');
  } catch (error) {
    if (error.name === 'AbortError') {
      console.error('Waiting for the event was canceled!');
    } else {
      console.error('There was an error', error.message);
    }
  }
}

foo(ee, 'foo', ac.signal);
ac.abort(); // Abort waiting for the event
ee.emit('foo'); // Prints: Waiting for the event was canceled!
```

**`Since`**

v11.13.0, v10.16.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `emitter` | `_NodeEventTarget` |
| `eventName` | `string` \| `symbol` |
| `options?` | `StaticEventEmitterOptions` |

#### Returns

`Promise`<`any`[]\>

#### Inherited from

[default](lib_adapter.default.md).[once](lib_adapter.default.md#once-1)

#### Defined in

node_modules/@types/node/events.d.ts:194

▸ `Static` **once**(`emitter`, `eventName`, `options?`): `Promise`<`any`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `emitter` | `_DOMEventTarget` |
| `eventName` | `string` |
| `options?` | `StaticEventEmitterOptions` |

#### Returns

`Promise`<`any`[]\>

#### Inherited from

[default](lib_adapter.default.md).[once](lib_adapter.default.md#once-1)

#### Defined in

node_modules/@types/node/events.d.ts:195

___

### setMaxListeners

▸ `Static` **setMaxListeners**(`n?`, `...eventTargets`): `void`

```js
const {
  setMaxListeners,
  EventEmitter
} = require('events');

const target = new EventTarget();
const emitter = new EventEmitter();

setMaxListeners(5, target, emitter);
```

**`Since`**

v15.4.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `n?` | `number` | A non-negative number. The maximum number of listeners per `EventTarget` event. |
| `...eventTargets` | (`EventEmitter` \| `_DOMEventTarget`)[] | - |

#### Returns

`void`

#### Inherited from

[default](lib_adapter.default.md).[setMaxListeners](lib_adapter.default.md#setmaxlisteners-1)

#### Defined in

node_modules/@types/node/events.d.ts:317
