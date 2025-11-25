# FIAP - Faculdade de Informática e Administração Paulista 

<p align="center">
  <a href="https://www.fiap.com.br/">
    <img src="https://github.com/henriquehsilva/template-projeto-fiap/blob/main/assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width="40%" height="40%">
  </a>
</p>

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

## 📄 Licença

Projeto acadêmico - FIAP 2025 - [LICENSE](./LICENSE.md) 

---

**🌾 FarmTech Solutions** - Transformando dados em decisões inteligentes para a agricultura do futuro!

## Time
<p align="left">
  <a href="https://github.com/agodoi" target="_blank">
    <img src="https://github.com/agodoi.png" width="64" height="64" alt="@agodoi" />
  </a>
  <a href="https://github.com/SabrinaOtoni" target="_blank">
    <img src="https://github.com/SabrinaOtoni.png" width="64" height="64" alt="@SabrinaOtoni" />
  </a>
  <a href="https://github.com/henriquehsilva" target="_blank">
    <img src="https://github.com/henriquehsilva.png" width="64" height="64" alt="@henriquehsilva" />
  </a>
  <a href="https://github.com/manoellaweiser-gif" target="_blank">
    <img src="https://github.com/manoellaweiser-gif.png" width="64" height="64" alt="@manoellaweiser-gif" />
  </a>
  <a href="https://github.com/JoaoMDPaiva" target="_blank">
    <img src="https://github.com/JoaoMDPaiva.png" width="64" height="64" alt="@JoaoMDPaiva" />
  </a>
  <a href="https://github.com/Luiz-Frederico" target="_blank">
    <img src="https://github.com/Luiz-Frederico.png" width="64" height="64" alt="@Luiz-Frederico" />
  </a>
  <a href="https://github.com/younmariana-create" target="_blank">
    <img src="https://github.com/younmariana-create.png" width="64" height="64" alt="@younmariana-create" />
  </a>
</p>
