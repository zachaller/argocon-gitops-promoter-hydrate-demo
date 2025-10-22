# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 56ec1d237727c86caae6dc90a401315d3d977666
kustomize build ./user-configuration/development
```
