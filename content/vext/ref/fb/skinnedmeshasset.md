---
title: SkinnedMeshAsset
---

Inherits from [MeshAsset](/vext/ref/fb/meshasset)

## Summary

### Constructors

|  |
| --- |
| **[SkinnedMeshAsset](#constructor-0)**() |
| **[SkinnedMeshAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[SkinnedMeshAsset](#constructor-2)**(other: [MeshAsset](/vext/ref/fb/meshasset)) |
| **[SkinnedMeshAsset](#constructor-3)**(other: [Asset](/vext/ref/fb/asset)) |
| **[SkinnedMeshAsset](#constructor-4)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "boundingBoxPositionOffset" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "boundingBoxSizeOffset" >}} | [Vec3](/vext/ref/shared/type/vec3) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "SkinnedMeshAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### SkinnedMeshAsset {#constructor-0}

> **SkinnedMeshAsset**()

Creates a new [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset) frostbite instance.

### SkinnedMeshAsset {#constructor-1}

> **SkinnedMeshAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### SkinnedMeshAsset {#constructor-2}

> **SkinnedMeshAsset**(other: [MeshAsset](/vext/ref/fb/meshasset))

Casts an instance of type [MeshAsset](/vext/ref/fb/meshasset) to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [MeshAsset](/vext/ref/fb/meshasset) | The instance to cast to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). |

### SkinnedMeshAsset {#constructor-3}

> **SkinnedMeshAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). |

### SkinnedMeshAsset {#constructor-4}

> **SkinnedMeshAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset). |

## Properties

### {{% prop-heading "boundingBoxPositionOffset" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "boundingBoxSizeOffset" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [SkinnedMeshAsset](/vext/ref/fb/skinnedmeshasset) type.

