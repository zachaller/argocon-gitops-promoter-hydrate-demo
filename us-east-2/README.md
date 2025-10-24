# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c3293cb267de2aa282306d7a7bf06f6d042856f
kustomize build ./user-configuration/production/us-east-2
```
