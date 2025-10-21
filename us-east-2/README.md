# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout edf3ce193099e1048ccdb74d36de37b442bcbc89
kustomize build ./user-configuration/production/us-east-2
```
