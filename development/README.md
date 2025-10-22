# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 18d4392423e944f00a70fa0490cc661b64376aed
kustomize build ./user-configuration/development
```
