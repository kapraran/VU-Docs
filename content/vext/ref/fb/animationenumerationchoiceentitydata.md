---
title: AnimationEnumerationChoiceEntityData
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                     | Description                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AnimationEnumerationChoiceEntityData()                                                          | Create a new instance of this container type.                                                                                                                   |
| AnimationEnumerationChoiceEntityData(AnimationEnumerationChoiceEntityData other)                | Create a reference copy of an instance of the same type.                                                                                                        |
| AnimationEnumerationChoiceEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData).                            |
| AnimationEnumerationChoiceEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData).                    |
| AnimationEnumerationChoiceEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData).              |
| AnimationEnumerationChoiceEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData). |

## Properties

| Name  | Type           | Description |
| ----- | -------------- | ----------- |
| realm | [Realm](Realm) |             |
| value | number         |             |

## Methods

| Type                                                                         | Name            | Parameters                                     |
| ---------------------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [AnimationEnumerationChoiceEntityData](AnimationEnumerationChoiceEntityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |