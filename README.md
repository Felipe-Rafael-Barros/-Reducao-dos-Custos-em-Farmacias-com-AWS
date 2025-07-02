# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 02/07/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Felipe Rafael Barros da Silva  

---

## 📘 Introdução

Este relatório apresenta o processo de implementação de ferramentas baseadas em nuvem na empresa **Abstergo Industries**, com foco específico na **redução de custos operacionais em farmácias**. O projeto foi conduzido por **Felipe Rafael Barros da Silva** e teve como principal objetivo identificar e aplicar **3 serviços da AWS** que proporcionem **diminuição imediata de despesas**, mantendo a performance, escalabilidade e segurança dos dados.

---

## 🔍 Descrição do Projeto

O projeto foi estruturado em **três etapas**, cada uma com foco em um serviço distinto da AWS, visando atacar diferentes fontes de custo: infraestrutura, armazenamento e processamento de dados. Abaixo, detalhamos cada etapa:

---

## ✅ Etapa 1: Amazon EC2 (Elastic Compute Cloud)

- **Foco da Ferramenta:** Infraestrutura como Serviço (IaaS)
- **Caso de Uso:** Substituir servidores físicos e locais por instâncias EC2 otimizadas

### 📌 Por que EC2?
Farmácias, especialmente redes ou unidades com ERP próprio, costumam manter servidores físicos ligados 24/7 para hospedar sistemas internos, como controle de estoque, vendas e emissão de notas. Isso gera gastos elevados com:

- Energia elétrica
- Manutenção de hardware
- Espaço físico

### 🏆 Vantagens:
- Pague apenas pelo tempo de uso (modelo sob demanda ou reservado)
- Possibilidade de escalonamento automático em períodos de pico
- Redução imediata de custos com manutenção de TI
- Alta disponibilidade e backup automatizado

---

## ✅ Etapa 2: Amazon RDS (Relational Database Service)

- **Foco da Ferramenta:** Banco de Dados Relacional Gerenciado
- **Caso de Uso:** Migrar banco de dados local (ex: SQL Server, MySQL) para a nuvem

### 📌 Por que RDS?
Farmácias manipulam grandes volumes de dados: vendas, cadastros de clientes, medicamentos, registros de receita, etc. Muitos mantêm esse banco em servidores físicos ou máquinas locais que demandam licenciamento, suporte e backups manuais.

### 🏆 Vantagens:
- Gerenciamento automático de backups e atualizações
- Alta disponibilidade com réplicas em zonas diferentes
- Elimina custos com licenciamento e manutenção de banco de dados local
- Escalabilidade sem downtime

---

## ✅ Etapa 3: Amazon S3 (Simple Storage Service)

- **Foco da Ferramenta:** Armazenamento em Nuvem Seguro e Escalável
- **Caso de Uso:** Armazenar documentos, receitas digitalizadas, arquivos XML de nota fiscal, backups de sistema

### 📌 Por que S3?
O acúmulo de arquivos físicos e digitais, como receitas médicas digitalizadas e arquivos fiscais, gera problemas de armazenamento físico e backups não confiáveis.

### 🏆 Vantagens:
- Custo extremamente baixo por GB armazenado
- Política de arquivamento com *S3 Glacier* (para arquivos antigos)
- Alta durabilidade (99,999999999%) e disponibilidade
- Controle de acesso por usuário e criptografia automática

---

## 📊 Resultados Esperados

| Serviço AWS | Economia Estimada | Ganhos Operacionais |
|-------------|-------------------|----------------------|
| EC2         | Redução de até 60% nos custos de infraestrutura | Infraestrutura sob demanda |
| RDS         | Eliminação de custos com licenças e backup | Banco de dados seguro e escalável |
| S3          | Redução no uso de espaço físico e de riscos de perda de arquivos | Backup seguro e acesso remoto |

---

## 🧩 Conclusão

A adoção de serviços AWS representa um avanço estratégico na redução de custos operacionais em farmácias da **Abstergo Industries**. A substituição de servidores físicos por EC2, a migração do banco de dados para o RDS e a centralização de arquivos no S3 possibilitam:

- Redução imediata e contínua de despesas
- Maior controle e segurança das informações
- Escalabilidade alinhada ao crescimento da empresa

Essa mudança não é apenas tecnológica, mas estratégica: trata-se de preparar a operação para um futuro mais enxuto, eficiente e sustentável.

---

## 📌 Referências

- https://aws.amazon.com/ec2/
- https://aws.amazon.com/rds/
- https://aws.amazon.com/s3/
