# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 93694fd4ce69942a0fb1dd2668cc4a27a5daa7a1
kustomize build ./user-configuration/staging/integration
```
