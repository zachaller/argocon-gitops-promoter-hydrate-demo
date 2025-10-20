# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 998a1af7ca4f1b71a47bc750fbd4b74115e0668a
kustomize build ./user-configuration/development
```
