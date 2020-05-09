---
layout: post
title: Getting into the act - Enterprise Portal Account
hide: true
feature-img: assets/img/pexels/computer.jpeg
author: sorabhm
tags: [Enterprise Account, Azure, Blueprint, Governance, Cloud Guild, Landing Zone]
---

Let's focus on what WebArachnids have been doing during the "Plan" stage. They have already established different business groups with a key focus on the preparation of a functional stories backlog. The technical teams on the other hand have started playing with Microsoft Azure free accounts and trying to map the Digital inventory with the respective services in Azure.

Following the footsteps of some bigger enterprises in the region, e.g. NAB/KMart/Target they have started a Cloud guild model internally. To learn more on what [NAB Cloud Guild](https://medium.com/@nabtechblog/how-the-nab-cloud-guild-was-built-14c00f57a604){:target="_blank"} is read here.
You may ask is it necessary for every organisation to follow this model? I would say no, the main perspective behind this was to fill the skillset gaps and investing in your own employees. Learning relevant skills will help the scrum teams to understand and speak the common Cloud terminologies, complexities they may face during the implementation, and build a secure and production quality platform.

In the meanwhile, given the focus on Time to market, the leadership team have partnered with Microsoft for the migration project and helping the technical teams setup the **Landing Zone**. But the first thing WebArachnids require is an Enterprise Portal Account. Any organisation planning to use Microsoft Azure services, need to sign an Enterprise Customer agreement and setup an enterprise account. You can find more about [Enterprise account](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/ea-portal-get-started){:target="_blank"}

In my earlier post ["The first steps"](../02/The-first-steps.html){:target="_blank"}, you might have observed that "Governance" & "Manage" phase spans across other stages. Cloud Governance and Management is an iterative process, the traditional policies and processes have to be rethink and modified. Let's take an example of Enterprise account, for better management there are few recommended hierarchies which can be setup.

![Enterprise Portal Account]({{ "/assets/img/ea-hierarchies.png" | relative_url }})
_Image Credits: [Microsoft Docs](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/ea-portal-get-started)_{:target="_blank"}

Each hierarchy level acts like a logical container, it helps you

* assign roles
* manage billing/invoicing for different projects or departments
* control and add policies, say you want to control on what types of VMs a non-prod project can use
* define and assign Blueprints

![Enterprise Portal Account]({{ "/assets/img/Azure-MgmtGroup-Blueprint.png" | relative_url }})
_Image Credits: [Steve Buchanan Blog](http://www.buchatech.com/2018/09/architect-your-cloud-with-azure-blueprints/)_

Just to get you started Blueprints are a declarative way to orchestrate the deployment of various resource templates and other artifacts such as:

* Role Assignments
* Policy Assignments
* Azure Resource Manager templates
* Resource Groups

They enables Architects/Administrators to define/deploy a repeatable set of resources following the same compliance standards. We will cover these in detail during Security learning path. Consider this as a beginning of Security baselining of the policies which will be reviewed during the migration phase.

Go through the EA Portal setup and the terminologies [here](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/ea-portal-get-started){:target="_blank"}. We will cover **Landing Zone** in our next post.

#SM