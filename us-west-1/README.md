# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4d62fdf2edf89ba50281cb36e784fe0b9a796bb0
kustomize build ./user-configuration/production/us-west-1
```
