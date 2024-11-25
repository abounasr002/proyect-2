Projet CV

HTML / CSS

   1.1. Structure

 <head>
 <body>
    <header>
    <main>
    <footer>
 </body>

1.2. Header

        
Div "container" englobant le header. Background linear-gradient, display flex, space-between.
Div "identité" englobant nom-prénom (h1) et métier (h2). text align center.
Balise "img" contenant la photo
Div "infos-perso" contenant trois "p", text align right.

1.3. Main

        
Deux sections principales "left part" et l'aside "right part". Display grid (60%, 30%)
Div experience-list dans la left-part, contenant 4 balise articles. Chaque article contienr "h4", "img", "h5" et un "p". Display flex, wrap
Hover des articles: transition 0.2s ease in, scale 1.01.

        
Div "formation", "compétences" et "qualités" dans l'aside "right-part". Flex wrap.
Before pour la div compétence: content "", position relative / absolute, border radius.

1.4. Footer 

        
Div container qui l'englobe. Text align center.

Media Queries

    2.1. Format Tablette

        
Diminution de la width de l'article
Diminution taille images
Disparition du before dans les compétences

    2.2. Format tel - Supression des images - Supression de la div "info-perso" - Supression de l'hover - Display block sur le main

Technologies utilisées

Visual Studio Code
Langage HTML
Langage CSS
Utilisation de font awesome
Utilisation de font-family
Maquette inspirée de discord
Maquette créee sur Excalidraw
