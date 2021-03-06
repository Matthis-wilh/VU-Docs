---
title: AILocoCoverBinding
---

## Summary

### Constructors

|  |
| --- |
| **[AILocoCoverBinding](#constructor-0)**() |
| **[AILocoCoverBinding](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "prepareFire" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "throwGrenade" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "peekOut" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "idleBehindCover" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "peekType" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "coverTypeEnum" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "coverFireStyle" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "enterCover" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "exitCover" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "isCloseCover" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "distanceScale" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "absoluteDistance" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "angleToNormal" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "outAngle" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "threatAngle" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "stopExitCoverOutAround" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "enterStrategy" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "exitStyle" >}} | [AntRef](/vext/ref/fb/antref) |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [AILocoCoverBinding](/vext/ref/fb/ailococoverbinding) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "AILocoCoverBinding" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### AILocoCoverBinding {#constructor-0}

> **AILocoCoverBinding**()

Creates a new [AILocoCoverBinding](/vext/ref/fb/ailococoverbinding) frostbite instance.

### AILocoCoverBinding {#constructor-1}

> **AILocoCoverBinding**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [AILocoCoverBinding](/vext/ref/fb/ailococoverbinding) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "prepareFire" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "throwGrenade" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "peekOut" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "idleBehindCover" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "peekType" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "coverTypeEnum" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "coverFireStyle" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "enterCover" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "exitCover" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "isCloseCover" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "distanceScale" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "absoluteDistance" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "angleToNormal" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "outAngle" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "threatAngle" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "stopExitCoverOutAround" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "enterStrategy" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "exitStyle" %}}

> **[AntRef](/vext/ref/fb/antref)**

## Methods

### Clone {#clone}

> **Clone**(): [AILocoCoverBinding](/vext/ref/fb/ailococoverbinding)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[AILocoCoverBinding](/vext/ref/fb/ailococoverbinding)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [AILocoCoverBinding](/vext/ref/fb/ailococoverbinding) type.

