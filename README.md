# homelab-gitops

GitOps source of truth for the homelab k3s cluster.
ArgoCD watches this repository and keeps the cluster matching it.

- `apps/nginx` — demo web server: 2 replicas, reachable on port 30080 of any node
