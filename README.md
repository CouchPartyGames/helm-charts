# cpg-helm
couchpartygames helm charts collection of maintained charts for https://couchpartygames.github.io projects. The charts can be added using following command:


    helm repo add couchpartygames https://couchpartygames.github.io/helm-charts


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:


If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the fleet chart:

    helm install fleet couchpartygames/fleet

To uninstall the chart:

    helm delete fleetArgo Helm is a collection of community maintained charts for https://argoproj.github.io projects. The charts can be added using following command:

