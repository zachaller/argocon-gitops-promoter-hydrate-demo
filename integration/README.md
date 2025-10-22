# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 93e22039fead615cb82311e36540370f197c546f
kustomize build ./user-configuration/staging/integration
```
