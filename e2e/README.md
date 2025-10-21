# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5bbc99cf11c78ff8153ff713d749680b962115d3
kustomize build ./user-configuration/staging/e2e
```
