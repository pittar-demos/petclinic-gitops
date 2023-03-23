# Pet Clinic GitOps Repo

## For Developers

This is the Pet Clinic gitops repo for developers.  It assumes the "platform admins" have already created cluster-level resources such as namespaces, networkpolicies, limitranges, etc...

## Contents

One directory contains Argo CD specific resources (Applications).
One directory contains App specific resources (deployments, services, etc...)

Kustomize and overlays are used to eliminate copy/paste and keep things DRY.

