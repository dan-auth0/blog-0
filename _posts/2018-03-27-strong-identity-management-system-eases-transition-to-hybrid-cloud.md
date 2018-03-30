---
layout: post
title: "How a Strong Identity Management System Can Ease Your Transition to the Hybrid Cloud"
description: "With hybrid cloud deployment becoming popular, keeping tight control on authentication and authorization has become essential."
date: 2018-03-27 8:30
category: Growth, Identity, Trends
design:: 
  bg_color: "#1A1A1A"
  image: 
author:
  name: 
  url:
  mail:
  avatar: 
tags: 
  - hybrid-cloud
  - cloud
  - identity-management
  - enterprise
  - tracking
related:
  - 2018-03-28-security-vs-convenience
  - 2018-03-16-identity-as-a-service-in-2018
  - 2017-12-08-how-poor-identity-access-management-equals-security-breaches
---


The ability to clearly observe, track, and log in as your authorized users allows for the swift implementation of updates and early alerts of any suspicious behavior.

Moving to a hybrid cloud model is the first step that many companies take when undergoing a digital transformation. Less expensive and resource-intense than a full private cloud option — yet still providing an extra measure of security, compared with the public cloud — hybrid deployment has become [highly popular](https://assets.rightscale.com/uploads/pdfs/RightScale-2017-State-of-the-Cloud-Report.pdf) among tech professionals.

Yet once you migrate to a hybrid cloud model, it can become increasingly difficult to keep track of your users. Previously, your team likely conducted critical tasks on-premises. Now, with the opportunity for multiple users to log in and work with sensitive data from a range of locations and devices, keeping tabs on authentications (who has signed in) and authorizations (who has permission to use private resources) becomes essential. 

A clear identity management system can help your team organize user information in a way that makes it easy for administrators to have a birds-eye view of actions taking place and make quick changes if need be. You can build this yourself or outsource your identity and access management (IAM) needs to ensure they are professional, up-to-date, and don't cause additional security concerns. 

## Track Your Users in the Hybrid Cloud 

A robust IAM strategy can show you who is currently logged into your network. Having the full picture is essential to staying organized and rooting out any suspicious activity. For example, Auth0 provides a simple, efficient [dashboard](https://auth0.com/user-management) to centralize a range of user interface tools.

<p style="text-align: center;">
  <img src="https://cdn.auth0.com/blog/strong-identity-management-system-eases-transition-to-hybrid-cloud/permissions.png" alt="Define permissions for your application">
</p>

With this, an administrator is able to view all current users, their locations, login history, and additional personal information. From here administrators are able to supervise password resets, block and delete users, and perform a range of other tasks.

After granting a new member access, the administrator can simply add a user and create his or her profile, populating it with further details:

<p style="text-align: center;">
  <img src="https://cdn.auth0.com/blog/strong-identity-management-system-eases-transition-to-hybrid-cloud/matias.png" alt="Device list for a particular user">
</p>

The above profile breaks down all devices the administrator has authorized for this particular user. This allows the administrator to confirm that the user is accessing any private data from an approved source. If the administrator has any questions about a user's behavior, he or she may unlink a particular device at any time.


{% include tweet_quote.html quote_text="A robust IAM strategy can show you who is currently logged into your network. Having the full picture is essential to staying organized and rooting out any suspicious activity." %}

## Log In As an Individual User

Within a comprehensive IAM system, an administrator can also [impersonate a user](https://auth0.com/docs/user-profile/user-impersonation), allowing him or her to better understand and/or troubleshoot issues that might arise. For example, if a user reports a bug, but you aren't able to see the issue from your angle, you can:

1. Ask for further information, including a more detailed description and/or screenshots; or 
2. Expedite the process (particularly if the issue is critical) by logging in as the specific user and experiencing the problem yourself in order to create a targeted solution.

Using the Auth0 dashboard, you can easily select the user you want to log in as using the drop-down menu.

<p style="text-align: center;">
  <img src="https://cdn.auth0.com/blog/strong-identity-management-system-eases-transition-to-hybrid-cloud/userdetails.png" alt="Sign in as user drop-down">
</p>

While it's possible to construct a user impersonation feature on your own, the potential for [even more security complications](https://auth0.com/blog/how-not-to-troubleshoot-bugs-by-impersonating-users/) is high. As you shift your business to a hybrid cloud model, outsourcing this feature will ensure it is always up to date and doesn't cause additional problems. 

Auth0’s [Sign in As](https://auth0.com/how-it-works) feature, for example, includes:

* **Detailed auditing** of who impersonated a user when, which dissuades abuse.
* **Restrictions on impersonation,** which can help you comply with corporate policies around privacy and sensitive data.
* **Unlimited customization** on who can impersonate who and when, using the Auth0 [Rules engine](https://auth0.com/docs/rules), which allows you to write arbitrary Javascript to define the relationship between  `user.impersonated` (the impersonated login) and `user.impersonator` (the impersonating login).

An efficient user impersonation method can allow administrators to troubleshoot quickly and accurately, helping maintain company operations during a digital overhaul.

{% include tweet_quote.html quote_text="As you shift your business to a hybrid cloud model, outsourcing a user impersonation feature will ensure it's always up to date and doesn't cause additional problems, such as security complications." %}

## Restrict Access to Sensitive Documents

In the hybrid cloud, your workflow is split between confidential tasks in the private cloud and less sensitive ones in the public cloud. With a strong IAM system, you can allow access to private documents based on a user's ID. This can limit the amount of damage that can occur if someone's username or login details are stolen. IAM companies like Auth0 facilitate different permissions based on the user.

<p style="text-align: center;">
  <img src="https://cdn.auth0.com/blog/strong-identity-management-system-eases-transition-to-hybrid-cloud/userlist.png" alt="Auth0 users list">
</p>

To make the task more efficient, Auth0's [authorization extension](https://auth0.com/blog/announcing-authorization-extension-v2/) allows you to combine your users and give permission such as “approve:reports” to an entire group. As you can see above, several permissions can be created within each application, allowing administrators to assert control over nearly all actions taking place on their network.

Only a highly detailed identity management system will truly help you unlock the potential of the private portion of your hybrid cloud system.

## Conclusion: When to Shift to the Hybrid Cloud

While the hybrid cloud has enormous advantages, such as the ability to quickly scale alongside your growing company, it isn't appropriate for all organizations. Setting up your own servers on the private end of the hybrid cloud can be costly, hindering teams with small computing budgets. Major cloud service providers like [Amazon Web Services](https://aws.amazon.com/), [Google Cloud](https://cloud.google.com/), and [Microsoft Azure](https://azure.microsoft.com/en-us/) can offer a certain level of intrusion monitoring in a basic public cloud option, which can often provide enough security for smaller teams.

However, if your company has the funds, moving to the hybrid cloud can allow your most business-critical applications to remain behind an additional firewall. Creating or outsourcing a strong identity management system to better monitor and control your users in the hybrid cloud will open even further opportunities to fix bugs and root out unusual log-ins as your company continues to grow.