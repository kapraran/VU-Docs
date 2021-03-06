---
title: DataContainerAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[DataContainerAsset](#constructor-0)**() |
| **[DataContainerAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[DataContainerAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[DataContainerAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "data" >}} | [DataContainer](/vext/ref/shared/type/datacontainer) \| nil |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "DataContainerAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### DataContainerAsset {#constructor-0}

> **DataContainerAsset**()

Creates a new [DataContainerAsset](/vext/ref/fb/datacontainerasset) frostbite instance.

### DataContainerAsset {#constructor-1}

> **DataContainerAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [DataContainerAsset](/vext/ref/fb/datacontainerasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### DataContainerAsset {#constructor-2}

> **DataContainerAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [DataContainerAsset](/vext/ref/fb/datacontainerasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [DataContainerAsset](/vext/ref/fb/datacontainerasset). |

### DataContainerAsset {#constructor-3}

> **DataContainerAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [DataContainerAsset](/vext/ref/fb/datacontainerasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [DataContainerAsset](/vext/ref/fb/datacontainerasset). |

## Properties

### {{% prop-heading "data" %}}

> **[DataContainer](/vext/ref/shared/type/datacontainer)** \| **nil**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [DataContainerAsset](/vext/ref/fb/datacontainerasset) type.

