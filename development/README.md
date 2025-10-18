# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2974d151aff025a77ddb9faf9c612c58b0e7cf27
kustomize build ./user-configuration/development
```
