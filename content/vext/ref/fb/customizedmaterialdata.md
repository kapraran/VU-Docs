---
title: CustomizedMaterialData
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[CustomizedMaterialData](#constructor-0)**() |
| **[CustomizedMaterialData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[CustomizedMaterialData](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "materialNames" >}} | string[] |
| {{< prop "colorParameters" >}} | [UnlockableColorCollection](/vext/ref/fb/unlockablecolorcollection)[] |
| {{< prop "textureParameters" >}} | [UnlockableTextureCollection](/vext/ref/fb/unlockabletexturecollection)[] |
| {{< prop "textureSliceParameters" >}} | [UnlockableTextureSliceCollection](/vext/ref/fb/unlockabletextureslicecollection)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "CustomizedMaterialData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### CustomizedMaterialData {#constructor-0}

> **CustomizedMaterialData**()

Creates a new [CustomizedMaterialData](/vext/ref/fb/customizedmaterialdata) frostbite instance.

### CustomizedMaterialData {#constructor-1}

> **CustomizedMaterialData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [CustomizedMaterialData](/vext/ref/fb/customizedmaterialdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### CustomizedMaterialData {#constructor-2}

> **CustomizedMaterialData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [CustomizedMaterialData](/vext/ref/fb/customizedmaterialdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [CustomizedMaterialData](/vext/ref/fb/customizedmaterialdata). |

## Properties

### {{% prop-heading "materialNames" %}}

> **string**[]

### {{% prop-heading "colorParameters" %}}

> **[UnlockableColorCollection](/vext/ref/fb/unlockablecolorcollection)**[]

### {{% prop-heading "textureParameters" %}}

> **[UnlockableTextureCollection](/vext/ref/fb/unlockabletexturecollection)**[]

### {{% prop-heading "textureSliceParameters" %}}

> **[UnlockableTextureSliceCollection](/vext/ref/fb/unlockabletextureslicecollection)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [CustomizedMaterialData](/vext/ref/fb/customizedmaterialdata) type.

