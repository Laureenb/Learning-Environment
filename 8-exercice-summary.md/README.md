# starting-web-developpment

Intro
-----

Je pense que dans l'ensemble le HTML / CSS c'est bien déroulé.
Je dois apprendre à mieux organiser mon code, qu'il soit plus propre.
Utiliser plus les ID et mieux organiser mes div et mes classes en les
nommant correstement.

Mon défaut: je m'attarde trop sur les détails...

Mes sites ne sont pas encore responsive, ils correspondent à la taille de
mon écran 1366 x 768.


Exo 1
-----

Exercice en groupe, au début j'ai un peu confondu le Markdown et le HTML.

Exo 2
-----

Cet exercice était plus une permière approche pour la création CSS.


Exo 3
-----

La difficulté dans cet exercice était pour moi la barre de menu et le positionnement des 
éléments à l'intérieur.

exemple:
menu {
	background-color: #F2E900;
	text-align: horizontal;
	width: 100%;		
}

.link {
	text-decoration: none;
	color: #48473A; 
	font-family: Lucida Sans Typewriter, monospace;
	font-size: 16px;
	margin: 12px;
	line-height: 20px;
	text-shadow: 1px 1px #f7eeee;
}

J'ai réussi à créer des ancres pour que les liens du menu puissent renvoyer dans la page.

exemple:
<div id="menu">
	<ul>
		<li><a class="link" href="#sect1">Acceuil</a></li>
		<li><a class="link" href="#sect2">Le Collectif</a></li>
		<li><a class="link" href="#sect3">Agenda</a></li>
		<li><a class="link" href="#sect4">Contact</a></li>
		<li><a class="link" href="http://be.brussels/vivre-a-bruxelles/participation-a-la-vie-publique/participer-a-la-vie-associative" target="_blank">Autres Associations</a></li>
	</ul>
</div>
.
.
.
.
<a id="sect3"/>
	<div id="titre"><h1>Agenda</h1></div>
		<div class="content1">Nous sommes présent tous les mardis et vendredis dans votre commune, de 18h à 19h.<br/> 
		Toute la nourriture est redistribuée <strong>le jour même</strong>. Les objets, vêtements et meubles seront soit redistribués, soit revendus aux bénéfices du fond d'aide social de votre commune.<br/><br/>
		<i>"La solidarité, c'est <strong>aider</strong> chacun à porter le poids de la vie et à la rendre plus facile."</i>(<a href="http://www.mon-poeme.fr/citations-henri-frederic-amiel/"target="_blank">Citation de Henri-Frédéric Amiel</a>)
		</div>


Exo 4
-----

Je crois que c'est l'exercice qui m'a pris le plus de temps. J'ai eu beaucoup de mal à
faire en sorte qu'on ne puisse pas scroler la page...j'y ai passé beaucoup de temps pour 
tout refaire et qu'au final cela ne fonctionne toujours pas... Grâce à Axel j'ai découvert
la propriété overflow-x, qui permet de figer la page à partir de l'axe verticale ou 
horizontale.

exemple:
overflow-x: hidden;

La qualité de l'image m'a aussi pris beaucoup de temps à régler car je suis partie d'une 
image du web où la qualité n'était déja pas bonne à la base. 

Exo 5
-----
Pour créer le cv, ce qui m'a pris un peu plus de temps c'est de trouver comment arrondir 
mon image (j'ai pour  finir travailler sur PS mais la solution se trouve dans l'exo 8).

Les petits ronds m'on pris également un peu de temps.

exemple:

<!-- PUCES -->
.puce-container {
	padding-top: 0%;
    padding-bottom: 10%;
    padding-left: 10%;
    padding-right: 25%;
}
 .puce {
    border-radius: 50%;
    width: 20px;
    height: 20px;
    float: right;
    margin-left: 2%;
    margin-right: 2%;
 }
  .puce-blanche {
 	background: white;
 }
  .puce-noire {
 	background: black;
 }
 .arrondi-blanc {
 	border: 2px solid white;
 }
<!-- PUCES -->

Je me rends compte également que j'ai beaucoup de difficulté à nommé mes classes...
c'est quelque chose sur lequel je dois travailler.


Exo 6
-----

Pour la Vcard, j'ai repris pas mal de choses que j'avais faite dans le cv, je
trouve plus cohérent d'utiliser plus ou moins la même présentation.


Exo 7
-----

Pour l'exercice Star Wars, je me suis pas mal inspiré de codes sur le net que j'ai 
modifié, tout en essayant de les modifiés et de rajouter des propriétés. 
La difficulté était de faire en sorte que ma balise vidéo ne soit pas visible.

astuce:
lorem + Tab


Exo 8
-----

Dans cet exercice, j'ai perdu un peu de temps a régler la taille de mes images. 
J'ai créer une balise image, une classe image et j'ajoutais des padding 
et des margin à mes div conteneur. 

Du coups, je me suis un peu embrouillé et j'ai du réinitialiser la plupart de 
mes div.   

exemple:
.imagetim {
	width: 19%;
    background-position: center center;
    margin-left: 38%;
    border-radius: 50%;
    border: 5px solid #EBEBEB;


  