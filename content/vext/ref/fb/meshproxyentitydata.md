---
title: MeshProxyEntityData
---
### Base Classes

[SpatialEntityData](SpatialEntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| MeshProxyEntityData()                                                          | Create a new instance of this container type.                                                                                 |
| MeshProxyEntityData(MeshProxyEntityData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| MeshProxyEntityData([SpatialEntityData](SpatialEntityData) other)              | Upcast an instance of type [SpatialEntityData](SpatialEntityData) to [MeshProxyEntityData](MeshProxyEntityData).              |
| MeshProxyEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [MeshProxyEntityData](MeshProxyEntityData).                            |
| MeshProxyEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [MeshProxyEntityData](MeshProxyEntityData).                    |
| MeshProxyEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [MeshProxyEntityData](MeshProxyEntityData).              |
| MeshProxyEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MeshProxyEntityData](MeshProxyEntityData). |

## Properties

| Name               | Type                                                        | Description |
| ------------------ | ----------------------------------------------------------- | ----------- |
| mesh               | [MeshAsset](MeshAsset)                                      |             |
| basePoseTransforms | [LinearTransform](/vext/ref/shared/class/LinearTransform)\[\] |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [MeshProxyEntityData](MeshProxyEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MeshProxyEntityData](MeshProxyEntityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |