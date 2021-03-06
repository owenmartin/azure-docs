---
title: Security controls for Azure Event Hubs
description: A checklist of security controls for evaluating Azure Event Hubs
services: event-hubs
ms.service: event-hubs
author: spelluru

ms.topic: conceptual
ms.date: 09/23/2019
ms.author: spelluru

---
# Security controls for Azure Event Hubs

This article documents the security controls built into Azure Event Hubs.

[!INCLUDE [Security controls Header](../../includes/security-controls-header.md)]

## Network

| Security control | Yes/No | Notes | Documentation |
|---|---|--|--|
| Service endpoint support| Yes |  |  |
| VNet injection support| No | |  |
| Network isolation and firewalling support| Yes |  |  |
| Forced tunneling support| No |  |  |

## Monitoring & logging

| Security control | Yes/No | Notes| Documentation |
|---|---|--|--|
| Azure monitoring support (Log analytics, App insights, etc.)| Yes | |  |
| Control and management plane logging and audit| Yes |  |  |
| Data plane logging and audit| Yes |   |  |

## Identity

| Security control | Yes/No | Notes| Documentation |
|---|---|--|--|
| Authentication| Yes | | [Authorize access to Azure Event Hubs](authorize-access-event-hubs.md), [Authorize access to Event Hubs resources using Azure Active Directory](authorize-access-azure-active-directory.md), [Authorizing access to Event Hubs resources using Shared Access Signatures](authorize-access-shared-access-signature.md) |
| Authorization|  Yes | | [Authenticate a managed identity with Azure Active Directory to access Event Hubs Resources](authenticate-managed-identity.md), [Authenticate an application with Azure Active Directory to access Event Hubs resources](authenticate-application.md), [Authenticate access to Event Hubs resources using shared access signatures (SAS)](authenticate-shared-access-signature.md) |

## Data protection

| Security control | Yes/No | Notes | Documentation |
|---|---|--|--|
| Server-side encryption at rest: Microsoft-managed keys |  Yes | |  |
| Server-side encryption at rest: customer-managed keys (BYOK) | No |  |  |
| Column level encryption (Azure Data Services)| N/A | |  |
| Encryption in transit (such as ExpressRoute encryption, in VNet encryption, and VNet-VNet encryption)| Yes | |  |
| API calls encrypted| Yes |  |  |

## Configuration management

| Security control | Yes/No | Notes| Documentation |
|---|---|--|--|
| Configuration management support (versioning of configuration, etc.)| Yes | |  |

## Next steps

- Learn more about the [built-in security controls across Azure services](../security/fundamentals/security-controls.md).
