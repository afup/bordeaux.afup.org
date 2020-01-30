---
id: 102
title: 'Dojo PHP du 27 Septembre à Bordeaux : un coup de poker!'
date: 2012-09-28T15:48:23+00:00
author: romain
layout: post
guid: http://bordeaux.afup.org/?p=102
permalink: /2012/09/28/dojo-php-du-28-octobre-a-bordeaux-un-coup-de-poker/
categories:
  - Actualité
---
[<img class="alignleft size-thumbnail wp-image-106" src="http://bordeaux.afup.org/files/2012/09/IMG_1615-150x150.jpg" alt="" width="150" height="150" />](http://bordeaux.afup.org/files/2012/09/IMG_1615.jpg)Hier s&rsquo;est tenu notre deuxième coding Dojo hébergé de nouveau dans les locaux d&rsquo;<a href="http://www.alliaform.fr" target="_blank">AlliaForm</a> et qui en a profité pour offrir l&rsquo;apéro. Une dizaine de personnes y ont participé, membres historiques mais également nouveaux venus, chacun apportant ses propres normes, habitudes et méthodes de travail. Un échange fructueux dans une ambiance décontractée et propice à la discussion.

&nbsp;

Le temps d&rsquo;attendre les retardataires avec un petit verre de vin et quelques tranches de saucisson, et nous nous sommes rapidement mis au travail en commençant par valider la proposition de Lorenzo de tenter le kata &nbsp;&raquo; <a href="http://codingdojo.org/cgi-bin/wiki.pl?KataPokerHands" target="_blank">poker hands</a> &laquo;&nbsp;.

[<img class="alignnone size-medium wp-image-103" src="http://bordeaux.afup.org/files/2012/09/IMG_1616-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1616-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1616-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1616.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1616.jpg)

Celui-ci consiste à tirer deux mains de 5 cartes et comparer les jeux pour déterminer laquelle dispose de la plus forte combinaison. Une paire, deux paires,  full, suite&#8230;en gros, une partie de poker simplifiée. Nous avons donc commencé par poser les constantes du problème par écrit.

[<img class="alignnone size-medium wp-image-104" src="http://bordeaux.afup.org/files/2012/09/IMG_1618-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1618-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1618-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1618.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1618.jpg)

Nous nous sommes ensuite attelés à écrire notre premier test et notre classe Card représentant une carte. Les alternances de <span style="color: #ff0000">ROUGE</span> / <span style="color: #339966">VERT <span style="color: #000000">ont pu commencer!</span></span>

[<img class="alignnone size-medium wp-image-105" src="http://bordeaux.afup.org/files/2012/09/IMG_1611-200x300.jpg" alt="" width="200" height="300" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1611-200x300.jpg 200w, https://bordeaux.afup.org/files/2012/09/IMG_1611-682x1024.jpg 682w, https://bordeaux.afup.org/files/2012/09/IMG_1611.jpg 1000w" sizes="(max-width: 200px) 100vw, 200px" />](http://bordeaux.afup.org/files/2012/09/IMG_1611.jpg)         [<img class="alignnone size-medium wp-image-108" src="http://bordeaux.afup.org/files/2012/09/IMG_1604-200x300.jpg" alt="" width="200" height="300" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1604-200x300.jpg 200w, https://bordeaux.afup.org/files/2012/09/IMG_1604-682x1024.jpg 682w, https://bordeaux.afup.org/files/2012/09/IMG_1604.jpg 1000w" sizes="(max-width: 200px) 100vw, 200px" />](http://bordeaux.afup.org/files/2012/09/IMG_1604.jpg)

Environ toutes les 5 à 10 minutes, le développeur au clavier laissait sa place afin que tout le monde puisse passer devant l&rsquo;écran. Ont ensuite suivi, les classe Deck (représentant un jeu de carte complet) et Hand (un tirage de 5 cartes depuis la classe Deck).

[<img class="alignnone size-full wp-image-111" src="http://bordeaux.afup.org/files/2012/09/IMG_1603.jpg" alt="" width="1000" height="667" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1603.jpg 1000w, https://bordeaux.afup.org/files/2012/09/IMG_1603-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1603-449x300.jpg 449w" sizes="(max-width: 1000px) 100vw, 1000px" />](http://bordeaux.afup.org/files/2012/09/IMG_1603.jpg)

Arrivés à 10 heures moins 20, les estomacs ont pris le dessus et nous avons décidé que la fin de l&rsquo;exercice ferait l&rsquo;objet d&rsquo;un nouveau dojo d&rsquo;ici quelques semaines. Nous nous sommes donc dirigés vers la place du marché des Chartrons pour finir la soirée autour d&rsquo;un bon repas. A suivre donc&#8230;

Pour ceux qui seraient intéressés par le travail réalisé pendant cet exercice, voici un <a href="http://www.alliaform.fr/media/files/dojo.zip" target="_blank">fichier zip</a> contenant les classes et les tests associés.

Pour finir, quelques photos en vrac du groupe d&rsquo;hier :

[<img class="alignnone size-medium wp-image-117" src="http://bordeaux.afup.org/files/2012/09/IMG_1608-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1608-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1608-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1608.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1608.jpg) [<img class="alignnone size-medium wp-image-116" src="http://bordeaux.afup.org/files/2012/09/IMG_1609-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1609-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1609-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1609.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1609.jpg)

[<img class="alignnone size-medium wp-image-115" src="http://bordeaux.afup.org/files/2012/09/IMG_1613-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1613-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1613-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1613.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1613.jpg)

[<img class="alignnone size-medium wp-image-114" src="http://bordeaux.afup.org/files/2012/09/IMG_1621-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1621-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1621-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1621.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1621.jpg)

[<img class="alignnone size-medium wp-image-113" src="http://bordeaux.afup.org/files/2012/09/IMG_1625-300x200.jpg" alt="" width="300" height="200" srcset="https://bordeaux.afup.org/files/2012/09/IMG_1625-300x200.jpg 300w, https://bordeaux.afup.org/files/2012/09/IMG_1625-449x300.jpg 449w, https://bordeaux.afup.org/files/2012/09/IMG_1625.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px" />](http://bordeaux.afup.org/files/2012/09/IMG_1625.jpg)

&nbsp;

&nbsp;