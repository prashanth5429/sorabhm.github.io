---
layout: post
title: Speaking the same language
hide: true
feature-img: assets/img/pexels/book-coffee.webp
author: sorabhm
tags: [Glossary, Azure, Terminology]
---

There is a proverb "When in Rome, do as Romans do", the phrase means that it is advisable to follow the conventions of the area in which you are residing or visiting. And communication is an important aspect, but to understand and convey your thoughts clearly you need to speak the same language they do.

Below table categorises and provides the common terms used on Azure Platform, which you must understand while you are learning. This is an evergrowing list and I will try to maintain it going forward.

Term or concept | Description
--------------- | ------------
Identity | A thing that can get authenticated. An identity can be a user with a username and password. Identities also include applications or other servers that might require authentication through secret keys or certificates.
Account | An identity that has data associated with it. You cannot have an account without an identity.
Azure AD account | An identity created through Azure AD or another Microsoft cloud service, such as Office 365. Identities are stored in Azure AD and accessible to your organization's cloud service subscriptions. This account is also sometimes called a Work or school account.
Azure subscription | Used to pay for Azure cloud services. You can have many subscriptions and they're linked to a credit card.
Azure tenant | A dedicated and trusted instance of Azure AD that's automatically created when your organization signs up for a Microsoft cloud service subscription, such as Microsoft Azure, Microsoft Intune, or Office 365. An Azure tenant represents a single organization.
Single tenant | Azure tenants that access other services in a dedicated environment are considered single tenant.
Multi-tenant | Azure tenants that access other services in a shared environment, across multiple organizations, are considered multi-tenant.
Azure AD directory | Each Azure tenant has a dedicated and trusted Azure AD directory. The Azure AD directory includes the tenant's users, groups, and apps and is used to perform identity and access management functions for tenant resources.
Custom domain | Every new Azure AD directory comes with an initial domain name, domainname.onmicrosoft.com. In addition to that initial name, you can also add your organization's domain names, which include the names you use to do business and your users use to access your organization's resources, to the list. Adding custom domain names helps you to create user names that are familiar to your users, such as alain@contoso.com.
Account Administrator | This classic subscription administrator role is conceptually the billing owner of a subscription. This role has access to the Azure Account Center and enables you to manage all subscriptions in an account. For more information, see Classic subscription administrator roles, Azure Role-based access control (RBAC) roles, and Azure AD administrator roles.
Service Administrator | This classic subscription administrator role enables you to manage all Azure resources, including access. This role has the equivalent access of a user who is assigned the Owner role at the subscription scope. For more information, see Classic subscription administrator roles, Azure RBAC roles, and Azure AD administrator roles.
Owner | This role helps you manage all Azure resources, including access. This role is built on a newer authorization system called role-base access control (RBAC) that provides fine-grained access management to Azure resources. For more information, see Classic subscription administrator roles, Azure RBAC roles, and Azure AD administrator roles.
Azure AD Global administrator | This administrator role is automatically assigned to whomever created the Azure AD tenant. Global administrators can do all of the administrative functions for Azure AD and any services that federate to Azure AD, such as Exchange Online, SharePoint Online, and Skype for Business Online. You can have multiple Global administrators, but only Global administrators can assign administrator roles (including assigning other Global administrators) to users.
VNet | Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. A Virtual Network (VNet) is a logical representation of your network in the cloud. It allows you to define your own private IP address space and segment the network into subnets.
Region | A set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.
Geography | An area of the world containing at least one Azure region. Geographies define a discrete market that preserve data residency and compliance boundaries. Geographies allow customers with specific data-residency and compliance needs to keep their data and applications close. Geographies are fault-tolerant to withstand complete region failure through their connection to our dedicated high-capacity networking infrastructure.
Availability Zone | Unique physical locations within a region. Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking.
recommended region | A region that provides the broadest range of service capabilities and is designed to support Availability Zones now, or in the future. These are designated in the Azure portal as Recommended.
alternate (other) region | A region that extends Azure's footprint within a data residency boundary where a recommended region also exists. Alternate regions help to optimize latency and provide a second region for disaster recovery needs. They are not designed to support Availability Zones (although Azure conducts regular assessment of these regions to determine if they should become recommended regions). These are designated in the Azure portal as Other.
foundational service | A core Azure service that is available in all regions when the region is generally available.
mainstream service | An Azure service that is available in all recommended regions within 12 months of the region/service general availability or demand-driven availability in alternate regions.
specialized service | An Azure service that is demand-driven availability across regions backed by customized/specialized hardware.
resource | A manageable item that is available through Azure. Virtual machines, storage accounts, web apps, databases, and virtual networks are examples of resources. Resource groups, subscriptions, management groups, and tags are also examples of resources.
resource group | A container that holds related resources for an Azure solution. The resource group includes those resources that you want to manage as a group. You decide which resources belong in a resource group based on what makes the most sense for your organization. See Resource groups.
resource provider | A service that supplies Azure resources. For example, a common resource provider is Microsoft.Compute, which supplies the virtual machine resource. Microsoft.Storage is another common resource provider. See Resource providers and types.
Resource Manager template | A JavaScript Object Notation (JSON) file that defines one or more resources to deploy to a resource group, subscription, management group, or tenant. The template can be used to deploy the resources consistently and repeatedly. See Template deployment overview.
declarative syntax | Syntax that lets you state "Here is what I intend to create" without having to write the sequence of programming commands to create it. The Resource Manager template is an example of declarative syntax.
Service Principal | An Azure service principal is an identity created for use with applications, hosted services, and automated tools to access Azure resources. This access is restricted by the roles assigned to the service principal, giving you control over which resources can be accessed and at which level. For security reasons, it's always recommended to use service principals with automated tools rather than allowing them to log in with a user identity.
Managed Identity | Managed identities for Azure resources is a feature of Azure Active Directory. It provides Azure services with an automatically managed identity in Azure Active Directory. You can use this identity to authenticate to any service that supports Azure AD authentication, without having credentials in your code.

#SM