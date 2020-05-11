---
title: "DLP SDK | MicrosoftDocs"
description: Power Platform data loss prevention (DLP) SDK
author: jimholtz
manager: kvivek
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 05/11/2020
ms.author: jimholtz
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---
# Power Platform data loss prevention (DLP) SDK 

This topic introduces the capabilities of the DLP SDK and shows you how DLP can help you manage your tenant and environment policy with experiences ranging from creating, reading, updating, to removing DLP policies. More information : [Data loss prevention policies](wp-data-loss-prevention.md)

## How to run this sample

1. Download or clone the [Samples repo](https://github.com/microsoft/PowerApps-Samples/tree/master/powershell/admin-center) so that you have a local copy.

2. Open **PowerShell ISE** as an admin.

3. Run the following command:

    ```powershell
    Install-Module -Name Microsoft.PowerApps.Administration.PowerShell -Force
    ```

4. Edit RunSamples.ps1 and make the following changes:
   - Replace $TenantAdminName value with your tenant admin account
   - Replace $TenantAdminPassword value with your tenant admin account password
   - Replace $EnvironmentAdminName value with your environment admin account
   - Replace $EnvironmentAdminPassword value with your environment admin account password

5. Run RunSamples.ps1.

## What this sample does

This sample calls DLP APIs in Microsoft.PowerApps.Administration.PowerShell to create, read, update and remove DLP policies.

## How this sample works

This sample provides some DLP scenarios about how to call DLP APIs for your reference. You can run the sample and see the result.
