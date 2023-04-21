<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen and (min-width : 650px) " href="screen.css"> 
    <link rel="stylesheet" type="text/css" media="screen and (max-width : 650px) " href="print.css">

    <title>Présentation du jeu</title>
  </head>
  <body>
    <div id="header">
      <ul id="menu">
        <li><a href="#description">Description du jeu</a></li>
        <li><a href="#regles">Règles du jeu</a></li>
        <li><a href="#cartes">Cartes du jeu</a></li>
        <li><a href="#contact">CONTACT</a></li>
      </ul>
    </div>
    
    <div id="logo">
      <img alt="erreur" src = "image/logo.png" id="logoImage">
    </div>

    <div class="blocs">  
      <h1 class="titre"> Description du jeu</h1>
      <p>
        Nous souhaitons créer un nouveau jeu de combat en application mobile. L’idée est de garder l’essence des jeux de société tout 
        en s’adaptant aux technologies de nos jours. 
        <br>
        Pour cela nous avons conceptualisé un jeu de société qui conserve une structure de jeu traditionnelle :      
        une pile de défausse/pioche (même tas) et un nombre défini de cartes dans les mains des joueurs
        <br>
        L’étiquette de “Pionnier” que notre jeu porte se doit au plateau de jeu. Étant donné qu’un dispositif électronique 
        (smartphone ou tablette) remplira cette fonction, la totalité des cartes comporte un QR code qui permettra d'interagir avec le 
        “Plateau”. 
        <br>
        En ce qui concerne la jouabilité, nous avons voulu exploiter les facilités offertes par le monde actuel. 
        Pas besoin de se balader avec une boîte de jeu de société par ci par là. Le but est que toute personne ayant une connexion 
        internet, puisse télécharger l’application et imprimer les cartes gratuitement n’importe où.
      </p>
    </div>
    
    <div class="blocs">  
      <h1 class="titre" id= "regles"> Règles du jeu</h1>
      <p>La partie se déroule sur un champ, elle comprend de 2 à 8 joueurs et le nombre de tentes dépendra du nombre des joueurs : il y aura 2 tentes vides en plus.
        <br>
        Il existe trois catégories de cartes:
        <ol>
          <li>
            désigne les tentes (ces dernières sont situées à côté du dispositif) Un premier visuel sur le plateau accompagné de 6 cartes tentes.
          </li>
          <li>
            les attaques et les défenses (ces cartes sont dans les mains des joueurs et dans la pile de défausse)
          </li>
          <li>
            les avatars. Il y  aura un maximum de huit cartes et chacune représentera un avatar unique que les joueurs choisiront pour jouer (ces cartes sont dans les mains des joueurs)
          </li>
        </ol>
      </p>
      <p>
        Chaque carte physique sera représentée avec un QR code unique. Les joueurs doivent pointer le QR code de la carte vers la caméra frontale du média électronique. Le système enregistrera automatiquement la valeur correspondante et affichera l'animation adéquate.
        <br>
        Après avoir sélectionné un personnage, le joueur sera positionné aléatoirement dans l'une des tentes. Les joueurs, à tour de rôle, utiliseront une et une seule des cartes de leur main (attaque ou défense) afin d’effectuer les actions correspondantes sur la tente désignée. Le joueur qui se trouve dans la tente choisie, reçoit l'action correspondante. Lorsqu'il ne reste qu'une seule personne sur la plateforme, le gagnant est généré et le jeu se termine. 
        <br>
        Nous avons également ajouté des tentes vides afin de confondre la prise de décision du joueur qui attaque.Cela permet de créer un moment d’amusement dans la vraie vie, puisque le joueur peut rater son attaque si jamais il choisit d’attaquer l’une des deux tentes vides.
        <br>
        Pour pouvoir utiliser une arme, il nous faut avoir l'énergie suffisante pour pouvoir déclencher une attaque. L'énergie se gagne à chaque début de tour du joueur. On peut imaginer par exemple que chaque joueur gagne +2 points d'énergie à chaque début du tour (cela reste un exemple, on cherchera à trouver la valeur qui équilibre le plus le jeu).
        <br>
        Lorsque le joueur défend, différentes valeurs de défense sont générées selon le bouclier (cartes catégorie 2). La valeur de défense peut compenser l'attaque des autres joueurs, réduisant ainsi la perte de ses points de santé. La valeur de défense ne durera qu'un tour, quand ce joueur scanne une prochaine carte, la valeur de défense expirera. 
        <br>
        Chaque joueur a 3 vies et chacune d’entre elles est composée de 5 PS (Points de Santé). Quand un joueur perd ses 3 vies alors il est éliminé. Le dernier joueur vivant est le gagnant.               
      </p>
    </div>
    
    <div class="blocs">    
      <h1 class="titre" id= "cartes"> Cartes du jeu</h1>  
      <div class="lien"><a href="carteExemple.png">Vous pouvez télécharger les cartes en cliquant ici</a></div>
    </div>

    <div class="blocs">    
      <h1 class="titre" id= "contact"> CONTACT</h1>
      <div class="lien"><a href="mailto:qfightr@exemple.com">Vous pouvez nous contacter en cliquant ici</a></div>
    </div>
  </body>
</html>
