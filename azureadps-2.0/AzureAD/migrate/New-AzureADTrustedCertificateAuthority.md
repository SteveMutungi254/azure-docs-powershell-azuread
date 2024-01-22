---
title: New-AzureADTrustedCertificateAuthority
description: This article provides migration details from New-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

ms.service: active-directory
ms.topic: reference
ms.date: 01/20/2024
ms.author: eunicewaweru
manager: CelesteDG
author: msewaweru
ms.reviewer: stevemutungi
---

# New-AzureADTrustedCertificateAuthority

This article provides migration details from New-AzureADTrustedCertificateAuthority command to Microsoft Graph PowerShell.

## Summary

+ Azure AD Command: [New-AzureADTrustedCertificateAuthority](/powershell/module/azuread/new-azureadtrustedcertificateauthority)
+ Azure AD Module: AzureAD
+ Microsoft Graph Command: [New-MgOrganizationCertificateBasedAuthConfiguration](/powershell/module/microsoft.graph.identity.signins/new-mgorganizationcertificatebasedauthconfiguration) ([Community Examples](https://github.com/orgs/msgraph/discussions?discussions_q=New-MgOrganizationCertificateBasedAuthConfiguration))
+ Graph Module: Microsoft.Graph.Identity.SignIns
+ Graph Endpoint: POST /organization/{id}/certificateBasedAuthConfiguration

## Permissions

[!INCLUDE [permissions-table](~/graphref/api-reference/v1.0/includes/permissions/certificatebasedauthconfiguration-post-certificatebasedauthconfiguration-permissions.md)]

## Property Mapping

|Azure AD Name|Microsoft Graph Name|
|---|---|
|CertificateAuthorityInformation (AuthorityType,CrlDistributionPoint,DeltaCrlDistributionPoint,TrustedCertificate)|certificateAuthority (certificate,certificateRevocationListUrl,deltaCertificateRevocationListUrl,isRootAuthority,issuer,issuerSki)|

> [!NOTE]
> You can also the [API details](/graph/api/certificatebasedauthconfiguration-post-certificatebasedauthconfiguration) for more information.