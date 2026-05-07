# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 7fc76e06ec1f7bb84ab053c6ccc2b2c7c0fc03c9
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
