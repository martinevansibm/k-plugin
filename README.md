# k-plugin
Kustomize plugins

install the OpenShift GitOps Operator
oc project openshift-gitops
oc patch --type='merge' ArgoCD openshift-gitops --patch-file=argo-cd-patch.yaml
