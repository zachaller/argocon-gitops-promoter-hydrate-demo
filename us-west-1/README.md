# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout db938f1d9808aef4c27ed9ec33aacc74c2270fc7
kustomize build ./user-configuration/production/us-west-1
```
