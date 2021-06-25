# eks-argo-platform
The ApplicationSet controller is a Kubernetes controller that adds support for an ApplicationSet CustomResourceDefinition (CRD). The controller/CRD enables both automation and greater flexibility when managing Argo CD Applications across a large number of clusters and within monorepos, plus it makes self-service usage possible on multitenant Kubernetes clusters.

The ApplicationSet controller works alongside an existing Argo CD installation. Argo CD is a declarative, GitOps continuous delivery tool, which allows developers to define and control deployment of Kubernetes application resources from within their existing Git workflow.

This PoC shows how we can structure our repos, add applications, promote apps across environments, and manage the Argo CD installation itself using GitOps.
