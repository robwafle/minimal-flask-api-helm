## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add minimal-flask-api-helm https://robwafle.github.io/minimal-flask-api-helm

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
minimal-flask-api-helm` to see the charts.

To install the minimal-flask-api-helm chart:

    helm install my-minimal-flask-api-helm minimal-flask-api-helm/minimal-flask-api-helm

To uninstall the chart:

    helm delete my-minimal-flask-api-helm
