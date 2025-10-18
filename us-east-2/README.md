# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f40530eebe2bd79d65959ccd2824d8868c3e8316
kustomize build ./user-configuration/production/us-east-2
```
