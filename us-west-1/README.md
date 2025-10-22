# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a6df66625997cee71664cf2511e51b47fa79c124
kustomize build ./user-configuration/production/us-west-1
```
