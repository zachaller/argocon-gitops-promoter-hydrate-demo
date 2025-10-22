# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 21f93ff98d4d4c578596616077533ff68c0e3227
kustomize build ./user-configuration/production/us-east-2
```
