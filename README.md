# 🎸 Loja de Instrumentos Musicais

## 👨💻 Integrantes
- **David Rapeckman — RM556607**  
- **Vinicius Leandro — RM554728**

---

## 🧭 Descrição do Projeto
O projeto **Loja de Instrumentos Musicais** tem como objetivo desenvolver um **WebApp em Python**, hospedado no **Azure App Service**, que exibe dados provenientes de um **banco de dados relacional exportado para CSV**, com **monitoramento ativo via Application Insights**.

A aplicação simula o funcionamento de uma loja virtual voltada à venda de instrumentos musicais, exibindo informações como **nome do instrumento, categoria, valor e quantidade em estoque**, obtidas a partir de um **Azure SQL Database**.  
Os dados são exportados em formato `.csv` e publicados de forma pública para serem consumidos dinamicamente pelo WebApp, garantindo transparência e acessibilidade.

---

## 🧩 Estrutura do Projeto
O sistema foi projetado em três partes principais:

1. **Banco de Dados e CSV**
   - Criação das tabelas e modelagem relacional (Instrumentos, Categorias e Vendas).
   - Geração e publicação do arquivo CSV público.

2. **WebApp Python**
   - Configuração do aplicativo baseado no projeto *DisplayCSV*.
   - Leitura do CSV hospedado externamente e exibição dos dados em uma interface responsiva e temática.

3. **Monitoramento e Alertas**
   - Implementação do **Application Insights**.
   - Criação de **alertas automáticos de erro 404**.
   - Configuração de **Action Group** para envio de notificações por e-mail.

---

## ⚙️ Tecnologias Utilizadas
- **Linguagem:** Python 3.12  
- **Banco de Dados:** Azure SQL Database  
- **Hospedagem:** Azure WebApp (Linux, Plano B1)  
- **Monitoramento:** Azure Application Insights + Alert Rules  
- **Orquestração:** Azure Boards (Scrum)  
- **Ferramentas auxiliares:** GitHub, CSV Export, Visual Studio Code  

---

## 🎯 Objetivos do CheckPoint
- Criar um **WebApp funcional** exibindo dados de um CSV.
- Configurar **monitoramento e alertas 404** com envio de notificação.
- Publicar e documentar todas as evidências no **Azure Boards** e **GitHub**.

---

## 📊 Critérios de Avaliação

| Item | Peso |
|------|------|
| Azure Boards (Epics, Features, PBIs, Tasks) | 3,0 |
| WebApp (funcional e publicado) | 2,0 |
| Banco de Dados (script SQL + CSV válido) | 2,0 |
| Monitoramento (Application Insights + Alerta 404) | 2,0 |
| Documentação (prints, repositório e estrutura) | 1,0 |

---

## 🚀 Resumo
Projeto acadêmico desenvolvido para o **Checkpoint 2** da disciplina **DevOps Tools & Cloud Computing (FIAP)**.  
Tem como propósito integrar práticas de **desenvolvimento, monitoramento e automação em nuvem** com o ecossistema Azure, demonstrando na prática a aplicação de conceitos de **observabilidade, deploy e versionamento contínuo**.
