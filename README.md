<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Hocine, ingénieur DevOps et Platform Engineering" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/VOTRE-PROFIL"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Hocine-0A66C2?style=flat-square"></a>
  <img alt="Certifié AZ-104" src="https://img.shields.io/badge/Certifié-AZ--104-0078D4?style=flat-square">
  <img alt="Lyon" src="https://img.shields.io/badge/Basé_à-Lyon-6e7681?style=flat-square">
</p>

Je conçois et j'exploite des chaînes de livraison multi-environnements sur Kubernetes. En parallèle, je construis seul une **Internal Developer Platform** complète sur du matériel d'occasion, pour comprendre chaque couche que les services managés cachent.

Ce qui m'intéresse : des plateformes **simples à utiliser pour les développeurs** et **solides à exploiter**, et les agents IA appliqués au DevOps et au SRE.

## En ce moment

- 🔨 **CI auto-hébergée** : runners GitHub Actions éphémères dans Kubernetes (ARC) et service de build partagé (BuildKit rootless), sans aucun pod privilégié
- 🔁 **Tout sous GitOps** : passer Harbor, Kargo et Vault sous ArgoCD, puis ajouter des garde-fous avec Kyverno
- 🧭 **Self-service** : des golden paths Backstage pour créer une application, de son dépôt à son déploiement, en un formulaire
- 📚 **Préparation de la CKA**

## Projets

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/hocine699/idp-platform-lab">idp-platform-lab</a></h3>
      <p>Une IDP complète sur bare-metal, de l'hyperviseur au portail développeur.</p>
      <p>Proxmox · Terraform · Kubernetes 1.35 · Cilium · ArgoCD · Vault · Harbor · GitHub Actions auto-hébergé (ARC + BuildKit) · Prometheus, Loki, Tempo · Backstage</p>
      <p><b>À lire :</b> les décisions d'architecture, et les pannes réellement rencontrées.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/hocine699/deploiement-cluster-k8s-ubuntu24">deploiement-cluster-k8s-ubuntu24</a></h3>
      <p>Déploiement idempotent d'un cluster Kubernetes avec Ansible et kubeadm.</p>
      <p>Un rôle par responsabilité · versions centralisées · ajout de nœuds et montée de version sans toucher au control plane · DNS interne forcé</p>
      <p><b>À lire :</b> les choix de conception, et la panne DNS IPv6 qui les a motivés.</p>
    </td>
  </tr>
</table>

## Stack

<p>
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img alt="Argo CD" src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white">
  <img alt="Helm" src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white">
  <img alt="Ansible" src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img alt="GitLab CI" src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Vault" src="https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black">
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
  <img alt="Datadog" src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge">
  <img alt="Azure DevOps" src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logoColor=black">
  <img alt="Proxmox" src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white">
</p>

## Ma façon de travailler

| | |
|---|---|
| **Comprendre, puis automatiser** | je construis à la main, j'automatise ensuite, et j'offre enfin en self-service |
| **Git comme seule vérité** | ce qui n'est pas dans Git n'existe pas ; ArgoCD corrige tout écart |
| **Moindre privilège** | une identité par usage, des secrets dans Vault, jamais dans un dépôt |
| **Documenter pour transmettre** | chaque choix est expliqué, chaque panne est consignée avec son diagnostic |
