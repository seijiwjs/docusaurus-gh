---
id: "SceneTree_Scene.Scene"
title: "Class: Scene"
sidebar_label: "Scene"
custom_edit_url: null
---



Class representing the environment where all the displayed assets live.

## Constructors

### constructor

• **new Scene**()

Create a scene.

#### Defined in

[SceneTree/Scene.ts:35](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L35)

## Properties

### displayEnvMapParam

• **displayEnvMapParam**: [`BooleanParameter`](Parameters/SceneTree_Parameters_BooleanParameter.BooleanParameter)

**`member`** displayEnvMapParam - Boolean that determines whether or not the environment map should be displayed.

#### Defined in

[SceneTree/Scene.ts:23](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L23)

___

### envMapLODParam

• **envMapLODParam**: [`NumberParameter`](Parameters/SceneTree_Parameters_NumberParameter.NumberParameter)

**`member`** envMapLODParam - TODO

#### Defined in

[SceneTree/Scene.ts:28](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L28)

___

### envMapParam

• **envMapParam**: [`ImageParameter`](Parameters/SceneTree_Parameters_ImageParameter.ImageParameter)

**`member`** envMapParam - The image displayed and used for the environment map.

#### Defined in

[SceneTree/Scene.ts:18](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L18)

___

### root

• `Protected` **root**: [`TreeItem`](SceneTree_TreeItem.TreeItem)

#### Defined in

[SceneTree/Scene.ts:30](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L30)

## Methods

### getResourceLoader

▸ **getResourceLoader**(): [`ResourceLoader`](SceneTree_resourceLoader.ResourceLoader)

Returns resourceLoader object set on class initialization.

#### Returns

[`ResourceLoader`](SceneTree_resourceLoader.ResourceLoader)

- The return value.

#### Defined in

[SceneTree/Scene.ts:51](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L51)

___

### getRoot

▸ **getRoot**(): [`TreeItem`](SceneTree_TreeItem.TreeItem)

Returns the scene's root item(`TreeItem`) that owns every item in the scene.

#### Returns

[`TreeItem`](SceneTree_TreeItem.TreeItem)

- The return value.

#### Defined in

[SceneTree/Scene.ts:42](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L42)

___

### setEnvMap

▸ **setEnvMap**(`envMap`): `void`

Sets Environment Map with the BaseImage you'd like to display in your scene background.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `envMap` | [`EnvMap`](Images/SceneTree_Images_EnvMap.EnvMap) | The envMap value. |

#### Returns

`void`

#### Defined in

[SceneTree/Scene.ts:60](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L60)

___

### setupGrid

▸ **setupGrid**(`gridSize?`, `resolution?`, `gridColor?`): [`GridTreeItem`](SceneTree_GridTreeItem.GridTreeItem)

Sets up and displays the scene grid of a given size and resolution. The Grid is oriented on the XY plane
and highlights the X and Y axes with Red and Green lines. Grids are useful in displaying scene scale and coordinate system.
The Grid geometry does not return a bounding box and so does not effect the bounding of the scene.
The GridTreeItem display a grid of a given size and resolution. The Grid is oriented on the XY plane
and highlights the X and Y axes with Red and Green lines.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `gridSize` | `number` | `5` | The size of the grid. |
| `resolution` | `number` | `50` | The resolution of the grid. |
| `gridColor` | [`Color`](../Math/Math_Color.Color) | `defaultGridColor` | The color of the grid. |

#### Returns

[`GridTreeItem`](SceneTree_GridTreeItem.GridTreeItem)

- The return value.

#### Defined in

[SceneTree/Scene.ts:76](https://github.com/ZeaInc/zea-engine/blob/41278600/src/SceneTree/Scene.ts#L76)

