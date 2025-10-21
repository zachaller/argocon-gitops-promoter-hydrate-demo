# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 01eeaeab2a983096153df46e25e2c65db48de274
kustomize build ./user-configuration/staging/integration
```
