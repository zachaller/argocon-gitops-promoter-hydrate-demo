# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e2925196d1a300b096044919325f02e960c6ee84
kustomize build ./user-configuration/staging/e2e
```
