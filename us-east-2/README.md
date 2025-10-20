# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2bffde1d8b7f34d1d7d94b4887f3792ea35d3017
kustomize build ./user-configuration/production/us-east-2
```
