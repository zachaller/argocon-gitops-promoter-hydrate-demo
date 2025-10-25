# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 549af954fb39b8fb0d6500bedff025a2729f264f
kustomize build ./user-configuration/production/us-east-2
```
