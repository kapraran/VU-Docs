---
title: AwardStatus
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                    | Description                                              |
| ------------------------------ | -------------------------------------------------------- |
| AwardStatus()                  | Create a new instance of this structure type.            |
| AwardStatus(AwardStatus other) | Create a reference copy of a structure of the same type. |

## Properties

| Name          | Type                               | Description |
| ------------- | ---------------------------------- | ----------- |
| code          | string                             |             |
| currentValue  | number                             |             |
| originalValue | number                             |             |
| counters      | [CounterStatus](CounterStatus)\[\] |             |
| isCounting    | bool                               |             |

## Methods

| Type                       | Name            | Parameters |
| -------------------------- | --------------- | ---------- |
| [AwardStatus](AwardStatus) | [Clone](#clone) |            |

### Clone

> [AwardStatus](AwardStatus) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).