# INF8225 — Projet : RAG pour Question Answering (HyDE vs RAG Fusion)
Dans ce projet, nous explorons et comparons différentes méthodes de **Retrieval-Augmented Generation (RAG)** appliquées au **Question Answering**. Plus précisément, nous étudions les approches **HyDE** (Hypothetical Document Embeddings) et **RAG Fusion** (avec et sans reranker), afin d’évaluer leurs performances sur des jeux de données spécifiques.

Pour comparer nos résultats, nous utilisons le jeu de données **rag-mini-bioasq**, disponible sur Hugging Face via le lien suivant : [rag-mini-bioasq](https://huggingface.co/datasets/rag-datasets/rag-mini-bioasq).

```text
Structure du dépôt
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

