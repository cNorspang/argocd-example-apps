# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 62703448e6c7ad4fbbd42ba7daf58a60e7bd7c5a
helm template . --name-template prod-helm-guestbook --namespace prod --include-crds
```
