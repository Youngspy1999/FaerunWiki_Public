---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Town Council
leader: Harbin Wester
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - SwordCoast
size: Small village
population: 
commonraces:
  - Humans
  - Elves
  - Dwarves
  - Half-elves
  - Gnomes
  - Halflings
religion:
  - Tymora
  - Waukeen
exports:
  - Cold iron
  - Gold
  - Platinum
  - Skins
  - Timber
imports:
  - Something Else
---



> [!infobox]
> # `=this.file.name`
> ![[Emblem - Phandalin.webp]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[Voonlar]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`
## Overview
  
Phandalin était situé dans les collines perdues des montagnes de l'épée, au sud de la forêt de Neverwinter. C'était au nord-est de Leilon, où la route qui menait de la High Road à Triboar se transformait en sentier. C'était une région riche en ressources naturelles et en opportunités d'aventure.

Le climat était tempéré, avec une pluviométrie annuelle moyenne de 18 pouces (46 centimètres). Le Icespire Peak était visible depuis la ville par temps clair.
  
À la fin du 15ème siècle DR, Phandalin était une ville modeste et architecturalement ennuyeuse de pionniers travailleurs construite au-dessus des ruines de l'ancien Phandalin. La ville a rapidement grandi pour atteindre environ cinquante structures bien entretenues construites en rondins et en pierres, avec trois puits profonds fournissant de l'eau. La ville était dominée par un verger de pommiers à l'ouest et un manoir en ruines au sommet d'une colline à l'est. Les habitants se rassemblaient dans une petite place de la ville et un espace vert adjacent.

### Phandalin Map

>```leaflet
>### Tutorial: https://youtu.be/54EyMzJP5DU
>### id must be unique
>id: Phandalin_map
>### Lock pins so they can't be moved
>lock: true
>### If true, view of map will recenter as you zoom out. 
>recenter: true
>### If true, disables mouse scroll for zomming in and out of a map. Button controls still work. 
>noScrollZoom: true
>image:  [[Map -Phandalin.webp]] 
>### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)
>### Map Pixel Width x 1 / (Pixels between Bar Scale / 100) 
>### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit. 
>bounds: [[0,0], [813.90, 1148.54]]
>height: 700px
>width: 90%
>### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
>lat: 574.27
>long: 406.95
>### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
>minZoom: -1.5
>### Max zoom is 18. 
>maxZoom: 1.5
>### Hover mouse over the Reset Zoom icon to see your current zoom level. 
>defaultZoom: -0.5
>### How far it zooms in or out with each step. Can be in decimals. 
>zoomDelta: 0.5
>### This is a string so can be any text. Change it to match your maps measurement scale. 
>unit: feet
>scale: 1
>darkMode: false
>```




### Phandalin Picture
![[Photo - Phandelin.webp]]



## Notable NPCs
Placeholder



## Story
Lorsque Phandalin a été rétablie à la fin du 15ème siècle DR, elle n'avait tout d'abord aucun gouvernement réellement fonctionnel, et le Phandalin Miner's Exchange a commencé à agir comme centre de tenue de registres pour les revendications minières locales. Les habitants élisaient également annuellement un "Maître de la ville" qui faisait office de juge et de médiateur, ainsi que de tenancier des registres de la ville. En 1491 DR, Harbin Wester était le Maître de la ville perpétuel.

Après une foi diminuée dans les capacités d'un seul Maître de la ville à faire face aux menaces pesant sur le village au début des années 1490 DR, les habitants ont plutôt élu un Conseil municipal de trois membres, composé à l'origine de Harbin Wester, Sildar Hallwinter et Trilena Stonehill. Trilena a finalement été remplacée par Halia Thornton, qui a ensuite disparu. En 1496 DR, les habitants ont décidé d'élargir le conseil de trois à cinq membres et d'élire en plus un maire.

## History

**Première réinstallation**

Au milieu ou à la fin du XIVe siècle DR, Phandalin était notable comme l'une des ruines les mieux préservées le long de la [[Sword Coast]] . Les visiteurs étaient mis en garde que bien que les trois puits de la ville contenaient encore de l'eau, l'un était contaminé par une toxine indétectable qui était fatale à tous sauf aux orques et aux demi-orques.

La ville a été réinstallée quelques années avant l'année des Tempêtes de Foudre, 1374 DR. Le petit village était une communauté de travailleurs acharnés, avec sa ressource la plus notable extraite dans les mines de fer froid voisines. L'homme industrieux nommé Danley a rassemblé un groupe de vétérans endurcis de la Guerre de l'Ombre pour nettoyer les mines de fer froid de leurs habitants humanoïdes monstrueux et reprendre la production de fer froid. Le plan a été interrompu lorsque deux représentants de la soi-disant "Compagnie minière du froid" sont arrivés à Phandalin et ont déclaré la propriété des mines, et ont éliminé les orques et autres créatures qui les infestaient. Les soupçons de Danley ont été éveillés alors qu'il y avait quelque chose de faux dans ces affirmations. Il soupçonnait le Réseau Noir ou une nation voisine. La "Compagnie minière" a refusé d'employer des gens de Phandalin et a vendu le fer froid à une source inconnue, jamais à des caravanes de marchands qui passaient par le village. Danley s'est allié à un groupe de mercenaires qui travaillaient pour la princesse marchande Sa'Sani pour enquêter sur les mines. Daniel Merriwether et Chester Paulson, les chefs des opérations, se sont révélés être des mages oni magiquement déguisés Radbur et Gromcheck et des mineurs - des orques et des gobelins déguisés. La "Compagnie minière du froid" a ensuite été fermée et revendiquée par Danley et le peuple de Phandalin.

**Deuxième réinstallation**

Après le Spellplague, Phandalin était une fois de plus en ruines. À partir de l'année des Rouleaux de la Montagne Néant, 1486 DR, des colons de [[Neverwinter]] et de [[Waterdeep]] ont commencé à réinstaller les ruines de Phandalin, et la ville reconstruite était bien établie en l'an de la Sorcière Écarlate, 1491 DR.

Autour de cette période, deux défis ont été lancés à la ville. L'un était un groupe de bandits connus sous le nom de Redbrands, ou les Ruffians Redbrand, qui se sont installés à Phandalin, établissant leur repaire sous le Manoir Tresendar. Ils ont commis plusieurs actes terribles, tels que racketter les entreprises locales, kidnapper plus d'une douzaine de voyageurs pour les vendre en esclavage, tuer le sculpteur sur bois Thel Dendrar pour sa défiance, et plus tard kidnapper sa famille. L'autre défi était l'apparition de Cryovain, un dragon blanc qui revendiquait Icespire Hold comme sa tanière et la région autour de Phandalin comme son territoire. Le dragon terrorisait la ville et ses voisins, et déplaçait également les orques et les monstres des montagnes de l'épée qui menaçaient également la sécurité de Phandalin. Peu impressionnés par la façon dont le maître de ville, Harbin Wester, a géré ces défis, les habitants de la ville ont restructuré leur gouvernement pour inclure un conseil municipal de trois personnes.

Peu après, Volothamp Geddarm est passé par la ville et a écrit à son sujet dans son livre, Le Guide des Monstres de Volo, ce qui a provoqué un afflux de touristes et d'aventuriers. Cela a entraîné un boom dans l'industrie touristique de la ville, conduisant à une explosion de la concurrence entre les auberges et tavernes de la ville. L'afflux de touristes a non seulement apporté plus d'affaires à Phandalin, mais a également conduit à une augmentation des incidents de nobles visitants et de chercheurs de sensations malchanceux se mettant en danger avec des monstres locaux. La nouvelle popularité de la ville coïncidait avec l'apparition de Gavmogon, un beholder ayant accès à un puissant artefact qui lui permettait de répandre la folie dans la région.

Au cours des années suivantes, une grande partie de la richesse minérale qui était censée affluer vers Phandalin n'a pas vu le jour. La ville pouvait passer des mois sans nouveaux revenus des opérations minières, et les efforts pour ouvrir l'ancienne

## Trades
Phandalin était adjacente à des terres propices à l'agriculture et à l'élevage, et était suffisamment proche de la forêt de Neverwinter pour soutenir une industrie du bois et de la coupe de bois. La plupart de la richesse, cependant, provenait de l'exploitation minière dans les montagnes de l'épée voisines pour l'or, le platine, le minerai, le bois, les peaux et le fer froid.

## Points of interest

**Auberges et Tavernes**

[[Inn Stonehill]] : Une auberge modeste dirigée par un jeune homme humain court et sympathique nommé Toblen Stonehill. Toblen venait de l'est de Triboar, cherchant l'opportunité dans la prospection comme beaucoup d'autres. Il a bientôt découvert qu'il en savait plus sur la gestion d'une auberge que sur l'exploitation minière, et il a donc établi l'auberge.

[[The Sleeping Giant]] : Un trou d'eau délabré, sale et dangereux. Il était connu pour être fréquenté par un groupe de bandits, les Redbrands. Il était exploité par une naine acariâtre appelée Grista.

[[Danley and Sons Inn]] : La seule auberge lorsque la ville a été brièvement réinstallée à la fin du XIVe siècle DR.

**Magasins et entreprises**

[[Barthen's Provisions]] : Le plus grand poste commercial de Phandalin, ouvert du lever au coucher du soleil. Il était dirigé par un homme chauve et mince, d'âge moyen, au caractère aimable, Elmar Barthen. Ce magasin a été fermé et transformé en temple en 1496 DR.

[[Edermath Orchard]] : Un champ de vergers avec la simple maison d'un demi-elfe aux cheveux argentés nommé Daran Edermath. Daran était un maréchal à la retraite dans les terres de la Côte du Dragon. Lorsqu'il a pris sa retraite, il est retourné dans la région de Neverwinter, qui était son lieu d'origine, pour cultiver des pommes et faire du cidre.

[[Lionshield Coster]] : Un fournisseur d'armes et d'armures appartenant au Lionshield Coster. La maîtresse de ce poste était une femme à la langue acérée nommée Linene Graywind, qui dirigeait l'entreprise avec sa fille Minghee.

[[Phandalin Miner's Exchange]] : Un poste de traite où les mineurs pesaient leurs trouvailles et étaient payés. Les archives du townsmaster étaient conservées ici, avec la responsabilité d'aucun seigneur local. L'échange était dirigé par les Zhentarim, qui ont tenté de prendre lentement le contrôle de Phandalin. Leur agent d'origine était Halia Thornton, qui a finalement été remplacée par Sharna Quirstiron.

[[La forge]] : Le forgeron local était Alger Frakk, qui dirigeait cette forge avec son apprenti, Maza Fieldsalder.

[[Le travailleur du bois]] : Une entreprise de sculpture sur bois dirigée par Thel Dendrar jusqu'à sa mort en 1491 DR.

**Temples et sanctuaires**

[[Shrine of Luck]] : Un petit sanctuaire en pierre des ruines et le seul temple de Phandalin, dédié à Tymora. Il était sous la garde d'une jeune elfe zélée et membre des Harpers, Sœur Garaele.
Temple de la Déesse de la Monnaie : Un temple dédié à Waukeen en 1496 DR à l'emplacement de l'ancien Barthen's Provisions. Il était géré par le Ditch Fundi distant, bien que les services de temple réels étaient supervisés par deux acolytes, Hesten Jenz et Mischka Solmen.

[[Shrine of Waukeen]] : Un petit sanctuaire construit lorsque la ville a été brièvement réinstallée à la fin du XIVe siècle DR.

**Autres lieux**

[[Alderleaf Farm]] : Une ferme simple dirigée par une sage demi-halfling nommée Qelline Alderleaf. Elle était amie de longue date du druide, Reidoth.

[[Townmaster's Hall]] : Un petit bâtiment qui servait de siège au gouvernement de la ville. Il abritait également une petite mais fonctionnelle prison dans la cave.

[[Tresendar Manor]] : Plus un château qu'un manoir, c'était un bâtiment ancien abandonné après les raids orques de 951 DR. À la fin du XVe siècle DR, les caves, qui servaient autrefois de refuge sûr lorsque la propriété était attaquée. Il a également servi de lieu de repos pour les membres décédés de la famille Tresendar, ont été transformés en repaire des Redbrands. Le bâtiment a ensuite été transformé en hall de guilde pour Acquisitions Incorporated.


