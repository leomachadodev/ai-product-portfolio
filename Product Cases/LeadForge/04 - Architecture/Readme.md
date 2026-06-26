# LeadForge

# 04 - Architecture

## Visão Geral

A arquitetura do LeadForge foi projetada para centralizar todo o processo de prospecção comercial em uma única plataforma.

O sistema foi estruturado em módulos independentes, permitindo que cada CRM opere de forma isolada, com sua própria Inteligência Artificial, catálogo de serviços, pipeline comercial e base de leads.

Essa abordagem permite atender diferentes nichos de mercado sem compartilhar contexto entre operações comerciais distintas.

---

# Arquitetura do Produto

A plataforma foi organizada nos seguintes módulos principais:

- Dashboard
- CRM por Nicho
- Busca Automática de Leads
- Pipeline Comercial
- Gestão de Leads
- Cérebro da IA
- Catálogo de Serviços
- Administração

---

# Fluxo Macro do Produto

Criar CRM

↓

Configurar Cérebro da IA

↓

Cadastrar Serviços

↓

Buscar Leads

↓

Classificar Oportunidades

↓

Pipeline Comercial

↓

Contato

↓

Negociação

↓

Fechamento

---

# Módulos

## Dashboard

Responsável pela gestão dos CRMs criados pelo usuário.

Principais responsabilidades:

- Criar novos CRMs
- Visualizar quantidade de leads
- Gerenciar operações comerciais
- Acessar cada CRM individualmente

---

## CRM por Nicho

Cada CRM representa um segmento específico de mercado.

Exemplos:

- Escritórios Contábeis
- Dentistas
- Gestores de Tráfego
- Imobiliárias

Cada CRM possui configuração totalmente independente.

---

## Busca Automática de Leads

Permite localizar empresas através do Google Maps utilizando filtros como:

- Nicho
- Cidade
- Quantidade de resultados
- Nota mínima
- Empresas sem site

Os leads encontrados são enviados automaticamente para o CRM correspondente.

---

## Pipeline Comercial

Organiza visualmente todas as oportunidades utilizando Kanban.

Principais estágios:

- Novo Lead
- Contato Feito
- Em Negociação
- Proposta Enviada
- Fechado
- Perdido

---

## Gestão de Leads

Cada lead possui informações como:

- Empresa
- Cidade
- Avaliação Google
- Website
- WhatsApp
- Histórico Comercial
- Situação Atual

---

## Cérebro da IA

Módulo responsável pela contextualização da Inteligência Artificial.

Permite configurar:

- Dados da Empresa
- Cliente Ideal (ICP)
- Processo Comercial
- Serviços
- Diferenciais
- Comunicação
- Regras da IA
- Critérios de Qualificação
- Mensagens utilizadas pela IA

Todo esse contexto é utilizado nas automações e atendimentos realizados pela Inteligência Artificial.

---

## Catálogo de Serviços

Cada CRM possui seu próprio catálogo de serviços.

Cada serviço pode possuir:

- Nome
- Descrição
- Preço
- Prazo de entrega
- Status

Essas informações também são utilizadas pela IA durante o atendimento.

---

## Administração

Responsável pelas configurações gerais da plataforma.

---

# Perfis de Usuário

Administrador

↓

Usuário

---

# Principais Entidades

- Usuário
- CRM
- Lead
- Empresa
- Serviço
- Pipeline
- IA
- Mensagem

---

# Relacionamento entre Entidades

Usuário

↓

CRM

↓

Cérebro da IA

↓

Serviços

↓

Busca Automática

↓

Lead

↓

Pipeline

↓

Negociação

---

# Integrações

O LeadForge foi concebido para integração com:

- Google Maps
- OpenAI
- Evolution API
- WhatsApp
- Supabase
- N8N
- Webhooks

---

# Escalabilidade

A arquitetura permite evolução através da inclusão de novos módulos sem alterar a estrutura principal da plataforma.

Exemplos:

- Lead Scoring
- Campanhas
- E-mail Marketing
- Agentes Especializados
- CRM Omnichannel
- Dashboard Executivo
- Aplicativo Mobile

---

# Resultado da Architecture

Ao concluir esta etapa foi definida toda a arquitetura funcional do LeadForge, estabelecendo seus módulos, entidades, integrações e fluxo operacional, criando uma estrutura escalável para evolução contínua da plataforma.
⭐ Ficou MUITO melhor.

Depois de analisar as telas, identifiquei o verdadeiro núcleo do produto.

O LeadForge não gira em torno do Pipeline.

Ele gira em torno do CRM por Nicho.

Na prática, a arquitetura é:

Usuário

↓

CRM por Nicho

↓

Cérebro da IA

↓

Serviços

↓

Busca Automática

↓

Leads

↓

Pipeline

↓

Negociação