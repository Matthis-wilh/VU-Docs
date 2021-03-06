---
title: OBBData
---

Inherits from [BaseShapeData](/vext/ref/fb/baseshapedata)

## Summary

### Constructors

|  |
| --- |
| **[OBBData](#constructor-0)**() |
| **[OBBData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[OBBData](#constructor-2)**(other: [BaseShapeData](/vext/ref/fb/baseshapedata)) |
| **[OBBData](#constructor-3)**(other: [GameObjectData](/vext/ref/fb/gameobjectdata)) |
| **[OBBData](#constructor-4)**(other: [GameDataContainer](/vext/ref/fb/gamedatacontainer)) |
| **[OBBData](#constructor-5)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "transform" >}} | [LinearTransform](/vext/ref/shared/type/lineartransform) |
| {{< prop "halfExtents" >}} | [Vec3](/vext/ref/shared/type/vec3) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "OBBData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### OBBData {#constructor-0}

> **OBBData**()

Creates a new [OBBData](/vext/ref/fb/obbdata) frostbite instance.

### OBBData {#constructor-1}

> **OBBData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [OBBData](/vext/ref/fb/obbdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### OBBData {#constructor-2}

> **OBBData**(other: [BaseShapeData](/vext/ref/fb/baseshapedata))

Casts an instance of type [BaseShapeData](/vext/ref/fb/baseshapedata) to [OBBData](/vext/ref/fb/obbdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [BaseShapeData](/vext/ref/fb/baseshapedata) | The instance to cast to [OBBData](/vext/ref/fb/obbdata). |

### OBBData {#constructor-3}

> **OBBData**(other: [GameObjectData](/vext/ref/fb/gameobjectdata))

Casts an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata) to [OBBData](/vext/ref/fb/obbdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [GameObjectData](/vext/ref/fb/gameobjectdata) | The instance to cast to [OBBData](/vext/ref/fb/obbdata). |

### OBBData {#constructor-4}

> **OBBData**(other: [GameDataContainer](/vext/ref/fb/gamedatacontainer))

Casts an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer) to [OBBData](/vext/ref/fb/obbdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [GameDataContainer](/vext/ref/fb/gamedatacontainer) | The instance to cast to [OBBData](/vext/ref/fb/obbdata). |

### OBBData {#constructor-5}

> **OBBData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [OBBData](/vext/ref/fb/obbdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [OBBData](/vext/ref/fb/obbdata). |

## Properties

### {{% prop-heading "transform" %}}

> **[LinearTransform](/vext/ref/shared/type/lineartransform)**

### {{% prop-heading "halfExtents" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [OBBData](/vext/ref/fb/obbdata) type.

