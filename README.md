# SQL-Analysis-Project-GlobalTech-Supplies

# Overview

Este projeto simula uma empresa fictícia chamada GlobalTech Supplies, que atua na distribuição de produtos de tecnologia e escritório em diferentes regiões e segmentos de mercado.
O objetivo é utilizar consultas SQL para analisar dados de clientes, pedidos, produtos e vendas, identificando gargalos de rentabilidade e apoiando decisões estratégicas.

# Contexto

Nesse projeto, procurei ampliar minha prática em SQL utilizando dados confiáveis e IA para gerar um problema de negócio baseado no contexto dos dados. Os dados desse projeto são do curso Microsoft Power BI Para Business Intelligence e Data Science da Data Science Academy.

# Estrutura do Banco de Dados

O banco é composto por quatro tabelas principais:
- TB_CLIENTES: informações de clientes (ID, nome, localização, mercado, segmento).
- TB_PEDIDOS: dados dos pedidos (ID, data, modo de envio, prioridade).
- TB_PRODUTOS: catálogo de produtos (ID, nome, categoria, subcategoria).
- TB_VENDAS: transações de vendas (pedido, produto, cliente, quantidade, valor, custo de envio).

# Problema de Negócio (Gerado por IA)
A empresa percebeu queda na margem de lucro em alguns segmentos e regiões.
As hipóteses levantadas foram:
- Custos de envio elevados em determinados mercados.
- Produtos/categorias com baixa margem de rentabilidade.
- Modos de envio impactando negativamente os custos.

# Relatórios Desenvolvidos
- Margem por Região e Segmento → Diretoria Comercial.
- Rentabilidade por Categoria/Subcategoria → Gerente de Produtos.
- Impacto do Modo de Envio → Gerente de Logística.
- Clientes mais e menos rentáveis → Equipe de Relacionamento (CRM).

# Consultas SQL
As queries foram organizadas em /queries e cada uma contém comentários explicando:
- O objetivo da consulta.
- A lógica utilizada (JOINs, agregações, filtros).
- O resultado esperado.

# Relatórios
Na pasta /reports estão os documentos dos relatórios gerados, organizados por área responsável.

# Como Reproduzir
- Importar as tabelas no SQLite.
- Executar os scripts da pasta /queries.
- Conferir os relatórios na pasta /reports.

# Conclusão
Este projeto mostra como SQL pode ser aplicado para resolver problemas reais de negócios, transformando dados brutos em insights estratégicos.
Ele também serve como material de estudo para quem deseja praticar consultas SQL em cenários empresariais.

