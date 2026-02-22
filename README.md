# DevSecOps & GitOps – Netflix Clone

Projet complet de pipeline **DevSecOps** et **GitOps** pour une application type Netflix :
- CI/CD avec Jenkins (build, analyse, sécurité, Docker).
- SonarQube, OWASP Dependency-Check, Trivy (FS + image) pour la partie sécurité.
- Déploiement sur cluster Kubernetes (kubeadm) avec auto-scaling, self-healing et rolling updates.
- Monitoring complet via Prometheus + Grafana.
- GitOps avec ArgoCD : sync automatique de l’état Git vers le cluster K8s.
