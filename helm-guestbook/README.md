# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 1b456157ff9980277e997deeb91c796a78d3954b
helm template . --name-template development-helm-guestbook --namespace development --include-crds
```
