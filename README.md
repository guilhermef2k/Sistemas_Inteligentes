# Disciplina: Sistemas Inteligentes 

Repositório destinado ao armazenamento e documentação dos trabalhos e projetos desenvolvidos na disciplina de **Sistemas Inteligentes**, ministrada pelo Prof. Pedro Thiago Valério de Souza no curso de Engenharia da UFERSA (Pau dos Ferros).

---

## 👥 Autores
* **[Alex Bruno Duarte](https://github.com/alexb7z)** 
* **[Guilherme de França Vasconcelos](https://github.com/guilhermef2k)**

---

## 🚀 Projetos Desenvolvidos

### 1º Projeto: Predição de Potência em Usina Termelétrica (UTCC)
Construção de um modelo de **Regressão Linear Múltipla** para prever a produção de energia de uma usina de ciclo combinado com base em sensores ambientais.
* **Resultados:** R² de 0.9301 e RMSE de 4.5026 MW.
* **Tecnologias:** Python, Pandas, Scikit-Learn, Matplotlib e Seaborn.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/Regress%C3%A3o%20Linear/regressao_linear.ipynb)

---

### 2º Projeto: Predição de Doença Cardíaca (UCI Cleveland)
Construção de um modelo de **Regressão Logística** para classificar a presença ou ausência de doença cardíaca com base em indicadores clínicos.
* **Resultados:** Recall de 0.9286 e AUC-ROC de 0.9545.
* **Tecnologias:** Python, Pandas, Scikit-Learn.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/Regress%C3%A3o%20Log%C3%ADstica/Regressao_Logistica.ipynb)

---

### 3º Projeto: Classificação de Qualidade de Vinhos (UCI Wine Quality)
Desenvolvimento de um classificador **k-Nearest Neighbors (k-NN)** para categorizar vinhos tintos em níveis de qualidade (Baixa, Média e Alta)[cite: 3].
* **Resultados:** Acurácia global de 0.6875 (k=1)[cite: 3].
* **Tecnologias:** Python, k-NN (Manual e Scikit-Learn), MinMaxScaler[cite: 3].

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/kNN/kNN_wine.ipynb)

---

### 4º Projeto: Classificação de Sinais de Radar (UCI Ionosphere)
Implementação de uma **Rede Neural Adaline** para classificar retornos de radar ionosférico como "Good" (coerente) ou "Bad" (sem estrutura)[cite: 4].
* **Resultados:** Acurácia global de 0.9577 e Recall de 1.0000 para a classe "Good" ($\eta = 0.001$)[cite: 4].
* **Tecnologias:** Python, Adaline (SGDClassifier), StandardScaler, Matplotlib[cite: 4].

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/Adaline.ipynb)

---

## 🛠️ Ferramentas Utilizadas
Projetos desenvolvidos no **Google Colab**, utilizando bibliotecas como NumPy, Pandas, Matplotlib e Scikit-Learn[cite: 2, 3, 4].

## 📂 Estrutura do Repositório
* `/Regressão Linear`: Notebook e dataset de usina termelétrica.
* `/Regressão Logística`: Notebook e dataset de Cleveland.
* `/kNN`: Notebook e dataset de qualidade de vinhos[cite: 3].
* `/Adaline`: Notebook e dataset ionosférico[cite: 4].

---
*Este repositório é atualizado conforme o progresso das atividades letivas do semestre 2026.1.*
