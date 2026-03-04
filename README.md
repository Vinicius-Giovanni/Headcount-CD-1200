# BI Headcount CD 1200

Este repositório contém um projeto de **Power BI (PBIP)** para acompanhamento de **Headcount do CD 1200**.

## 🎯 Objetivo

O dashboard foi criado para apoiar a gestão do Centro de Distribuição 1200 com uma visão rápida de:

- Quantidade de colaboradores (headcount);
- Distribuição por **status**;
- Distribuição por **cargo**;
- Estrutura hierárquica (gerência, coordenação e chefia).

## 📁 Estrutura do projeto

- `BI Headcount CD 1200.pbip`: arquivo principal do projeto PBIP;
- `BI Headcount CD 1200.Report/`: definição das páginas e visuais do relatório;
- `BI Headcount CD 1200.SemanticModel/`: definição do modelo semântico;
- `main.py`: script Python simples presente no repositório;
- `pyproject.toml`: configuração do projeto Python.

## 📊 Principais visuais do BI

Com base na definição do relatório, o projeto possui visuais como:

- Gráfico de barras por **cargo**;
- Gráfico de rosca por **status**;
- Tabelas/matrizes com colaboradores e estrutura organizacional;
- Segmentação (filtro) por **empresa**.

## 🔎 Dimensões usadas no relatório

Alguns campos identificados na configuração do relatório:

- `nome`
- `status`
- `cargo`
- `empresa`
- `gerencia`
- `coordenador`
- `chefia`
- `matricula_nome`

## ▶️ Como abrir o projeto

1. Abra o **Power BI Desktop** (com suporte a projeto PBIP);
2. Abra o arquivo `BI Headcount CD 1200.pbip`;
3. Atualize as conexões de dados, se necessário;
4. Publique no serviço do Power BI (opcional).

## 🛠️ Manutenção

Para evolução deste BI, recomenda-se:

- Documentar origem e periodicidade das bases de dados;
- Versionar alterações de páginas/visuais via Git;
- Padronizar nomes de medidas e campos calculados;
- Registrar regras de negócio de headcount (ativos, afastados, terceiros etc.).

## 📌 Observação

Este README descreve o projeto de forma funcional e técnica para facilitar onboarding e manutenção do BI de headcount do CD 1200.
