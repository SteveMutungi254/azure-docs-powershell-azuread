---
title: Get-AzureADOAuth2PermissionGrant
description: This article provides migration details from Get-AzureADOAuth2PermissionGrant command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADOAuth2PermissionGrant

This article provides migration details from Get-AzureADOAuth2PermissionGrant command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADOAuth2PermissionGrant](/powershell/module/azuread/get-azureadoauth2permissiongrant)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgOauth2PermissionGrant](/powershell/module/microsoft.graph.identity.signins/get-mgoauth2permissiongrant) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgOauth2PermissionGrant))
+ Graph Module: Microsoft.Graph.Identity.SignIns
+ Graph Endpoint:  GET /oauth2PermissionGrants | /oauth2PermissionGrants/{oAuth2PermissionGrant-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/oauth2permissiongrant-get-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|All|All|
|Top|Top|