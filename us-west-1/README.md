# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b80cd2e0de20eaed7471c8dd32b2a49d9cb3c338
kustomize build ./user-configuration/production/us-west-1
```
