---
title: "Guidance to Business Testing (UAT Testing) during migration"
description: A process within Cloud Migration that focuses on the tasks of migrating workloads to the cloud
author: BrianBlanchard
ms.date: 4/4/2019
---

# Guidance to Business Testing (UAT Testing) during to migration

Traditionally seen as an IT function, User Acceptance Testing during a business transformation can be orchestrated solely by IT. However, this function is often most impactfully executed as a business function. IT then supports this business activity by facilitating the testing, developing testing plans, and automating tests when possible. While IT can often serve as a surrogate for testing, there is no replacement for first hand observation of real users attempting to leverage a new solution in the context of a real or replicated business process.

> [!NOTE]
> When available, automated testing is a much more effective and efficient means of testing any system. However, cloud migrations often focus most heavily on legacy systems or at least stable production systems. Often times, those systems aren't managed by thorough and well-maintained automated tests. This article assumes no such tests are available at the time of migration.

Second to automated testing, would be testing of the process and technology changes by power users. Power users are the people that commonly execute a real-world process that requires interactions with a technology tool or set of tools. Power users could be represented by an external customer using an e-commerce site to acquire goods or services. Power users could also be represented by a group of employees executing a business process, such as, a call center servicing customers and recording their experiences.

The goal of Business Testing is to solicit validation from Power Users to certify that the new solution performs inline with expectations and does not imped business processes. If that goal isn't met, the Business Testing serves as a feedback loop that can help define why & how the application isn't meeting expectations.

## Business Activities during Business Testing

During Business Testing, the first evolution of testing is manually driven directly with customers. This is the purest, but most time consuming form of feedback loop.

* Identify Power Users:The business generally has a better understanding of the power users that are most impacted by a technical change.
* Align & Prepare Power Users: Ensure power users understand the business objectives, desired outcomes, and expected changes to business processes. Prepare power users and their management structure for the testing process.
* Engage in Feedback Loop Interpretation: Help the IT staff understand the impact of various points of feedback from power users.
* Clarify Process Change: When transformation could trigger a change to business processes, communicate the change and any downstream impacts.
* Prioritize Feedback: Help the IT team prioritize feedback based on the business impact.

At times, Information Technology (IT) may employee analysts or product owners that can serve as proxies for the business testing activities above. However, business participation is highly encouraged and is likely to produce favorable business outcomes.

## IT Activities during Business Testing

IT serves as one of the recipients of the business testing output. The feedback loops exposed during business testing will eventually become work items that define technical change or process change. As a recipient, IT is expected to aid in facilitation, collection of feedback, and management of resultant technical actions. The activities IT performs during business testing are commonly as follows:

* Provide structure and logistics for business testing
* Aid in facilitation during testing
* Provide a means and process for recording feedback
* Help the business prioritize and validate feedback
* Develop plans for acting on technical changes
* Identify existing automated tests that could streamline the testing by Power Users
* For changes that could require repeated deployment or testing: Study testing processes, define benchmarks, and create automation to further streamline Power User Testing

## Next steps

In conjunction with business testing, [optimization of migrated assets](./optimize.md) can refine cost and workload performance.

> [!div class="nextstepaction"]
> [Optimize migrated assets](./optimize.md)