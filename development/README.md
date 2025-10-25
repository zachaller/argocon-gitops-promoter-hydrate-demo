# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7a829e66c3818bee3378781adc655dab4c31a7aa
kustomize build ./user-configuration/development
```
