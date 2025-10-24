# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6530386a77e0628175da70fd82c161373c96736a
kustomize build ./user-configuration/production/us-east-2
```
