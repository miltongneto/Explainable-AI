# Explainable-AI
Aplicação de técnicas de Explainable AI (XAI)

O notebook [xai.ipynb](xai.ipynb) contém diversos experimentos de XAI para o problema de classificação de doença cardíaca.

Os experimentos contém com os seguintes algoritmos:
- Feature Importance
- LIME
- Anchor
- SHAP
- Partial Dependence Plot (PDP)
- Accumulated Local Effects Plot (ALE)
- Counterfactual

## Como executar o projeto
```
git clone https://github.com/miltongneto/Explainable-AI/
cd Explainable-AI
pip install -r requirements.txt
jupyter notebook 
```

Também é possível ver os experimentos através do arquivo HTML ([xai.html](xai.html)).

## Libs utilizadas para XAI
- [alibi](https://github.com/SeldonIO/alibi)
- [Anchor](https://github.com/marcotcr/anchor)
- [ELI5](https://github.com/TeamHG-Memex/eli5)
- [lime](https://github.com/marcotcr/lime)
- [PDPbox](https://github.com/SauceCat/PDPbox)
- [SHAP](https://github.com/slundberg/shap)

## Dataset
A base de dados com informações de doenças cardíacas está disponível no repositório do UCI Machine Learning (https://archive.ics.uci.edu/ml/datasets/heart+disease).
O problema foi abordado como classificação binária, realizando a predição se apresenta a doença ou não.
As features são:
- **age** - age
- **sex** - sex (1 = male; 0 = female)
- **cp** - chest pain type (4 values: 1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 = asymptomatic)
- **trestbps** - resting blood pressure
- **chol** - serum cholestoral in mg/dl
- **fbs** - fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg** - resting electrocardiographic results (values 0,1,2)
- **thalach** - maximum heart rate achieved
- **exang** - exercise induced angina (1 = yes; 0 = no)
- **oldpeak** - ST depression induced by exercise relative to rest
- **slope** - the slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 = downsloping)
- **ca** - number of major vessels (0-3) colored by flourosopy
- **thal**- 3 = normal; 6 = fixed defect; 7 = reversable defect


## Modelagem
O objetivo deste projeto não está na performance do classificador, mas sim em sua interpretação e em explicar suas decisões. Ainda assim foram realizados devidas separações do dataset em conjuntos de treino, validação e teste, e também aplicada as métricas de avaliação. Os modelos foram o Random Forest do scikit-learn e uma rede neural artificial do Keras.

## Resultados

### Feature Importance
### LIME
### Anchor
### SHAP
### Partial Dependence Plot (PDP)
### Accumulated Local Effects Plot (ALE)
### Counterfactual

