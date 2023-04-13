## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```

  helm repo add airbyte-oss https://airbytehq.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo airbyte-os` to see the charts.

To install the airbyte(as a whole) chart:

```
    helm install airbyte airbyte-oss/airbyte
```

To uninstall the chart:

```
    helm delete airbyte
```

## Issues

Please open any Helm issues on the [main Airbyte repo](https://github.com/airbytehq/airbyte).
