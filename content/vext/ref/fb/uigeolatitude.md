---
title: UIGeoLatitude
---

## Summary

### Constructors

|  |
| --- |
| **[UIGeoLatitude](#constructor-0)**() |
| **[UIGeoLatitude](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "degrees" >}} | int |
| {{< prop "minuites" >}} | int |
| {{< prop "seconds" >}} | int |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [UIGeoLatitude](/vext/ref/fb/uigeolatitude) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIGeoLatitude" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIGeoLatitude {#constructor-0}

> **UIGeoLatitude**()

Creates a new [UIGeoLatitude](/vext/ref/fb/uigeolatitude) frostbite instance.

### UIGeoLatitude {#constructor-1}

> **UIGeoLatitude**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIGeoLatitude](/vext/ref/fb/uigeolatitude) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "degrees" %}}

> **int**

### {{% prop-heading "minuites" %}}

> **int**

### {{% prop-heading "seconds" %}}

> **int**

## Methods

### Clone {#clone}

> **Clone**(): [UIGeoLatitude](/vext/ref/fb/uigeolatitude)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[UIGeoLatitude](/vext/ref/fb/uigeolatitude)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIGeoLatitude](/vext/ref/fb/uigeolatitude) type.

