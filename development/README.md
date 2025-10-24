# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c523198ab50579df80d534af32d4590b0cafdf9d
kustomize build ./user-configuration/development
```
