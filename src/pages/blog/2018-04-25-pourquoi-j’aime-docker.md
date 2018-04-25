---
templateKey: blog-post
title: Pourquoi j’aime Docker ?
date: 2018-04-25T00:00:00+02:00
description: '  '
tags:
  - digitech
---
![Docker by Laurel](/img/docker-by-laurel.jpg)

En tant que développeuse, je passe beaucoup de temps à tester et essayer des nouvelles technologies ou langages. Le jour ou j’ai découvert Docker j’ai tout de suite été emballée sans être vraiment capable d’expliquer pourquoi autour de moi et encore moins à quoi il servait : « c’est un containeur et on est pas obligé de tout virtualiser … » . Pas très convaincant comme première approche!

## Pour développer et tester en local

Je ne sais pas pour vous mais quand je commence une formation (tuto, mooc, etc.) j’ai souvent besoin d’installer quelque chose de plus sur mon mac.

Par exemple pour Ruby il manque ceci, pour Node.js cela. Le pire c’est peut-être de devoir installer deux versions différentes d’un framework, langage ou autre parce qu’ils ne sont pas compatibles!

Je fais une parenthèse perso: je suis adepte du concept Less is more. Ça signifie « moins c’est mieux » si on traduit un peu abruptement, une forme de minimalisme et d’état d’esprit. Tout ça pour dire que d’en mettre partout dans le mac et de bidouiller pour que tout s’installe et soit compatible.. trop peu pour moi.

Au début je faisais des sauvegardes ou des clones pour pouvoir faire un retour arrière rapide ou formater de temps à autre mais à part l’intérêt de sauvegarder ses données, je ne trouvais pas cette manip optimale. J’ai également testé les virtualisations et donc un système dans le système… C’est bien dans certains cas mais sans façon vu mon besoin, les temps d’installation, config / pré-requis pour que ce soit fluide et prêt à l’emploi.

C’est là que [Docker](https://www.docker.com) intervient. Une fois installé et [pris en main](https://docs.docker.com/get-started/), il permet de mettre en place des structures super légères, simples à installer / désinstaller. De multiples images officielles ont été créées et mises à disposition [sur leur site](https://store.docker.com/search?q=&source=verified&type=image). Il suffit de faire son marché!

Avant j’utilisais le mode serveur qu’on peut mettre en place dans le mac. Aujourd’hui je cloisonne mon utilisation classique et mon environnement de dev 

￼

Attention, je ne dis pas que Docker c’est magique. Il demande une prise en main et une montée en compétence en fonction de ce que vous voulez faire. J’ai juste fait le choix de l’apprendre et le comprendre pour gagner en temps et en confort par la suite. Vu les possibilités…  je n’ai pas de regrets!

## Pour une utilisation en environnement de développement

Une des autres forces de Docker est donc l’utilisation en équipe avec une structure plus poussée. Pour les cas les plus fréquents, des tests, de l’intégration continue du versionning etc. Pour ceux qui travaillent en micro service, on peut mettre en place une architecture où un service = un container par exemple. Imaginons une évolution serveur de PHP 5.6 à PHP 7. Si l’architecture est construite de sorte que PHP soit un container dédié relié aux autres. Il suffit de créer un nouveau container et de faire le test en le connectant au reste de l’architecture. L’image des Lego est souvent citée, on peut aussi imaginer des calques empilés les uns sur les autres comme en design. Il suffit d’en changer un sans remettre en question le reste du dessin 

￼

Certains basculent aussi sur ce genre d’architecture en production, j’y reviendrais plutôt au fil de mes posts sur Docker !

Et pour le côté magique quand même, il y a [PWD (Play With Docker)](https://labs.play-with-docker.com) qui est super pour s’essayer au début mais aussi plus tard pour faire des tests et récupérer l’environnement [grâce à un lien](https://training.play-with-docker.com).

L’image que j’ai utilisée a été réalisée par [Laurel](https://twitter.com/bloglaurel) et je vous invite à découvrir [ses oeuvres](https://bloglaurel.com) et [son histoire](https://commeconvenu.com).
