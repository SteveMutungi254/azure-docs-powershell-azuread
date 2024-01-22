---
title: Remove-AzureADMSServicePrincipalDelegatedPermissionClassification
description: This article provides migration details from Remove-AzureADMSServicePrincipalDelegatedPermissionClassification command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 12/17/2023
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Remove-AzureADMSServicePrincipalDelegatedPermissionClassification

This article provides migration details from Remove-AzureADMSServicePrincipalDelegatedPermissionClassification command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Remove-AzureADMSServicePrincipalDelegatedPermissionClassification](/powershell/module/azuread/remove-azureadmsserviceprincipaldelegatedpermissionclassification)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Remove-MgServicePrincipalDelegatedPermissionClassification](/powershell/module/microsoft.graph.applications/remove-mgserviceprincipaldelegatedpermissionclassification) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Remove-MgServicePrincipalDelegatedPermissionClassification))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  DELETE /servicePrincipals/{servicePrincipal-id}/delegatedPermissionClassifications/{delegatedPermissionClassification-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/serviceprincipal-delete-delegatedpermissionclassifications-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|Id|DelegatedPermissionClassificationId|
|ServicePrincipalId|ServicePrincipalId|