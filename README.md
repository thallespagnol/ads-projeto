# 📊 Análise de Cancelamento de Clientes (Churn)

Este projeto faz parte de um estudo de **Data Insights** para entender por que uma base de mais de 50 mil clientes apresenta uma alta taxa de inatividade. O objetivo é identificar os principais motivos de cancelamento e propor ações estratégicas para reduzir esse número.

## 📋 Contexto
A empresa percebeu que a maioria da sua base de clientes já cancelou o serviço. Para reverter esse cenário, analisamos o comportamento desses clientes para encontrar padrões (gatilhos) que levam ao cancelamento.

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas**: Para manipulação e limpeza de dados.
* **Plotly**: Para visualização de dados e criação de gráficos interativos.
* **Jupyter Notebook**: Para o desenvolvimento da análise exploratória.

## 📈 Principais Insights Extraídos
Durante a análise no arquivo `inicial.ipynb`, identificamos três grandes motivos de cancelamento:

1. **Tipo de Contrato:** Clientes com contrato mensal têm uma taxa de cancelamento altíssima.
2. **Atendimento (Call Center):** Clientes que ligam mais de 4 vezes para o suporte tendem a cancelar.
3. **Atraso no Pagamento:** Clientes com mais de 20 dias de atraso dificilmente permanecem na base.

### Resultados da Estratégia Proposta:
Ao simular a correção desses problemas (convertendo contratos mensais em anuais e melhorando o suporte), a taxa de cancelamento caiu de **56%** para aproximadamente **18%**.

## 📁 Estrutura do Repositório
* `cancelamentos.csv`: Base de dados contendo informações demográficas e de consumo dos clientes.
* `inicial.ipynb`: Notebook com todo o passo a passo da limpeza e análise dos dados.
