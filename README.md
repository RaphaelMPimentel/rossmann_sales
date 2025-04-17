# Previsão de Vendas em Lojas

## Visão Geral do Projeto

Neste projeto, desenvolvi uma solução completa para **previsão de vendas** utilizando dados históricos e metadados de lojas. O processo envolveu desde o preparo e análise exploratória dos dados até a engenharia de atributos e modelagem preditiva com aprendizado de máquina.

**Objetivo**: Prever as vendas diárias para as próximas 6 semanas, oferecendo suporte às decisões estratégicas da empresa de maneira escalável e automatizada.

**Resultado-chave**:  
> Aplicativo no Telegram conectado a modelos de previsão, permitindo que cada gerente de loja consulte, de forma prática, suas projeções futuras de vendas.

## Aplicativo no Telegram

Foi desenvolvido um aplicativo com API integrada ao Telegram, que disponibiliza previsões personalizadas de vendas por loja para as próximas 6 semanas.  
Essa interface oferece **acesso simples, direto e funcional** aos resultados da modelagem preditiva.

![app](img/app.png)

## Problema de Negócio

Após uma reunião com o CFO, os gerentes de loja foram solicitados a apresentar previsões detalhadas de vendas. A demanda simultânea por previsões individuais criou a necessidade urgente de uma solução precisa, automatizada e escalável.

## Estrutura do Projeto

### 1. **Preparação dos Dados**
- Leitura e junção de datasets de vendas e informações de loja
- Padronização de nomes (`snake_case`)
- Tratamento de dados faltantes e ajustes de tipo

### 2. **Análise Exploratória (EDA)**
- Sumários estatísticos
- Visualizações de séries temporais e desempenho por loja
- Análise de sazonalidade e identificação de outliers

### 3. **Engenharia de Atributos**
- Criação de variáveis para capturar tendências e sazonalidade
- Codificação de variáveis categóricas
- Normalização de atributos numéricos

### 4. **Estatísticas Descritivas**
- Análise de tendência central e variabilidade
- Relações entre atributos e a variável alvo (`sales`)

### 5. **Modelagem Preditiva**
- Treinamento e validação com modelos como:
  - Regressão Linear
  - Random Forest Regressor
  - XGBoost Regressor
- Otimização de hiperparâmetros
- Avaliação com **MAE**, **MAPE** e **RMSE**

### 6. **Geração de Insights e Forecasting**
- Avaliação da importância das variáveis
- Comparação entre previsões e vendas reais

## Funcionalidades do Projeto

- **Pipeline automatizado** de preparação de dados
- **Visualizações de alto impacto**: linhas do tempo, heatmaps e comparações por loja
- **Validação temporal personalizada** com rolling validation
- **Modelos robustos** de ensemble e boosting

## Bibliotecas e Ferramentas

- **Manipulação de Dados**: `pandas`, `numpy`
- **Visualização**: `matplotlib`, `seaborn`
- **Modelagem**: `scikit-learn`, `xgboost`, `boruta`

## Principais Insights

- **Sazonalidade clara**: Picos de venda em determinados meses e feriados
- **Desempenho por loja**: Algumas lojas se destacam sistematicamente
- **Fatores influentes**: Promoções, feriados e tipo de loja são cruciais

## Próximos Passos

- Incorporar fatores externos (ex: clima, economia local)
- Deploy em ambiente de produção para previsões em tempo real
- Criar alertas automáticos com base em desvios de previsão

## Competências Demonstradas

- **Forecasting com séries temporais**
- **Engenharia de Atributos voltada a negócios**
- **Automatização de processos analíticos**
- **Integração de modelos com interfaces práticas (Telegram Bot)**
- **Visão de produto e usabilidade em soluções analíticas**
