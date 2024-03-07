---
title: "Notre projet"
description: "Retrouvez ici une description complète du développement notre projet"
featured_image: '/images/Zoom_moyen.png'
menu:
  main:
    weight: 1
---

# Spécifications techniques :

Notre dispositif doit mettre en avant les caractéristiques suivantes :  

**-Collecte et analyse des données :** Le prototype collectera, stockera et analysera les données de mouvement en temps réel.  
**-Évaluation des performances :** Le système doit permettre d’obtenir un retour sur la qualité de réalisation des figures et des mouvements, en quantifiant les figures.  
**-Interface utilisateur :** Une interface graphique devra être développée pour afficher les données en temps réel.  
**-Modulable :** Le dispositif ne doit en aucun cas être une contrainte pour le sportif, il doit être léger, sans fil, et autonome.

## Composants : 
Pour ce projet, nous devions travailler avec des cartes fournies par ST Microelectronics. Notre choix s'est porté sur la **STEVAL Proteus 1**.
Ce kit a retenu notre attention pour les caractéristiques suivantes : 
  
**-Accéléromètre et gyroscope intégré :** ces capteurs de haute précision nous permettent de mesurer et quantifier les mouvements de rotation, la vitesse angulaire, l'accélération et autres paramètres cinématiques.  
**-Connectivité :** Ce kit est équipé d'une connectivité sans fil Bluetooth afin de transmettre les données collectées en temps réel à un dispositif de réception externe.  
**-Alimentation :** La batterie intégrée permet au dispositif d'être autonome pour un utilisation continue lors des épreuves et entraînements sportifs. Son autonomie est évaluée entre 74h et 84h, soit 10 jours d'entraînement.  
**-Support :** Petit et compact, le dispositif est léger et d'adapte à la morphologie et aux mouvements des athlètes sans provoquer de gêne.

Enfin, notre protoype s'accompagne d'une carte **Raspberry Pi 3**, un dispositif de réception externe permettant d'analyser les données.

# Fonctionnement : 

Lorsque l'athlète porte le dispositif, les capteurs d’accéléromètre et de gyroscope collectent en continu des données sur les mouvements de rotation et de positionnement de l’athlète.   
Les données des capteurs sont transmises à la Raspberry Pi 3 via le module Bluetooth.  
Le système de traitement des données analyse les données, et reconnait de manière objective les acrobaties réalisées.  
L'interface utilisateur affiche les résultats en temps réel sur un PC, fournissant des retours à l'athlète sur sa performance.  
Les données collectées peuvent également être stockées pour une analyse ultérieure ou pour suivre la progression de l'athlète. 

# Design : 
La conception ergonomique du dispositif est un aspect essentiel de notre projet. Notre approche repose sur l'utilisation d’un élastique se fixant selon les préférences du sportif, avec le dispositif électronique fixés par bandes auto-agrippantes. Le système sera spécialement conçu pour s'adapter de manière confortable aux athlètes sans entraver leur performance.  
{{< figure src="/images/Zoom_fort.png" title="Photographie du design de notre prototype" >}}

# Planning et budget :
Les jalons clés du développement de notre projet sont les suivants :  
-16/10/23 : Lancement du projet  
-19/10/23 : Publication du cahier des charges à ST Microelectronics & olympiades  
-01/02/24 : Finale du concours I-Novgames  
-11/03/24 : Soutenance jury ISEN  

Le coût total materiel pour la réalisation de notre prototype est de 103,17€ : 
-STeval Proteus 1: 46,39€  
-Raspberry Pi 3: 49,80€  
-Support: 6,98€  

