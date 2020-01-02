---
title: ExtendedConstraintsData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| ExtendedConstraintsData()                                                          | Create a new instance of this container type.                                                                                         |
| ExtendedConstraintsData(ExtendedConstraintsData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| ExtendedConstraintsData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [ExtendedConstraintsData](ExtendedConstraintsData). |

## Properties

| Name                 | Type   | Description |
| -------------------- | ------ | ----------- |
| heading              | number |             |
| width                | number |             |
| falloff              | number |             |
| angularConstraintMin | number |             |
| angularConstraintMax | number |             |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [ExtendedConstraintsData](ExtendedConstraintsData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [ExtendedConstraintsData](ExtendedConstraintsData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |