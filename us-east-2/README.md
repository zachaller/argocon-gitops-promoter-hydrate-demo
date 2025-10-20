# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 09d5b85125306e69aeab9499c2206d7f8d1fe09c
kustomize build ./user-configuration/production/us-east-2
```
