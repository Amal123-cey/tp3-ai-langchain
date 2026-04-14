# TP IA - Notebook LangChain

Ce TP montre un exemple d'utilisation d'agents et d'outils avec LangChain, OpenAI et d'autres bibliothèques Python.

## Contenu du projet
- `tp3.ipynb` : notebook principal qui crée plusieurs agents et outils
- `requirements.txt` : dépendances Python nécessaires
- `.env.example` : modèle de fichier de configuration pour la clé OpenAI
- `.gitignore` : exclusions Git pour le projet

## Installation
1. Ouvrir un terminal dans le dossier du projet
2. Installer les dépendances :

```powershell
python -m pip install -r requirements.txt
```

## Configuration
1. Copier `.env.example` en `.env`
2. Remplir la clé API OpenAI :

```text
OPENAI_API_KEY=your_openai_api_key_here
```

## Exécution
1. Démarrer Jupyter Notebook ou JupyterLab
2. Ouvrir `tp3.ipynb`
3. Exécuter les cellules dans l'ordre pour tester les agents et les outils

## Objectifs du TP
- Créer un agent de base avec `langchain`
- Utiliser `langchain-openai` pour appeler un modèle GPT
- Ajouter des outils personnalisés (`get_weather`, `get_employee_info`, `search_web`)
- Tester une sélection dynamique de modèle avec un middleware
- Manipuler des variables d'environnement avec `python-dotenv`

## Lien GitHub
Ajouter le lien du dépôt ici :

`https://github.com/votre-utilisateur/votre-repository`

## Nom recommandé pour le repository
`tp3-ai-langchain`
