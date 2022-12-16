# M2_ILW_Projet_Spe
Projet de spécialité M2 ILW Ensitech

Le projet consiste en l'étude de l'évolution et la prédiction des prix des biens/terrains immobiliers en France. 

Il va contenir deux étapes majeures : 
  * La recupération de bases de données par plusieurs moyens, leur concaténation.
  (Base déjà réalisées, bases que l'on va créer ect...)
  
  * Une fois une grande base de données créée, nous utiliserons notre jeu de données afin d'entrainer un algorithme de Machine Learning pour prédire l'évolution théorique du marché.
  (Type, Taille, Lieu, Pièces, Taux de Criminalité, Transport à proximité, Commerces ect...)
  
***************** PARTIE 1 *****************

Afin d'entrainer notre IA à faire des prédictions, nous aurons besoin de récuperer des bases de données depuis diverses plateformes.
Nous allons concaténer différentes données afin de créer notre propre base de données.

Dans l'idéal, l'étude du produit désiré (appartement, maison, terrain, ect...) se fera sous différents critères de recherche et prendra en compte différents attributs géographiques : 

Critères de recherches : 
  - Lieu
  - Nombre de pièces
  - Type de structure
  - Surface terrain
  
 Attributs géographiques : 
  - Type de ville
  - Transports à proximité (métro, bus, train, aréoport)
  - Taux Criminalité locale
  - Zone industrielle
  
  16/12/2022 - Création d'un document sur lequel seront regroupés les critères de recherche.
             - Modification de 8 bases de données tirées du WEB afin d'en extraire les données lié au Val D'Oise
             - Focalisation du projet au Val D'Oise
             - La base de donnée des aéroports ne sera pas utilisable car aucune donnée n'appartient au Val D'Oise.
             - Mise à jour du fichier THE_CSV
             
***************** PARTIE 2 *****************

Sur un site WEB, nous permettrons à l'utilisateur de rentrer des criètres de recherches précis parmis une multitude de propositions afin d'affiner ces choix.
L'IA qui aura été entrainée avec notre base de données lui affichera un résultat(prix théorique) prenant en compte les valeurs précédentes.

***************** DOCUMENTS A RENDRE *****************
  Fichiers qui seront présentés : 
  
    Rapport écrit (30 - 60 pages) 
    Présentation PPTX du projet
    Les codes Front et Back
    
  Technologies utilisées : 
  
    JAVA
    JAVASCRIPT
    HTML
    PHP
    CSS
    PYTHON
    POWERPOINT
    EXCEL
    
  Gestion de projet :
  
    Jira 
    Scrum 
    
  Conception de projet: 
    
    StartUML
 
  Méhodes utilisées : 
  
    Extraction, transformation, chargement de données  (ETL)
    Machine Learning( reseau de neurone, Regression ...) 
    Site web 
