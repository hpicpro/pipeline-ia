# pipeline-ia
Test pour la création d'une piepeline spark co-construit avec l'IA
Créer un projet pour maitriser l'IA avec la création d'une pipeline spark

## Objectifs

### Préparation du projet

Installation de l'environnement python, java et spark

Création de votre dossier de travail et création de votre environnement virtuel

```
mkdir -p C:/users/Moi/Documents/projets/pipeline-ia

python -m venve .venv

.\.venv\Scripts\Activate.ps1

python -m pip install --updgrade pip

pip install "pyspsark>=4.0,<4.1" pytest ruff

```

installation de java

lancement du premier test depuis l'environnement python venv
```
python -c "from pyspark.sql import SparkSession; s = SparkSession.builder.master('local[2]').appName('test').getOrCreate(); print('Spark version :', s.version); s.stop()"
```

That's work !





### Création de l'environnement

### Test de l'environnement

### Passage sur l'IA

#### premier prompt

