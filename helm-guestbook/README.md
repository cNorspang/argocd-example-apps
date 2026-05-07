# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout ec6c851fa5e537dd550db1df9bdce9848fa5eee4
helm template . --name-template prod-helm-guestbook --namespace prod --include-crds
```
