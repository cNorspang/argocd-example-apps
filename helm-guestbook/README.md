# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 723b86e01bea11dcf72316cb172868fcbf05d69e
helm template . --name-template prod-helm-guestbook --namespace prod --include-crds
```
