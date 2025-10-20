# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5fe16847ec2e01ca286ded2f7ab385f1aa3df830
kustomize build ./user-configuration/staging/integration
```
