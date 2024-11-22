Thierry de Médio - RM 88839
João Pedro Nobre Buitor Carelli - RM 95762


# Previsão de Consumo Energético em Estações de Carregamento de Veículos Elétricos

## **Descrição do Projeto**
Este projeto visa desenvolver um modelo de Machine Learning para prever o consumo energético (**kwhTotal**) em sessões de carregamento de veículos elétricos. A solução foi implementada utilizando um dataset de carregamentos, com dados históricos sobre sessões, como duração, custos e tipo de instalação.

O modelo pode ser utilizado para otimizar o gerenciamento das estações, permitindo prever demanda, planejar recursos e reduzir custos.

---

## **Tecnologias Utilizadas**
- **Linguagem:** Python
- **Bibliotecas:** 
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib

---

## **Dataset**
Os dados utilizados foram provenientes de um dataset contendo:
- **Registros:** 3395 sessões de carregamento.
- **Colunas Relevantes:**
  - `chargeTimeHrs`: Duração do carregamento (horas).
  - `weekday`: Dia da semana.
  - `facilityType`: Tipo de instalação.
  - `dollars`: Custo associado à sessão.
  - `kwhTotal`: Consumo energético (variável alvo).

---

## **Metodologia**
1. **Pré-processamento dos Dados:**
   - Seleção de colunas numéricas.
   - Exclusão de colunas categóricas para simplificar o modelo.

2. **Divisão dos Dados:**
   - **80% Treinamento**: Para ajustar o modelo.
   - **20% Teste**: Para avaliar o desempenho.

3. **Modelo Preditivo:**
   - Algoritmo utilizado: **Random Forest Regressor**.
   - Métrica de Avaliação: **Root Mean Squared Error (RMSE)**.

4. **Visualização:**
   - Gráfico comparando valores reais e previstos do consumo energético.

---

## **Resultados**
- **RMSE:** 2.58 kWh, indicando uma precisão moderada do modelo.
- **Comparação Gráfica:**
  O gráfico gerado mostrou que o modelo consegue capturar tendências gerais, mas ainda apresenta desvios em cenários específicos.

---

