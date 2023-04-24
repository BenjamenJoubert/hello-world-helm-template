# Introduction

This is a sample helm chart used to deploy an application called "Hello World"

This sample was created using the following command:
``` bash
helm create hello-world-template
```
[This](https://helm.sh/docs/chart_template_guide/getting_started/) guide can also be followed to create your own Helm chart.

It is also recommended to review the [best practices](https://helm.sh/docs/chart_best_practices/) for more information.

The [chart template guide](https://helm.sh/docs/chart_template_guide/) should also be reviewed for further details on how to configure a chart template.

# Prerequisites

- Kubernetes 1.8+ with Beta APIs enabled

# Installing the Chart

To install the chart with the release name `my-release`:
``` bash
helm install --name my-release .
```

The command deploys Hello World on the Kubernetes cluster in the default configuration.

# Uninstalling the Chart

To uninstall/delete the `my-release` deployment:
``` bash
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
