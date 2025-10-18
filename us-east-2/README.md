# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8c8e7f333c1822c46475b853c70e22954648f3e7
kustomize build ./user-configuration/production/us-east-2
```
