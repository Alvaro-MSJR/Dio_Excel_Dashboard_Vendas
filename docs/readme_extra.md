🎮 Xbox Sales Dashboard | Excel 2016 | Business Intelligence Project










📌 Índice

1. Visão Geral Técnica

2. Arquitetura do Projeto

3. Modelagem de Dados

4. Camada de Processamento

5. Dashboard e Camada de Apresentação

6. Filtros e Interatividade

7. Indicadores e Métricas

8. Aplicação de Negócio

9. Como Atualizar a Base

1. Visão Geral Técnica

Projeto desenvolvido em Excel 2016 com foco em:

Estruturação de base transacional

Modelagem analítica

Consolidação via Tabelas Dinâmicas

Construção de Dashboard executivo

Aplicação de boas práticas de organização e layout

Objetivo: transformar dados brutos de vendas do produto Xbox em informações estratégicas orientadas à tomada de decisão.

2. Arquitetura do Projeto

O arquivo Excel está estruturado em 4 camadas lógicas:

/assets        → Identidade visual (logos, cores, ícones)
/data          → Base bruta de vendas
/calculos      → Tabelas dinâmicas e métricas consolidadas
/dashboard     → Camada visual executiva

Abas do Arquivo:
Aba	Função Técnica
Asset	Biblioteca visual (cores, tipografia, identidade)
Base	Base de dados transacional
Calculo	Processamento analítico (Tabelas Dinâmicas)
Dashboard	Visualização consolidada

Arquitetura organizada no padrão Base → Processamento → Visualização (sem mistura de camadas).

3. Modelagem de Dados

A base contém dados estruturados com variáveis como:

Produto

Data

Quantidade vendida

Valor unitário

Receita total

Categoria

A modelagem segue padrão tabular estruturado para permitir:

Agregações por período

Consolidação por produto

Cálculo de indicadores de performance

Não há segmentação por região.
Os filtros disponíveis são:

Produto

Período

4. Camada de Processamento

A aba Calculo contém:

Tabelas Dinâmicas

Consolidações de Receita

Agrupamentos por período

Rankings de produto

Base para construção dos gráficos

Principais operações realizadas:

SOMA para agregação de receita

SOMA.SE para consolidação condicional

PROCV para vinculação de atributos auxiliares

Cálculos percentuais para análise de participação

Agrupamento de datas em períodos

Processamento separado da camada visual para garantir:

✔ Governança
✔ Reprodutibilidade
✔ Facilidade de manutenção

5. Dashboard e Camada de Apresentação

A aba Dashboard consolida:

KPIs principais

Gráficos comparativos

Indicadores de performance

Visão executiva limpa e objetiva

Elementos Visuais:

Cards de indicadores

Gráficos de colunas

Gráficos de tendência temporal

Ranking de produtos

Layout padronizado

A identidade visual é controlada via aba Asset, garantindo consistência estética.

6. Filtros e Interatividade

O dashboard possui:

🎛 Segmentação por Produto

Permite análise individual ou comparativa.

📅 Segmentação por Período

Permite visualizar evolução temporal.

Toda a navegação é dinâmica e impacta simultaneamente:

Indicadores

Gráficos

Rankings

7. Indicadores e Métricas

Exemplos de métricas exibidas:

Receita Total

Volume de Vendas

Ticket Médio

Participação por Produto

Evolução Temporal

Produto com Maior Receita

Os indicadores são derivados diretamente das Tabelas Dinâmicas.

8. Aplicação de Negócio

Este dashboard permite:

Avaliar performance de vendas

Identificar produtos com maior contribuição

Analisar tendência ao longo do tempo

Apoiar decisões comerciais

Simular cenários via filtros

Aplicável para:

Controladoria

Planejamento Comercial

BI Corporativo

Gestão de Portfólio de Produtos

9. Como Atualizar a Base

Acessar aba Base

Inserir novos registros mantendo o padrão das colunas

Atualizar todas as Tabelas Dinâmicas

O Dashboard será atualizado automaticamente

Fluxo técnico:

Base → Atualizar Tabelas Dinâmicas → Dashboard Atualizado


---

📢 TEXTO DE APRESENTAÇÃO PARA LINKEDIN

🎮 Dashboard de Vendas Xbox | Excel 2016 | Business Intelligence

Desenvolvi um dashboard analítico estruturado em Excel 2016 com foco em modelagem de dados, consolidação via Tabelas Dinâmicas e construção de camada executiva orientada à tomada de decisão.

O projeto foi estruturado em três camadas:

• Base transacional organizada
• Camada de processamento analítico
• Dashboard executivo interativo

Principais entregas:

✔ KPIs consolidados
✔ Análise de performance por produto
✔ Evolução temporal de vendas
✔ Métricas derivadas (ticket médio, participação, ranking)
✔ Navegação dinâmica via filtros de produto e período

O foco foi aplicar boas práticas de organização, separação de camadas e clareza visual, simulando um fluxo de BI tradicional mesmo dentro do Excel.

Esse projeto reforça minha atuação em:

Business Intelligence

Data Analytics

Modelagem de dados

Consolidação de métricas

Construção de dashboards executivos

Repositório disponível no GitHub.

#Excel #BusinessIntelligence #DataAnalytics #Dashboard #BI #DataVisualization #AnaliseDeDados #Controladoria