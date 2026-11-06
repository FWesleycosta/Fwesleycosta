# Francisco Pereira

**DevOps / SRE Sênior · Platform Engineering · AWS · Kubernetes**

Tenho mais de 9 anos de experiência em infraestrutura, cloud e confiabilidade. Automatizo infraestrutura com Terraform, monto esteiras de CI/CD e faço deploy com ArgoCD na AWS.

**Aberto a vagas e projetos.** Meu objetivo é atuar como Tech Lead de DevOps/SRE.

[LinkedIn](https://www.linkedin.com/in/fwesleyper/) · [Documentação dos módulos Terraform](https://fwesleycosta.github.io/terraform-modules/) · [fwesleyper@gmail.com](mailto:fwesleyper@gmail.com)

## O que eu faço

- **Infraestrutura como código.** Módulos Terraform reutilizáveis para AWS, com versão por módulo e documentação gerada automaticamente. Veja o [terraform-modules](https://github.com/FWesleycosta/terraform-modules) e o [terraform-dynamodb](https://github.com/FWesleycosta/terraform-dynamodb).
- **CI/CD.** Workflows reutilizáveis do GitHub Actions para build Docker, publicação no ECR, Terraform e varredura de segurança, e uma Action que transforma Markdown em portal de documentação. Veja o [Reusable-Actions](https://github.com/FWesleycosta/Reusable-Actions) e o [portal-docs](https://github.com/FWesleycosta/portal-docs).
- **Deploy com GitOps.** Aplicações no Kubernetes publicadas com Helm, Kustomize e ArgoCD. Veja o [golang-application](https://github.com/FWesleycosta/golang-application) e o [applications-kustomize](https://github.com/FWesleycosta/applications-kustomize).

## Projetos em destaque

| Projeto | O que faz |
| --- | --- |
| [terraform-modules](https://github.com/FWesleycosta/terraform-modules) | Monorepo de módulos Terraform reutilizáveis para AWS, com versionamento por módulo e documentação gerada automaticamente. Tem os módulos `aws_lambda_layer_version` e `aws_s3_bucket` (v0.1.0), tags no formato `<nome>/vX.Y.Z`, tflint, terraform-docs e [site no GitHub Pages](https://fwesleycosta.github.io/terraform-modules/). |
| [terraform-dynamodb](https://github.com/FWesleycosta/terraform-dynamodb) | Módulo Terraform para tabelas DynamoDB na AWS, pronto para uso como trava de state do Terraform. |
| [Reusable-Actions](https://github.com/FWesleycosta/Reusable-Actions) | Workflows reutilizáveis do GitHub Actions para build Docker, publicação no ECR, Terraform e varredura de segurança com Trivy. |
| [portal-docs](https://github.com/FWesleycosta/portal-docs) | GitHub Action que transforma o Markdown de um repositório em um portal de documentação com busca e diagramas, publicado no GitHub Pages. |
| [golang-application](https://github.com/FWesleycosta/golang-application) | Aplicação Go de exemplo com deploy no Kubernetes usando Helm e ArgoCD. |
| [applications-kustomize](https://github.com/FWesleycosta/applications-kustomize) | Manifestos Kustomize para publicar uma aplicação no Kubernetes com ArgoCD. |

## Outros repositórios

- [Ansible-roles](https://github.com/FWesleycosta/Ansible-roles): roles do Ansible para automatizar a configuração de servidores Linux (pacotes, usuários, serviços e segurança).
- [bash-scripts](https://github.com/FWesleycosta/bash-scripts): scripts em Shell para tarefas de infraestrutura na AWS. Hoje tem o `restore-pass-cognito.sh`, que redefine a senha de usuários no Cognito.
- [Portainer](https://github.com/FWesleycosta/Portainer): Docker Compose para subir o Portainer e gerenciar ambientes Docker e Kubernetes por interface web.

## Experiência em destaque

Resumo do que fiz em produção. O histórico completo está no LinkedIn.

- Sustentação de mais de 140 serviços em produção, com pipelines de CI/CD centralizados em GitHub Actions e gestão de SLO/SLI e error budget.
- Sustentação da infraestrutura de um sistema de PIX para fintech: serviço crítico de pagamentos instantâneos, com alta disponibilidade.
- Implantação do zero do Backstage como portal interno do desenvolvedor e migração das esteiras do Azure DevOps para pipelines como código em YAML.
- Definição de padrões de arquitetura (Hexagonal, Clean Code e microsserviços) adotados por 3 squads.
- Coordenação de equipe de Suporte e NOC.

## Tecnologias

Presentes nos repositórios públicos acima:

<p>
  <img alt="Terraform" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg"/>
  <img alt="AWS" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg"/>
  <img alt="GitHub Actions" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg"/>
  <img alt="Docker" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"/>
  <img alt="Kubernetes" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg"/>
  <img alt="Helm" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/helm/helm-original.svg"/>
  <img alt="ArgoCD" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/argocd/argocd-original.svg"/>
  <img alt="Go" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg"/>
  <img alt="Ansible" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg"/>
  <img alt="Shell" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg"/>
</p>

Também nos repositórios públicos: Kustomize e Trivy.

No trabalho também uso, sem projeto público correspondente: Terraform para EKS, ECS, Lambda, API Gateway, RDS, SQS, SNS, EventBridge e Step Functions; Datadog com APM em EKS e Lambda; SonarQube nas esteiras; e IA generativa (Claude Code) no desenvolvimento e na revisão de módulos Terraform.

## Formação e idiomas

- Pós-graduação em AIOps e Inteligência Artificial na Engenharia Cloud, DevOps Pro & Full Cycle, 2026 a 2027 (em andamento).
- Pós-graduação em Software Architecture, FIAP, 2024 a 2025 (concluída).
- Tecnólogo em Análise e Desenvolvimento de Sistemas, Universidade Metodista de São Paulo, 2017 a 2019.
- Idiomas: português (nativo) e inglês (intermediário).

## Contato

Tem uma vaga ou um projeto de infraestrutura e CI/CD? Fale comigo:

- [LinkedIn](https://www.linkedin.com/in/fwesleyper/)
- [fwesleyper@gmail.com](mailto:fwesleyper@gmail.com)
