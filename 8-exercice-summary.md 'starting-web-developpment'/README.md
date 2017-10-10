# starting-web-developpment

Intro
-----

Je pense que dans l'ensemble le HTML / CSS c'est bien déroulé.
Je dois apprendre à mieux organiser mon code, qu'il soit plus propre.
Utiliser plus d'ID et mieux organiser mes div et mes classes en les
nommant correctement.

Mon défaut: je m'attarde trop sur les détails...

Mes sites ne sont pas encore responsive, ils correspondent à la taille de
mon écran 1366 x 768.


Exo 1
-----

Exercice en groupe: au début j'ai un peu confondu le Markdown et le HTML.

Exo 2
-----

Je considère plus cet exercice comme une permière approche pour la création CSS.
Donc pas mal de test et pas vraiment de contrainte. 


Exo 3
-----

La difficulté dans cet exercice était pour moi la barre de menu et le positionnement des 
links à l'intérieur.

exemple:

`menu {`<br/>
	`background-color: #F2E900;`<br/>
	`text-align: horizontal;`<br/>
	`width: 100%;`		<br/>
`}`<br/>
`.link {`<br/>
	`text-decoration: none;`<br/>
	`color: #48473A; `<br/>
	`font-family: Lucida Sans Typewriter, monospace;`<br/>
	`font-size: 16px;`<br/>
	`margin: 12px;`<br/>
	`line-height: 20px;`<br/>
	`text-shadow: 1px 1px #f7eeee;`<br/>
`}`<br/>

J'ai réussi à créer des ancres pour que les liens du menu puissent renvoyer dans la page.

exemple:

<`div id="menu"`><br/>
	<`ul`><br/>
		<`li><a class="link" href="#sect1">Acceuil</a></li`><br/>
		<`li><a class="link" href="#sect2">Le Collectif</a></li`><br/>
		<`li><a class="link" href="#sect3">Agenda</a></li`><br/>
		<`li><a class="link" href="#sect4">Contact</a></li`><br/>
		<`li><a class="link" href="http://be.brussels/vivre-a-bruxelles/participation-a-la-vie-publique/participer-a-la-vie-associative" target="_blank">Autres Associations</a`></`li`><br/>
	</`ul`><br/>
</`div`><br/>
<`a id="sect3"/`><br/>
	<`div id="titre"><h1>Agenda</h1></div`><br/>
		<`div class="content1">Nous sommes présent tous les mardis et vendredis dans votre commune, de 18h à 19h.<br/> 
		Toute la nourriture est redistribuée <strong>le jour même</strong>. Les objets, vêtements et meubles seront soit redistribués, soit revendus aux bénéfices du fond d'aide social de votre commune.<br/`><br/>
		<`i>"La solidarité, c'est <strong>aider</strong> chacun à porter le poids de la vie et à la rendre plus facile."</i`><br/>(<`a href="http://www.mon-poeme.fr/citations-henri-frederic-amiel/"target="_blank">Citation de Henri-Frédéric Amiel</a`>)<br/>
<`/div`><br/>


Exo 4
-----

Je crois que c'est l'exercice qui m'a pris le plus de temps. J'ai eu beaucoup de mal à
faire en sorte qu'on ne puisse pas scroller la page...j'y ai passé beaucoup de temps pour 
le refaire et au final cela ne fonctionnait toujours pas... Grâce à Axel j'ai découvert
la propriété overflow-x, qui permet de figer la page à partir de l'axe verticale ou 
horizontale.

exemple:

`overflow-x: hidden;`

La qualité de l'image m'a aussi pris beaucoup de temps à régler car je suis partie d'une 
image du web où la qualité n'était déja pas bonne à la base. 

Exo 5
-----

Pour créer le cv, ce qui m'a pris un peu plus de temps c'est de trouver comment arrondir 
mon image (j'ai pour finir travaillé sur PS mais la solution se trouve dans l'exo 8).

Les puces m'ont également pris un peu de temps.

exemple:

`.puce-container {`<br/>
	`padding-top: 0%;`<br/>
    `padding-bottom: 10%;`<br/>
    `padding-left: 10%;`<br/>
    `padding-right: 25%;`<br/>
`}`<br/>
 `.puce {`<br/>
    `border-radius: 50%;`<br/>
    `width: 20px;`<br/>
    `height: 20px;`<br/>
    `float: right;`<br/>
    `margin-left: 2%;`<br/>
    `margin-right: 2%;`<br/>
 `}`<br/>
  `.puce-blanche {`<br/>
 	`background: white;`<br/>
 `}`<br/>
  `.puce-noire {`<br/>
 	`background: black;`<br/>
 `}`<br/>
 `.arrondi-blanc {`<br/>
 	`border: 2px solid white;`<br/>
`}`<br/>

Je me rends compte aussi que j'ai beaucoup de difficultés à nommer mes classes...
C'est quelque chose sur lequel je dois travailler.


Exo 6
-----

Pour la Vcard, j'ai repris pas mal de choses que j'avais faite dans le cv, je
trouve plus cohérent d'utiliser plus ou moins la même présentation.


Exo 7
-----

Pour l'exercice Star Wars, je me suis pas mal inspirée de codes sur le net que j'ai 
modifié, tout en essayant de rajouter des propriétés. 
La difficulté était de faire en sorte que ma balise vidéo ne soit pas visible.

astuce:
lorem + Tab


Exo 8
-----

Dans cet exercice, j'ai perdu un peu de temps a régler la taille de mes images. 
J'ai créé une balise image, une classe image et ajouté des padding 
et des margin à mes div conteneur. 
Dû coup, je me suis un peu embrouillé et j'ai du réinitialiser la plupart de 
mes div.   

exemple:

`.imagetim {`<br/>
	`width: 19%;`<br/>
    `background-position: center center;`<br/>
    `margin-left: 38%;`<br/>
    `border-radius: 50%;`<br/>
    `border: 5px solid #EBEBEB;`<br/>
`}`<br/>

  