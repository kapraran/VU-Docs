---
title: SpawnSpeedData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| SpawnSpeedData()                                                          | Create a new instance of this container type.                                                                       |
| SpawnSpeedData(SpawnSpeedData other)                                      | Create a reference copy of an instance of the same type.                                                            |
| SpawnSpeedData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [SpawnSpeedData](SpawnSpeedData).                      |
| SpawnSpeedData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [SpawnSpeedData](SpawnSpeedData).        |
| SpawnSpeedData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SpawnSpeedData](SpawnSpeedData). |

## Properties

| Name  | Type   | Description |
| ----- | ------ | ----------- |
| speed | number |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [SpawnSpeedData](SpawnSpeedData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SpawnSpeedData](SpawnSpeedData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |