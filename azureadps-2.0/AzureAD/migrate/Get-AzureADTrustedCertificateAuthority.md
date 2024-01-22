---
title: Get-AzureADTrustedCertificateAuthority
description: This article provides migration details from Get-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/19/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Get-AzureADTrustedCertificateAuthority

This article provides migration details from Get-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Get-AzureADTrustedCertificateAuthority](/powershell/module/azuread/get-azureadtrustedcertificateauthority)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Get-MgOrganizationCertificateBasedAuthConfiguration](/powershell/module/microsoft.graph.identity.signins/get-mgorganizationcertificatebasedauthconfiguration) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgOrganizationCertificateBasedAuthConfiguration))
+ Graph Module: Microsoft.Graph.Identity.SignIns
+ Graph Endpoint:  GET /organization/{organization-id}/certificateBasedAuthConfiguration | /organization/{organization-id}/certificateBasedAuthConfiguration/{certificateBasedAuthConfiguration-id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/certificatebasedauthconfiguration-get-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|TrustedIssuer||
|TrustedIssuerSki||
||OrganizationId|