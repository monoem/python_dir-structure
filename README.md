readme_content = """# Gestion d'une Structure de Dossiers + Export JSON (Python)

Ce dépôt contient **trois scripts Python** permettant de :
1) créer une arborescence de dossiers à partir d’un dictionnaire,
2) écrire la structure dans un fichier **JSON**,
3) ré-afficher (et/ou créer si absent) la structure selon la présence du fichier JSON.

> Environnement illustratif : Windows (chemins en `C:\\Users\\...`), mais les scripts fonctionnent aussi sous Linux/Mac en adaptant le chemin de base.

---

## 🗂️ Contenu du dépôt

- `partie 01 - Creation des dossiers.py` : crée l’arborescence de dossiers via `os.makedirs`. fileciteturn0file1  
- `partie 02 - Ecriture du fichier json.py` : crée l’arborescence **et** écrit la structure dans un fichier JSON. fileciteturn0file2  
- `partie 03 - Print de la hierarchie si deja existante.py` : si le JSON existe, affiche la hiérarchie; sinon, crée l’arborescence puis génère le JSON. fileciteturn0file0

---

## 🔧 Pré-requis

- Python 3.8+ recommandé
- Droits d’écriture sur le répertoire de base
- (Optionnel) Environnement virtuel


### Installation rapide (optionnel)
```bash
# Créer et activer un venv (Windows)
python -m venv .venv
.venv\\Scripts\\activate

# ou (Linux/Mac)
python3 -m venv .venv
source .venv/bin/activate
