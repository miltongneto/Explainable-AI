# Explainable-AI
Aplicação de técnicas de Explainable AI (XAI)

O notebook [xai.ipynb](xai.ipynb) contém diversos experimentos de XAI para o problema de classificação de doença cardíaca (https://archive.ics.uci.edu/ml/datasets/heart+disease).

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
