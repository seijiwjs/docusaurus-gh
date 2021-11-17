---
id: "Renderer_GLRenderTarget.GLRenderTarget"
title: "Class: GLRenderTarget"
sidebar_label: "GLRenderTarget"
custom_edit_url: null
---



Class representing a GL render target.

## Hierarchy

- [`EventEmitter`](../Utilities/Utilities_EventEmitter.EventEmitter)

  ↳ **`GLRenderTarget`**

  ↳↳ [`GLImageAtlas`](Renderer_GLImageAtlas.GLImageAtlas)

## Constructors

### constructor

• **new GLRenderTarget**(`gl`, `params?`)

Create a GL render target.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `gl` | `WebGL12RenderingContext` | The webgl rendering context. |
| `params?` | `Record`<`string`, `any`\> | The params value. |

#### Overrides

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[constructor](../Utilities/Utilities_EventEmitter.EventEmitter#constructor)

#### Defined in

[Renderer/GLRenderTarget.ts:32](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L32)

## Properties

### \_\_gl

• `Protected` **\_\_gl**: `WebGL12RenderingContext`

#### Defined in

[Renderer/GLRenderTarget.ts:7](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L7)

___

### \_\_id

• `Protected` **\_\_id**: `number`

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[__id](../Utilities/Utilities_EventEmitter.EventEmitter#__id)

#### Defined in

[Utilities/BaseClass.ts:11](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L11)

___

### \_\_prevBoundFbo

• `Protected` **\_\_prevBoundFbo**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:26](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L26)

___

### clearColor

• **clearColor**: [`Color`](../Math/Math_Color.Color)

#### Defined in

[Renderer/GLRenderTarget.ts:22](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L22)

___

### colorMask

• `Protected` **colorMask**: `boolean`[]

#### Defined in

[Renderer/GLRenderTarget.ts:23](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L23)

___

### depthTexture

• `Protected` **depthTexture**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:9](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L9)

___

### filter

• `Protected` **filter**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:17](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L17)

___

### flipY

• `Protected` **flipY**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:19](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L19)

___

### format

• `Protected` **format**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:15](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L15)

___

### frameBuffer

• `Protected` **frameBuffer**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:11](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L11)

___

### height

• `Protected` **height**: `number` = `0`

#### Defined in

[Renderer/GLRenderTarget.ts:21](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L21)

___

### internalFormat

• `Protected` **internalFormat**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:16](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L16)

___

### listeners

• **listeners**: `Record`<`string`, (`event`: [`BaseEvent`](../Utilities/Utilities_BaseEvent.BaseEvent)) => `void`[]\> = `{}`

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[listeners](../Utilities/Utilities_EventEmitter.EventEmitter#listeners)

#### Defined in

[Utilities/EventEmitter.ts:26](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L26)

___

### params

• `Protected` **params**: `Record`<`string`, `any`\> = `{}`

#### Defined in

[Renderer/GLRenderTarget.ts:13](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L13)

___

### textureDesc

• `Protected` **textureDesc**: `number`[]

#### Defined in

[Renderer/GLRenderTarget.ts:10](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L10)

___

### textureTargets

• `Protected` **textureTargets**: `any`[]

#### Defined in

[Renderer/GLRenderTarget.ts:8](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L8)

___

### textureType

• `Protected` **textureType**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:24](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L24)

___

### type

• `Protected` **type**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:14](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L14)

___

### width

• `Protected` **width**: `number` = `0`

#### Defined in

[Renderer/GLRenderTarget.ts:20](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L20)

___

### wrap

• `Protected` **wrap**: `any`

#### Defined in

[Renderer/GLRenderTarget.ts:18](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L18)

## Methods

### bindColorTexture

▸ **bindColorTexture**(`renderstate`, `unif`, `channelId?`): `boolean`

The bindColorTexture method.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `renderstate` | `RenderState` | `undefined` | The object tracking the current state of the renderer |
| `unif` | `Uniform` | `undefined` | - |
| `channelId` | `number` | `0` | The channelId value. |

#### Returns

`boolean`

- The return value.

#### Defined in

[Renderer/GLRenderTarget.ts:249](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L249)

___

### bindDepthTexture

▸ **bindDepthTexture**(`renderstate`, `unif`): `boolean`

The bindDepthTexture method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderstate` | `RenderState` | The object tracking the current state of the renderer |
| `unif` | `Uniform` | The WebGL uniform |

#### Returns

`boolean`

- The return value.

#### Defined in

[Renderer/GLRenderTarget.ts:264](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L264)

___

### bindForReading

▸ **bindForReading**(): `void`

Binds the render target in preparation for 'readPixels' calls to pull data back to main memory.

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:228](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L228)

___

### bindForWriting

▸ **bindForWriting**(`renderstate?`, `clear?`): `void`

The bindForWriting method.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `renderstate?` | `RenderState` | `undefined` | The object tracking the current state of the renderer |
| `clear` | `boolean` | `false` | The clear value. |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:186](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L186)

___

### bindToUniform

▸ **bindToUniform**(`renderstate`, `unif`, `bindings?`): `boolean`

The bindToUniform method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderstate` | `RenderState` | The renderstate param. |
| `unif` | `Uniform` | The WebGL uniform |
| `bindings?` | `any` | The bindings param. |

