---
layout: post
title:  "La revue de code bienveillante"
description: >
    Je pratique la revue de code depuis plusieurs années maintenant, et bizarrement, c'est toujours un exercice difficile.
---

Je pratique la revue de code depuis plusieurs années maintenant, et bizarrement, c'est toujours un exercice difficile. Qu'on la reçoive ou qu'on la donne, que ce soit en pair programming, en groupe, ou par des revues de Pull requests, je pense que l'on doit faire preuve de bienveillance.

## Ce que j'attends d'une revue

Pour moi, une revue de code à plusieurs objectifs qui sont à court, moyen et long terme, très bénéfiques.

Tout d'abord, je pars d'un constat simple : que l'on soit développeur depuis 10, 20, 5 ou 2 ans, on fait **toujours** des erreurs, et l'on en fera toujours. Et pas forcement des erreurs d'inatention, cela peut être des erreurs d'achitecture, de conception, de nommage... et plus on les détectent tôt, plus le coût pour les réparer, pour rembourser la dette sera faible. Et puis, aucun développeur ne peut penser toujours à tout, c'est impossible. De plus, chacun à des compétences différentes et complémentaires. Faire de la revue de code permet de mettre à profit les différences et la complémentarité des développeurs. Certains connaissent les fonctions les plus performantes, certains font plus attention à la lisibilité du code. Ce serait dommage de ne pas profiter de tout ce panel de compétences.

**Photo de perles a repasser => welcome to the jungle**

J'ai un fils qui a 4 ans maintenant. Je fais souvent avec lui des perles à repasser. On choisit ensemble un modèle qu'il réalise ensuite seul en général. Souvent, il me demande si *"c'est bien comme ça papa ?"*, il est tellement concentré sur des détails que parfois il fait des erreurs d'inatention, et c'est normal, c'est ce que l'on appelle trivialement *avoir la tête dans le guidon*. Mais un décalage d'une perle au début, c'est facile à détecter et à corriger, si on s'en rend compte à la fin, il faut parfois déplacer de une case des dizaines de perles... et c'est long et pénible... une revue régulière peut l'éviter ! Et je pense que mon fils la compris.

De plus, je fais souvent mes petits modèles à côté (mon côté vieux geek traumatisé du pixel art :) ) et mon fils m'observe. Un jour, j'ai pris une pince à épiler pour attraper les perles, depuis, quand on commence, mon fils en veux une aussi, et il s'en sert pour aller plus vite et être plus précis. En revoyant mon code, il a appris.

Et c'est vrai que l'on apprend énormenent en lisant le code des autres et sans le savoir, on transmet, on partage des façons de faire en soumettant du code à de la revue. 

Dans un précédent poste, j'ai réécrit une partie du framework Symfony dans un framework maison en l'adaptant à celui-ci (je n'expliquerai pas pourquoi...). En lisant, copiant, paraphrasant, comprennant, réécrivant, j'ai énormément appris. De nouvelles façon de tester, des application de design pattern, des architectures auxquelles je n'avais pas pensé. Même si le travail pouvait sembler inutile et pénible, il a en réalité été très riche en enseignement. Mais à cette époque, je ne faisais pas relire mon code, un problème de culture je pense, et si je faisais une erreur d'inatention, on me *pointait du doigt*.

Lorsque l'on pratique quotidiennement des revues en équipe, en plus d'avoir moins d'erreurs, on commence progressivement à **partager la responsabilité des erreurs**. Comment blamer un développeur ayant introduit un bug si la moitier de l'équipe à valider ce code ? Parcequ'il n'a pas écrit de test ? Pourquoi ne pas lui avoir dit avant de mettre un +1 ? Parcequ'il n'a pas pensé à tout ? Mais je n'y ai pas pensé non plus quand j'ai écrit *LGTM*...

Et progressivement, on ne parle plus de **mon code**, **son code** ou **ton code**, on parle uniquement **du code**. Car en réalité, le code n'appartient à personne et a tous en même temps. C'est notre responsabilité commune. Et le partager, le relire, le revoir, le réécrire nous amène à l'améliorer de façon continue.

## La revue fénéante