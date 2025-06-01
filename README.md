# Tableau de bord pour l'analyse des données 
Déverrouillez vos analyses facilement. 

Ce tableau de bord, construit avec Dash et Plotly, permet aux data scientists, analystes et étudiants d'effectuer des tests statistiques (t-test, Shapiro-Wilk, Chi-squared, ANOVA) et de visualiser les résultats via des graphiques interactifs, le tout dans une interface web élégante.
# Les fonctions de ce tableauu de bord :
permet de :
📂 Importez facilement vos fichiers CSV ou Excel en un seul clic pour commencer .

📊Analysez vos données en profondeur grâce à des visualisations interactives et des outils puissants .

Gérez les données manquantes en utilisant des méthodes statistiques comme la moyenne, la médiane, ou même des algorithmes avancés .

🔍Effectuez des tests statistiques pour découvrir des relations significatives dans vos données .

Obtenez des prédictions avancées avec des modèles d'apprentissage automatique pour la maladie d'Alzheimer  en quelques étapes simples .
# Guide 
1- cliquez sur commencer l'exploration 
![image](https://github.com/user-attachments/assets/a9985535-f930-471d-9b4a-b1ef306315e8)
2- chargez le fichier de type csv ou excel :
![image](https://github.com/user-attachments/assets/733d4b3e-81ca-4cfa-89ab-e9364a857c4d)
3- Cliquez sur résumé des données:
![image](https://github.com/user-attachments/assets/5fef354c-cc5a-4563-8e2c-fa749e53b9f3)
4- imputez les valeurs manquantes  en utilisant des méthodes statistiques selon la nature de la variable (qualitative ou quantitative ) :
![image](https://github.com/user-attachments/assets/90108de0-0247-4635-8d84-d10a73e7b869)
5- Sélectionnez la colonne pour faire  la visualisation :
![image](https://github.com/user-attachments/assets/10aee763-76d4-44f5-bfd8-463d4650ebd4)
6- Visualisation des Corrélations:
![image](https://github.com/user-attachments/assets/197c4e52-cb54-403b-aecc-068f648f7a50)
7- effectuez une regression linéaire :
![image](https://github.com/user-attachments/assets/a9adb1e4-51be-4472-aae3-8011ca142f52)
8- Sélectionnez le type de test que vous voulez le faire :
![image](https://github.com/user-attachments/assets/8bea6129-f797-4e2e-a571-c3f6b3807988)
9- la partie de la prediction pour la maladie  d'Alzheimer avec le modéle Random Forest :
vous pouvez soit chargez un fichier qui content les données d'un patient et cliquez sur prédire pour voir les résultats de la prediction si le patient il est malade ou pas avec un niveau de confiance et aussi un echelle qui exprime le risque d'etre malade .

ou bien vous pouvez faire une prediction manuelle en ecrivant les données nécessaires pour le patient 

NB: le fichier doit avoir ces données :
Âge
Score MMSE (0-30)
CDR (0-3)
Niveau d'éducation (années)
Antécédents familiaux (0=Non, 1=Oui)
![image](https://github.com/user-attachments/assets/6829f167-0f00-4b8a-8dc9-e35e6e4d60b9)
et finalement la partie des questions fréquentes et les réponses :
![image](https://github.com/user-attachments/assets/9e5040c4-85db-4493-8aa5-d3220ef99b70)

## Prérequis

- Python 3.8 ou supérieur  
- Git (pour cloner le dépôt)  
- Jupyter Notebook (installé via les dépendances)
## Les etapes a suivre pour tester l'application :

1. Cloner le dépôt:

   ```bash
   git clone https://github.com/NsiriNour/Tableau_de_bord_
   cd Tableau_de_bord_
   ```

2. Installer les dépendances:

   ```bash
   pip install -r requirements.txt
   ```

3. lancer jupyter notebook:

   ```bash
   jupyter notebook
   ```
Une fois Jupyter ouvert dans votre navigateur, ouvrez le fichier projet fin d'annee.ipynb.

Exécutez les cellules du notebook pour lancer l'application et accéder à l'interface web 

port par défaut : http://127.0.0.1:8063
---

