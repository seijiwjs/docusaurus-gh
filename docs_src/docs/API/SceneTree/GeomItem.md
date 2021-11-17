---
id: "SceneTree_GeomItem.GeomItem"
title: "Class: GeomItem"
sidebar_label: "GeomItem"
custom_edit_url: null
---



Class representing a geometry item in a scene tree.

**Parameters**
* **Geometry(`GeometryParameter`):** The geometry to be rendered for this GeomItem
* **Material(`MaterialParameter`):** The Material to use when rendering this GeomItem
* **GeomOffsetXfo(`XfoParameter`):** Provides an offset transformation that is applied only to the geometry and not inherited by child items.
* **GeomMat(`Mat4Parameter`):** Calculated from the GlobalXfo and the GeomOffsetXfo, this matrix is provided to the renderer for rendering.

## Hierarchy

- [`BaseGeomItem`](SceneTree_BaseGeomItem.BaseGeomItem)

  ↳ **`GeomItem`**

## Constructors

### constructor

• **new GeomItem**(`name?`, `geometry?`, `material?`, `xfo?`)

Creates a geometry item.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name?` | `string` | The name of the geom item. |
| `geometry?` | [`BaseGeom`](Geometry/SceneTree_Geometry_BaseGeom.BaseGeom) | The geometry value. |
| `material?` | [`Material`](SceneTree_Material.Material) | The material value. |
| `xfo?` | [`Xfo`](../Math/Math_Xfo.Xfo) | The initial Xfo of the new GeomItem. |

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[constructor](SceneTree_BaseGeomItem.BaseGeomItem#constructor)

#### Defined in

[SceneTree/GeomItem.ts:97](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L97)

## Properties

### \_\_childItems

• `Protected` **\_\_childItems**: [`TreeItem`](SceneTree_TreeItem.TreeItem)[] = `[]`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__childItems](SceneTree_BaseGeomItem.BaseGeomItem#__childitems)

#### Defined in

[SceneTree/TreeItem.ts:49](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L49)

___

### \_\_childItemsEventHandlers

• `Protected` **\_\_childItemsEventHandlers**: `Record`<`string`, `number`\>[] = `[]`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__childItemsEventHandlers](SceneTree_BaseGeomItem.BaseGeomItem#__childitemseventhandlers)

#### Defined in

[SceneTree/TreeItem.ts:50](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L50)

___

### \_\_childItemsMapping

• `Protected` **\_\_childItemsMapping**: `Record`<`string`, `number`\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__childItemsMapping](SceneTree_BaseGeomItem.BaseGeomItem#__childitemsmapping)

#### Defined in

[SceneTree/TreeItem.ts:51](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L51)

___

### \_\_cutAway

• `Protected` **\_\_cutAway**: `boolean`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__cutAway](SceneTree_BaseGeomItem.BaseGeomItem#__cutaway)

#### Defined in

[SceneTree/BaseGeomItem.ts:17](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L17)

___

### \_\_cutAwayDist

• `Protected` **\_\_cutAwayDist**: `number`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__cutAwayDist](SceneTree_BaseGeomItem.BaseGeomItem#__cutawaydist)

#### Defined in

[SceneTree/BaseGeomItem.ts:19](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L19)

___

### \_\_cutAwayVector

• `Protected` **\_\_cutAwayVector**: [`Vec3`](../Math/Math_Vec3.Vec3)

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__cutAwayVector](SceneTree_BaseGeomItem.BaseGeomItem#__cutawayvector)

#### Defined in

[SceneTree/BaseGeomItem.ts:18](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L18)

___

### \_\_highlightMapping

• `Protected` **\_\_highlightMapping**: `Record`<`string`, [`Color`](../Math/Math_Color.Color)\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__highlightMapping](SceneTree_BaseGeomItem.BaseGeomItem#__highlightmapping)

#### Defined in

[SceneTree/TreeItem.ts:76](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L76)

___

### \_\_highlights

• `Protected` **\_\_highlights**: `string`[] = `[]`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__highlights](SceneTree_BaseGeomItem.BaseGeomItem#__highlights)

#### Defined in

[SceneTree/TreeItem.ts:77](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L77)

___

### \_\_id

• `Protected` **\_\_id**: `number`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__id](SceneTree_BaseGeomItem.BaseGeomItem#__id)

#### Defined in

[Utilities/BaseClass.ts:11](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L11)

___

### \_\_layers

• `Protected` **\_\_layers**: `string`[]

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__layers](SceneTree_BaseGeomItem.BaseGeomItem#__layers)

#### Defined in

[SceneTree/BaseGeomItem.ts:20](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L20)

___

### \_\_metaData

• `Protected` **\_\_metaData**: `Record`<`string`, `any`\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__metaData](SceneTree_BaseGeomItem.BaseGeomItem#__metadata)

#### Defined in

[SceneTree/BaseItem.ts:39](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L39)

___

### \_\_name

• `Protected` **\_\_name**: `string`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__name](SceneTree_BaseGeomItem.BaseGeomItem#__name)

#### Defined in

[SceneTree/BaseItem.ts:34](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L34)

___

### \_\_ownerItem

• `Protected` **\_\_ownerItem**: [`Owner`](SceneTree_Owner.Owner) = `undefined`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__ownerItem](SceneTree_BaseGeomItem.BaseGeomItem#__owneritem)

#### Defined in

[SceneTree/BaseItem.ts:35](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L35)

___

### \_\_path

• `Protected` **\_\_path**: `string`[]

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__path](SceneTree_BaseGeomItem.BaseGeomItem#__path)

#### Defined in

[SceneTree/BaseItem.ts:36](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L36)

___

### \_\_selectable

• `Protected` **\_\_selectable**: `boolean` = `true`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__selectable](SceneTree_BaseGeomItem.BaseGeomItem#__selectable)

#### Defined in

[SceneTree/BaseItem.ts:37](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L37)

___

### \_\_selected

• `Protected` **\_\_selected**: `boolean` = `false`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__selected](SceneTree_BaseGeomItem.BaseGeomItem#__selected)

#### Defined in

[SceneTree/BaseItem.ts:38](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L38)

___

### \_\_visible

• `Protected` **\_\_visible**: `boolean` = `true`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__visible](SceneTree_BaseGeomItem.BaseGeomItem#__visible)

#### Defined in

[SceneTree/TreeItem.ts:79](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L79)

___

### \_\_visibleCounter

• `Protected` **\_\_visibleCounter**: `number` = `1`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[__visibleCounter](SceneTree_BaseGeomItem.BaseGeomItem#__visiblecounter)

#### Defined in

[SceneTree/TreeItem.ts:80](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L80)

___

### assetItem

• `Protected` **assetItem**: [`AssetItem`](SceneTree_AssetItem.AssetItem) = `null`

#### Defined in

[SceneTree/GeomItem.ts:71](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L71)

___

### boundingBoxParam

• **boundingBoxParam**: [`BoundingBoxParameter`](Parameters/SceneTree_Parameters_BoundingBoxParameter.BoundingBoxParameter)

**`member`** boundingBoxParam - Stores the bounding box for this tree item

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[boundingBoxParam](SceneTree_BaseGeomItem.BaseGeomItem#boundingboxparam)

#### Defined in

[SceneTree/TreeItem.ts:68](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L68)

___

### calcGeomMatOperator

• `Protected` **calcGeomMatOperator**: [`Operator`](Operators/SceneTree_Operators_Operator.Operator)

#### Defined in

[SceneTree/GeomItem.ts:72](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L72)

___

### cullable

• **cullable**: `boolean` = `true`

#### Defined in

[SceneTree/GeomItem.ts:73](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L73)

___

### deprecatedParamMapping

• **deprecatedParamMapping**: `Record`<`string`, `any`\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[deprecatedParamMapping](SceneTree_BaseGeomItem.BaseGeomItem#deprecatedparammapping)

#### Defined in

[SceneTree/ParameterOwner.ts:23](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L23)

___

### disableBoundingBox

• **disableBoundingBox**: `boolean` = `false`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[disableBoundingBox](SceneTree_BaseGeomItem.BaseGeomItem#disableboundingbox)

#### Defined in

[SceneTree/TreeItem.ts:47](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L47)

___

### geomBBox

• `Protected` `Optional` **geomBBox**: [`Box3`](../Math/Math_Box3.Box3)

#### Defined in

[SceneTree/GeomItem.ts:69](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L69)

___

### geomIndex

• `Protected` **geomIndex**: `number` = `-1`

#### Defined in

[SceneTree/GeomItem.ts:70](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L70)

___

### geomMatParam

• **geomMatParam**: [`Mat4Parameter`](Parameters/SceneTree_Parameters_Mat4Parameter.Mat4Parameter)

**`member`** geomMatParam - Calculated from the GlobalXfo and the GeomOffsetXfo, this matrix is provided to the renderer for rendering.

#### Defined in

[SceneTree/GeomItem.ts:88](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L88)

___

### geomOffsetXfoParam

• **geomOffsetXfoParam**: [`XfoParameter`](Parameters/SceneTree_Parameters_XfoParameter.XfoParameter)

**`member`** geomOffsetXfoParam - Provides an offset transformation that is applied only to the geometry and not inherited by child items.

#### Defined in

[SceneTree/GeomItem.ts:78](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L78)

___

### geomParam

• **geomParam**: [`GeometryParameter`](Parameters/SceneTree_Parameters_GeometryParameter.GeometryParameter)

**`member`** geomParam - The geometry to be rendered for this GeomItem

#### Defined in

[SceneTree/GeomItem.ts:83](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L83)

___

### globalXfoOp

• `Protected` **globalXfoOp**: [`Operator`](Operators/SceneTree_Operators_Operator.Operator)

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[globalXfoOp](SceneTree_BaseGeomItem.BaseGeomItem#globalxfoop)

#### Defined in

[SceneTree/TreeItem.ts:82](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L82)

___

### globalXfoParam

• **globalXfoParam**: [`XfoParameter`](Parameters/SceneTree_Parameters_XfoParameter.XfoParameter)

**`member`** globalXfoParam - Stores the global Xfo for this tree item.
global xfos are calculated from the localXfo and parentXfo.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[globalXfoParam](SceneTree_BaseGeomItem.BaseGeomItem#globalxfoparam)

#### Defined in

[SceneTree/TreeItem.ts:57](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L57)

___

### listenerIDs

• `Protected` **listenerIDs**: `Record`<`string`, `number`\> = `{}`

#### Defined in

[SceneTree/GeomItem.ts:68](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L68)

___

### listeners

• **listeners**: `Record`<`string`, (`event`: [`BaseEvent`](../Utilities/Utilities_BaseEvent.BaseEvent)) => `void`[]\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[listeners](SceneTree_BaseGeomItem.BaseGeomItem#listeners)

#### Defined in

[Utilities/EventEmitter.ts:26](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L26)

___

### localXfoParam

• **localXfoParam**: [`XfoParameter`](Parameters/SceneTree_Parameters_XfoParameter.XfoParameter)

**`member`** localXfoParam - Stores the local Xfo for this tree item.
local Xfos are the offset from the parent's coordinate frame.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[localXfoParam](SceneTree_BaseGeomItem.BaseGeomItem#localxfoparam)

#### Defined in

[SceneTree/TreeItem.ts:63](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L63)

___

### materialParam

• **materialParam**: [`MaterialParameter`](Parameters/SceneTree_Parameters_MaterialParameter.MaterialParameter)

**`member`** materialParam - The Material to use when rendering this GeomItem

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[materialParam](SceneTree_BaseGeomItem.BaseGeomItem#materialparam)

#### Defined in

[SceneTree/BaseGeomItem.ts:25](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L25)

___

### overlay

• `Protected` **overlay**: `boolean`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[overlay](SceneTree_BaseGeomItem.BaseGeomItem#overlay)

#### Defined in

[SceneTree/BaseGeomItem.ts:16](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L16)

___

### paramEventListenerIDs

• `Protected` **paramEventListenerIDs**: `Record`<`string`, `number`\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[paramEventListenerIDs](SceneTree_BaseGeomItem.BaseGeomItem#parameventlistenerids)

#### Defined in

[SceneTree/ParameterOwner.ts:20](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L20)

___

### paramMapping

• `Protected` **paramMapping**: `Record`<`string`, `number`\> = `{}`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[paramMapping](SceneTree_BaseGeomItem.BaseGeomItem#parammapping)

#### Defined in

[SceneTree/ParameterOwner.ts:21](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L21)

___

### params

• **params**: [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>[] = `[]`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[params](SceneTree_BaseGeomItem.BaseGeomItem#params)

#### Defined in

[SceneTree/ParameterOwner.ts:22](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L22)

___

### visibleParam

• **visibleParam**: [`BooleanParameter`](Parameters/SceneTree_Parameters_BooleanParameter.BooleanParameter)

**`member`** visibleParam - Whether this tree item is visible or not.
Any given tree item is also is affected by parent's visibility.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[visibleParam](SceneTree_BaseGeomItem.BaseGeomItem#visibleparam)

#### Defined in

[SceneTree/TreeItem.ts:74](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L74)

## Methods

### \_cleanBoundingBox

▸ `Private` **_cleanBoundingBox**(`bbox`): [`Box3`](../Math/Math_Box3.Box3)

The _cleanBoundingBox method.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `bbox` | [`Box3`](../Math/Math_Box3.Box3) | The bounding box value. |

#### Returns

[`Box3`](../Math/Math_Box3.Box3)

- The return value.

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[_cleanBoundingBox](SceneTree_BaseGeomItem.BaseGeomItem#_cleanboundingbox)

#### Defined in

[SceneTree/GeomItem.ts:123](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L123)

___

### addChild

▸ **addChild**(`childItem`, `maintainXfo?`, `fixCollisions?`): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Adds a child.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `childItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | `undefined` | The child TreeItem to add. |
| `maintainXfo` | `boolean` | `true` | Boolean that determines if the Global Xfo value is maintained. If true, when moving items in the hierarchy from one parent to another, the local Xfo of the item will be modified to maintain and the Global Xfo. Note: this option defaults to false because we expect that is the behavior users would expect when manipulating the tree in code. To be safe and unambiguous, always try to specify this value. |
| `fixCollisions` | `boolean` | `true` | Modify the name of the item to avoid name collisions with other children of the same parent. If false, an exception wll be thrown instead if a name collision occurs. |

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

