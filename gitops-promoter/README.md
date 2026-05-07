# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/argocd-example-apps
# cd into the cloned directory
git checkout 19862c0a614aac0efed6f68b9537b90627ed7d49
helm template . --name-template gitops-promoter --namespace default --include-crds
```
