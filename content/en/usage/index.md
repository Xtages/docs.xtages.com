---
title: "Usage"
weight: 500
---

Go to the Account page to see usage statistics for the entire organization.

{{< respfig src="nav_menu.png" caption="Account link." >}}

In the Usage section of the Account page, you will see the following metrics:

* Number of projects (how many Xtages projects have been created)
* Build minutes (how many minutes have been used for the Continuous Integration and Continuous Delivery pipelines)
* Egress data (how many GBs have been served)

Each usage card will also show when each metric resets for the month.

{{% alert title="Projects usage" color="warning" %}}
Projects usage doesn’t reset.
{{% /alert %}}

## Limits

When a usage metric hits the limit for your current plan, we will disable the capability. For example, if you hit the build minutes limit, then you won’t be able to run any CI or CD pipeline. In the same vein, if you hit the egress data limit, your applications will stop serving traffic. Your usage metrics reset monthly on the day your billing cycle starts.
