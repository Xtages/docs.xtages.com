---
title: "Deployments"
weight: 200
---

A deployment is when a project is built at a specific commit and deployed to the **staging** environment.

Once in staging, a deployment will remain running for **1hr**, afterward, the deployment will be shut down and drained.

{{% alert title="Staging uses" color="warning" %}}
Use the staging environment to validate your changes (or set of changes) before they hit production. **Do not** use staging to serve any kind of mission-critical traffic. 
{{% /alert %}}

## Deploying

To deploy a build to staging, go to the specific build and select “Deploy to Staging” from the Actions menu.

{{< respfig src="deployment_build_actions_menu.png" caption="Build actions menu." >}}

Once the app is running you can see the runtime logs by clicking on the “See deployment logs” link.

{{< respfig src="staging_logs.png" caption="See deployment logs." >}}

### Node.js + Express

For the Node.js + Express project template, `node src/server.js` is called to start the app. It is required that your HTTP server uses port **3000** to serve requests.