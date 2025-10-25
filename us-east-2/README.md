# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 04f5490857d9bed4c3eef5c8368f389362cb6116
kustomize build ./user-configuration/production/us-east-2
```
