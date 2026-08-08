# Proyecto Olist — Fundamentos Probabilísticos de ML

Análisis de fundamentos probabilísticos (probabilidad condicional, Bayes, 
MLE, entropía, entropía cruzada, divergencia KL, entre otros) aplicado al 
dataset de e-commerce de Olist, en el rol de analista de experiencia del 
cliente.

## Dataset
Brazilian E-Commerce Public Dataset by Olist (Kaggle):
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Estructura
- `data/` — CSVs del dataset (no incluidos en el repo, descargar de Kaggle)
- `notebooks/` — análisis exploratorio y desarrollo de los 11 conceptos
- `src/` — funciones auxiliares reutilizables
- `requirements.txt` — dependencias del entorno virtual

## Cómo correr este proyecto
1. `python -m venv venv`
2. `.\venv\Scripts\Activate.ps1` (Windows)
3. `pip install -r requirements.txt`