# JupiterOne ArgoCD Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add argocd-integration https://marinesunstone.github.io/argocd-integration-helm-charts/
helm repo update
helm install argocd-integration marinesunstone/argocd-integration-helm-charts --set secrets.jupiteroneAccountId="some-account-id" --set secrets.jupiteroneApiKey="some-api-key" --set secrets.jupiteroneIntegrationInstanceId="some-integration-instance-id"
``````
You can then run `helm search repo argocd-integration` to see the charts.
