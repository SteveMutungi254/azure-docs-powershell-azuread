---
title: Get-AzureADMSServicePrincipalDelegatedPermissionClassification
description: This article provides migration details from Get-AzureADMSServicePrincipalDelegatedPermissionClassification command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADMSServicePrincipalDelegatedPermissionClassification

This article provides migration details from Get-AzureADMSScopedRoleMembership command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADMSServicePrincipalDelegatedPermissionClassification](/powershell/module/azuread/get-azureadmsserviceprincipaldelegatedpermissionclassification)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgServicePrincipalDelegatedPermissionClassification](/powershell/module/microsoft.graph.applications/get-mgserviceprincipaldelegatedpermissionclassification) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgServicePrincipalDelegatedPermissionClassification))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  GET /servicePrincipals/{servicePrincipal-id}/delegatedPermissionClassifications | /servicePrincipals/{servicePrincipal-id}/delegatedPermissionClassifications/{delegatedPermissionClassification-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/serviceprincipal-list-delegatedpermissionclassifications-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|Filter|Filter|
|Id|DelegatedPermissionClassificationId|
|ServicePrincipalId|ServicePrincipalId|