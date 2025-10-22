# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c80544d7dfa067896a5541ba2439b8f647c3704c
kustomize build ./user-configuration/production/us-east-2
```
