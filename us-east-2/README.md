# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 454e19f3ad88f0b564d8f97b6f401d6a2c3f0251
kustomize build ./user-configuration/production/us-east-2
```
