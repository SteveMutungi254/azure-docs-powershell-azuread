---
title: Remove-AzureADServicePrincipalKeyCredential
description: This article provides migration details from Remove-AzureADServicePrincipalKeyCredential command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 12/17/2023
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Remove-AzureADServicePrincipalKeyCredential

This article provides migration details from Remove-AzureADServicePrincipalKeyCredential command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Remove-AzureADServicePrincipalKeyCredential](/powershell/module/azuread/remove-azureadserviceprincipalkeycredential)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Remove-MgServicePrincipalKey](/powershell/module/microsoft.graph.applications/remove-mgserviceprincipalkey) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Remove-MgServicePrincipalKey))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  DELETE /oauth2PermissionGrants/{oAuth2PermissionGrant-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/permissions/serviceprincipal-removekey-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|
|KeyId|KeyId|