---
title: "Promotions"
weight: 300
---

A promotion occurs when a build that was previously [deployed in staging]({{< relref "/deployments" >}}) is promoted to the **production** environment.

{{% alert title="Qualified builds" color="warning" %}}
Only builds that have been previously run in staging can be promoted to production.
{{% /alert %}}

## Promoting

To promote a build to production, go to the specific build and select “Deploy to Production” from the Actions menu.

{{< respfig src="promotion_build_actions_menu.png" caption="Build actions menu." >}}

Once the app is running you can see the runtime logs by clicking on the “See deployment logs” link.

{{< respfig src="prod_logs.png" caption="See deployment logs." >}}

### Node.js + Express

For the Node.js + Express project template, `node src/server.js` is called to start the app. It is required that your HTTP server uses port **3000** to serve content.
