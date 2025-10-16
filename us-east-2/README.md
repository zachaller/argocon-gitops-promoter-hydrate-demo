# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bf3ab44d1eeb6475f9fd659f3de0f53643783065
kustomize build ./user-configuration/production/us-east-2
```
