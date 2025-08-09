---
title: Soutenir Aegisub
menu:
  docs:
    parent: introduction
weight: 2500
aliases:
  - /docs/latest/Support/
---

Vous voulez soutenir Aegisub ? Eh bien, c'est simple !

### Retours

Vous pouvez nous donnez des retours - commentaires, critiques,
suggestions, etc. Les rapports de bogues et demandes de nouvelles
foncitonnalités sont toujours les bienvenues. Consultez notre
[forums](http://forums.aegisub.org) et le [suivi des bogues](http://devel.aegisub.org/),
ou venez discuter dans la [chaîne IRC](irc://irc.rizon.net/aegisub).

### Faites passer le mot

Vous aimez Aegisub ? Dites-le à vos amis ! Faire passer le mot est une
bonne façon pour aider Aegisub à être le meilleur éditeur de sous-titre.

### Donations

Vous vous sentez généreux ? Envisagez de nous faire une donation ! 
Nous faisons tout ça pendant notre temps libre, vous savez.

### Programmer

> « avec suffisamment d'yeux, tous les bugs sont superficiels »

_-- Linus Torvalds_

Envie de vraiment aider, ou vous havez juste du code dont vous voulez faire don ?
Quelques conseils du readme.txt de l'arbre source :

Premièrement, une partie du code est plutôt lisible, une partie est décente
et une partie est un bazar raccommodé. Bonne chance. ;)

Avant de coder une nouvelle fonctionnalité, vous devriez probablement aller
sur l'IRC et voir avec un développeur pour vérifier que c'est une fonction
qu'Aegisub devrait avoir, ou vous risquez le risque de gaspiller du travail.
Par contre, les réparations de bogues non sollicité sont généralement acceptées.

Deuxièmement, si vous voulez coder quoi que ce soit pour Aegisub,
vous devez accepter ces termes :

1. Vous devez publier le correctif dans le domaine publique ou donner son copyright
   à un des développeurs. Ceci est pour éviter qu'un fichier source soit détenu
   par trop de personnes. (Exception : Les changements MAJEURS peuvent être acceptés
   sous licence BSD sous votre nom. Consultez les développeurs.)
1. Soyez SÛR qu'il puisse être compilé et qu'il fonctionne correctement
   avant de le soumettre aux développeurs.
1. Les correctifs doivent normalement être appliqués au git master/main, sauf s'ils
   concernent un bug présent dans stable mais pas master.
1. Les demandes de tirage doivent être rebasée sur le git master (ou stable, si applicable),
   et vous devez avoir un sujet de branche par demande de tirage. S'il-vous-plaît,
   n'ayez pas de fusion de commits dans votre historique.
1. Aegisub n'a pas un seul style cohésif de code, mais essayez de suivre un style qui
   est déjà présent quelque part dans le programme (et préférablement celui du code
   que vous touchez).

Troisièmement, tout est disponible sous la licence BSD. D'après le GNU lui-même,
le BSD est compatible GPL, significant que vous pouvez lier le code GPL au code
BSD. Rappelez-vous, cependant, que si un fichier source a un contenu sous BSD et
GPL, il sera régit par GPL.
