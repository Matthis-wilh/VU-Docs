---
title: EnlightenDbSystem
---

## Summary

### Constructors

|  |
| --- |
| **[EnlightenDbSystem](#constructor-0)**() |
| **[EnlightenDbSystem](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "boundingBox" >}} | [AxisAlignedBox](/vext/ref/shared/type/axisalignedbox) |
| {{< prop "atlasStartX" >}} | int |
| {{< prop "atlasStartY" >}} | int |
| {{< prop "outputWidth" >}} | int |
| {{< prop "outputHeight" >}} | int |
| {{< prop "pixelCount" >}} | int |
| {{< prop "pixelSize" >}} | float |
| {{< prop "systemId" >}} | int |
| {{< prop "instances" >}} | [EnlightenDbInstance](/vext/ref/fb/enlightendbinstance)[] |
| {{< prop "inputSystems" >}} | int[] |
| {{< prop "systemCache" >}} | [PrecomputeCache](/vext/ref/fb/precomputecache) |
| {{< prop "clusteringCache" >}} | [PrecomputeCache](/vext/ref/fb/precomputecache) |
| {{< prop "preClusteringCache" >}} | [PrecomputeCache](/vext/ref/fb/precomputecache) |
| {{< prop "lightTransportCache" >}} | [PrecomputeCache](/vext/ref/fb/precomputecache) |
| {{< prop "visibilityCache" >}} | [PrecomputeCache](/vext/ref/fb/precomputecache) |
| {{< prop "terrainSystem" >}} | bool |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [EnlightenDbSystem](/vext/ref/fb/enlightendbsystem) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "EnlightenDbSystem" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### EnlightenDbSystem {#constructor-0}

> **EnlightenDbSystem**()

Creates a new [EnlightenDbSystem](/vext/ref/fb/enlightendbsystem) frostbite instance.

### EnlightenDbSystem {#constructor-1}

> **EnlightenDbSystem**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [EnlightenDbSystem](/vext/ref/fb/enlightendbsystem) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "boundingBox" %}}

> **[AxisAlignedBox](/vext/ref/shared/type/axisalignedbox)**

### {{% prop-heading "atlasStartX" %}}

> **int**

### {{% prop-heading "atlasStartY" %}}

> **int**

### {{% prop-heading "outputWidth" %}}

> **int**

### {{% prop-heading "outputHeight" %}}

> **int**

### {{% prop-heading "pixelCount" %}}

> **int**

### {{% prop-heading "pixelSize" %}}

> **float**

### {{% prop-heading "systemId" %}}

> **int**

### {{% prop-heading "instances" %}}

> **[EnlightenDbInstance](/vext/ref/fb/enlightendbinstance)**[]

### {{% prop-heading "inputSystems" %}}

> **int**[]

### {{% prop-heading "systemCache" %}}

> **[PrecomputeCache](/vext/ref/fb/precomputecache)**

### {{% prop-heading "clusteringCache" %}}

> **[PrecomputeCache](/vext/ref/fb/precomputecache)**

### {{% prop-heading "preClusteringCache" %}}

> **[PrecomputeCache](/vext/ref/fb/precomputecache)**

### {{% prop-heading "lightTransportCache" %}}

> **[PrecomputeCache](/vext/ref/fb/precomputecache)**

### {{% prop-heading "visibilityCache" %}}

> **[PrecomputeCache](/vext/ref/fb/precomputecache)**

### {{% prop-heading "terrainSystem" %}}

> **bool**

## Methods

### Clone {#clone}

> **Clone**(): [EnlightenDbSystem](/vext/ref/fb/enlightendbsystem)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[EnlightenDbSystem](/vext/ref/fb/enlightendbsystem)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [EnlightenDbSystem](/vext/ref/fb/enlightendbsystem) type.

