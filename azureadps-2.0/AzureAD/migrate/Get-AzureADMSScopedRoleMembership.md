---
title: Get-AzureADMSScopedRoleMembership
description: This article provides migration details from Get-AzureADMSScopedRoleMembership command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADMSScopedRoleMembership

This article provides migration details from Get-AzureADMSScopedRoleMembership command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADMSScopedRoleMembership](/powershell/module/azuread/get-azureadmsscopedrolemembership)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgUserScopedRoleMemberOf](/powershell/module/microsoft.graph.identity.directorymanagement/get-mguserscopedrolememberof) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgUserScopedRoleMemberOf))
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement
+ Graph Endpoint:  GET /users/{user-id}/scopedRoleMemberOf | /users/{user-id}/scopedRoleMemberOf/{scopedRoleMembership-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/user-list-scopedrolememberof-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|Id|UserId|
|ScopedRoleMembershipId|ScopedRoleMembershipId|