# Azure Updates 09/2022 - Highlights

### API Management
##### General Availability

Azure API Management support for the MSAL authorization library is now generally available.
You can provide a more secure OAuth 2.0 authorization code flow using PKCE when implementing user sign-in and sign-up actions 
in the developer portal through Azure Active Directory and Azure Active Directory B2C.
 
Announcement: https://azure.microsoft.com/updates/generally-available-azure-api-management-support-for-msal-in-developer-portal/

Documentation: https://docs.microsoft.com/azure/api-management/api-management-howto-aad?WT.mc_id=wwc-aces#migrate-to-msal

---

### App Service

##### Preview Features

Azure App Configuration now supports replicating your configuration data in the configuration store to replicas in other Azure regions. 
Available to standard tier subscribers, any updates or additions to key/values in the configuration store or in a replica will be automatically synchronized,
using an eventual consistency model.

This delivers benefits including:
 - Increased resiliency:
   Replication across regions means that your configuration data will still be accessible should a service outage impact your store or 
   any one of the replicas.
 - Minimize latency – Now your applications can consume the data locally rather than issuing cross-region requests.
 - Optimize request distribution – Replicas and the configuration store have unique applicable request limits,
   enabling you to distribute requests efficiently to avoid exhausting the request limits on either the replicas or the configuration store.
   
Announcement: https://azure.microsoft.com/updates/public-preview-app-configuration-geo-replication-support/

Documentation: https://docs.microsoft.com/azure/azure-app-configuration/concept-geo-replication?WT.mc_id=wwc-aces

---

### Container Apps

##### Updated Features

Azure Container Apps (ACA) support for Dapr release 1.8.3 is now generally available.
All Container App Environments have been automatically upgraded to consume 1.8.3

Dapr v1.8 release notes: https://github.com/dapr/dapr/releases/tag/v1.8.0

Announcement: https://azure.microsoft.com/updates/general-availability-dapr-release-18-support-in-azure-container-apps/

Documentation: https://docs.microsoft.com/azure/container-apps/dapr-overview?tabs=bicep1%2Cyaml?WT.mc_id=wwc-aces

---

### Azure Regions

##### Region Updates

- 3 Availability Zones in UAE North
- New region: Qatar (with AZs)

Announcements: 
https://azure.microsoft.com/updates/generally-available-uae-north-availability-zones/
https://azure.microsoft.com/updates/general-availability-microsoft-azure-available-from-new-cloud-region-in-qatar/
              
Documentation: https://news.microsoft.com/en-xm/2022/08/23/microsoft-launches-azure-availability-zones-to-heighten-competitiveness-of-uae-organizations/