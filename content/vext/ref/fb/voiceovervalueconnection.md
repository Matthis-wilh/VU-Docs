---
title: VoiceOverValueConnection
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[VoiceOverValueConnection](#constructor-0)**() |
| **[VoiceOverValueConnection](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[VoiceOverValueConnection](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "targetNode" >}} | [VoiceOverExpressionNode](/vext/ref/fb/voiceoverexpressionnode) \| nil |
| {{< prop "targetValue" >}} | [VoiceOverValue](/vext/ref/fb/voiceovervalue) \| nil |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "VoiceOverValueConnection" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### VoiceOverValueConnection {#constructor-0}

> **VoiceOverValueConnection**()

Creates a new [VoiceOverValueConnection](/vext/ref/fb/voiceovervalueconnection) frostbite instance.

### VoiceOverValueConnection {#constructor-1}

> **VoiceOverValueConnection**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [VoiceOverValueConnection](/vext/ref/fb/voiceovervalueconnection) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### VoiceOverValueConnection {#constructor-2}

> **VoiceOverValueConnection**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [VoiceOverValueConnection](/vext/ref/fb/voiceovervalueconnection). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [VoiceOverValueConnection](/vext/ref/fb/voiceovervalueconnection). |

## Properties

### {{% prop-heading "targetNode" %}}

> **[VoiceOverExpressionNode](/vext/ref/fb/voiceoverexpressionnode)** \| **nil**

### {{% prop-heading "targetValue" %}}

> **[VoiceOverValue](/vext/ref/fb/voiceovervalue)** \| **nil**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [VoiceOverValueConnection](/vext/ref/fb/voiceovervalueconnection) type.

