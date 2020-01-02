---
title: SimpleTransformNodeData
---
### Base Classes

[AudioGraphNodeData](AudioGraphNodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| SimpleTransformNodeData()                                                          | Create a new instance of this container type.                                                                                         |
| SimpleTransformNodeData(SimpleTransformNodeData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| SimpleTransformNodeData([AudioGraphNodeData](AudioGraphNodeData) other)            | Upcast an instance of type [AudioGraphNodeData](AudioGraphNodeData) to [SimpleTransformNodeData](SimpleTransformNodeData).            |
| SimpleTransformNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SimpleTransformNodeData](SimpleTransformNodeData). |

## Properties

| Name      | Type                                                 | Description |
| --------- | ---------------------------------------------------- | ----------- |
| x         | [AudioGraphNodePort](AudioGraphNodePort)             |             |
| y         | [AudioGraphNodePort](AudioGraphNodePort)             |             |
| z         | [AudioGraphNodePort](AudioGraphNodePort)             |             |
| operation | [SimpleTransformOperation](SimpleTransformOperation) |             |
| angleUnit | [AngleUnit](AngleUnit)                               |             |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SimpleTransformNodeData](SimpleTransformNodeData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SimpleTransformNodeData](SimpleTransformNodeData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |