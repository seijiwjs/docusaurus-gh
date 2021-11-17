---
id: "Renderer_Drawing_GLGeomLibrary.GLGeomLibrary"
title: "Class: GLGeomLibrary"
sidebar_label: "GLGeomLibrary"
custom_edit_url: null
---



Class representing a GL geom.

## Hierarchy

- [`EventEmitter`](../../Utilities/Utilities_EventEmitter.EventEmitter)

  ↳ **`GLGeomLibrary`**

## Constructors

### constructor

• **new GLGeomLibrary**(`renderer`)

Create a GLGeomLibrary.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderer` | [`GLBaseRenderer`](../Renderer_GLBaseRenderer.GLBaseRenderer) | The renderer object |

#### Overrides

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[constructor](../../Utilities/Utilities_EventEmitter.EventEmitter#constructor)

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:45](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L45)

## Properties

### \_\_destroyed

• `Protected` **\_\_destroyed**: `boolean` = `false`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:40](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L40)

___

### \_\_gl

• `Protected` **\_\_gl**: `WebGL12RenderingContext`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:20](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L20)

___

### \_\_id

• `Protected` **\_\_id**: `number`

#### Inherited from

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[__id](../../Utilities/Utilities_EventEmitter.EventEmitter#__id)

#### Defined in

[Utilities/BaseClass.ts:11](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L11)

___

### attributesAllocator

• `Protected` **attributesAllocator**: [`Allocator1D`](../../Utilities/Utilities_Allocator1D.Allocator1D)

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:31](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L31)

___

### bufferNeedsRealloc

• `Protected` **bufferNeedsRealloc**: `boolean`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:30](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L30)

___

### dirtyGeomIndices

• `Protected` **dirtyGeomIndices**: `Set`<`number`\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:32](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L32)

___

### freeGeomIndices

• `Protected` **freeGeomIndices**: `number`[]

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:22](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L22)

___

### geomBuffersTmp

• `Protected` **geomBuffersTmp**: `any`[]

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:27](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L27)

___

### geomRefCounts

• `Protected` **geomRefCounts**: `number`[]

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:24](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L24)

___

### geomVertexCounts

• `Protected` **geomVertexCounts**: `Int32Array`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:34](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L34)

___

### geomVertexOffsets

• `Protected` **geomVertexOffsets**: `Int32Array`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:33](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L33)

___

### geoms

• `Protected` **geoms**: [`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom)[]

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:23](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L23)

___

### geomsDict

• `Protected` **geomsDict**: `Record`<`string`, `number`\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:25](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L25)

___

### glGeomsDict

• `Protected` **glGeomsDict**: `Record`<`string`, [`GLGeom`](Renderer_Drawing_GLGeom.GLGeom)\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:26](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L26)

___

### glattrbuffers

• `Protected` **glattrbuffers**: `Record`<`string`, `any`\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:28](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L28)

___

### indexBuffer

• `Protected` **indexBuffer**: `WebGLBuffer` = `null`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:39](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L39)

___

### indicesAllocator

• `Protected` **indicesAllocator**: [`Allocator1D`](../../Utilities/Utilities_Allocator1D.Allocator1D)

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:36](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L36)

___

### indicesCounts

• `Protected` **indicesCounts**: `Int32Array`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:37](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L37)

___

### indicesOffsets

• `Protected` **indicesOffsets**: `Int32Array`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:38](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L38)

___

### listeners

• **listeners**: `Record`<`string`, (`event`: [`BaseEvent`](../../Utilities/Utilities_BaseEvent.BaseEvent)) => `void`[]\> = `{}`

#### Inherited from

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[listeners](../../Utilities/Utilities_EventEmitter.EventEmitter#listeners)

#### Defined in

[Utilities/EventEmitter.ts:26](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L26)

___

### numIndices

• `Protected` **numIndices**: `number`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:35](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L35)

___

### renderer

• `Protected` **renderer**: [`GLBaseRenderer`](../Renderer_GLBaseRenderer.GLBaseRenderer)

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:19](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L19)

___

### shaderAttrSpec

• `Protected` **shaderAttrSpec**: `Record`<`string`, `any`\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:21](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L21)

___

### shaderBindings

• `Protected` **shaderBindings**: `Record`<`string`, `any`\>

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:29](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L29)

## Methods

### addGeom

▸ **addGeom**(`geom`): `number`

