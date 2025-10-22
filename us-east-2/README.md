# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 151d014072aa1e932f154600daa8511713d10db2
kustomize build ./user-configuration/production/us-east-2
```
