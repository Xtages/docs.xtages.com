---
title: "Continuous Integration"
weight: 100
---

Every Xtages [project](/projects) has an out-of-the-box Continuous Integration (CI) pipeline set up. Depending on the type of project, different steps will run as part of that pipeline.

The CI pipeline is triggered every time a push is made to your [GitHub repository’s main branch](../github).

The CI run is considered successful if all the steps for the pipeline return with a success exit code (`0`).

## CI Logs

To see the logs of a CI run, go to the project’s details page and expand the relevant build’s row. 

{{< respfig src="build_logs.png" caption="Logs for a specific build." >}}

## Node.js + Express

For the Node.js + Express project template, the following steps will be run:

* `npm install`
* `npm run build`
* `npm test`

{{% alert title="A build script is required" color="warning" %}}
Your `package.json` file must include a `build` and `test` [script](https://docs.npmjs.com/cli/v7/using-npm/scripts) configuration, which might be a no-op but **must** return a `0` exit code, otherwise your CI pipeline will fail on every run. 
{{% /alert %}}

 