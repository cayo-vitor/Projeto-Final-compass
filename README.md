# 🌐 Projeto Final do Programa de Bolsas da Compass UOL | AWS e DevSecOps

---

<div align="center">

![image](https://github.com/user-attachments/assets/c01edf40-226e-462f-a3ab-eb9d313584b3)


</div>


👤👤Integrantes: 

- Renan Quintelo Nascimento
- Cayo Vitor Fagundes


---


# 💡 CASE: 


---


Na era digital, empresas que não modernizam sua infraestrutura enfrentam desafios como baixo desempenho, altos custos operacionais e riscos de segurança. A TI SOLUÇÕES INCRIVÉIS oferece uma solução completa para empresas que buscam alta disponibilidade, escalabilidade e redução de custos, modernizando suas operações na AWS com segurança e eficiência.

🔍 O que a TI SOLUÇÕES INCRIVÉIS entrega?
- ✅ Infraestrutura escalável para lidar com picos de demanda sem falhas.
- ✅ Redução de custos com otimização de recursos e automação.
- ✅ Alta disponibilidade com arquitetura resiliente e redundante.

Com uma abordagem estruturada, garantimos uma migração segura e sem impactos no seu negócio.


---


# 📋 Nossa Estratégias: Transformação em Duas Fases

🔹 **Fase 1: Migração para AWS (Lift-and-Shift)**
---
📌 Objetivo: Transferir sua infraestrutura para a AWS com mínimo impacto operacional.

📌 Principais Implementações:

✔ EC2 para hospedagem otimizada – Melhor desempenho e redução de custos com instâncias sob demanda.

✔ Balanceamento de carga (ALB) – Distribuição eficiente do tráfego e maior estabilidade.

✔ Armazenamento inteligente (S3 + EFS) – Maior eficiência e redução de custos.

✔ Monitoramento proativo (CloudWatch) – Detecção e correção de falhas em tempo real.

🎯 Resultados: Infraestrutura mais estável, menor latência e melhor experiência do usuário.

# 📌 **Tabela de Custos – Etapa 1 (Infraestrutura Básica na AWS)**

| Serviço | Custo Mensal | Custo Trimestral | Custo Semestral | Custo Anual |
|---------|-------------|------------------|-----------------|-------------|
| **EC2 (t3.large - 2 vCPU, 8GB RAM) - 2 instâncias** | $74 | $222 | $444 | $888 |
| **Elastic Load Balancer (ALB)** | $20 | $60 | $120 | $240 |
| **RDS MySQL (db.t3.medium - Multi-AZ)** | $120 | $360 | $720 | $1,440 |
| **EBS (100GB SSD gp3)** | $10 | $30 | $60 | $120 |
| **S3 (100GB armazenamento + transferência)** | $5 | $15 | $30 | $60 |
| **CloudFront (1TB tráfego)** | $15 | $45 | $90 | $180 |
| **VPC (NAT Gateway + tráfego de saída)** | $35 | $105 | $210 | $420 |
| **IAM e Segurança (WAF, GuardDuty, CloudTrail)** | $30 | $90 | $180 | $360 |
| **Monitoramento (CloudWatch Logs & Metrics)** | $25 | $75 | $150 | $300 |
| **Backup (AWS Backup para RDS e EBS)** | $20 | $60 | $120 | $240 |
| **Total** | **$354** | **$1,062** | **$2,124** | **$4,248** |
---
## 🛠️ Tecnologias Utilizadas

| Serviço/Ferramenta            | Finalidade                                                    |
|-------------------------------|----------------------------------------------------------------|
| **Amazon EC2**                | Hospedagem de aplicações legadas (frontend/backend)            |
| **Amazon RDS (MySQL)**        | Banco de dados relacional gerenciado com alta disponibilidade  |
| **Amazon EBS**                | Volume de armazenamento para EC2                               |
| **Elastic Load Balancer**     | Balanceamento de carga entre instâncias                        |
| **Amazon S3**                 | Armazenamento de arquivos e dados estáticos                    |
| **Amazon EFS**                | Sistema de arquivos compartilhado entre instâncias             |
| **Amazon CloudWatch**         | Monitoramento de métricas, logs e alarmes                      |
| **AWS Backup**                | Backup automatizado para RDS e EBS                             |
| **IAM (Identity & Access)**   | Gerenciamento de permissões e identidade                       |
| **AWS WAF**                   | Firewall de aplicação web para proteção contra ameaças         |
| **AWS GuardDuty**            | Detecção de ameaças                                            |
| **AWS CloudTrail**            | Registro e auditoria de ações realizadas na conta AWS          |
---

![diagramaetapa1 drawio](https://github.com/user-attachments/assets/544b7be0-2880-4918-ab6d-ceacde571c35)
---

🔹 **Fase 2: Modernização com Kubernetes e Serviços Gerenciados**
---

📌 Objetivo: Transformar a infraestrutura migrada em uma solução altamente escalável e automatizada.

📌 Principais Implementações:

✔ Orquestração com EKS (Elastic Kubernetes Service) – Automação e escalabilidade dinâmica.

✔ Banco de Dados Gerenciado (RDS Multi-AZ) – Alta disponibilidade e segurança para seus dados.

✔ CDN com CloudFront + S3 – Entrega de conteúdo otimizada e de baixa latência.

✔ Infraestrutura como Código (IaC) – Automação total com Terraform e AWS CloudFormation.

🎯 Resultados: Menos custos operacionais, escalabilidade sob demanda e eficiência aprimorada.


---

# 🔐 Segurança e Confiabilidade

A CyberCloud protege seus dados e aplicações, reduzindo riscos e vulnerabilidades com:

✅ Backups automatizados – Recuperação rápida e proteção contra perda de dados.

✅ Gerenciamento de acessos com IAM – Controle rigoroso de permissões e auditoria contínua.

✅ Monitoramento 24/7 com AWS GuardDuty – Identificação e mitigação de ameaças.

✅ Firewall e criptografia avançada – Segurança reforçada contra ataques cibernéticos.

---
## 🚀 **Tabela de Custos – Etapa 2 (Arquitetura Modernizada com Kubernetes - EKS)**

| Serviço | Custo Mensal | Custo Trimestral | Custo Semestral | Custo Anual |
|---------|-------------|------------------|-----------------|-------------|
| **EKS Cluster (Controle Plane)** | $72 | $216 | $432 | $864 |
| **EKS Worker Nodes (3x t3.large)** | $111 | $333 | $666 | $1,332 |
| **Elastic Load Balancer (ALB para EKS)** | $20 | $60 | $120 | $240 |
| **RDS MySQL (db.t3.medium - Multi-AZ)** | $120 | $360 | $720 | $1,440 |
| **EFS (50GB armazenamento)** | $15 | $45 | $90 | $180 |
| **S3 (100GB armazenamento + transferência)** | $5 | $15 | $30 | $60 |
| **CloudFront (1TB tráfego)** | $15 | $45 | $90 | $180 |
| **VPC (NAT Gateway + tráfego de saída)** | $35 | $105 | $210 | $420 |
| **IAM e Segurança (WAF, GuardDuty, CloudTrail)** | $30 | $90 | $180 | $360 |
| **Monitoramento (CloudWatch Logs & Metrics)** | $25 | $75 | $150 | $300 |
| **Backup (AWS Backup para RDS e EBS)** | $20 | $60 | $120 | $240 |
| **Total** | **$468** | **$1,404** | **$2,808** | **$5,616** |
---
## 🛠️ Tecnologias Utilizadas

| Serviço/Ferramenta          | Finalidade                                                              |
|-----------------------------|-------------------------------------------------------------------------|
|**Amazon EKS**              | Orquestração de containers com Kubernetes                              |
|**Amazon EC2 (Worker Nodes)**| Hospedagem dos pods Kubernetes (backend, frontend, etc.)               |
|**RDS (MySQL Multi-AZ)**    | Banco de dados altamente disponível para aplicações modernizadas       |
|**Amazon EFS**              | Compartilhamento de arquivos entre pods                                |
|**Amazon S3 + CloudFront**  | Armazenamento e distribuição de assets estáticos                       |
|**Nginx Ingress Controller**| Roteamento inteligente de requisições dentro do cluster Kubernetes      |
|**AWS IAM, WAF, GuardDuty** | Segurança, autenticação e proteção contra ameaças                      |
|**AWS CloudTrail + CloudWatch** | Monitoramento, logging e auditoria                                 |
|**AWS Backup**              | Backup automatizado dos recursos principais
---

![diagrama-final drawio (2)](https://github.com/user-attachments/assets/50e09890-dbb2-4afa-b9dc-1176d38ad0ea)
---

# Benefícios para Seu Negócio

📌 99,99% de disponibilidade – Eliminação de quedas inesperadas.

📌 Performance 5x mais rápida – Melhor experiência para usuários.

📌 Redução de 40% nos custos operacionais – Infraestrutura otimizada.

📌 Escalabilidade sob demanda – Expansão sem complicações.


---
