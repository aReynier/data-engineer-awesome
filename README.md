# Awesome data engineer
✨ Bienvenue sur cet Awesome ✨

Le but de ce dépôt est de rassembler **uniquement des liens**, utiles dans le cadre d'un parcours de data engineer. Ceci est une initiative personnelle, mais toute contribution reste la bienvenue.

## Sommaire
### Data engineering
- [Généralités sur le data engineering](/00_generalities/00_01_generalities.md)
- [Github](/01_github/01_01_github.md)
- [bash](/02_bash/02_01_bash.md)
- [cron](/03_cron/03_01_cron.md)
- Conception:
    - [Merise](/04_conception/04_01_merise.md)
    - [UML](/04_conception/04_02_uml.md)
- Base de données:
    - [Généralités](/05_database/05_01_generalities.md)
    - [PostgreSQL](/05_database/05_02_postgresql.md)
    - [HDFS](/05_database/05_03_hdfs.md)
    - [MongoDB](/05_database/05_04_mongodb.md)
    - [Apache Hive](/05_database/05_05_apache_hive.md)
- [Data warehouse](/06_data_warehouse/06_01_data_warehouse.md)
- [Data lake](/07_data_lake/07_01_data_lake.md)
- [Big data](/08_big_data/08_01_big_data.md)
- [SQL](/09_sql/09_01_sql.md)
- [Python](/10_python/10_01_python.md)
- [Hadoop](/11_hadoop/11_01_hadoop.md)
- [Spark](/12_spark/12_01_spark.md)
- Extraction et transformation de données:
    - [Airbyte](/13_data_extract_transform/13_01_airbyte.md)
    - [Talend](/13_data_extract_transform/13_02_talend.md)
- orchestration et déploiement:
    - [Docker](/14_orchestrate_deploy/14_01_docker.md)
    - [Kubernetes](/14_orchestrate_deploy/14_02_kubernetes.md)
    - [Airflow](/14_orchestrate_deploy/14_04_dagster.md)
    - [Dagster](/14_orchestrate_deploy/14_04_dagster.md)
    - [CI/CD](/14_orchestrate_deploy/14_05_ci_cd.md)
- Cloud:
    - [Azure](/15_cloud/15_01_aws.md)
    - [AWS](/15_cloud/15_02_azure.md)
    - [CGP](/15_cloud/15_03_cgp.md)

### Sujets connexes
- [Anglais professionnel](/16_professional_english/16_01_professional_english.md)
- Feuille de calcul:
    - [Excel](/17_spreadsheet/17_01_excel.md)
    - [Google sheets](/17_spreadsheet/17_01_google_sheets.md)
- [Intelligence artificielle](/18_ia/18_01_ia.md)
- [Mathématiques orientés data](/19_data_math/19_01_data_math.md)
- [Cybersécurité](/20_cybersecurity/20_01_cybersecurity.md)

## Comment contribuer ? 

Envie de participer à ce dépôt ? Tout d'abord merci!

Voici comment faire :

### 1. Fork le dépôt

### 2. Ajouter du contenu

#### Pour ajouter un lien
C'est tout simple :
- Un tiret eespace, suivi d'une petite description du contenu puis deux points
- Et le lien juste en dessous!

**Par exemple :**
- Site de référence sur les diagrammes UML :
https://www.uml-diagrams.org/

#### Pour les commits
Dans l'idéal, employer conventional commits

#### Pour ajouter un ou plusieurs liens 
Le principal ici est de mettre un "scope" correspond à la partie correpondante pour savoir où le lien a été rajouté, pour le moment, pas besoin d'ajouter les numéros de partie. Par exemple, pour un lien concernant les formes normales:
```
docs(normal-forms): Add link
```

#### Pour modifier la structure
Même principe : utilisez un scope (sauf si l'opération est plus grosse qu'une simple section) et précisez l'opération dans le titre.

#### Pour les corrections
Utilisez le mot-clé "fix" au lieu de "docs" :
```
fix(README): correct some typos
```

### 3. Pull Request
Proposez vos modifications via une PR ! Encore merci!
