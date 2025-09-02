# Estudo de Benefícios e Abertura de Agências

Este repositório contém análises realizadas sobre dados de concessão de benefícios do INSS, com foco em identificar cidades atrativas para abertura de novas agências e avaliar métricas financeiras relacionadas ao negócio.

## 📂 Estrutura do Projeto

- `app/` → Notebook principal (`app.ipynb`) com todo o fluxo de análise.
- `app/` → Notebook principal (`Clean_Data.ipynb`) com os principais tratamentos da base bruta.
- `bases/dimensao/` → Contém tabelas auxiliares/dimensionais para cruzamento de informações.
- `bases/tratadas/` → Base consolidada (`BASE_CONSOLIDADA.csv`) e outras bases tratadas para análise.

## 🚀 Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** → Manipulação de dados
- **NumPy** → Cálculos numéricos
- **Tabulate** → Exibição de tabelas
- **Jupyter Notebook** → Ambiente de análise

## 🔎 Etapas do Estudo

1. **Leitura e Tratamento dos Dados**
   - Importação da base consolidada.
   - Criação da variável `municipio_uf` a partir das colunas originais.
   - Filtro para competências específicas (2025-01, 2025-02, 2025-03).

2. **Análise de Abertura de Agências**
   - Contagem de benefícios concedidos por município.
   - Consolidação de totais e médias.
   - Seleção das **30 cidades mais atrativas** para implantação de novas agências.

3. **Análise Financeira**
   - **Breakeven (ponto de equilíbrio):** quantidade mínima de clientes necessários para sustentar a operação mensalmente.
   - **Payback:** tempo necessário para recuperar o investimento inicial.
   - **LTV (Lifetime Value):** valor esperado por cliente ao longo do tempo, incluindo análises por permanência e escalabilidade.

## 📊 Resultados Esperados

- Lista das **30 cidades com maior potencial** para abertura de novas agências.
- Indicadores de viabilidade financeira por cidade (conversão, payback, LTV).
- Insights estratégicos sobre **onde há escala** e **quem vale mais por cliente**.

## 📝 Como Reproduzir

1. Clone o repositório:
   ```bash
   git clone https://github.com/BENITEZGUI/teste-tecnico.git
