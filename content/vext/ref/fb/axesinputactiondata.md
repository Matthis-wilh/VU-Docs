---
title: AxesInputActionData
---

Inherits from [InputActionData](/vext/ref/fb/inputactiondata)

## Summary

### Constructors

|  |
| --- |
| **[AxesInputActionData](#constructor-0)**() |
| **[AxesInputActionData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[AxesInputActionData](#constructor-2)**(other: [InputActionData](/vext/ref/fb/inputactiondata)) |
| **[AxesInputActionData](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "axis" >}} | [InputDeviceAxes](/vext/ref/fb/inputdeviceaxes) |
| {{< prop "normalizeInput" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "AxesInputActionData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### AxesInputActionData {#constructor-0}

> **AxesInputActionData**()

Creates a new [AxesInputActionData](/vext/ref/fb/axesinputactiondata) frostbite instance.

### AxesInputActionData {#constructor-1}

> **AxesInputActionData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [AxesInputActionData](/vext/ref/fb/axesinputactiondata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### AxesInputActionData {#constructor-2}

> **AxesInputActionData**(other: [InputActionData](/vext/ref/fb/inputactiondata))

Casts an instance of type [InputActionData](/vext/ref/fb/inputactiondata) to [AxesInputActionData](/vext/ref/fb/axesinputactiondata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [InputActionData](/vext/ref/fb/inputactiondata) | The instance to cast to [AxesInputActionData](/vext/ref/fb/axesinputactiondata). |

### AxesInputActionData {#constructor-3}

> **AxesInputActionData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [AxesInputActionData](/vext/ref/fb/axesinputactiondata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [AxesInputActionData](/vext/ref/fb/axesinputactiondata). |

## Properties

### {{% prop-heading "axis" %}}

> **[InputDeviceAxes](/vext/ref/fb/inputdeviceaxes)**

### {{% prop-heading "normalizeInput" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [AxesInputActionData](/vext/ref/fb/axesinputactiondata) type.

