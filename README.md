# Projet d'Analyse des Attentes Professionnelles

Ce projet analyse les attentes et préférences professionnelles à partir de données d'enquête. L'analyse inclut des décompositions démographiques, les priorités professionnelles selon le genre et les catégories socioprofessionnelles, ainsi que les préférences pour l'indépendance dans les activités professionnelles.

Ce projet est réalisé en utilisant **R**, avec un accent sur le nettoyage des données, les statistiques descriptives et la visualisation.

---

## Fonctionnalités

- **Nettoyage des données** : Gère les valeurs manquantes et convertit les variables caractères en facteurs.
- **Statistiques descriptives** :
  - Distribution par âge.
  - Répartition par genre.
  - Catégories socioprofessionnelles des parents.
- **Analyse des attentes professionnelles** :
  - Priorités par genre.
  - Attentes selon les catégories socioprofessionnelles.
- **Visualisation** :
  - Graphiques en barres pour les fréquences et priorités.
  - Nuages de points pour les corrélations.
- **Visualisations personnalisées** : Met en évidence les tendances et relations entre les questions de l'enquête.

---

## Structure du projet

```
📁 Dossier du projet
├── data_questio.csv               # Jeu de données pour l'analyse
├── etude.py                       # Script Python pour le traitement avancé des données
├── main.py                        # Script principal R pour l'analyse des données
├── README.md                      # Documentation du projet
```

---

## Installation

### Prérequis
Ce projet nécessite **R** et les bibliothèques R suivantes :
- `tidyverse`
- `ggplot2`

### Étapes
1. Installez R depuis [CRAN](https://cran.r-project.org/).
2. Installez les bibliothèques requises dans R :
   ```R
   install.packages(c("tidyverse", "ggplot2"))
   ```

---

## Utilisation

### Exécution de l'analyse
1. Assurez-vous que `data_questio.csv` se trouve dans le répertoire de travail.
2. Exécutez le script `main.py` dans RStudio ou votre environnement R préféré :
   ```R
   source("main.py")
   ```

---

## Principaux résultats

1. **Distribution par âge** :
   - Tableau de fréquences et graphique en barres des groupes d'âge.
   
2. **Priorités par genre** :
   - Graphiques en barres montrant les attentes professionnelles selon le genre.
   
3. **Catégories socioprofessionnelles** :
   - Répartition des catégories socioprofessionnelles des parents des répondants.
   - Attentes professionnelles selon l'origine socioprofessionnelle.

4. **Corrélation** :
   - Nuage de points entre la clarté initiale et actuelle des objectifs professionnels.

5. **Préférences pour l'indépendance** :
   - Graphique en barres des préférences pour des activités professionnelles indépendantes.

6. **Valeurs sensibles** :
   - Distribution des valeurs auxquelles les répondants sont le plus sensibles dans les politiques d'entreprise.

---

## Visualisations

- **Graphiques en barres** : Représentent la distribution et les fréquences.
- **Nuages de points** : Mettent en évidence les corrélations entre les variables.
- **Graphiques en barres groupées** : Comparent les priorités professionnelles entre groupes.

---

## Processus de nettoyage des données

1. **Renommage des colonnes** : Supprime les caractères spéciaux et les espaces des noms de colonnes.
2. **Valeurs manquantes** : Supprime les lignes contenant des valeurs manquantes.
3. **Transformation des données** : Convertit les colonnes de type caractère en facteurs.

---

## Contributions

Les contributions sont les bienvenues ! Pour contribuer :
1. Forkez le dépôt.
2. Créez une branche pour vos modifications.
3. Commitez vos changements.
4. Ouvrez une pull request.

---

## Licence

Ce projet est sous licence MIT.

---

## Contact

**Shimwa Galille**  
[Profil GitHub](https://github.com/Shimwa-Galille)

---

## Remerciements

- Le projet utilise les bibliothèques R `tidyverse` et `ggplot2` pour la manipulation et la visualisation des données.

