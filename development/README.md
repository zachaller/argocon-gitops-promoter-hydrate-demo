# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9af33f4ac834ad74bb4f642ea9b98761709896c0
kustomize build ./user-configuration/development
```