Adds a geom to the GLGeomLibrary.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `geom` | [`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom) | The geom to be managed by this GLGeomLibrary. |

#### Returns

`number`

- The index of the geom in the GLGeomLibrary

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:137](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L137)

___

### allocateBuffers

▸ **allocateBuffers**(`index`): `void`

Allocates space for the geomBuffers for the specified geometry

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index of the geom to upload |

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:244](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L244)

___

### bind

▸ **bind**(`renderstate`): `boolean`

The bind method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderstate` | `RenderState` | The renderstate value. |

#### Returns

`boolean`

- Returns true if binding was successful

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:485](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L485)

___

### cleanGeomBuffers

▸ **cleanGeomBuffers**(): `void`

Cleans the state of this GeomSet during rendering.

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:440](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L440)

___

### clearBuffers

▸ **clearBuffers**(): `void`

The clearBuffers method.

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:520](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L520)

___

### constructGLGeom

▸ **constructGLGeom**(`geom`): [`GLGeom`](Renderer_Drawing_GLGeom.GLGeom)

Given a BaseGeom, constructs the GLGeom that manages the state of the geometry in the GPU.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `geom` | [`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom) | The geom value. |

#### Returns

[`GLGeom`](Renderer_Drawing_GLGeom.GLGeom)

- The return value.

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:106](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L106)

___

### destroy

▸ **destroy**(): `void`

The destroy is called by the system to cause explicit resources cleanup.
Users should never need to call this method directly.

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:547](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L547)

___

### emit

▸ **emit**(`eventName`, `event?`): `void`

Triggers all listener functions in an event.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` | The name of the event. |
| `event` | [`BaseEvent`](../../Utilities/Utilities_BaseEvent.BaseEvent) | The data you want to pass down to all listener functions as parameter. |

#### Returns

`void`

#### Inherited from

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[emit](../../Utilities/Utilities_EventEmitter.EventEmitter#emit)

#### Defined in

[Utilities/EventEmitter.ts:154](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L154)

___

### genBuffers

▸ **genBuffers**(): `void`

Generates the GPU buffers required to store all the geometries

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:308](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L308)

___

### getClassName

▸ **getClassName**(): `string`

Returns the unmangled name of the class.

#### Returns

`string`

- The name of the class definition.

#### Inherited from

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[getClassName](../../Utilities/Utilities_EventEmitter.EventEmitter#getclassname)

#### Defined in

[Utilities/BaseClass.ts:33](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L33)

___

### getGeom

▸ **getGeom**(`index`): [`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom)

Returns a Geom managed by this GLGeomLibrary.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index of the geom to retrieve |

#### Returns

[`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom)

- The return value.

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:224](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L224)

___

### getGeomOffsetAndCount

▸ **getGeomOffsetAndCount**(`index`): `number`[]

Returns a Geom managed by this GLGeomLibrary.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index of the geom to retrieve |

#### Returns

`number`[]

- The return value.

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:233](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L233)

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

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[getId](../../Utilities/Utilities_EventEmitter.EventEmitter#getid)

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

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[off](../../Utilities/Utilities_EventEmitter.EventEmitter#off)

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

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[on](../../Utilities/Utilities_EventEmitter.EventEmitter#on)

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
| `listener` | (`event`: [`BaseEvent`](../../Utilities/Utilities_BaseEvent.BaseEvent)) => `void` | The listener value |

#### Returns

`number`

- the id that can be used to remove the listener.

#### Inherited from

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[once](../../Utilities/Utilities_EventEmitter.EventEmitter#once)

#### Defined in

[Utilities/EventEmitter.ts:82](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L82)

___

### removeGeom

▸ **removeGeom**(`geom`): `void`

Removes a Geom managed by this GLGeomLibrary.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `geom` | [`BaseGeom`](../../SceneTree/Geometry/SceneTree_Geometry_BaseGeom.BaseGeom) | The geom to remove |

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:185](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L185)

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

[EventEmitter](../../Utilities/Utilities_EventEmitter.EventEmitter).[removeListenerById](../../Utilities/Utilities_EventEmitter.EventEmitter#removelistenerbyid)

#### Defined in

[Utilities/EventEmitter.ts:134](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L134)

___

### unbind

▸ **unbind**(`renderstate`): `void`

The unbind method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `renderstate` | `RenderState` | The object tracking the current state of the renderer |

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:505](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L505)

___

### uploadBuffers

▸ **uploadBuffers**(`index`): `void`

The uploadBuffers method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index of the geom to upload |

#### Returns

`void`

#### Defined in

[Renderer/Drawing/GLGeomLibrary.ts:365](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Renderer/Drawing/GLGeomLibrary.ts#L365)

