# 🌾 Classificação de Grãos com Machine Learning

Este projeto aplica a metodologia **CRISP-DM** (Cross-Industry Standard Process for Data Mining) para desenvolver um modelo de aprendizado de máquina capaz de classificar variedades de grãos de trigo com base em suas características físicas.

O objetivo é automatizar o processo de classificação em cooperativas agrícolas, aumentando a eficiência e reduzindo erros humanos.

## 📋 Sobre o Projeto

Utilizamos o **Seeds Dataset** do UCI Machine Learning Repository, que contém medições geométricas de grãos de trigo pertencentes a três variedades:
1. **Kama**
2. **Rosa**
3. **Canadian**

### Atributos Analisados
- Área
- Perímetro
- Compacidade
- Comprimento do Núcleo
- Largura do Núcleo
- Coeficiente de Assimetria
- Comprimento do Sulco do Núcleo

## 🚀 Metodologia (CRISP-DM)

O desenvolvimento seguiu as seguintes etapas:

1.  **Análise e Pré-processamento**:
    - Análise exploratória de dados (EDA) com histogramas, boxplots e scatter plots.
    - Verificação de valores ausentes e outliers.
    - Padronização dos dados utilizando `StandardScaler`.

2.  **Modelagem**:
    - Implementação e comparação de diversos algoritmos:
        - K-Nearest Neighbors (KNN)
        - Support Vector Machine (SVM)
        - Random Forest
        - Naive Bayes
        - Logistic Regression

3.  **Otimização**:
    - Ajuste de hiperparâmetros utilizando `GridSearchCV` para os modelos de melhor desempenho (SVM e Random Forest).

4.  **Avaliação e Interpretação**:
    - Análise de métricas como Acurácia, Precisão, Recall e F1-Score.
    - Interpretação da importância das features.

## 📊 Resultados

Os modelos **SVM** e **Random Forest** apresentaram os melhores resultados, com acurácia superior a **90%** após a otimização. As características como *Área*, *Perímetro* e *Comprimento do Sulco* mostraram-se determinantes para a distinção entre as variedades.

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas** & **NumPy** (Manipulação de dados)
- **Matplotlib** & **Seaborn** (Visualização)
- **Scikit-learn** (Machine Learning)
- **Jupyter Notebook**

## ⚙️ Como Executar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2.  Instale as dependências necessárias (caso não tenha):
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Execute o notebook `grain_classification.ipynb` em um ambiente Jupyter ou Google Colab.

---
Desenvolvido como parte da atividade "Da Terra ao Código" - FIAP.
