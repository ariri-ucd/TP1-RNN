# TP1 – RNN : Génération de musique au format ABC

## Description du projet
Ce projet met en pratique les concepts théoriques étudiés sur les **Réseaux de Neurones Récurrents (RNN)** pour résoudre un problème concret : la génération automatique de musique au format **ABC**.

Le TP inclut :  
- La manipulation de données textuelles musicales (fichiers ABC).  
- La conception d’un **modèle RNN** avec **PyTorch**.  
- L’entraînement du modèle sur un corpus musical.  
- La génération de nouvelles séquences musicales à partir d’une séquence de départ.

## Contenu du dépôt
- `TP1_RNN_ARIRI.ipynb` : Notebook principal du TP avec toutes les étapes (prétraitement, modèle, entraînement, génération).  
- `compte_rendu_TP1_ARIRI.pdf` : Rapport détaillé du TP.  
- `README.md` : Ce fichier d’information.  
## Prérequis
Avant de lancer le notebook, assurez-vous d’avoir installé :  
- Python ≥ 3.8  
- PyTorch  
- NumPy  
- pandas  
- matplotlib  
- (optionnel) jupyter ou JupyterLab  

Installation des dépendances via pip :  
```bash
pip install torch numpy pandas matplotlib jupyter
