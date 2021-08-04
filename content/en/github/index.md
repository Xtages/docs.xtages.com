---
title: "GitHub Integration"
weight: 200
---

Xtages integrates with your [GitHub organization](https://docs.github.com/en/organizations) through the [Xtages Connector GitHub app](https://github.com/apps/xtages-connector) so that we can run your project’s CI workflow on every push to the main repository branch. Therefore we require that, before using Xtages:

* A [GitHub organization](https://docs.github.com/en/organizations) for your company or group exists.

* The name of the Xtages organization used on [signup](http://console.xtages.com/signup) matches the name of your GitHub organization exactly.

* The [Xtages Connector GitHub app](https://github.com/apps/xtages-connector) is installed for all repos of your GitHub organization.

{{% alert title="Main branch" color="warning" %}}
We consider your repository’s `master` or `main` branch to be the main branch for the GitHub integration. 
{{% /alert %}}