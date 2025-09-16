# Taquin / Puzzle à glissière

Projet réalisé en deuxième année de licence informatique par :
- Nohan Lebreton
- Gaye Becaye
- Benjamin Guillot
- Brian Longuet


**Objectif**

Ce projet avait pour but de mettre en pratique les principes de la programmation orientée objet en Java, tout en consolidant nos compétences en conception logicielle. L’application développée est un jeu de puzzle à glissière :
- Jouable avec ou sans interface graphique
- Développée en Java 11.0.27
- Conçue selon le patron de conception MVC et le pattern Observer

**Mode d'emploi :**

Pour compiler :

javac -d build src/modele/taquin/*.java src/modele/tuile/*.java src/modele/*.java src/vue/terminal/*.java src/main/Main.java src/controle/gui/*.java src/vue/gui/*.java src/controle/terminal/*.java


Pour executer :

java -cp build main.Main
