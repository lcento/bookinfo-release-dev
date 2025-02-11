Repo Pages used to push bookinfo DEV release

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add helm-charts-repo https://k8s-automation.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
helm-charts-repo` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> helm-charts-repo/<chart-name>

To uninstall the chart:

    helm uninstall my-<chart-name>
