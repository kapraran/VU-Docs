---
title: UIInterruptFlow
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| UIInterruptFlow()                                                          | Create a new instance of this container type.                                                                         |
| UIInterruptFlow(UIInterruptFlow other)                                     | Create a reference copy of an instance of the same type.                                                              |
| UIInterruptFlow([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIInterruptFlow](UIInterruptFlow).                                      |
| UIInterruptFlow([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIInterruptFlow](UIInterruptFlow). |

## Properties

| Name          | Type                               | Description |
| ------------- | ---------------------------------- | ----------- |
| interruptFlow | [InterruptFlow](InterruptFlow)\[\] |             |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [UIInterruptFlow](UIInterruptFlow) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIInterruptFlow](UIInterruptFlow) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |