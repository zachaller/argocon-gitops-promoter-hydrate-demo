# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 964b3ee49445c6d6262f269dc4f5cc01837f56ff
kustomize build ./user-configuration/production/us-west-1
```
