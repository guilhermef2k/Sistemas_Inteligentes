# Disciplina: Sistemas Inteligentes 

Repositório destinado ao armazenamento e documentação dos trabalhos e projetos desenvolvidos na disciplina de **Sistemas Inteligentes**, ministrada pelo Prof. Pedro Thiago Valério de Souza no curso de Engenharia da UFERSA (Pau dos Ferros).

---

## 👥 Autores
* **Alex Bruno Duarte**
* **Guilherme de França Vasconcelos**

---

## 🚀 Projetos Desenvolvidos

### 1º Projeto: Predição de Potência em Usina Termelétrica (UTCC)
Este projeto consistiu na construção de um modelo matemático de **Regressão Linear Múltipla** para prever a produção de energia de uma usina de ciclo combinado com base em sensores ambientais.

* **Objetivo:** Otimizar o despacho energético através da análise de variáveis como Temperatura (AT), Vácuo (V), Pressão (AP) e Umidade (RH).
* **Resultados Alcançados:**
    * **R²:** 0.9301 (O modelo explica 93% da variabilidade dos dados).
    * **RMSE:** 4.5026 MW.
* **Tecnologias:** Python, Pandas, Scikit-Learn, Matplotlib e Seaborn.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/Regress%C3%A3o%20Linear/regressao_linear.ipynb)

---

### 2º Projeto: Predição de Doença Cardíaca (UCI Cleveland)
Construção de um modelo de **Regressão Logística** para classificar a presença ou ausência de doença cardíaca com base em indicadores clínicos coletados em consultas de rotina.

* **Objetivo:** Criar uma ferramenta de triagem precoce capaz de identificar pacientes de risco com alta confiabilidade.
* **Resultados Alcançados:**
    * **Recall:** 0.9286 (Alta capacidade de identificar pacientes doentes).
    * **AUC-ROC:** 0.9545 (Excelente capacidade de distinção entre as classes).
* **Tecnologias:** Python, Pandas, Scikit-Learn (LogisticRegression, StandardScaler).

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhermef2k/Sistemas_Inteligentes/blob/main/Regress%C3%A3o%20Log%C3%ADstica/Regressao_Logistica.ipynb)

---

## 🛠️ Ferramentas Utilizadas
A maioria dos projetos neste repositório foi desenvolvida utilizando o **Google Colab**, permitindo um ambiente de desenvolvimento em nuvem colaborativo e focado em Ciência de Dados.

## 📂 Estrutura do Repositório
* `/Regressão Linear`: Contém o notebook e o `dataset` utilizado no primeiro projeto.
* `/Regressão Logística`: Contém o notebook e a pasta `dataSet` com os dados de Cleveland.

---
*Este repositório é atualizado conforme o progresso das atividades letivas do semestre 2026.1.*
