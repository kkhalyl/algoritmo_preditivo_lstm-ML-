# 📊 Previsão de Arrecadação com IA - SEFAZ

Este projeto foi desenvolvido como resposta a uma demanda do setor de arrecadação da Sefaz, com o objetivo de automatizar as previsões de arrecadação que antes eram feitas manualmente, consumindo tempo e suscetíveis a imprecisões.

---

## 💡 Objetivo

Utilizar redes neurais recorrentes (LSTM e GRU) para analisar a arrecadação histórica (desde 1999) e prever os valores futuros até 2025.

---

## !Atenção!

Todos os dados utilizados foram substituídos por valores irreais para garantir a proteção dos dados.

---

## 🧠 Técnicas Utilizadas

- Redes Neurais Recorrentes (LSTM e GRU)
- Ajuste de hiperparâmetros
- Normalização com MinMaxScaler
- Avaliação com MSE e MAE
- Visualização com matplotlib

---

## 📈 Resultados

- Modelo capaz de capturar tendências, sazonalidades e picos.
- Gráficos claros para análise comparativa entre valores reais e previstos.
- Previsões confiáveis para apoiar a tomada de decisão no setor público.

---

## 🚀 Tecnologias

- Python
- TensorFlow / Keras
- Pandas / NumPy / Matplotlib
- Google Colab (ambiente de desenvolvimento)

---

## 📎 Executando

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seuusuario/previsao-arrecadacao-sefaz.git
cd previsao-arrecadacao-sefaz
pip install -r requirements.txt