#### Returns

`boolean`

- The return value.

#### Defined in

[Renderer/GLRenderTarget.ts:425](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L425)

___

### checkFramebuffer

▸ **checkFramebuffer**(): `void`

The checkFramebuffer method.

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:152](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L152)

___

### clear

▸ **clear**(`clearDepth?`): `void`

The clear method.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `clearDepth` | `boolean` | `true` | The clearDepth value. |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:213](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L213)

___

### configure

▸ **configure**(`params`): `void`

The configure method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `Record`<`string`, `any`\> | The params param. |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:50](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L50)

___

### destroy

▸ **destroy**(): `void`

The destroy is called by the system to cause explicit resources cleanup.
Users should never need to call this method directly.

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:457](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L457)

___

### emit

▸ **emit**(`eventName`, `event?`): `void`

Triggers all listener functions in an event.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The name of the event. |
| `event` | [`BaseEvent`](../Utilities/Utilities_BaseEvent.BaseEvent) | The data you want to pass down to all listener functions as parameter. |

#### Returns

`void`

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[emit](../Utilities/Utilities_EventEmitter.EventEmitter#emit)

#### Defined in

[Utilities/EventEmitter.ts:154](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L154)

___

### getClassName

▸ **getClassName**(): `string`

Returns the unmangled name of the class.

#### Returns

`string`

- The name of the class definition.

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[getClassName](../Utilities/Utilities_EventEmitter.EventEmitter#getclassname)

#### Defined in

[Utilities/BaseClass.ts:33](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L33)

___

### getId

▸ **getId**(): `number`

Every instance of each class based on BaseClass is assigned a unique number.
This number is not persistent in between different loads of a scene.
Returns the unique id of the object.

#### Returns

`number`

- The Id of the object.

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[getId](../Utilities/Utilities_EventEmitter.EventEmitter#getid)

#### Defined in

[Utilities/BaseClass.ts:25](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L25)

___

### off

▸ **off**(`eventName`, `listener?`): `void`

Removes a listener function from the specified event, using either the function or the index id. Depends on what is passed in.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The name of the event. |
| `listener?` | (`event`: `any`) => `void` | The listener function or the id number. |

#### Returns

`void`

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[off](../Utilities/Utilities_EventEmitter.EventEmitter#off)

#### Defined in

[Utilities/EventEmitter.ts:97](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L97)

___

### on

▸ **on**(`eventName`, `listener?`): `number`

Adds a listener function for a given event name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The name of the event. |
| `listener?` | (`event`: `any`) => `void` | The listener function(callback). |

#### Returns

`number`

- the id that can be used to remove the listener.

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[on](../Utilities/Utilities_EventEmitter.EventEmitter#on)

#### Defined in

[Utilities/EventEmitter.ts:44](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L44)

___

### once

▸ **once**(`eventName`, `listener`): `number`

Similar to the `on` method with the difference that when the event is triggered,
it is automatically unregistered meaning that the event listener will be triggered at most one time.

Useful for events that we expect to trigger one time, such as when assets load.
```javascript
const asset = new Asset();
asset.once('loaded', () => {
  console.log("Yay! the asset is loaded")
})
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The eventName value |
| `listener` | (`event`: [`BaseEvent`](../Utilities/Utilities_BaseEvent.BaseEvent)) => `void` | The listener value |

#### Returns

`number`

- the id that can be used to remove the listener.

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[once](../Utilities/Utilities_EventEmitter.EventEmitter#once)

#### Defined in

[Utilities/EventEmitter.ts:82](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L82)

___

### removeListenerById

▸ **removeListenerById**(`eventName`, `id`): `void`

remove listener by ID returned from #on

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The name of the event. |
| `id` | `number` | The id returned by addListener |

#### Returns

`void`

#### Inherited from

[EventEmitter](../Utilities/Utilities_EventEmitter.EventEmitter).[removeListenerById](../Utilities/Utilities_EventEmitter.EventEmitter#removelistenerbyid)

#### Defined in

[Utilities/EventEmitter.ts:134](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L134)

___

### resize

▸ **resize**(`width`, `height`, `preserveData?`): `void`

The resize method.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `width` | `number` | `undefined` | The width value. |
| `height` | `number` | `undefined` | The height value. |
| `preserveData` | `boolean` | `false` | The preserveData value. |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:286](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L286)

___

### unbind

▸ **unbind**(`renderstate?`): `void`

The unbind method.

#### Parameters

| Name | Type |
| :------ | :------ |
| `renderstate?` | `RenderState` |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:276](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L276)

___

### unbindForReading

▸ **unbindForReading**(): `void`

The unbindForReading method.

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:237](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L237)

___

### unbindForWriting

▸ **unbindForWriting**(`renderstate?`): `void`

The unbindForWriting method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderstate?` | `RenderState` | The object tracking the current state of the renderer |

#### Returns

`void`

#### Defined in

[Renderer/GLRenderTarget.ts:202](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/GLRenderTarget.ts#L202)

