---
title: Get-AzureADServicePrincipalMembership
description: This article provides migration details from Get-AzureADServicePrincipalMembership command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADServicePrincipalMembership

This article provides migration details from Get-AzureADServicePrincipalMembership command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADServicePrincipalMembership](/powershell/module/azuread/get-azureadserviceprincipalmembership)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgServicePrincipalTransitiveMemberOf](/powershell/module/microsoft.graph.applications/get-mgserviceprincipaltransitivememberof) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgServicePrincipalTransitiveMemberOf))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  GET /servicePrincipals/{servicePrincipal-id}/transitiveMemberOf | /servicePrincipals/{servicePrincipal-id}/transitiveMemberOf/{directoryObject-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/serviceprincipal-list-transitivememberof-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|