---
title: "deviceManagementSettingProfileConstraint resource type"
description: "Constraint enforcing a given profile metadata"
author: "dougeby"
localization_priority: Normal
ms.prod: "Intune"
doc_type: resourcePageType
---

# deviceManagementSettingProfileConstraint resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Constraint enforcing a given profile metadata


Inherits from [deviceManagementConstraint](../resources/intune-deviceintent-devicemanagementconstraint.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|source|String|The source of the entity|
|types|String collection|A collection of types this entity carries|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceManagementSettingProfileConstraint"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementSettingProfileConstraint",
  "source": "String",
  "types": [
    "String"
  ]
}
```


