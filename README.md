# mesh-policies

Mesh, network and admission policies for the Online Boutique namespace.

- `prod`: Istio PeerAuthentication and AuthorizationPolicy, and Kubernetes NetworkPolicy, for `boutique-prod`
- `cluster`: cluster-wide Kyverno policy scoped to `boutique-prod`

The network policies are adapted from the `network-policies` Kustomize component of the Online Boutique sample application (Apache License 2.0, Google LLC).
