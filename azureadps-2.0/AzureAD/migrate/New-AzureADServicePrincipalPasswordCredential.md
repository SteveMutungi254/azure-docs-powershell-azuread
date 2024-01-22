---
title: New-AzureADServicePrincipalPasswordCredential
description: This article provides migration details from New-AzureADServicePrincipalPasswordCredential command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/20/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# New-AzureADServicePrincipalPasswordCredential

This article provides migration details from New-AzureADServicePrincipalPasswordCredential command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [New-AzureADServicePrincipalPasswordCredential](/powershell/module/azuread/new-azureadserviceprincipalpasswordcredential)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Add-MgServicePrincipalPassword](/powershell/module/microsoft.graph.applications/add-mgserviceprincipalpassword) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Add-MgServicePrincipalPassword))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint: POST /servicePrincipals/{servicePrincipal-id}/addPassword

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/serviceprincipal-addpassword-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|
|CustomKeyIdentifier||
|EndDate||
|StartDate||
|Value||