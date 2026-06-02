Ajouter des trucs tt seul





**PR AJOUTER DES IMAGES :**



Dans la colonne où tu veux l'ajouter, ajoute simplement une ligne :



<img src="images/titre\\\_de\\\_l\\\_image.jpeg/png/mp4" alt="Sketch + \*\*numéro associé dans la bdd\*\*" onclick="openLightbox(this.src)">







**POUR AJOUTER DES VIDEOS :**



<video autoplay muted loop playsinline controls

&#x20;      onclick="openLightbox('images/TITREDEVIDEO.mp4','video')">



&#x20; <source src="images/TITREDEVIDEO.mp4" type="video/mp4">



</video>



**QUELLE COLONNE ?**



le premier <div class="column"> = colonne de gauche

le deuxième <div class="column"> = colonne de droite







**FAUT IL TOUCHER AU CSS ?**



Non.



Tant que tu utilises :



<div class="column">



si il te dit de changer "this.src" ne le fais pas !!

