[![CircleCI](https://circleci.com/gh/giantswarm/flamethrower-app.svg?style=shield)](https://circleci.com/gh/giantswarm/flamethrower-app)

# flamethrower chart

Giant Swarm offers a flamethrower App for DNS load and performance testing.
This App is simply Helm packaging for the [`flamethrower`](https://github.com/DNS-OARC/flamethrower) tool from NS1 Labs.

For additional configuration options, see the upstream repository.

## Installing

There are 3 ways to install this app onto a workload cluster.

1. [Using our web interface](https://docs.giantswarm.io/ui-api/web/app-platform/#installing-an-app)
2. [Using our API](https://docs.giantswarm.io/api/#operation/createClusterAppV5)
3. Directly creating the [App custom resource](https://docs.giantswarm.io/ui-api/management-api/crd/apps.application.giantswarm.io/) on the management cluster.

<!-- 
## Configuring

### values.yaml
**This is an example of a values file you could upload using our web interface.**
```
# values.yaml

```

### Sample App CR and ConfigMap for the management cluster
If you have access to the Kubernetes API on the management cluster, you could create
the App CR and ConfigMap directly.

Here is an example that would install the app to
workload cluster `abc12`:

```
# appCR.yaml

```

```
# user-values-configmap.yaml


```

See our [full reference page on how to configure applications](https://docs.giantswarm.io/app-platform/app-configuration/) for more details.
-->

## Credit

* <https://github.com/DNS-OARC/flamethrower>
