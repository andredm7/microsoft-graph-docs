---
title: "Get telephoneNumberManagementRoot"
description: "Read the properties and relationships of microsoft.graph.teamsAdministration.telephoneNumberManagementRoot object."
author: "pavellatif"
ms.date: 07/23/2025
ms.localizationpriority: medium
ms.subservice: "teams"
doc_type: apiPageType
---

# Get telephoneNumberManagementRoot

Namespace: microsoft.graph.teamsAdministration

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of [microsoft.graph.teamsAdministration.telephoneNumberManagementRoot](../resources/teamsadministration-telephonenumbermanagementroot.md) object.

## Permissions

Choose the permission or permissions marked as least privileged for this API. Use a higher privileged permission or permissions [only if your app requires it](/graph/permissions-overview#best-practices-for-using-microsoft-graph-permissions). For details about delegated and application permissions, see [Permission types](/graph/permissions-overview#permission-types). To learn more about these permissions, see the [permissions reference](/graph/permissions-reference).

<!-- {
  "blockType": "permissions",
  "name": "teamsadministration-telephonenumbermanagementroot-get-permissions"
}
-->
[!INCLUDE [permissions-table](../includes/permissions/teamsadministration-telephonenumbermanagementroot-get-permissions.md)]

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /admin/teams/telephoneNumberManagement
```

## Optional query parameters

This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers

|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required. Learn more about [authentication and authorization](/graph/auth/auth-concepts).|

## Request body

Don't supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [microsoft.graph.teamsAdministration.telephoneNumberManagementRoot](../resources/teamsadministration-telephonenumbermanagementroot.md) object in the response body.

## Examples

### Request

The following example shows a request.
<!-- {
  "blockType": "request",
  "name": "get_telephonenumbermanagementroot"
}
-->
``` http
GET https://graph.microsoft.com/beta/admin/teams/telephoneNumberManagement
```


### Response

The following example shows the response.
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.teamsAdministration.telephoneNumberManagementRoot"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.teamsAdministration.telephoneNumberManagementRoot",
    "id": "6457f48a-3688-7ab7-51df-e716ef0c3445"
  }
}
```

