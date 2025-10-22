# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 549e87847c171b0687d19ec0fa53f9290ecdb414
kustomize build ./user-configuration/staging/integration
```
