---
title: Remove-AzureADOAuth2PermissionGrant
description: This article provides migration details from Remove-AzureADOAuth2PermissionGrant command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 12/17/2023
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Remove-AzureADOAuth2PermissionGrant

This article provides migration details from Remove-AzureADOAuth2PermissionGrant command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Remove-AzureADOAuth2PermissionGrant](/powershell/module/azuread/remove-azureadoauth2permissiongrant)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Remove-MgOauth2PermissionGrant](/powershell/module/microsoft.graph.identity.signins/remove-mgoauth2permissiongrant) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Remove-MgOauth2PermissionGrant))
+ Graph Module: Microsoft.Graph.Identity.SignIns
+ Graph Endpoint:  DELETE /oauth2PermissionGrants/{oAuth2PermissionGrant-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/permissions/oauth2permissiongrant-delete-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|OAuth2PermissionGrantId|