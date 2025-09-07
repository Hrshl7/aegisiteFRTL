---
title: FAQ
menu:
  docs:
    parent: introduction
weight: 2600
aliases:
  - /docs/latest/FAQ/
---

Une petite collection de Questions Fréquemment Posées (FAQ) à propos d'Aegisub - surtout des trucs qui ne rentraient nul part ailleurs.

###  Effets de karaoké?

Allez voir les [tutoriels de modèles karaoké]({{< relref "Automation/Karaoke_Templater/Tutorial_1" >}}).

### Est-ce que je peux créer des sous-titres DVD avec Aegisub ?

Pas directement, non, mais il y a un chouette programme appelé [MaestroSBT](https://sourceforge.net/projects/maestrosbt/) qui peut convertir des SSA en VOBSubs. Il y a un bon nombre de restrictions sur quels tags et autre peuvent être utilisés, donc lire le manuel en premier est conseillé. Notez aussi qu'il n'accepte pas les ASS - seulement les SSA. Vous pouvez utiliser le dialogue Aegisub Fichier -> Exporter les sous-titres... pour sauvegarder les vrais fichiers SSA.

### Est-ce qu'Aegisub accepte de sauvegarder en SRT ?

Oui, mais seulement si ça veut dire qu'aucune information ne sera perdue. En d'autres mots, si vous avez des balises prioritaires qui ne sont pas `\1c`, `\b`, ou `\i`, Aegisub n'acceptera pas de sauvegarder directement en SRT. Par contre, vous pouvez toujours exporter en SRT en utilisant la boîte de dialogue Fichier -> Exporter les sous-titres.... Désélectionnez juste toutes les boîtes.

### J'ai trouvé un bogue !?

Signalez-le sur le [traqueur de bogues](https://github.com/TypesettingTools/Aegisub/issues). S'il-vous-plaît, incluez autant de détails que possible dans votre rapport ! Rappelez-vous que si un bogue n'esta pas sur le traqueur de bogues, à notre connaissance, il _n'existe pas_.

### Pourquoi Aegisub n'a pas la \<fonction X> ? \<Programme Y> l'a !

Très sûrement parce que nous ne savions pas que vous la vouliez. Demandez-la sur le [traqueur de bogues](https://github.com/TypesettingTools/Aegisub/issues) et voyez ce qui se passe.

### Où est-ce que je peux trouver plus d'information et/ou recevoir de l'aide ?

Pour les choses par rapport à Aegisub, le [serveur Discord](https://discord.gg/AZaVyPr) et la [chaîne IRC](irc://irc.rizon.net/aegisub) sont des bons endroits pour poser vos questions.

Pour les question générales sur les vidéos, [Doom9.org](https://www.doom9.org) and [ses
forums](https://forum.doom9.org) sont généralement l'endroit où aller.

### Est-ce qu'il y a des bogues VSFilster dont je dois être au courant ?

En un mot : [oui](https://web.archive.org/web/20110811220802/http://asa.diac24.net/VSFilter#BUGS).
