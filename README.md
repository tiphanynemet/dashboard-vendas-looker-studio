# 📊 Painel de Acompanhamento de Vendas - Google Looker Studio

## Descrição do Projeto

Este projeto apresenta um dashboard interativo desenvolvido no **Google Looker Studio** para análise e acompanhamento de vendas. O painel oferece uma visão do desempenho comercial, incluindo análises temporais, geográficas, por categoria de produtos e perfil de clientes.

## Objetivo

Fornecer insights estratégicos sobre vendas através de visualizações que permitem:
- Monitoramento de performance de vendas
- Análise de tendências temporais
- Identificação de produtos e regiões de maior desempenho
- Segmentação de clientes VIP e não-VIP

---

## Principais Métricas e Visualizações

### KPIs Principais
- **Total de Vendas**: R$ 1,7 milhões
- **Média de Vendas**: R$ 8,4 mil
- **Quantidade de Produtos**: 200 unidades
- **Período de Análise**: Dezembro 2024 - Junho 2025

### Gráficos e Análises

#### 1. Vendas por Mês
- Visualização temporal mostrando sazonalidade
- Destaque para vale em dezembro/2024 e pico em fevereiro/2025

#### 2. Vendas por Categoria
- **Alimentos**: 22,5%
- **Vestuário**: 21,6%
- **Brinquedos**: 19,7%
- **Eletrônicos**: 19,2%
- **Móveis**: 17%

#### 3. Top 10 Produtos
1. Jogo de Tabuleiro - R$ 123,9 mil
2. Mesa - R$ 114 mil
3. Arroz - R$ 103,7 mil
4. Jaqueta - R$ 98,1 mil
5. Cadeira - R$ 97 mil
6. Leite - R$ 96,9 mil
7. Tênis - R$ 83,9 mil
8. Café - R$ 80,7 mil
9. Camiseta - R$ 79,2 mil
10. Notebook - R$ 77,2 mil

#### 4. Vendas por Estado
- **Bahia (BA)**: R$ 393,9 mil (líder)
- **Pernambuco (PE)**: R$ 269,8 mil
- **Rio Grande do Sul (RS)**: R$ 253,1 mil
- **Paraná (PR)**: R$ 224,4 mil
- **Rio de Janeiro (RJ)**: R$ 212 mil
- **São Paulo (SP)**: R$ 174,3 mil
- **Minas Gerais (MG)**: R$ 155,1 mil

---

## Tecnologias e Pré-requisitos

### Tecnologias Utilizadas
- **Google Looker Studio**: Plataforma principal para criação do dashboard
- **Fonte de Dados**: Arquivo CSV 

### Estrutura dos Dados (Campos Principais)
- `total_venda`: Valor total das vendas
- `nome_produto`: Nome do produto vendido
- `categoria`: Categoria do produto
- `estado`: Estado da venda
- `status_vip`: Classificação do cliente (VIP/Não VIP)
- `data_venda`: Data da transação

### Pré-requisitos
Para visualizar este projeto, você precisará de:
- Conta Google ativa
- Acesso ao Google Looker Studio
- O link do dashboard (disponível no arquivo `DASHBOARD_URL.txt` neste repositório)

---

## Insights Principais e Recomendações

### Descobertas Importantes
1. **Sazonalidade**: Forte variação mensal com pico em **fevereiro**.
2. **Distribuição Geográfica**: **Bahia** representa o maior mercado.
3. **Mix de Produtos**: **Alimentos** lideram as vendas por categoria.
4. **Top Performer**: **Jogo de Tabuleiro** é o produto mais vendido.

### Recomendações Estratégicas
- Investir em marketing na região Nordeste (**BA, PE**).
- Aumentar estoque de produtos de alto valor (jogos de tabuleiro e móveis).
- Desenvolver estratégias específicas para período de baixa (**dezembro**).
- Expandir programa VIP para aumentar ticket médio.
