---
title: .alter-merge cluster policy request classification command- Azure Data Explorer
description: This article describes the .alter-merge cluster policy request classification command in Azure Data Explorer.
services: data-explorer
author: orspod
ms.author: orspodek
ms.reviewer: yonil
ms.service: data-explorer
ms.topic: reference
ms.date: 09/26/2021
---
# .alter-merge cluster request classification policy

Enables or disables a cluster's request classification policy. For more information, see [Request classification policy](request-classification-policy.md)).

## Syntax

`.alter-merge` `cluster` `policy` `request_classification` `"`*Serialized partial policy*`"`

### Examples

### Enable the policy

```kusto
.alter-merge cluster policy request_classification '{"IsEnabled":true}'
```

### Disable the policy

```kusto
.alter-merge cluster policy request_classification '{"IsEnabled":false}'
```
