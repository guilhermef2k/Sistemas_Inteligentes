# 4º Projeto: Classificação de Sinais de Radar Ionosférico (Adaline)

Este projeto consiste na implementação e análise de uma rede neural **Adaline** (Adaptive Linear Neuron) para a classificação de sinais de radar. O objetivo é distinguir sinais que indicam a presença de estrutura eletrônica coerente na ionosfera ("Good") daqueles que não indicam ("Bad").

---

## 📑 Visão Geral
O monitoramento da ionosfera é vital para sistemas de GPS e telecomunicações. Utilizando o dataset **Ionosphere** do repositório UCI, este projeto aplica o algoritmo Adaline para automatizar a identificação de irregularidades atmosféricas que podem causar falhas de transmissão.

---

## 🛠️ Tecnologias e Bibliotecas
* **Linguagem:** Python
* **Bibliotecas:** * `Pandas` e `NumPy` para manipulação de dados.
    * `Scikit-Learn` para implementação do modelo (`SGDClassifier`) e métricas.
    * `Matplotlib` para visualização das curvas de convergência.
    * `StandardScaler` para padronização Z-score.

---

## 🚀 Metodologia

### 1. Pré-processamento
* **Recodificação Bipolar:** Conversão dos rótulos para `-1` (Bad) e `1` (Good), padrão necessário para o funcionamento do Adaline.
* **Padronização:** Aplicação de Z-score em todos os 34 atributos contínuos para garantir a estabilidade do Gradiente Descendente.
* **Divisão de Dados:** Separação estratificada entre treino (80%) e teste (20%).

### 2. Estudo da Taxa de Aprendizagem ($\eta$)
Foram testados cinco valores de $\eta$ ($10^{-4}, 10^{-3}, 10^{-2}, 5 \times 10^{-2}, 10^{-1}$) para observar o comportamento da função de custo (MSE) ao longo de 200 épocas.
* **Resultado:** O valor de **$\eta = 0.001$** foi selecionado por apresentar a convergência mais estável e o menor erro final.

---

## 📊 Resultados Obtidos

O modelo final apresentou um desempenho robusto, com destaque para a capacidade de identificar todos os sinais estruturados:

* **Acurácia Global:** 95.77%
* **Precisão (Good):** 93.88%
* **Recall (Good):** 100.00%
* **F1-Score (Good):** 96.84%

### Matriz de Confusão
```text
[[22  3]  -> (Sinais Bad)
 [ 0 46]]  -> (Sinais Good)