childItem - The child TreeItem that was added.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[addChild](SceneTree_BaseGeomItem.BaseGeomItem#addchild)

#### Defined in

[SceneTree/TreeItem.ts:535](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L535)

___

### addHighlight

▸ **addHighlight**(`name`, `color`, `propagateToChildren?`): `void`

Adds a highlight to the tree item.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `name` | `string` | `undefined` | The name of the tree item. |
| `color` | [`Color`](../Math/Math_Color.Color) | `undefined` | The color of the highlight. |
| `propagateToChildren` | `boolean` | `false` | A boolean indicating whether to propagate to children. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[addHighlight](SceneTree_BaseGeomItem.BaseGeomItem#addhighlight)

#### Defined in

[SceneTree/TreeItem.ts:243](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L243)

___

### addLayer

▸ **addLayer**(`name`): `void`

Adds a layer to current item.

**`todo`** Need to find the layer and add this item to it.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name of the layer. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[addLayer](SceneTree_BaseGeomItem.BaseGeomItem#addlayer)

#### Defined in

[SceneTree/BaseGeomItem.ts:66](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L66)

___

### addParameter

▸ **addParameter**(`param`): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

Adds `Parameter` object to the owner's parameter list.

**`emits`** `parameterAdded` with the name of the param.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param` | [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\> | The parameter to add. |

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- With `owner` and `valueChanged` event set.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[addParameter](SceneTree_BaseGeomItem.BaseGeomItem#addparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:133](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L133)

___

### addParameterDeprecationMapping

▸ **addParameterDeprecationMapping**(`key`, `paramName`): `void`

Add a mapping from one name to a new parameter.
This is used to handle migrating parameters to new names.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The parameter name. |
| `paramName` | `string` | The parameter name. |

#### Returns

`void`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[addParameterDeprecationMapping](SceneTree_BaseGeomItem.BaseGeomItem#addparameterdeprecationmapping)

#### Defined in

[SceneTree/ParameterOwner.ts:90](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L90)

___

### childBBoxChanged

▸ `Private` **childBBoxChanged**(): `void`

The _childBBoxChanged method.

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[childBBoxChanged](SceneTree_BaseGeomItem.BaseGeomItem#childbboxchanged)

#### Defined in

[SceneTree/TreeItem.ts:356](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L356)

___

### childNameChanged

▸ `Private` **childNameChanged**(`event`): `void`

When a child's name changed, we update our acceleration structure.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `Record`<`string`, `any`\> | The start value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[childNameChanged](SceneTree_BaseGeomItem.BaseGeomItem#childnamechanged)

#### Defined in

[SceneTree/TreeItem.ts:461](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L461)

___

### clone

▸ **clone**(`context?`): [`GeomItem`](SceneTree_GeomItem.GeomItem)

The clone method constructs a new geom item, copies its values
from this item and returns it.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `context?` | `Record`<`string`, `any`\> | The context value. |

#### Returns

[`GeomItem`](SceneTree_GeomItem.GeomItem)

- Returns a new cloned geom item.

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[clone](SceneTree_BaseGeomItem.BaseGeomItem#clone)

#### Defined in

[SceneTree/GeomItem.ts:281](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L281)

___

### copyFrom

▸ **copyFrom**(`src`, `context?`): `void`

Copies current GeomItem with all its children.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `src` | [`GeomItem`](SceneTree_GeomItem.GeomItem) | The geom item to copy from. |
| `context?` | `Record`<`string`, `any`\> | The context value. |

#### Returns

`void`

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[copyFrom](SceneTree_BaseGeomItem.BaseGeomItem#copyfrom)

#### Defined in

[SceneTree/GeomItem.ts:293](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L293)

___

### deleteMetadata

▸ **deleteMetadata**(`key`): `void`

Removes metadata for a given key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[deleteMetadata](SceneTree_BaseGeomItem.BaseGeomItem#deletemetadata)

#### Defined in

[SceneTree/BaseItem.ts:261](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L261)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[emit](SceneTree_BaseGeomItem.BaseGeomItem#emit)

#### Defined in

[Utilities/EventEmitter.ts:154](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L154)

___

### fromJSON

▸ **fromJSON**(`json`, `context`): `void`

The fromJSON method decodes a json object for this type.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `json` | `Record`<`string`, `any`\> | The json object this item must decode. |
| `context` | `Record`<`string`, `any`\> | The context value. |

#### Returns

`void`

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[fromJSON](SceneTree_BaseGeomItem.BaseGeomItem#fromjson)

#### Defined in

[SceneTree/GeomItem.ts:183](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L183)

___

### generateUniqueName

▸ **generateUniqueName**(`name`): `string`

Verifies if there's a child with the specified name.
If there's one, modifiers are applied to the name and returned.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name value. |

#### Returns

`string`

- Returns a unique name.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[generateUniqueName](SceneTree_BaseGeomItem.BaseGeomItem#generateuniquename)

#### Defined in

[SceneTree/TreeItem.ts:409](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L409)

___

### getChild

▸ **getChild**(`index`): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Returns child element in the specified index.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index to remove the child TreeItem. |

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

- Return the child TreeItem.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getChild](SceneTree_BaseGeomItem.BaseGeomItem#getchild)

#### Defined in

[SceneTree/TreeItem.ts:547](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L547)

___

### getChildByName

▸ **getChildByName**(`name`): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Returns child element with the specified name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name value. |

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

- Return the child TreeItem.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getChildByName](SceneTree_BaseGeomItem.BaseGeomItem#getchildbyname)

#### Defined in

[SceneTree/TreeItem.ts:557](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L557)

___

### getChildIndex

▸ **getChildIndex**(`childItem`): `number`

Returns index position of the specified item.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `childItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | The child TreeItem value. |

#### Returns

`number`

- Child index in children array.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getChildIndex](SceneTree_BaseGeomItem.BaseGeomItem#getchildindex)

#### Defined in

[SceneTree/TreeItem.ts:659](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L659)

___

### getChildNames

▸ **getChildNames**(): `string`[]

Returns children names as an array of strings.

#### Returns

`string`[]

- An array of names for each child.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getChildNames](SceneTree_BaseGeomItem.BaseGeomItem#getchildnames)

#### Defined in

[SceneTree/TreeItem.ts:570](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L570)

___

### getChildren

▸ **getChildren**(): [`TreeItem`](SceneTree_TreeItem.TreeItem)[]

Returns children list, but children are not required to have hierarchy structure(`TreeItem`).
Meaning that it could be another kind of item than `TreeItem`.

i.e. **BaseImage**

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)[]

- List of `TreeItem` owned by current TreeItem.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getChildren](SceneTree_BaseGeomItem.BaseGeomItem#getchildren)

#### Defined in

[SceneTree/TreeItem.ts:389](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L389)

___

### getClassName

▸ **getClassName**(): `string`

Returns the unmangled name of the class.

#### Returns

`string`

- The name of the class definition.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getClassName](SceneTree_BaseGeomItem.BaseGeomItem#getclassname)

#### Defined in

[Utilities/BaseClass.ts:33](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L33)

___

### getCutDist

▸ **getCutDist**(): `number`

Getter for the cutaway distance.

#### Returns

`number`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getCutDist](SceneTree_BaseGeomItem.BaseGeomItem#getcutdist)

#### Defined in

[SceneTree/BaseGeomItem.ts:126](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L126)

___

### getCutVector

▸ **getCutVector**(): [`Vec3`](../Math/Math_Vec3.Vec3)

Returns cutaway vector value.

#### Returns

[`Vec3`](../Math/Math_Vec3.Vec3)

- `Vec3` when it is set, `false` on default.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getCutVector](SceneTree_BaseGeomItem.BaseGeomItem#getcutvector)

#### Defined in

[SceneTree/BaseGeomItem.ts:107](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L107)

___

### getHighlight

▸ **getHighlight**(): [`Color`](../Math/Math_Color.Color)

Returns the color of the current highlight.

#### Returns

[`Color`](../Math/Math_Color.Color)

- The color value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getHighlight](SceneTree_BaseGeomItem.BaseGeomItem#gethighlight)

#### Defined in

[SceneTree/TreeItem.ts:313](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L313)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getId](SceneTree_BaseGeomItem.BaseGeomItem#getid)

#### Defined in

[Utilities/BaseClass.ts:25](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/BaseClass.ts#L25)

___

### getLayers

▸ **getLayers**(): `string`[]

Returns all layers in current item.

#### Returns

`string`[]

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getLayers](SceneTree_BaseGeomItem.BaseGeomItem#getlayers)

#### Defined in

[SceneTree/BaseGeomItem.ts:76](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L76)

___

### getMetadata

▸ **getMetadata**(`key`): `Record`<`string`, `any`\>

Gets Item's meta-data value by passing the `key` string.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key value under which to check for metadata. |

#### Returns

`Record`<`string`, `any`\>

- Returns the metadata associated with the given key.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getMetadata](SceneTree_BaseGeomItem.BaseGeomItem#getmetadata)

#### Defined in

[SceneTree/BaseItem.ts:232](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L232)

___

### getName

▸ **getName**(): `string`

Returns the name of the base item.

#### Returns

`string`

- Returns the base item name.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getName](SceneTree_BaseGeomItem.BaseGeomItem#getname)

#### Defined in

[SceneTree/BaseItem.ts:74](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L74)

___

### getNumChildren

▸ **getNumChildren**(): `number`

Returns the number of child elements current `TreeItem` has.

#### Returns

`number`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getNumChildren](SceneTree_BaseGeomItem.BaseGeomItem#getnumchildren)

#### Defined in

[SceneTree/TreeItem.ts:398](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L398)

___

### getNumParameters

▸ **getNumParameters**(): `number`

Returns the number of parameters current object has.

#### Returns

`number`

- Amount of parameters in current object.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getNumParameters](SceneTree_BaseGeomItem.BaseGeomItem#getnumparameters)

#### Defined in

[SceneTree/ParameterOwner.ts:39](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L39)

___

### getOwner

▸ **getOwner**(): [`Owner`](SceneTree_Owner.Owner)

The getOwner method returns the current owner of the item.
The item is a child of the current owner.

#### Returns

[`Owner`](SceneTree_Owner.Owner)

- Returns the current owner.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getOwner](SceneTree_BaseGeomItem.BaseGeomItem#getowner)

#### Defined in

[SceneTree/BaseItem.ts:154](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L154)

___

### getParameter

▸ **getParameter**(`paramName`): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

Returns `Parameter` object using the given name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `paramName` | `string` | The parameter name. |

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- Parameter object value

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getParameter](SceneTree_BaseGeomItem.BaseGeomItem#getparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:100](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L100)

___

### getParameterByIndex

▸ **getParameterByIndex**(`index`): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

Returns `Parameter` object in a given index

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | Position of the parameter in the array |

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- Parameter object value

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getParameterByIndex](SceneTree_BaseGeomItem.BaseGeomItem#getparameterbyindex)

#### Defined in

[SceneTree/ParameterOwner.ts:68](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L68)

___

### getParameterIndex

▸ **getParameterIndex**(`paramName`): `number`

Returns the index of a parameter in parameter list.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `paramName` | `string` | Name of the parameter. |

#### Returns

`number`

- Position in the array

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getParameterIndex](SceneTree_BaseGeomItem.BaseGeomItem#getparameterindex)

#### Defined in

[SceneTree/ParameterOwner.ts:58](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L58)

___

### getParameters

▸ **getParameters**(): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>[]

Returns all the parameters of the object.

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>[]

- Parameter List

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getParameters](SceneTree_BaseGeomItem.BaseGeomItem#getparameters)

#### Defined in

[SceneTree/ParameterOwner.ts:48](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L48)

___

### getParentItem

▸ **getParentItem**(): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Returns the parent of current TreeItem.

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

- Returns the parent item.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getParentItem](SceneTree_BaseGeomItem.BaseGeomItem#getparentitem)

#### Defined in

[SceneTree/TreeItem.ts:163](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L163)

___

### getPath

▸ **getPath**(): `string`[]

Returns the current path of the item in the tree as an array of names.

#### Returns

`string`[]

- Returns an array.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getPath](SceneTree_BaseGeomItem.BaseGeomItem#getpath)

#### Defined in

[SceneTree/BaseItem.ts:111](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L111)

___

### hasMetadata

▸ **hasMetadata**(`key`): `boolean`

Checks to see if there is metadata for a given key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key value under which to check for metadata. |

#### Returns

`boolean`

- Returns `true` if metadata exists under the given key, otherwise returns `false`.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[hasMetadata](SceneTree_BaseGeomItem.BaseGeomItem#hasmetadata)

#### Defined in

[SceneTree/BaseItem.ts:242](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L242)

___

### hasParameter

▸ **hasParameter**(`paramName`): `boolean`

Validates if the specified parameter exists in the object.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `paramName` | `string` | The parameter name. |

#### Returns

`boolean`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[hasParameter](SceneTree_BaseGeomItem.BaseGeomItem#hasparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:78](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L78)

___

### insertChild

▸ **insertChild**(`childItem`, `index`, `maintainXfo?`, `fixCollisions?`): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Inserts a child. It accepts all kind of `TreeItem`, not only `TreeItem`.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `childItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | `undefined` | The child TreeItem to insert. |
| `index` | `number` | `undefined` | The index to add the child item. |
| `maintainXfo` | `boolean` | `false` | Boolean that determines if the Xfo value is maintained. |
| `fixCollisions` | `boolean` | `true` | Modify the name of the item to avoid name collisions. If false, an exception wll be thrown instead if a name collision occurs. |

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

- The index of the child item in this items children array.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[insertChild](SceneTree_BaseGeomItem.BaseGeomItem#insertchild)

#### Defined in

[SceneTree/TreeItem.ts:478](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L478)

___

### insertParameter

▸ **insertParameter**(`param`, `index`): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

Adds `Parameter` object to the owner's parameter list using the index.
It replaces the event in the specified index.

**`emits`** `parameterAdded` with the name of the param.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param` | [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\> | The parameter to insert. |
| `index` | `number` | The index value. |

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- With `owner` and `valueChanged` event set.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[insertParameter](SceneTree_BaseGeomItem.BaseGeomItem#insertparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:147](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L147)

___

### isCutawayEnabled

▸ **isCutawayEnabled**(): `boolean`

Checks if cutaway is enabled.

#### Returns

`boolean`

- Returns `true` if enabled.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isCutawayEnabled](SceneTree_BaseGeomItem.BaseGeomItem#iscutawayenabled)

#### Defined in

[SceneTree/BaseGeomItem.ts:88](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L88)

___

### isHighlighted

▸ **isHighlighted**(): `boolean`

Returns `true` if this items has a highlight color assigned.

#### Returns

`boolean`

- `True` if this item is highlighted.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isHighlighted](SceneTree_BaseGeomItem.BaseGeomItem#ishighlighted)

#### Defined in

[SceneTree/TreeItem.ts:326](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L326)

___

### isOverlay

▸ **isOverlay**(): `boolean`

Returns `true` if overlay is enabled for current item.

#### Returns

`boolean`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isOverlay](SceneTree_BaseGeomItem.BaseGeomItem#isoverlay)

#### Defined in

[SceneTree/BaseGeomItem.ts:56](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L56)

___

### isSelectable

▸ **isSelectable**(): `boolean`

Returns a boolean indicating if this item is selectable.

#### Returns

`boolean`

- Returns a boolean indicating if the item is selectable.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isSelectable](SceneTree_BaseGeomItem.BaseGeomItem#isselectable)

#### Defined in

[SceneTree/BaseItem.ts:183](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L183)

___

### isSelected

▸ **isSelected**(): `boolean`

The isSelected method.

#### Returns

`boolean`

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isSelected](SceneTree_BaseGeomItem.BaseGeomItem#isselected)

#### Defined in

[SceneTree/BaseItem.ts:207](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L207)

___

### isVisible

▸ **isVisible**(): `boolean`

Returns visible parameter value for current TreeItem.

#### Returns

`boolean`

- The visible param value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[isVisible](SceneTree_BaseGeomItem.BaseGeomItem#isvisible)

#### Defined in

[SceneTree/TreeItem.ts:184](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L184)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[off](SceneTree_BaseGeomItem.BaseGeomItem#off)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[on](SceneTree_BaseGeomItem.BaseGeomItem#on)

#### Defined in

[Utilities/EventEmitter.ts:44](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L44)

___

### onPointerDown

▸ **onPointerDown**(`event`): `void`

Called by the Viewport when events are received by the canvas element.
The event is propagated to a TreeItem if it is under the pointer at the time.
The ZeaPointerEvent abstracts the Mouse, touch and our custom XR events.
This method emits the ZeaPointerEvent with the key 'pointerDown', and
propagates it up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaPointerEvent`](../Utilities/Events/Utilities_Events_ZeaPointerEvent.ZeaPointerEvent) | The event value |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onPointerDown](SceneTree_BaseGeomItem.BaseGeomItem#onpointerdown)

#### Defined in

[SceneTree/TreeItem.ts:762](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L762)

___

### onPointerEnter

▸ **onPointerEnter**(`event`): `void`

Called by the Viewport when the mouse or other pointer enters the canvas element.
The event is propagated to a TreeItem if it is under the pointer at the time.
The ZeaPointerEvent abstracts the Mouse, touch and our custom XR events.
This method emits the ZeaPointerEvent with the key 'pointerEnter', and
propagates it up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaPointerEvent`](../Utilities/Events/Utilities_Events_ZeaPointerEvent.ZeaPointerEvent) | The pointer event that was generated from the user interaction |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onPointerEnter](SceneTree_BaseGeomItem.BaseGeomItem#onpointerenter)

#### Defined in

[SceneTree/TreeItem.ts:813](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L813)

___

### onPointerLeave

▸ **onPointerLeave**(`event`): `void`

Called by the Viewport when the mouse or other pointer leaves the canvas element.
The event is propagated to a TreeItem if it is under the pointer at the time.
The ZeaPointerEvent abstracts the Mouse, touch and our custom XR events.
This method emits the ZeaPointerEvent with the key 'pointerLeave', and
propagates it up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaPointerEvent`](../Utilities/Events/Utilities_Events_ZeaPointerEvent.ZeaPointerEvent) | The pointer event that was generated from the user interaction |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onPointerLeave](SceneTree_BaseGeomItem.BaseGeomItem#onpointerleave)

#### Defined in

[SceneTree/TreeItem.ts:830](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L830)

___

### onPointerMove

▸ **onPointerMove**(`event`): `void`

Called by the Viewport when events are received by the canvas element.
The event is propagated to a TreeItem if it is under the pointer at the time.
The ZeaPointerEvent abstracts the Mouse, touch and our custom XR events.
This method emits the ZeaPointerEvent with the key 'pointerMove', and
propagates it up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaPointerEvent`](../Utilities/Events/Utilities_Events_ZeaPointerEvent.ZeaPointerEvent) | The pointer event that was generated from the user interaction |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onPointerMove](SceneTree_BaseGeomItem.BaseGeomItem#onpointermove)

#### Defined in

[SceneTree/TreeItem.ts:796](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L796)

___

### onPointerUp

▸ **onPointerUp**(`event`): `void`

Called by the Viewport when events are received by the canvas element.
The event is propagated to a TreeItem if it is under the pointer at the time.
The ZeaPointerEvent abstracts the Mouse, touch and our custom XR events.
This method emits the ZeaPointerEvent with the key 'pointerDown', and
propagates it up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaPointerEvent`](../Utilities/Events/Utilities_Events_ZeaPointerEvent.ZeaPointerEvent) | The pointer event that was generated from the user interaction |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onPointerUp](SceneTree_BaseGeomItem.BaseGeomItem#onpointerup)

#### Defined in

[SceneTree/TreeItem.ts:779](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L779)

___

### onTouchCancel

▸ **onTouchCancel**(`event`): `void`

Called by the Viewport when the touch cancel event is received by the canvas element.
Emits the ZeaTouchEvent with the key 'touchCancel', and Propagates is up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaTouchEvent`](../Utilities/Events/Utilities_Events_ZeaTouchEvent.ZeaTouchEvent) | The wheel event that occurs. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onTouchCancel](SceneTree_BaseGeomItem.BaseGeomItem#ontouchcancel)

#### Defined in

[SceneTree/TreeItem.ts:858](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L858)

___

### onWheel

▸ **onWheel**(`event`): `void`

Called by the Viewport when the mouse wheel event is received by the canvas element.
Emits the ZeaWheelEvent with the key 'mouseWheel', and Propagates is up to the TreeItem's owner.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | [`ZeaWheelEvent`](../Utilities/Events/Utilities_Events_ZeaWheelEvent.ZeaWheelEvent) | The wheel event that occurs. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[onWheel](SceneTree_BaseGeomItem.BaseGeomItem#onwheel)

#### Defined in

[SceneTree/TreeItem.ts:844](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L844)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[once](SceneTree_BaseGeomItem.BaseGeomItem#once)

#### Defined in

[Utilities/EventEmitter.ts:82](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L82)

___

### parameterValueChanged

▸ `Private` **parameterValueChanged**(`event`): `void`

This method can be overridden in derived classes
to perform general updates (see GLPass or BaseItem).

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `Record`<`string`, `unknown`\> | The event object emitted by the parameter. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[parameterValueChanged](SceneTree_BaseGeomItem.BaseGeomItem#parametervaluechanged)

#### Defined in

[SceneTree/ParameterOwner.ts:122](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L122)

___

### propagateVisibility

▸ **propagateVisibility**(`val`): `void`

Updates current TreeItem visible state and propagates its value to children elements.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `val` | `number` | The val param. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[propagateVisibility](SceneTree_BaseGeomItem.BaseGeomItem#propagatevisibility)

#### Defined in

[SceneTree/TreeItem.ts:203](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L203)

___

### readBinary

▸ **readBinary**(`reader`, `context`): `void`

Loads state of the Item from a binary object.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `reader` | [`BinReader`](SceneTree_BinReader.BinReader) | The reader value. |
| `context` | `Record`<`string`, `any`\> | The context value. |

#### Returns

`void`

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[readBinary](SceneTree_BaseGeomItem.BaseGeomItem#readbinary)

#### Defined in

[SceneTree/GeomItem.ts:194](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L194)

___

### removeAllChildren

▸ **removeAllChildren**(): `void`

Removes all children Items.

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeAllChildren](SceneTree_BaseGeomItem.BaseGeomItem#removeallchildren)

#### Defined in

[SceneTree/TreeItem.ts:645](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L645)

___

### removeChild

▸ **removeChild**(`index`): `void`

Removes a child TreeItem by specifying its index.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeChild](SceneTree_BaseGeomItem.BaseGeomItem#removechild)

#### Defined in

[SceneTree/TreeItem.ts:607](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L607)

___

### removeChildByHandle

▸ **removeChildByHandle**(`childItem`): `void`

Removes the provided item from this TreeItem if it is one of its children.
An exception is thrown if the item is not a child of this tree item.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `childItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | The child TreeItem to remove. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeChildByHandle](SceneTree_BaseGeomItem.BaseGeomItem#removechildbyhandle)

#### Defined in

[SceneTree/TreeItem.ts:636](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L636)

___

### removeChildByName

▸ **removeChildByName**(`name`): `void`

Removes a child TreeItem by specifying its name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name param. |

#### Returns

`void`

- Return the child TreeItem.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeChildByName](SceneTree_BaseGeomItem.BaseGeomItem#removechildbyname)

#### Defined in

[SceneTree/TreeItem.ts:623](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L623)

___

### removeHighlight

▸ **removeHighlight**(`name`, `propagateToChildren?`): `void`

Removes a highlight to the tree item.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `name` | `string` | `undefined` | The name of the tree item. |
| `propagateToChildren` | `boolean` | `false` | A boolean indicating whether to propagate to children. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeHighlight](SceneTree_BaseGeomItem.BaseGeomItem#removehighlight)

#### Defined in

[SceneTree/TreeItem.ts:279](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L279)

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

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeListenerById](SceneTree_BaseGeomItem.BaseGeomItem#removelistenerbyid)

#### Defined in

[Utilities/EventEmitter.ts:134](https://github.com/ZeaInc/zea-engine/blob/41278600/src/Utilities/EventEmitter.ts#L134)

___

### removeParameter

▸ **removeParameter**(`name`): `void`

Removes `Parameter` from owner, by using parameter's name.

**`emits`** `parameterRemoved` with the name of the param.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The parameter name. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[removeParameter](SceneTree_BaseGeomItem.BaseGeomItem#removeparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:174](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L174)

___

### replaceParameter

▸ **replaceParameter**(`param`): [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

Replaces old `Parameter` by passing a new one with the same name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param` | [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\> | The parameter to replace. |

#### Returns

[`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- `Parameter` with `valueChanged` event set.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[replaceParameter](SceneTree_BaseGeomItem.BaseGeomItem#replaceparameter)

#### Defined in

[SceneTree/ParameterOwner.ts:196](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/ParameterOwner.ts#L196)

___

### resolvePath

▸ **resolvePath**(`path`, `index?`, `displayError?`): [`BaseItem`](SceneTree_BaseItem.BaseItem) \| [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

The resolvePath method traverses the subtree from this item down
matching each name in the path with a child until it reaches the
end of the path.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `path` | `string` \| `string`[] | `undefined` | The path value. |
| `index` | `number` | `0` | The index value. |
| `displayError` | `boolean` | `false` | - |

#### Returns

[`BaseItem`](SceneTree_BaseItem.BaseItem) \| [`Parameter`](Parameters/SceneTree_Parameters_Parameter.Parameter)<`any`\>

- The return value.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[resolvePath](SceneTree_BaseGeomItem.BaseGeomItem#resolvepath)

#### Defined in

[SceneTree/TreeItem.ts:679](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L679)

___

### setBoundingBoxDirty

▸ `Private` **setBoundingBoxDirty**(): `void`

The setBoundingBoxDirty method.

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setBoundingBoxDirty](SceneTree_BaseGeomItem.BaseGeomItem#setboundingboxdirty)

#### Defined in

[SceneTree/TreeItem.ts:364](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L364)

___

### setCutDist

▸ **setCutDist**(`cutAwayDist`): `void`

Sets cutaway distance value.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cutAwayDist` | `number` | The cutAwayDist value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setCutDist](SceneTree_BaseGeomItem.BaseGeomItem#setcutdist)

#### Defined in

[SceneTree/BaseGeomItem.ts:135](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L135)

___

### setCutVector

▸ **setCutVector**(`cutAwayVector`): `void`

Sets cutaway vector value.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cutAwayVector` | [`Vec3`](../Math/Math_Vec3.Vec3) | The cutAwayVector value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setCutVector](SceneTree_BaseGeomItem.BaseGeomItem#setcutvector)

#### Defined in

[SceneTree/BaseGeomItem.ts:116](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L116)

___

### setCutawayEnabled

▸ **setCutawayEnabled**(`state`): `void`

Sets cutaway state.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `state` | `boolean` | `true` to enable it, otherwise `false`. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setCutawayEnabled](SceneTree_BaseGeomItem.BaseGeomItem#setcutawayenabled)

#### Defined in

[SceneTree/BaseGeomItem.ts:97](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L97)

___

### setMetadata

▸ **setMetadata**(`key`, `metaData`): `void`

Assigns metadata to a given key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key value under which the metadata is is going to be saved. |
| `metaData` | `any` | The metaData value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setMetadata](SceneTree_BaseGeomItem.BaseGeomItem#setmetadata)

#### Defined in

[SceneTree/BaseItem.ts:252](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L252)

___

### setName

▸ **setName**(`name`): `void`

Sets the name of the base item(Updates path).

**`emits`** `nameChanged` with `newName` and `oldName` data.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The base item name. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setName](SceneTree_BaseGeomItem.BaseGeomItem#setname)

#### Defined in

[SceneTree/BaseItem.ts:84](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L84)

___

### setOverlay

▸ **setOverlay**(`val`): `void`

Sets overlay value.

**`todo`** Need to find the layer and add this item to it.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `val` | `boolean` | `true` to enable it. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setOverlay](SceneTree_BaseGeomItem.BaseGeomItem#setoverlay)

#### Defined in

[SceneTree/BaseGeomItem.ts:46](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseGeomItem.ts#L46)

___

### setOwner

▸ **setOwner**(`parentItem`): `void`

Sets the owner (another TreeItem) of the current TreeItem.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `parentItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | The parent item. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setOwner](SceneTree_BaseGeomItem.BaseGeomItem#setowner)

#### Defined in

[SceneTree/TreeItem.ts:120](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L120)

___

### setParentItem

▸ **setParentItem**(`parentItem`): `void`

Sets the parent of current TreeItem.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `parentItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | The parent item. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setParentItem](SceneTree_BaseGeomItem.BaseGeomItem#setparentitem)

#### Defined in

[SceneTree/TreeItem.ts:172](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L172)

___

### setSelectable

▸ **setSelectable**(`val`): `boolean`

Modifies the selectability of this item.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `val` | `boolean` | A boolean indicating the selectability of the item. |

#### Returns

`boolean`

- Returns true if value changed.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setSelectable](SceneTree_BaseGeomItem.BaseGeomItem#setselectable)

#### Defined in

[SceneTree/BaseItem.ts:193](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L193)

___

### setSelected

▸ **setSelected**(`sel`): `void`

Changes the current state of the selection of this item.

**`emits`** `selectedChanged` with selected state

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `sel` | `boolean` | Boolean indicating the new selection state. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setSelected](SceneTree_BaseGeomItem.BaseGeomItem#setselected)

#### Defined in

[SceneTree/BaseItem.ts:217](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L217)

___

### setVisible

▸ **setVisible**(`visible`): `void`

Sets visible parameter value.

#### Parameters

| Name | Type |
| :------ | :------ |
| `visible` | `boolean` |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[setVisible](SceneTree_BaseGeomItem.BaseGeomItem#setvisible)

#### Defined in

[SceneTree/TreeItem.ts:194](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L194)

___

### toJSON

▸ **toJSON**(`context?`): `Record`<`string`, `any`\>

The toJSON method encodes this type as a json object for persistence.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `context?` | `Record`<`string`, `any`\> | The context value. |

#### Returns

`Record`<`string`, `any`\>

- Returns the json object.

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[toJSON](SceneTree_BaseGeomItem.BaseGeomItem#tojson)

#### Defined in

[SceneTree/GeomItem.ts:172](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L172)

___

### toString

▸ **toString**(`context`): `string`

Returns string representation of current object's state.

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `Record`<`string`, `any`\> |

#### Returns

`string`

- The return value.

#### Overrides

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[toString](SceneTree_BaseGeomItem.BaseGeomItem#tostring)

#### Defined in

[SceneTree/GeomItem.ts:267](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L267)

___

### traverse

▸ **traverse**(`callback`, `includeThis?`): `void`

Traverse the tree structure from this point down
and fire the callback for each visited item.
Note: Depth only used by selection sets for now.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `callback` | (`treeItem`: [`TreeItem`](SceneTree_TreeItem.TreeItem), `depth`: `number`) => `unknown` | `undefined` | The callback value. |
| `includeThis` | `boolean` | `true` | Fire the callback for this item. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[traverse](SceneTree_BaseGeomItem.BaseGeomItem#traverse)

#### Defined in

[SceneTree/TreeItem.ts:731](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L731)

___

### unbindChild

▸ `Private` **unbindChild**(`index`, `childItem`): `void`

UnBind an item from the group. This method is called
automatically when an item is removed from the group.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | The index value. |
| `childItem` | [`TreeItem`](SceneTree_TreeItem.TreeItem) | item to unbind. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[unbindChild](SceneTree_BaseGeomItem.BaseGeomItem#unbindchild)

#### Defined in

[SceneTree/TreeItem.ts:586](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L586)

___

### updateChildNameMapping

▸ `Private` **updateChildNameMapping**(`start`): `void`

Updates the internal acceleration structure that speeds up looking up children by name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `start` | `number` | The start value. |

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[updateChildNameMapping](SceneTree_BaseGeomItem.BaseGeomItem#updatechildnamemapping)

#### Defined in

[SceneTree/TreeItem.ts:448](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L448)

___

### updatePath

▸ `Private` **updatePath**(): `void`

The updatePath method.

#### Returns

`void`

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[updatePath](SceneTree_BaseGeomItem.BaseGeomItem#updatepath)

#### Defined in

[SceneTree/TreeItem.ts:151](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L151)

___

### updateVisibility

▸ `Private` **updateVisibility**(): `boolean`

The updateVisibility method.

#### Returns

`boolean`

- Returns a boolean.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[updateVisibility](SceneTree_BaseGeomItem.BaseGeomItem#updatevisibility)

#### Defined in

[SceneTree/TreeItem.ts:213](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/TreeItem.ts#L213)

___

### getNumBaseItems

▸ `Static` **getNumBaseItems**(): `number`

The getNumBaseItems method returns the total number of base items created.
This method is used in debugging memory consumption.

#### Returns

`number`

- Returns the total number of base items created.

#### Inherited from

[BaseGeomItem](SceneTree_BaseGeomItem.BaseGeomItem).[getNumBaseItems](SceneTree_BaseGeomItem.BaseGeomItem#getnumbaseitems)

#### Defined in

[SceneTree/BaseItem.ts:62](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/BaseItem.ts#L62)

___

### setCalculatePreciseBoundingBoxes

▸ `Static` **setCalculatePreciseBoundingBoxes**(`value`): `void`

Sets the global boolean that controls if GeomItems calculate precise bounding boxes
or use the approximate bounding boxes that are much faster to generate.
Note: computing the precise bounding box is much slower and can make loading
big scenes take a bit longer. This setting is only relevant to geometries loaded
from zcad files.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `boolean` | true for precise bounding boxes, else false for faster approximate bounding boxes. |

#### Returns

`void`

#### Defined in

[SceneTree/GeomItem.ts:329](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/GeomItem.ts#L329)

