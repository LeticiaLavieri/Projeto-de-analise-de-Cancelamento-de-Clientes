# Análise de Cancelamentos de Clientes

Por meio do intensivo gratuito de Python "Python Power Up" realizado pela Hashtag Treinamentos, foi conduzida uma análise em um banco de dados fictício para verificar informações de clientes de uma empresa. O objetivo é entender o percentual de cancelamento desses clientes e os motivos por trás desses cancelamentos, propondo insights para a redução desses números.

---


### Objetivo do Projeto

Este projeto visa realizar uma análise detalhada dos dados de cancelamento de clientes para identificar padrões e motivos comuns. Utilizando Python e a biblioteca Plotly, foram desenvolvidas visualizações interativas para facilitar a compreensão dos fatores que contribuem para os cancelamentos. Com base nessa análise, foram propostas estratégias baseadas em dados para aumentar a retenção de clientes.

---

### Descrição do Banco de Dados

A base de dados utilizada contém informações detalhadas dos clientes, tais como:

* Idade
* Sexo
* Tempo como cliente
* Frequência de uso
* Número de ligações para o call center
* Dias de atraso de pagamento
* Plano pertencente ao cliente (assinatura)
* Tempo de duração do contrato
* Total gasto
* Meses desde a última interação
* Status de cancelamento (1 = cancelou, 0 = assinante)
  
A base possui 50.000 linhas e 12 colunas, estando no formato CSV.

### Ferramentas e Bibliotecas Utilizadas

* Editor de Python: VSCode
* Bibliotecas: Pandas, Plotly

 ---
 
 ### Metodologia
 
 **Importação e Tratamento de Dados:**

Importação da biblioteca Pandas e leitura do banco de dados utilizando a função read_csv(), armazenando o banco de dados na variável "tabela". <br>
Remoção da coluna ID, que não traz informações significativas para a análise, utilizando a função drop(). <br>
Remoção de informações vazias na tabela com a função dropna() para padronizar a base de dados e manter a consistência nas colunas.<br>

**Análise Descritiva e Visualização:**

Utilização da função value_counts() para verificar a quantidade de cancelamentos, normalizando a informação em percentual.<br>
Análise dos tipos de contrato (mensal, trimestral e anual) para verificar se este é um fator que afeta diretamente o cancelamento do serviço.<br>
Criação de gráficos utilizando a biblioteca Plotly. Utilizou-se a plotly.express para gerar histogramas de cada coluna relacionada ao cancelamento.<br>

---

### Insights e Recomendações

**Coleta de Dados:**
Reunir dados históricos dos clientes, incluindo perfis demográficos, comportamento de uso, feedbacks e motivos de cancelamento.
Identificação de Padrões de Cancelamento:

**Analisar correlações entre diferentes variáveis e os cancelamentos.**
Utilizar técnicas de segmentação para identificar grupos de clientes com comportamentos semelhantes.

**Geração de Insights:**
Identificar os principais motivos de cancelamento e os fatores que mais influenciam essa decisão.
Avaliar o impacto de diferentes características do serviço e do perfil do cliente nos cancelamentos.

---

<img src="https://github.com/LeticiaLavieri/Projeto-de-analise-de-Cancelamento-de-Clientes/blob/main/Graficos/Sexo%20-%20tempo%20como%20cliente%20-%20Idade.png?raw=true" width="400" height="450"><img src="https://github.com/LeticiaLavieri/Projeto-de-analise-de-Cancelamento-de-Clientes/blob/main/Graficos/assinatura%20-%20dias%20atraso-%20ligacoes.png?raw=true" width="400" height="450">

---

### Conclusão

Este projeto fornece uma visão clara e baseada em dados sobre os cancelamentos de clientes, possibilitando a tomada de decisões informadas para melhorar a retenção de clientes. Com uma análise robusta e visualizações interativas, a empresa pode identificar os principais motivos de cancelamento e implementar ações eficazes para reduzir esse número, otimizando seus resultados e aumentando a satisfação dos clientes.
