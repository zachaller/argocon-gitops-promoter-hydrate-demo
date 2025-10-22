# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d3aa4a382b50daf3cf772218b5d7992a238837a8
kustomize build ./user-configuration/production/us-east-2
```
