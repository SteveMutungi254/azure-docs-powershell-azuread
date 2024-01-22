---
title: Remove-AzureADTrustedCertificateAuthority
description: This article provides migration details from Remove-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/17/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# Remove-AzureADTrustedCertificateAuthority

This article provides migration details from Remove-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [Remove-AzureADTrustedCertificateAuthority](/powershell/module/azuread/remove-azureadtrustedcertificateauthority)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [Remove-MgOrganizationCertificateBasedAuthConfiguration](/powershell/module/microsoft.graph.identity.signins/remove-mgorganizationcertificatebasedauthconfiguration) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Remove-MgOrganizationCertificateBasedAuthConfiguration))
+ Graph Module: Microsoft.Graph.Identity.SignIns
+ Graph Endpoint:  DELETE /organization/{id}/certificateBasedAuthConfiguration/{id}

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/permissions/certificatebasedauthconfiguration-delete-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|CertificateAuthorityInformation||
|NA|CertificateBasedAuthConfigurationId|
|NA|OrganizationId|