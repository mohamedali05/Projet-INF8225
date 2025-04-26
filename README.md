# INF8225 — Projet : RAG pour Question Answering (HyDE vs RAG Fusion)

```text
Structure du dépôt :    
├── WikipediaTesting/                          # Tests sur un autre jeu de données (rag-mini-wikipedia)  
├── data/                                      # Jeu de données (rag-mini-bioasq)
├── fine_tuned_crossencoder/                   # Modèle reranker entraîné
├── models_encoder/                            # Modèle encodeur entrainé  
├── INF8225_Projet_Encoder_Base.ipynb          # Retrieval avec Encodeur (Modèle BGE de base)  
├── INF8225_Projet_Encoder_Finetuned.ipynb     # Retrieval avec Encodeur finetuné (DPR)  
├── INF8225_Projet_Hyde.ipynb                  # Retrieval avec HyDE  
├── INF8225_Projet_RAG_Fusion.ipynb            # Retrieval avec RAG Fusion (RRF)  
├── INF8225_Projet_RAG_Fusion_Reranker.ipynb   # Retrieval avec RAG Fusion + Reranker  
├── INF8225_Projet_RAG_Generator.ipynb         # Fichier template pour la génération de réponses (Modèle Mistral)
```
