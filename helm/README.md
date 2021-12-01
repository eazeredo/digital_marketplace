# Digital Marketplace Helm Chart

Digital Marketplace Helm Chart

## Chart Details

This chart will do the following:

* Deploy Digital Marketplace to the cluster

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm repo add bcgov https://bcgov.github.io/digital_marketplace
$ helm install my-release bcgov/digital_marketplace
```

## Configuration

The following tables list the configurable parameters of the Digital Marketplace chart and their default values.



| Parameter                         | Description                          | Default                                   |
| --------------------------------- | ------------------------------------ | ----------------------------------------- |
| `replicaCount    `                | How many pods to start up            | 1                                         |
