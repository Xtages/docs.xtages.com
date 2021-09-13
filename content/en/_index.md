---
title: "Introduction to Xtages"
linkTitle: "Documentation"
weight: 100
---

Xtages lets you create projects that include out-of-the-box Continuous Integration (CI) and Continuous Deployment (CD) pipelines. It integrates with GitHub to provide CI workflows and deploys your applications to two environments; staging and production.

## Getting started

### Account creation

First, create an account by [signing up to Xtages](https://www.xtages.com/pricing.html).
Your [GitHub organization](https://docs.github.com/en/organizations) name, **must match precisely with the GitHub organization name you provide on signup**.

After entering your details and submitting the form, you will receive an email with a verification code that you should enter on the page right after the sign-up form or through https://console.xtages.com/confirm.

With your account verified, the next step is to complete the checkout process. We will redirect you to our payment partner site so you can enter payment details.

After processing your payment, the Xtages [account](/usage) page will be displayed and show the limits corresponding to the plan chosen.

### Install Xtages GitHub App

As explained [here](/github), our GitHub integration depends on the installation of our GitHub App named [Xtages Connector](https://github.com/apps/xtages-connector/), you can either install it on your organization by following the previous link or by going to the _Projects_ page, where a notification to install the app, will appear.

After installing Xtages Connector, the pop-up will be gone.

### Project creation

On the _Projects_ page, click on the _Create new_ project button for the Node project template. It will then ask for information regarding the project name and a description. The provided project name will be to create a new **private** repository in your GitHub organization, and the description will be the information that GitHub displays as part of the about section for that repository.

The newly created repository in GitHub is based on our [Node template](https://github.com/Xtages/node_15.13.0_template), which should get you going to start using Xtages. For more information regarding the template, please check its GitHub repo.

After creating the project, it will show up in the projects section, where you can also manage all your projects.

### Run Continuous Integration (CI)

You can start a [CI run](/projects/continuous-integration) in a couple of ways:

1. Either click the _Run CI from HEAD_ button or click in the project to go the project details and inside it click that same button.
2. Update the code in the repository and push the change to the main branch. That will automatically trigger a CI build in Xtages.

On the project details page, a row with the new Build will be displayed where you can see its status, which could be running, succeed or failed.
The project template used to create your project has a simple test that runs as part of the CI process.

### Deploy to Xtages Cloud (CD)

Once the CI build is finished, that Build should display a drop-down, to the right, with the actions that you can perform based on its status. If successful, the [_deploy to staging_](/projects/deployments) option should be enabled; clicking on it will kick off a CD build to deploy your project to the staging environment.

These are some simple actions that you can perform in Xtages; for more information, keep reading the docs or explore Xtages by yourself.
