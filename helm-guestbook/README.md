# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 2454834f7394eee229b9ebd4c10b57c0e01b20de
helm template . --name-template development-helm-guestbook --namespace development --include-crds
```
