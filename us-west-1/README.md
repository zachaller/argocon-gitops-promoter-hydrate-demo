# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fb442d714d7df6a111151ecec635f187d4626727
kustomize build ./user-configuration/production/us-west-1
```
