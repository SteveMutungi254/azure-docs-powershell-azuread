---
title: Get-AzureADServicePrincipalCreatedObject
description: This article provides migration details from Get-AzureADServicePrincipalCreatedObject command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADServicePrincipalCreatedObject

This article provides migration details from Get-AzureADServicePrincipalCreatedObject command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADServicePrincipalCreatedObject](/powershell/module/azuread/get-azureadserviceprincipalcreatedobject)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgServicePrincipalCreatedObject](/powershell/module/microsoft.graph.applications/get-mgserviceprincipalcreatedobject) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgServicePrincipalCreatedObject))
+ Graph Module: Microsoft.Graph.Applications
+ Graph Endpoint:  GET /servicePrincipals/{servicePrincipal-id}/createdObjects | /servicePrincipals/{servicePrincipal-id}/createdObjects/{directoryObject-id}

## Permissions

|Permission type      | Permissions (from least to most privileged)              |
|:--------------------|:---------------------------------------------------------|
|Delegated (work or school account) | Application.Read.All, Application.ReadWrite.All, Directory.Read.All, Directory.ReadWrite.All    |
|Delegated (personal Microsoft account) | Not supported.    |
|Application | Application.Read.All, Application.ReadWrite.All, Directory.Read.All, Directory.ReadWrite.All |

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|ObjectId|ServicePrincipalId|
|All|All|
|Top|Top|