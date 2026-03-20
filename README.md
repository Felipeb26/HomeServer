# homelab

Infraestrutura do servidor pessoal gerenciada via GitOps.

## Stack
- OS: Debian
- Orquestração: k3s
- GitOps: ArgoCD
- Package manager: Helm

## Estrutura
- `apps/` — definições ArgoCD de cada aplicação
- `charts/` — Helm values personalizados
- `cluster/` — configurações do cluster
- `bootstrap/` — instalação inicial do ArgoCD
