---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Oligarchie
type: Métropole cité-état
politics: Oligarchie
leader: Lords of Waterdeep
guildsgroups:
  - Shadow Thieves
region:
  - SwordCoast
size: Huge City
population: 1347680
commonraces:
  - Humans
  - Halflings
  - Elves
  - Dwarves
  - Half-elves
  - Gnomes
  - Half-orcs
  - Others (pretty rare)
religion:
  - Déneir
  - Mystra
  - Oghma
exports:
  - Ameublement
  - armes
  - bières
  - métaux fins
  - objets en cuir
  - poteries
  - tissus
imports:
  - bétail
  - bois
  - céréales
  - cuir
  - minerai
  - produits exotiques
defences:
  - Force Grey
  - Griffon
  - Defenders Three
  - Dawnbringer Company
  - Walking Statues of Waterdeep
---



> [!infobox]
> # `=this.file.name`
> ![[Waterdeep_Emblem.webp]]
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
> [[Daggerford]] | 🕓: `VIEW[round((120* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[Baldur's Gate]] | 🕓: `VIEW[round((585* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
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
Waterdeep est une immense ville du Nord et une puissance cosmopolite majeure de Faerûn. Elle bénéficie d'un excellent port, d'un régime sage et tolérant, et d'un solide tradition magique qui produit de puissants magiciens du Bien (et quelques magiciens maléfiques). Cette ville est comme une polisseuse de diamant, lissant les défauts des individus pour qu'ils puissent donner le meilleur d'eux-mêmes
### Waterdeep Map


>```leaflet
>### Tutorial: https://youtu.be/54EyMzJP5DU
>### id must be unique
>id: Waterdeep_map
>### Lock pins so they can't be moved
>lock: true
>### If true, view of map will recenter as you zoom out. 
>recenter: true
>### If true, disables mouse scroll for zomming in and out of a map. Button controls still work. 
>noScrollZoom: true
>image: [[Map - Waterdeep.webp]]
>### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)
>### Map Pixel Width x 1 / (Pixels between Bar Scale / 100) 
>### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit. 
>bounds: [[0,0], [3719.00, 2790.634]]
>height: 1100px
>width: 100%
>### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
>lat: 1395.31
>long: 1859.50
>### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: -1.5
>### Max zoom is 18. 
>maxZoom: 1.5
>### Hover mouse over the Reset Zoom icon to see your current zoom level. 
>defaultZoom: 0
>### How far it zooms in or out with each step. Can be in decimals. 
>zoomDelta: 0.5
>### This is a string so can be any text. Change it to match your maps measurement scale. 
>unit: miles
>scale: 1
>darkMode: false
>```




### Waterdeep Picture
![[Photo - Waterdeep.webp]]



## Habitants
Les habitants de Waterdeep, les Waterdhavian, ont le défaut de penser que rien n'est vraiment nouveau et que la totalité du savoir humain et non-humain fait partie de leur héritage culturel. Ils sont globalement tolérants et respectueux des lois. Ils ont souvent des loisirs animés mais travaillent dur, menant leur vie à un rythme effréné. Ils luttent sans cesse pour gagner plus d'argent, source de respect, d'influence et de pouvoir à Waterdeep. Globalement, ils sont unis par le désir d'améliorer leur existence.

Malgré leur ouverture d'esprit, les Waterdhavian ont tendance à se méfier des Amniens et des "barbares du Nord".
## Story
  
**Histoire ancienne **

**−1288 DR** 
		Melairbode fut créé dans la montagne à côté et en dessous d'Aelinthaldaar par le roi nain Melair Ier, qui commença à y exploiter du mithral. À mesure que de plus en plus de nains du clan Melairkyn arrivaient, ils étendirent leur foyer pour inclure des zones de plus en plus proches de la surface, ce qui inquiétait les elfes. En échange d'une grande quantité de mithral extrait par les nains Melairkyn, les elfes créèrent un effet magique sur le plateau sur lequel se trouvait leur ville. Cela garantissait que quelle que soit la situation en dessous, la surface resterait intacte et ne s'effondrerait jamais en dessous. 
	**−1100 DR** 
		Aelinthaldaar fut rasée après que les elfes habitant la ville se soient retirés à Evermeet. Elle fut bientôt reprise par des tribus barbares qui l'utilisaient comme centre commercial à partir de −1088 DR, faisant affaire avec des peuples plus au sud. Le port naturel profond sur le site en faisait un point particulièrement avantageux pour tenir des réunions commerciales, car de grands navires pouvaient charger et décharger des marchandises. Finalement, les tribus firent de la région leur domicile permanent plutôt que de la revisiter pour chaque réunion commerciale. Cependant, les conflits étaient courants en raison des opportunités commerciales lucratives. 
	**−750 DR** 
		Les Netherese s'étaient installés à Melairbode sans y être invités et avaient établi leur foyer à côté des nains. L'Enclave de Sargauth fut taillée dans la roche par des sorts magiques, puis scellée. Au fil des ans, un manteau fut érigé qui servait à un but similaire à celui d'un mythal. 
	**−677 DR**
		Les drows commencèrent à repousser les nains Melairkyn et revendiquèrent de plus en plus de l'Undermountain pour eux-mêmes. 
	**−339 DR** 
		La perturbation du Tissage provoqua l'effondrement de la majeure partie de l'enclave nethérisienne ; ce qui restait devint ce que l'on appelle aujourd'hui Portcrâne. 
	**52 DR** 
		À cette époque, une communauté agricole permanente d'Illuskan avait été établie. 
		
**Fort de la Cape Noire** 
	
**168 DR** 
		Le magicien Halaster Blackcloak s'installa dans la région et construisit le Fort de Halaster un peu plus au nord-ouest de la communauté agricole. Entre 171 DR et 308 DR, il mena les Chasses de Halaster qui exterminèrent brutalement les drows et les duergars de l'Undermountain, dégageant l'espace pour ses propres desseins. 
	**211 DR** 
		Les drows finirent par expulser tous les nains Melairkyn restants de l'Undermountain. 
	**302 DR** 
		Les eaux du Marais des Lézards montèrent, forçant l'abandon de la colonie de Tavaray. Les établissements humains sur le site futur de Waterdeep devinrent beaucoup plus isolés, et le manque de prospérité et de contacts extérieurs amena la population à se diviser en tribus. 
	**307 DR** 
		Les apprentis d'Halaster Blackcloak, connus sous le nom de Sept, abandonnent le Fort de Halaster pour l'Undermountain. Le fort du magicien tomberait ensuite en désuétude. Fort de la Main Sanglante 
	**482 DR** 
		Un seigneur de guerre de Tethyr nommé Ulbaerag Main Sanglante vint dans la région et unifia les tribus, revendiquant la colonie comme "Fort de la Main Sanglante". Il commença à exporter du bois sur des navires destinés à des régions plus au sud qui ne bénéficiaient pas de si grands arbres que ceux que l'on trouvait dans le Nord. Ulbaerag rejeta activement l'opportunité de rejoindre le Royaume de Phalorm, connu sous le nom de "Royaume des Trois Couronnes". Ce n'est que lorsque son fils prit le pouvoir que le Fort de la Main Sanglante rejoignit finalement le Royaume. La construction de projets de construction et d'irrigation étendus a commencé. 
	**493 DR** 
		Les drows de l'Undermountain abandonnent enfin leur ancien foyer. 
	**615 DR** 
		La Horde des Terres Désolées a envahi Phalorm, détruisant Uthtower et menant à la formation de la Mer des Morts. Les Montagnes de l'Épée ont été infestées d'orcs, mais le Fort de la Main Sanglante a survécu. L'effondrement du Royaume des Trois Couronnes a conduit à la formation du Royaume de l'Homme. Malgré le maintien de son indépendance par le Fort de la Main Sanglante, il était largement considéré comme faisant partie du royaume. 
	**697 DR** 
		Sans héritier apparent au Royaume de l'Homme, il est tombé en guerre civile. Malgré le conflit, le Fort de la Main Sanglante est resté. 
	**734 DR**
		De mauvaises récoltes et des incendies d'été intenses ont poussé le dirigeant du Fort de la Main Sanglante, Raulbaera Main Sanglante, à établir une colonie périphérique nommée Fort de Rowan. Des années plus tard, il serait connu sous le nom d'Amphail.
		
**Nimoar's Hold**

**872/882 DR** 
		Un chef tribal connu sous le nom de Nimoar le Pillard mena sa tribu à la recherche d'un nouveau foyer après la chute des royaumes elfiques. Nimoar et sa tribu tombèrent sur le Fort de la Main Sanglante et n'eurent aucun mal à s'en emparer, le renommant "Fort de Nimoar". 
**887 DR** 
		Le Fort de Nimoar subit une attaque de pirates importante, mais tint bon et fut reconstruit. 
**889 DR**
		La tribu du Cerf-Élan, originaire de la Dessarin, mit le Fort de Nimoar en flammes, mais fut finalement vaincue. 
**927 DR** 
		Comme l'avait prophétisé le chaman orc, Wund des Montagnes de l'Épée, la Peste du Sang se répandit sur les sommets des montagnes, et à la suite de cet événement, il unifia les orques sous la direction du roi Uruth Ukrypt. Leur présence croissante allait déplacer de nombreuses bêtes et monstres, y compris un grand nombre de trolls.

**Age of Warlords**  
**Trollwars**  

En raison de vastes soulèvements orques et de la croissance démographique dans le nord, les trolls furent chassés de leurs foyers et poussés vers le sud, dans la région maintenant connue sous le nom de Evermoors. Cette migration provoqua un conflit important et durable avec les humains du Fort de Nimoar.

**932 DR** 
	Le premier conflit des Trollwars éclata cette année-là. Avant la fin de l'année, les humains purgèrent la région des marais des trolls. 
**936 DR**  
	Les armées orques d'Uruth Ukrypt attaquèrent le Fort de Nimoar lors d'une série de batailles qui marquèrent le début de la Guerre d'Orcfastings. Bien qu'ils remportèrent un certain nombre de victoires, le Duc de Calandor renversa le cours de la guerre en brisant le siège orc lors de la Bataille des Falaises Brûlantes. Finalement, le roi Uruth tomba lors de la Bataille de Westwood et le chaman orc Wund peu après. 
**940 DR**  
	Le deuxième conflit des Trollwars éclata lorsque les trolls firent des raids continus sur les établissements humains. Ils se poursuivirent pendant 12 ans. Nimoar mourut et Gharl fut choisi pour être le prochain "Seigneur de Guerre" du Fort de Nimoar. L'utilisation du nom "Waterdeep", comme alternative à "Nimoar's Hold", devint courante. 
**952 DR**  
	Le mage de 32 ans, Ahghairon, utilisa son pouvoir arcanique pour mettre fin aux Trollwars dans une victoire décisive. Cependant, les six Seigneurs de Guerre de la ville furent tués au combat. Un chevalier de Tyr nommé Samular Caradoon fut reconnu comme un héros pendant ce conflit et fonda par la suite l'Ordre Saint de Samular. Un temple et un monastère dédiés à Lathander furent construits à l'extérieur de la ville, qui seraient plus tard connus sous le nom de Spires of the Morning. 
**974 DR** 
Après le conflit, un fortifié fut construit sur les pentes de la montagne, et les murs continuèrent à s'agrandir à mesure que de plus en plus de gens des environs vinrent chercher protection dans la forteresse. Pendant cette période, le fort et la zone environnante furent connus sous le nom de "Free City of Waterdeep". 
**1010 DR**  
	Le Fort de Nimoar devint connu sous le nom de Free City of Waterdeep. Pendant cette année, le port fut fortifié et ses murs furent agrandis et reconstruits. Lauroun devint le premier Seigneur de Guerre de Waterdeep. 
**1024 DR**  
	Les aventuriers waterdhaviens connus sous le nom de Dawnbringer Company attaquèrent Ukrypt, un crypte sacré pour la Confrérie du Fléau Écarlate, qui leva la horde d'orcs des Os Brisés en représailles. Bien qu'ils furent la première horde d'orcs à quitter les montagnes depuis une génération, leur assaut sur Waterdeep fut arrêté lorsqu'ils furent attaqués par les "Griffes de la Côte", Lhammaruntosz. 
**1026 DR** 
	La Confrérie du Fléau Écarlate rassembla une autre horde d'orcs des Montagnes de l'Épée, connue sous le nom de Griffes Noires, et les envoya attaquer Waterdeep. La Seigneur de Guerre Laroun perdit la vie en défendant les remparts de la ville contre les assaillants monstrueux. Les orcs furent finalement vaincus à Stump Bog. Après la mort de Laroun, le Seigneur de Guerre Raurlor devint le souverain de Waterdeep.
	
**Age of Ahghairon** 

**1032 DR** Raurlor utilisa la richesse de la ville pour créer un vaste "Empire du Nord". Ahghairon exprima une forte opposition à cela en 1032 DR, et Raurlor ordonna qu'il soit arrêté. Lorsque Ahghairon utilisa sa magie pour empêcher son propre arrestation, Raurlor l'attaqua, mais Ahghairon transforma l'épée de Raurlor en serpent, qui infligea une morsure empoisonnée, le tuant finalement. Ahghairon se déclara le premier "Seigneur" de Waterdeep, créant le corps gouvernant presque entièrement anonyme qui durerait des siècles. Tous les seigneurs de la ville, sauf un, initialement lui-même, avaient leurs identités cachées aux citoyens de la ville. Sous Ahghairon, Waterdeep sécurisa les zones au nord pour les humains et construisit de nouvelles routes pour les interconnecter, tout en continuant à croître jusqu'à cinq fois sa taille, devenant de plus en plus prospère. La ville développa le surnom de "Couronne du Nord". Ahghairon restructura l'armée et la marine que Raurlor avait construites en garde-ville et en garde-côtes. 
**1035 DR** 
	Waterdeep commença à utiliser son système de quartiers de la ville. Les quatre quartiers originaux étaient le quartier du château, le quartier des métiers, le quartier du port et le quartier du temple. 
**1037 DR**  
	Des créatures d'un autre plan apparurent à Waterdeep après être sorties de l'Undermountain. Ahghairon et l'un des seigneurs masqués, Kherris, les renvoyèrent. 
**1064 DR** 
	La population de Waterdeep atteignit 50 000 habitants. 
**1071 DR**  
	La célèbre aventurière Ranressa Shiard revint sur les pentes du mont Waterdeep montée sur le ver de cuivre Galadaeros. Cet événement conduisit Ahghairon à placer un puissant mythal au-dessus de la ville, qui agissait comme une barrière magique contre les bêtes volantes. 1076 DR Waterdeep fut attaquée par Nelethra la Lance Ailée et le Sanglier Noir de Téthyr de la Vallée de Dessarin. 
**1101 DR**  
	Les murs de la ville furent encore agrandis pour inclure les Spires du Matin, le temple de Lathandar qui se trouvait auparavant à l'extérieur de la ville. 
**1148 DR**  
	Le nécromancien netherese Shradin Mulophor, qui serait plus tard connu sous le nom de "Seigneur des Os", découvrit les ruines de l'Enclave de Sargauth et utilisa les chambres détruites comme son propre domaine personnel. Il ouvrirait des routes commerciales avec divers pouvoirs du Sous-monde en reliant la rivière Sargauth à des voies navigables souterraines et une série de portails vers d'autres terres. 
**1150 DR**  
	Waterdeep fut touchée par la peste qui voyageait le long de la Côte de l'Épée. Khelben l'Ancien arriva pour la première fois dans la ville.
**1173 DR** 
Le repaire du Seigneur des Os était un établissement permanent à cette époque et est devenu connu sous le nom de "Port de l'Ombre", ou Skullport.
**1179 DR** 
Maulagrym a attaqué la Tour du Bâton noir mais a été vaincu par Khelben, Elminster, Hamiklar Wands et d'autres mages de Waterdhavien.
**1184 DR** 
Le Seigneur des Os a entrepris une expédition dans les Cavernes profondes et est revenu à Skullport en homme instable et imprévisible.
**1235 DR** 
La Côte de l'Épée a été envahie et Waterdeep assiégée par la plus grande horde d'orques de l'histoire enregistrée. Le siège de la ville a duré neuf mois, et a été brisé lorsque Ahghairon a utilisé des griffons pour faire voler des fournitures de nourriture et d'aide dans la ville. Ces actions courageuses ont conduit à la formation de la cavalerie de griffons.
**1246 DR** 
Le Seigneur masqué Kerrigan a commencé à assassiner d'autres Seigneurs de la ville. Il a assassiné trois des dirigeants de la ville dans une tentative de prendre le pouvoir, avant qu'Ahghairon ne le confronte dans un combat de magie qui s'est terminé par la mort du Seigneur masqué dans la Région Sud. C'est le seul acte de trahison connu parmi les Seigneurs de Waterdeep.
**1248 DR** 
Comme le crime et la tromperie ont commencé à se développer à Waterdeep, Ahghairon a ordonné la création de guildes de ville, une tendance des villes du sud, pour empêcher la propagation des problèmes.
**1250 DR** 
En raison d'un manque d'espace, les tombes individuelles dans le cimetière de Waterdeep ont été remplacées par des tombes, ce qui a conduit à la création de la Cité des Morts.
**1252 DR** 
Des problèmes avec les morts-vivants provenant de la voie la plus récemment construite ont conduit à l'élévation de murs autour de la Cité des Morts, pour la séparer du reste de la ville.
**1255 DR** 
Les Voleurs de l'Ombre ont commencé à opérer dans la ville de Waterdeep.

**Reign of Guildmasters**

**1256 DR**
Lord Ahghairon décéda et fut enterré de manière cérémonieuse dans sa tour. Celle-ci fut scellée, protégée par la magie, et au milieu du XIVe siècle DR, elle n'avait jamais été dérangée. Le décès d'Ahghairon fut suivi de troubles alors que les marchands de Waterdeep se disputaient le pouvoir. Rien ne fut entendu des Seigneurs masqués de Waterdeep. Cela était dû au fait que la plupart de leurs identités avaient déjà été compromises et qu'ils avaient été assassinés.
En réalité, après la mort d'Ahghairon, les seuls Seigneurs masqués survivants étaient le menuisier Baeron et l'apprenti sorcier Shilarn. Après deux mois, le pouvoir fut pris par le Conseil des Guildes, qui avait été nommé par Ahghairon. Cela laissa le Conseil des Guildes responsable de la règle de la ville.
Les guerres des guildes commencèrent. Cette période de six ans de querelles et de méfiance fut marquée par des luttes violentes entre les familles marchandes aux mains de mercenaires engagés.
**1262 DR**
Les guerres des guildes se terminèrent par une grande quantité de sang versé dans la ville. Après le conflit, seuls deux guildemestres survivants, le joaillier Ehlemm Zoar et le charpentier de navires Lhorar Gildeggh, restèrent en position de leadership. Fatigués et épuisés des querelles, ils décidèrent de gouverner ensemble, sous le titre de "Seigneurs Magistrats", en 1262 DR. Malgré leur partenariat initial, ils ne s'accordaient sur rien d'autre. Leurs querelles continuèrent à créer des tensions au sein de la ville et seraient connues sous le nom de "Gouvernance défectueuse des Seigneurs Magistrats".
Les Voleurs de l'Ombre commencèrent leurs opérations dans la ville.
Règnes de Baeron et Lhestyn
**1273 DR**
Les Seigneurs Magistrats furent visités par Baeron et Shilarn qui s'étaient dissimulés sous des capes. Shilarn ordonna aux Seigneurs Magistrats de quitter la ville. Quand ils refusèrent, elle les abattit avec sa magie et les tua tous les deux. Baeron et Shilarn, les deux anciens Seigneurs masqués restants, prirent le pouvoir et réinstallèrent les Seigneurs de Waterdeep. Baeron révéla publiquement son identité et assuma le rôle de Seigneur de l'Eau Profonde.
Les maisons Gildeggh et Zoar furent bannies de Waterdeep.
Afin de prévenir davantage la découverte des identités des Seigneurs masqués, un groupe de Magistrats nommés les Robes Noires fut instauré comme juges et dispensateurs de la loi. Uktar: Les Voleurs de l'Ombre furent interdits à Waterdeep.
**1276 DR**
Lhestyn naquit de Baeron et Shilarn.
La ville s'agrandit pour contenir six quartiers, avec l'ajout du quartier Nord et du quartier de la Mer.
**1298 DR**
Lhestyn, sous le pseudonyme de la "Dame Masquée", infiltra la guilde des voleurs de Waterdeep et les exposa dans toute la ville. Les membres du groupe furent soit tués sur-le-champ, soit chassés de la ville.
**1300 DR**
Lhestyn et Zelphar Arunsun de Neverwinter, le plus jeune fils de Khelben l'Ancien, se marièrent.
**1302 DR**
Lhestyn a donné naissance à Khelben Arunsun le Jeune, fils de Zelphar et petit-fils de Khelben "Blackstaff".
**1308 DR**
Lord Baeron est mort d'une fièvre, et sa femme Shilarn s'est jetée sur son bûcher funéraire.
Lhestyn est devenue la Dame ouverte de Waterdeep.
Le palais de Lhestyn a été construit sur les ruines d'une ancienne abbaye chaunteuse.
**1311 DR**
En guise de faveur aux Voleurs de l'Ombre, un liche anonyme de la Rune Tordue a assassiné Zelphar Arunsun au moyen d'une main d'arcane de force. L'identité du meurtrier de Zelphar resterait inconnue des seigneurs de la ville pendant plus d'un siècle.
Après la mort de son fils, Khelben "Blackstaff" est retourné à la Tour du Bâton noir pour former son petit-fils comme le nouveau Bâton noir. Khelben le Jeune a assumé la seigneurie sur la tour.
Pour mieux protéger la Dame ouverte et leurs proches, le Seigneur masqué Durnan a formé les Cordon-rouges.
Lhestyn a nommé Piergeiron le Paladinson comme son successeur pour gouverner Waterdeep en tant que Dame ouverte.

**Règne de Piergeiron**

**1314 DR**
Dame Lhestyn est morte et Piergeiron a pris la relève en tant que Dame ouverte de Waterdeep.
**1321 DR**
Khelben le Jeune a quitté Waterdeep. Khelben l'Ancien a continué à servir de seigneur de la tour, sous le prétexte de son petit-fils.
**1345 DR**
Pendant la Nuit des Feux du Temple, le désordre religieux entre les églises de Lathander, Selûne, Shar et Tempus a conduit les Flèches du Matin et la Maison des Héros à être incendiées. Les deux ont été reconstruits en moins d'un an.
**1355 DR**
Amril Zoar, membre de la famille Zoar exilée, a tué deux seigneurs masqués de la ville, Dame Tamaeril Bladesemmer et Seigneur Resengar la Barbe Blanche, et a gravement blessé le Seigneur Piergeiron. Après avoir été capturé, il a été épargné de l'exécution par Storm Silverhand et les Harpistes.
**1356 DR**
Les Guerres de Dragonspear éclatent après que des patrouilles de soldats de Waterdeep aient été attaquées par des démons et des gobelins des Marches ouvertes par le biais du Château de Dragonspear. :Le Tom de la Licorne a été volé à la Bibliothèque Verte, par Shond Tharavin. Cela a conduit à ce qu'un caravelle luskanite soit coulé par l'île Nelanther de Ruathym.
Waterdeep a négocié la paix entre Ruathym et la ville de Luskan.
Le Temps des Troubles
Pendant le Temps des Troubles de l'Année des Ombres, la magie a déraillé à Waterdeep comme partout ailleurs dans les Royaumes.
**1358 DR**
Kythorn 20 : Mystra, la grande déesse de la magie et l'une des plus puissantes des dieux, fut détruite. Un avatar d'une déesse apparut à Waterdeep, appelant les fidèles à elle. La nuit suivante, ils se rassemblèrent au temple de la Maison de la Lune et la proclamèrent être Selûne, la Déesse de la Lune. Cependant, le Seigneur Piergeiron et Khelben Arunsun étaient méfiants, et proposèrent d'être des hôtes bons mais vigilants. À l'instigation de l'avatar, une foule attaqua la supposée incroyante Vajra Valmeyjar, tandis que l'avatar vainquit Luna dans un combat de sorts sur les marches du temple devant les fidèles. L'avatar fut plus tard l'invité d'honneur lors d'une fête au Château de Waterdeep, mais cela fut perturbé par l'Armée Noire de la Nuit et ensuite par un combat de sorts entre l'avatar et Kyriani. Piergeiron et la noblesse en vinrent à penser que le comportement de la déesse était imprudent et qu'ils avaient peut-être été hâtifs en la bienvenue.
Selune v Shar DC Comics
Selûne et Shar se battent dans les rues de Waterdeep.

La magie chaotique fit se tordre et tournoyer les rues de Waterdeep, transformant les routes plates en monticules et creux dans le Dock Ward et le Sea Ward. Finalement, après avoir infiltré la Maison de la Lune et sauvé Luna, les héros de la taverne Selûne's Smile — Vajra, Kyriani, Timoth Eyesbright et Onyx the Invincible — exposèrent le faux avatar comme étant la déesse Shar, tandis que Luna elle-même était vraiment Selûne. De retour à Selûne's Smile, ils furent attaqués par un trio de cavaliers de nuit et leurs larbins, et virent l'Escalier Céleste s'élever du Mont Waterdeep. Shar attaqua les héros aux ruines de la taverne, mais finalement ils renouvelèrent Selûne. La défaite de Shar par Selûne dans les rues de Waterdeep devint célèbre dans tous les Royaumes.
Plus tard, Midnight et ses compagnons, Cyric, Kelemvor et Adon, arrivèrent à Waterdeep. Peu de temps après, Myrkul apparut dans la ville depuis la Piscine de la Perte sous l'auberge du Portail Bâillant avec l'une des Tablettes du Destin et invoqua une légion de démons et de morts-vivants qui se déversèrent dans la ville, provoquant de vastes incendies et des destructions généralisées, principalement dans les quartiers du Château, du Dock et du Sud de la ville. Midnight et ses compagnons étaient accompagnés par Elminster et Khelben l'Ancien alors qu'ils se retranchaient dans la Tour du Bâton Noir, ayant caché la tablette dans la bibliothèque de la tour.
Avant que Myrkul ne puisse monter l'Escalier Céleste, Midnight parvint à voler l'une des tablettes, grâce à sa croissance de pouvoir arcanique. Le dieu et ses sbires attaquèrent Midnight et ses alliés. Alors qu'un cavalier de griffon volait vers la tour et distrayait temporairement le Dieu Mort, Midnight parvint inexplicablement à désintégrer l'avatar de Myrkul, même au milieu d'une zone de silence. Après la mort de Myrkul, un nuage de pestilence brune tomba du toit de la tour et dériva sur deux pâtés de maisons de la ville, faisant flétrir les plantes et étouffant les gens et les animaux.
Midnight et Cyric accédèrent à la divinité.
**1361 DR**
Les histoires de la Maztica nouvellement découverte et les rumeurs d'un assassin des Harpistes se répandirent à Waterdeep.
**1364 DR**
En été de cette année, Waterdeep connut de sévères sécheresses et une activité de monstres accrue.
Shieldmeet : Les célébrations au Champ de Triomphe furent perturbées par le dragon vert Grimnoshtadrano.
**1365 DR**
Waterdeep établit un commerce limité avec Zakhara et Maztica, mais les voyages en mer étaient très dangereux.
**1369 DR**
Ches 30 : Une armée de monstres marins, dirigée par le requin-garou Iakhovas, envahit Waterdeep par le port lors de la Guerre de Deepwater. Une grande partie des quartiers du Dock et de la Mer furent endommagés lors du conflit.
Haute Moisson : Le Mage Fou Halaster libéra une horde de monstres dans la ville via des portails, détruisant une grande partie du Château et des Quartiers des Échanges dans ce qui allait devenir connu sous le nom de Haute Moisson de Halaster.
**1372 DR**
Khelben Blackstaff, Storm et Laeral Silverhand menèrent des armées contre les phaerimm qui s'étaient échappés du Mur de Sharn. ;1374 DR: :À cette année, les seuls vestiges de l'Aelinthaldaar longtemps détruit étaient des cryptes sous le Temple du Panthéon de la Seldarine, et la magie qui empêchait le plateau de s'effondrer.
**1375 DR**
Eleint 30 : Halaster Blackcloak mourut. En conséquence, des tremblements de terre ravagèrent la ville et de nombreux Waterdaviens eurent des visions liées à la mort du mage.
**1378 DR**
Le garde du corps loyal de Piergeiron, Madeiron Sunderstone, est tué dans une tentative d'assassinat contre le Seigneur de l'Eau Profonde.
**1379 DR**
Piergeiron le Paladinson meurt en fonction de son âge et de sa mauvaise santé, après plusieurs tentatives d'assassinat de la part de ceux de plus en plus impatients de le remplacer par leurs diverses marionnettes.
Un mois après sa mort, après que de nombreux candidats eurent été proposés par divers Seigneurs masqués, mais rejetés par d'autres, il fut remplacé par la marchande respectée dans le commerce du parchemin, du papier et de la reliure de livres Audreithra Teltorna. Elle était une candidate de compromis, initialement vue au sein des Seigneurs et à travers la ville comme une gardienne, mais qui a gagné le respect tout en étant en fonction.

**Spellplague**

**1385 DR**
Tarsakh 29 : La Peste des Sorts ravagea Toril, modifiant considérablement le paysage de Faerûn.
Six statues ambulantes furent exilées du plan éthéré et ravagèrent la ville.
Pendant le tumulte, les agents de Xanathar réussirent à assassiner la Seigneur de l'Eau Profonde Audreithra Teltorna, dans l'intention d'installer leur marionnette parmi les Seigneurs masqués comme son remplaçant. Cependant, ils exagérèrent leur jeu, et leur candidat, le charpentier de navires Andramas Rujyntral, fut rejeté par les Seigneurs. Une série d'assassinats parmi les Seigneurs suivit alors que les agents de Xanathar se vengeaient et cherchaient à éliminer les candidats rivaux au sein des Seigneurs et les adversaires les plus acharnés de Rujyntral, mais cela poussa divers seigneurs à engager des aventuriers pour assassiner à la fois Rujyntral et tous les agents de Xanathar qu'ils pouvaient identifier et traquer. Ils réussirent si bien que le Xanathar perdit non seulement Rujyntral, mais il subit la perte de tant d'agents humains loyaux qu'il décida de se retirer dans l'ombre, reconstruisant son réseau avec lenteur et prudence et restant bien loin des Seigneurs masqués (une politique qui resta en vigueur jusqu'à ce qu'un nouveau Xanathar succède au titre).
Les Seigneurs masqués endurèrent un peu plus de trois mois sans Seigneur de l'Eau Profonde à la barre, jusqu'à ce que les ravages de la Peste des Sorts exigent que leur porte-parole désigné (Voix intérimaire des Seigneurs) Watchlord Phulundaera Vantur (une vétéran chevronnée qui avait gravi les échelons ; son corps très marqué incorporait des membres et des organes magiquement liés de camarades tombés) soit adoptée comme Nouvelle Seigneur de l'Eau Profonde. Phulundaera était rusée et brute et sans chichis, et les guildes et les simples citoyens des rues l'aimaient, car elle représentait l'égalité de traitement en vertu des lois et des politiques de la ville, pour les hauts et les bas. Cette même qualité la rendait détestée par les nobles et les 'nouveaux riches' aspirants nobles, et ils essayèrent de lui organiser de nombreux accidents.
**1395 DR**
Une épidémie appelée l'Anathème Putrescent, qui provenait du Marais de la Souche, dévasta Waterdeep et les environs, en particulier les Champs Dorés. La combinaison de la maladie et de la perte de la réserve de grains tua des milliers de personnes dans tout le royaume.
La majorité des effets de la Peste des Sorts prirent fin et la plupart de la magie arcane revint à la normale.
**1445 DR**
Les "mains du temps", une "horloge golemique", furent achevées et installées dans la plus haute tour du Palais des Seigneurs.
**1468 DR**
Dagult Neverember, l'homme le plus riche de la ville, devint Seigneur de l'Eau Profonde.
**1479 DR**
À cette époque, le quartier de Field avait été établi, et Skullport n'était plus habité.
La 8ème statue ambulante, le Griffon, apparut à Waterdeep et défendit la Tour d'Ahghairon. Elle finit par s'installer près du sommet de Mount Waterdeep et devint finalement un repère de la ville.

**Post–Second Sundering**

**1489 DR**
En réponse à l'augmentation de l'activité des dragons et des cultistes, le Conseil de Waterdeep fut formé, réunissant des représentants de royaumes de tout le Sword Coast. La menace du Culte du Dragon fut mise en évidence lorsque le Seigneur masqué Arthagast Ulbrinter fut assassiné, bien qu'elle ait inspiré plus de détermination que de peur. Au milieu de ces événements, le Seigneur de l'Eau Profonde Dagult Neverember fut évincé par un vote des Seigneurs de Waterdeep, remplacé par Laeral Silverhand. Bien que Waterdeep ait été largement épargnée grâce à la dragonward, le quartier de Field fut quand même réduit en cendres par des attaques de dragons, ce qui déplaça un grand nombre de personnes.
**1490 DR**
Le château géant des nuages du comte Nimbolo et de la comtesse Mulara apparut dans les nuages et survola Waterdeep pendant un certain temps, déclenchant une panique générale. Des hérauts envoyés par Lady Laeral Silverhand ont tenté de calmer les citoyens et de promettre qu'il n'y avait pas de danger. En fait, les géants voulaient étudier l'histoire de Waterdeep et rencontrer ses dirigeants, car ils cherchaient des traces de l'ancien royaume des géants d'Ostoria.
**1491 DR**
La déesse Eilistraee réapparut sous les murs de Waterdeep, entraînant une augmentation du nombre de ses adeptes dans la ville. Ils finirent par rechercher Remallia Haventree et lui demandèrent un bosquet sacré dans les ruines du quartier de Field. En Mirtul, la crise du logement à Waterdeep s'était aggravée alors qu'une maladie mystérieuse tuait ou chassait tous les habitants de Downshadow, le quartier de Field restait désolé par le feu des dragons, et Mistshore était incendié par des agents du Seigneur masqué Braethan Cazondur, rendant les trois quartiers non officiels inhabitables.
La peur menaça de s'emparer de Waterdeep une fois de plus lorsque le château géant des nuages de Burruld survola l'océan près de la ville. Après que le Blackstaff Vajra Safahr eut paniqué et menacé les géants, le Seigneur de l'Eau Profonde Laeral Silverhand calma la situation, négocia avec Burruld, et apprit que leur but était de rechercher la fille perdue du roi Skyvald, la princesse Irie.
Au milieu de Mirtul, de nombreux Seigneurs masqués et d'autres personnes furent horriblement assassinés dans le cadre d'une conspiration de Cazondur pour prendre le contrôle de la ville. Le Seigneur de l'Eau Profonde Laeral Silverhand, assisté par Elminster et Mirt, travailla pour maintenir l'ordre dans la ville tout en enquêtant sur les meurtres. Alors qu'elle tentait d'appréhender Cazondur, Laeral elle-même fut tuée et désintégrée par un piège étonnamment simple impliquant des rochers tombants, mais elle récupéra avec l'aide d'Elminster. Un affrontement extrêmement dramatique au Palais de Waterdeep entre Laeral et Cazondur devant des serviteurs, des nobles et des maîtres de guilde assemblés se solda par la mort de Cazondur aux mains d'un troisième parti inattendu, les agents du Xanathar Belvarra Bowmantle et Suthool. Y compris Cazondur, un total de treize Seigneurs masqués et des dizaines d'autres furent tués, et plusieurs Seigneurs supplémentaires furent démasqués publiquement.
Une délégation de la ville de Mirabar disparut en route vers la ville, ayant été détournée par des cultistes de l'Œil Élémentaire Ancien.
**1492 DR**
La violence éclata dans les rues et les arrière-salles de la ville alors que des factions rivales cherchaient le trésor détourné de l'ancien Seigneur de l'Eau Profonde Dagult Neverember, guidées par la Pierre de Golorr. Les Gralhunds, les Cassalanters, Jarlaxle, Manshoon, Xanathar, et d'autres causèrent bien des problèmes les uns aux autres et à la ville alors qu'ils se battaient pour le prix. Le trésor fut finalement trouvé dans une section cachée des ruines de Melairkyn à l'intérieur d'Undermountain, gardée par le dragon d'or Aurinax, qui avait également reçu le Bâton de Dragon d'Ahghairon de Neverember.
## Points of Interest
  
Depuis le milieu du XIe siècle, Waterdeep était divisée en plusieurs quartiers de la ville. Comme les anciennes villes, telles que celles situées près de Sea of Fallen Stars, chaque quartier était à l'origine protégé par ses propres murs et gardes ; la nécessité d'un plus grand développement urbain a conduit à la destruction de nombreux de ces obstacles. Finalement, seuls les murs autour de la Ville des Morts sont restés.

**Castle Ward**
Ce quartier central englobait le mont Waterdeep et une grande partie du gouvernement de la ville. Situé à l'intérieur se trouvait le château de Waterdeep, le lieu du gouvernement, ainsi que le palais de Waterdeep (également connu sous le nom de Palais de Piergeiron), la résidence privée de Lord Piergeiron, et la Tour du Bâton Noir, la résidence de l'Archimage de Waterdeep. Ce quartier était également un lieu commun pour les aventuriers à la retraite, comme Mirt le prêteur sur gage, pour faire leur maison.

**City of the Dead**
Ce parc était entouré de hauts murs. Avant le Spellplague, il était souvent visité pendant la journée par des promeneurs et des pique-niqueurs ; la nuit, les portes de la Ville des Morts étaient fermées, car c'était le cimetière de Waterdeep. Cependant, après le Spellplague, il est tombé en désuétude. Les personnalités les plus importantes avaient leurs propres tombes personnelles ou des autels familiaux, tandis que d'autres étaient confinées à des cryptes plus grandes. La raison des gardes n'était pas de protéger les tombes, mais plutôt de protéger la ville des créatures mortes-vivantes occasionnelles qui ne pouvaient pas apprécier leurs hébergements.

**Great Harbor**
Le Grand Port de Waterdeep

**Dock Ward**
Comme on pourrait le supposer, le Dock Ward était situé juste à côté du Grand Port de Waterdeep et abritait les docks, les chantiers navals et les entrepôts du commerce maritime. Le port était habité par des sirènes qui maintenaient la paix dans leur propre ville aquatique.

**Downshadow**
En fait, le niveau supérieur de l'Undermountain, Downshadow était la nouvelle "sous-ville" développée au 15ème siècle DR.

**Field Ward**
Le Quartier des Champs non officiel était le quartier entre le North Trollwall et les murs de la ville récemment construits orientés vers le nord. C'était le quartier le plus pauvre de la ville, rempli de criminalité et abritant de nombreux demi-humains démunis.

**Mistshore**
N'étant pas strictement un quartier, Mistshore était le port naval en ruines. La région était habitée par des parias et des criminels qui vivaient le long du rivage ou sur des navires naufragés à moitié coulés dans le port.

**Mountainside**
Mountainside a été développé sur les pentes nord et nord-est du mont Waterdeep après la Seconde Pestilars lorsque les nobles riches et ceux de fortunes montantes ont fui vers un air plus propre.

**North Ward**
Niché dans la partie nord-est de la ville, le North Ward était le domicile de la noblesse et de leurs villas. Les classes aisées faisaient leur maison ici, loin de l'agitation des classes inférieures près des docks et dans le Quartier Sud.

**Sea Ward**
Le quartier le plus riche, le Sea Ward, contenait de nombreux temples de Waterdeep, ainsi qu'une bonne partie des nouvelles familles nobles et des aventuriers à la retraite qui pouvaient se permettre une ou deux villas. Le Champ de la Victoire, l'arène de Waterdeep, était situé ici.

**Southern Ward**
Parfois appelé simplement "Sud" par les habitants, le Quartier Sud était un lieu de maîtres de caravanes et de commerçants, car il était proche de la Porte Sud, l'ouverture vers le Commerce.

**Trades Ward**
La section commerciale de Waterdeep.

**Undercliff**
Le dernier quartier (en 1479 DR) formé à la base des falaises orientales. Il était relié au reste de la ville par des tunnels souterrains.


## Valuables
La ville était le centre du commerce des terres riches en minéraux au nord, des royaumes marchands d'Amn et de Calimshan au sud, des royaumes de la mer intérieure à l'est et des royaumes et des marchands de la mer à l'ouest. L'autorité de Waterdeep s'étendait de 30 milles (48 km) à 40 milles (64 km) de ses murs.

Au début des années 1370 DR, de la pierre était importée de Mirabar via Luskan pour être utilisée dans la construction, ayant été transportée magiquement. C'était un processus coûteux. Pendant cette période, il a été constaté que les wagons et les charrettes encombraient les marchés de la ville alors que les vendeurs étrangers tentaient de vendre autant que possible avant de rentrer chez eux pour l'hiver. Cette pratique était ignorée par la Garde, la Surveillance et les guildes.

La ville était également le plus grand port de spelljamming de Faerûn. Bienvenue pour la plupart des races spatiales, les lois de Waterdeep exigeaient que tous les vaisseau atterrissent sur l'océan à plusieurs milles de la ville et fassent leur approche finale par la mer. Les transgresseurs étaient punis de lourdes amendes et d'emprisonnement. Cette règle empêchait certains types de vaisseau d'atteindre jamais Waterdeep, mais était appliquée pour éviter une panique de la population. Les vaisseau en partance étaient soumis aux mêmes règles.

Le stationnement au port de Waterdeep entraînait des frais de 1 cp par 10 pieds (3 mètres) de longueur de quille par semaine. Les sages et les commerçants de Waterdeep étaient impatients d'écouter les histoires de l'espace sauvage et de commercer sur tous les produits que la ville avait à offrir.

## Système de transport
  
Waterdeep se caractérisait par ses rues et boulevards larges et animées. Son trafic dense, constant tout au long de la journée et la plupart de la nuit, était surveillé par les gardiens de la circulation de la Garde de la Ville. Les rues étaient bien entretenues et signalées par la Guilde des Scribes et Clerics, qui fabriquaient et installaient des étiquettes et des panneaux dans toutes les intersections.

Les transports en commun étaient disponibles à Waterdeep via plusieurs options :

Les charrettes étaient de grandes voitures collectives à deux étages qui comportaient un grand nombre de sièges et qui parcouraient des trajectoires prédéfinies le long des principaux boulevards. Les tarifs variaient entre 2 et 4 nibs (le nom local donné à des pièces de copper).

Les calèches à louer étaient des calèches à deux roues et deux places qui pouvaient être appelées et envoyées à des emplacements spécifiques. Les conducteurs de calèches à louer parcouraient les rues de la ville à la recherche de passagers, qui pouvaient appeler une calèche gratuite en criant. Les tarifs, convenus à l'avance, ne dépassaient rarement les 6 éclats (le nom local donné à des pièces de copper).

Les voitures étaient des véhicules de luxe pouvant accueillir jusqu'à 8 passagers confortablement. Les prix variaient, mais généralement les voitures et leurs chauffeurs et serviteurs respectifs étaient loués pour une journée entière.

## Defense
Waterdeep entretenait deux forces armées distinctes, la Garde de la Ville et la Surveillance de la Ville. La Garde de la Ville servait de soldats à Waterdeep et ses membres étaient en poste dans les garnisons, les patrouilles routières et les postes de surveillance, et servaient également de gardes du corps et de gardes de portes. La Surveillance était la force de police locale, agissant en tant que gendarmerie dans la ville. Les missions plus délicates prises au nom de la Cité des Splendeurs (nom alternatif à Waterdeep) étaient confiées à Force Grise, une force d'élite d'une douzaine de lanceurs de sorts expérimentés et de guerriers astucieux.

Waterdeep était protégée par de solides remparts sur ses côtés terrestres et était protégée en partie par le Mont Waterdeep du côté de la mer. Le Mont Waterdeep était parsemé de tours de guet et de positions défensives, et patrouillé par des unités de garde spéciales sur des vols de griffons connus sous le nom de Cavalerie des Griffons.

En dehors de cela, Waterdeep bénéficiait également d'une grande population autochtone d'aventuriers qui étaient souvent plus que disposés à s'occuper de tous les malfaiteurs menaçant leur ville natale. Des entreprises notables qui sont intervenues pour aider Waterdeep en temps de péril comprenaient le groupe de héros qui a tué le premier Xanathar, le groupe tout-halfling connu sous le nom des Trois Défenseurs, la Compagnie des Porteurs de l'Aube, et peut-être le plus célèbre, la Compagnie des Aventuriers Fous.

La ville était également le foyer des huit énormes statues ambulantes de Waterdeep. Sept de ces statues pouvaient être animées par le Bâton de Waterdeep pour défendre la ville, tandis qu'une était trop endommagée pour être activée. Ces statues étaient extrêmement destructrices et n'étaient utilisées que pour repousser des armées ou remporter des batailles autrement impossibles.


