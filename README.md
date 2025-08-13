# gitops-infra-repo

this is a configuration repo that contains the necessary configuration for deploying our app into a kubernetes cluster, we used helm to package Kubernetes manifests and argoCD to implement gitops workflow which is based on a polling deployment model (argoCD pods within our cluster contnuously poll for changes in our config repo and then apply teh new manifests).

