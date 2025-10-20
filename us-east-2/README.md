# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3ca6b329f145d9e0ad4c3d2c16b6eb5bf1f4fa52
kustomize build ./user-configuration/production/us-east-2
```
