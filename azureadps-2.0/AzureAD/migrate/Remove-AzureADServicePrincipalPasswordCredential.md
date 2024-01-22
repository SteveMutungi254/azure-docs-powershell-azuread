---
title: Remove-AzureADServicePrincipalPasswordCredential
description: This article provides migration details from Remove-AzureADServicePrincipalPasswordCredential command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/17/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Remove-AzureADServicePrincipalPasswordCredential

This article provides migration details from Remove-AzureADServicePrincipalPasswordCredential command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Remove-AzureADServicePrincipalPasswordCredential](/powershell/module/azuread/remove-azureadserviceprincipalpasswordcredential)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Remove-MgServicePrincipalPassword](/powershell/module/microsoft.graph.applications/remove-mgserviceprincipalpassword) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Remove-MgServicePrincipalPassword))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  DELETE /servicePrincipals/{servicePrincipal-id}/removePassword

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/permissions/serviceprincipal-removepassword-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|
|KeyId|KeyId|