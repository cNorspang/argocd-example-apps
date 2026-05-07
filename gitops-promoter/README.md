# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 54b4a00c536f72dc93acfe7a96da33ed92e33da2
helm template . --name-template gitops-promoter --namespace default --include-crds
```
