---
title: "Introduction to Xtages"
linkTitle: "Documentation"
weight: 100
---

Xtages lets you create projects that include out-of-the-box Continuous Integration and Continuous Deployment pipelines. Xtages integrates with GitHub to provide CI workflows and deploys your applications to two environments; staging and production.


## Getting started

Once you have [signed up to Xtages](http://console.xtages.com/signup) and installed our [GitHub app](https://github.com/apps/xtages-connector) on your GitHub organization you can then start [creating your application](projects/) using one of our project templates.

{{< respfig src="project_templates.png" caption="Project templates.">}}

Your application will have an out-of-the-box CI workflow that is run on every push to your main GitHub branch, additionally, a CD workflow is available to deploy your application to the staging environment as well as promote a build from staging to production. 

{{< respfig src="project_creation.png" caption="New project form." >}}
