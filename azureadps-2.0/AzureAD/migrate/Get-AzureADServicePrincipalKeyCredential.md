---
title: Get-AzureADServicePrincipalKeyCredential
description: This article provides migration details from Get-AzureADServicePrincipalKeyCredential command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADServicePrincipalKeyCredential

This article provides migration details from Get-AzureADServicePrincipalKeyCredential command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADServicePrincipalKeyCredential](/powershell/module/azuread/get-azureadserviceprincipalkeycredential)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgServicePrincipal](/powershell/module/microsoft.graph.applications/get-mgserviceprincipal) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgServicePrincipal))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  GET /servicePrincipals | /servicePrincipals/{servicePrincipal-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/serviceprincipal-get-permissions.md)]

View more [details on permissions](/graph/api/serviceprincipal-get#permissions).

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|