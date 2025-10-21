# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 45132e3cb294fe4477b2b6cd79e07d94e3eef728
kustomize build ./user-configuration/staging/integration
```
