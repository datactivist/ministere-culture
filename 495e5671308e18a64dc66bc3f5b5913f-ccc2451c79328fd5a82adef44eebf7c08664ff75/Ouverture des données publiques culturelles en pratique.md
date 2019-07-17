---
title: "Ouverture des données publiques culturelles en pratique"
tags: Templates, Talk
description: View the slide with "Slide Mode".
---

# Ouverture des données publiques culturelles en pratique

<!-- Put the link to this slide here so people can follow -->
slide: https://hackmd.io/@cecileLG/Formation-Min-Culture

---
## Qui sommes nous ?

- Datactivist est un .red[**pure player de l’open data**] créé en 2016, par Samuel Goëta et Joël Gombin.

- Se positionnant sur .red[**toutes les étapes du travail d’ouverture des données**], Datactivist travaille tant avec les producteurs de données qu’avec les réutilisateurs et participe à l’appropriation des données par chacun.

- Nous appliquons nos propres .red[**valeurs**] : nous sommes une coopérative ; nos supports de formation et nos contenus sont librement réutilisables, publiés en licence Creative Commons.

- Une approche issue de la recherche : voir notamment **https://datactivist.coop/these**. 

- Nous animons la communauté [#TeamOpenData](https://teamopendata.org).

---
## Nos activités

- Conseil sur les .red[**stratégies d’ouverture de données**] : nous aidons les organisations dans la conception et la mise en œuvre de leur stratégie d’ouverture de données.


- .red[**Accompagnement dans la réutilisation de données ouvertes**] : nous aidons les organisations à utiliser les données au quotidien. 

- .red[**Sensibilisation et formation à la donnée**] : nous formons à la culture générale des données, nous enseignons les grands principes et bonnes pratiques de l'open data et nous introduisons à la data science. 

- .red[**Médiation de données**] : nous organisons des hackathons, des open data camps, des expéditions de données...


La médiation de données est aussi fondamentalement une animation de communauté(s). 

---
### Rappel des objectifs de la formation 

> * Appréhender le contexte et les opportunités d’une politique Open Data.  
> * Appréhender les outils pour la mise à disposition des données et leur réutilisation. 
> * Présentation de cas pratiques appliqués aux données culturelles.

**Vos attentes spécifiques :** 
* Problématiques liées aux données du secteur culturel
* Spécificités de la mise en oeuvre de l'open data dans le secteur culturel

---
## Rappel du programme de la formation 

#### Jour 1

1. Origines historiques de l’ouverture des données 
1. Les grands principes de l’ouverture des données 
1. Cadre juridique de l’ouverture des données 
1. Open government et Etat plateforme : l’ouverture des données dans la modernisation de l’Etat 
1. Les success stories de l’open data culturel 
1. La conception d’une stratégie d’open data : principaux leviers politiques, organisationnels, économiques 
1. Aperçu des principaux acteurs politiques, économiques et associatifs de l’open data 
1. Les formats de données 
1. Tour d’horizon des portails d’open data (CKAN, data.culture.gouv.fr, data.gouv.fr…)

---
## Rappel du programme de la formation 

#### Jour 2 

* Identification des données 
* Négociations et frictions dans l’ouverture des données : comment éviter les obstacles de l’open data ? 
* Extraction des données 
* Conversion et mise en qualité des données 
* Les standards émergents de l’open data culturel 
* Publication des données culturelles et production de métadonnées 
* Animation de l’open data et incitations à la réutilisation de données 
* Gouvernance des données et gestion de la relation avec les réutilisateurs 

---

class: inverse, center, middle

# 1 - Origines historiques de l’ouverture des données

---
### La DDHC : le texte fondateur de l'open data ?

Aller au-delà du droit d'accès et de la réédition des comptes (_accountability_) : réduire les asymétries d'information en accédant au matériau brut de l'information et du savoir


![](https://datactivist.coop/occitanie/img/ddhc.png)


---

### Open data : un terme récent

Le terme est apparu pour la première fois dans les années 1970 dans les accords qu’a signés la NASA avec des pays partenaires en vue du partage de données satellitaires. 

C’est en 1995 qu’on en voit le premier usage public aux Etats-Unis dans un rapport de la National Academy of Science intitutlé "_On the Full and Open Exchange of Scientific Data_".

Dans le langage courant, cela fait .red[**près de 10 ans**] que l'ouverture des données est devenue un élément majeur des politiques publiques numériques. 

--- 

##  1.a  Au fait, c'est quoi une donnée ?

---
### Introduction 

#### Ecoutez [l'interview de Serge Abiteboul, commissaire scientifique de l’exposition Terradata et directeur de recherche à l’Inria](https://www.youtube.com/watch?v=qqvsiTUJy7k)

{%youtube qqvsiTUJy7k %}

---
## Les données sont partout !

<img src="https://datactivist.coop/SPoSGL/sections/img/dataeverywhere.png" height="350"/>

*source : [The Economist](https://www.emc.com/collateral/analyst-reports/ar-the-economist-data-data-everywhere.pdf)*
 
 
---

## Une définition des données


<img src="https://datactivist.coop/SPoSGL/sections/img/kitchin.png" height="300">
 
 
> *Les données sont couramment comprises comme les matériaux bruts produits dans l’abstraction du monde en catégories, mesures et toute autre forme de représentation-nombres, caractères, symboles, images, sons, ondes électromagnétiques, bits qui constituent les fondations sur lesquelles l’information et le savoir sont créés.*
> 
---

### La pyramide Data-Information-Knowledge-Wisdom

<img src="https://datactivist.coop/SPoSGL/sections/img/dikw_pyramid.svg" height="300"/>

Attribuée à [Russell Ackoff](http://en.wikipedia.org/wiki/Russell_L._Ackoff) en 1989, elle signfie que :


- Les **.red[données]** sont la matière "brute" de l'information conçues plutôt pour des machines.
- **.red[L'information]** pourrait être définie comme des données qui ont été interprétées pour dégager du sens pour des humains.
- En donnant du sens à de l'information, on obtient de la **.red[connaissance]**
- En donnant du sens à la connaissance on obtient de la **.red[sagesse]**.


_NB : le haut de la pyramide, est parfois remplacé par "compétence"_

---

### Les données, c'est aussi tout ce qui circule dans un ordinateur

Les données ne sont pas seulement le fondement du savoir, elles sont aussi la base de l'informatique. Tout ce qui circule dans un ordinateur, ce sont des données.

.pull-left[![](https://datactivist.coop/SPoSGL/sections/img/volume.png)]
.pull-right[
Pensez à votre abonnement téléphonique, chaque mois, vous payez pour consommer un certain volume de données quantifié en octet ou en bit. 

Le volume des données créées et traitées ne cesse de croitre en même temps que les capacités de calcul des ordinateurs. 
]

---

## 1.b  L'industrialisation de la production des données

---

### La tablette mésopotanienne : inscrire une réalité complexe
Vers 3200 av. J.-C., en Mésopotamie, la civilisation sumérienne a inventé l’écriture d'abord pour mémoriser des comptes (difficile de recenser des têtes de bétail ou des sacs de grains oralement).
.pull-left[
![](http://www.ladressemuseedelaposte.fr/IMG/arton1311-resp500-2.jpg)

.pull-right[

> "La compatibilité a été l'une des premières *success story* de l'écriture ; les premières tablettes comprennent souvent des listes de compte."
]
.footnote[Source : Abiteboul & Peugeot (2017). *Terra Data : qu'allons nous faire des données numériques ?*, Paris : Le Pommier.]
---

### La carte perforée (1884) : le début de la massification des données

Apparue au départ dans les métiers à tisser, les carte perforées contiennent des informations représentées par la présence ou l'absence de trous dans une position donnée.

.pull-left[
.middle[![](https://upload.wikimedia.org/wikipedia/commons/f/f2/Hollerith_punched_card.jpg)]
]
.pull-right[
Elles sont les premières mémoires de masse utilisées dans l'informatique au XIXe siècle.

En 1884, Herman Hollerith a déposé un brevet pour une machine à cartes perforées destinée à accélérer la production de statistiques pour les gouvernements. Deux ans plus tard, il crée IBM le géant de l'informatique.  
]

---

### Les bases de données relationnelles (1970)

Les bases de données relationnelles facilitent grandement le traitement des données puisqu'elles pparaissent à travers une interface utilisateur : « il faut protéger les futurs usagers de grandes banques de données d’avoir à connaitre comment les données sont organisées dans la machine » (Codd 1970). 

.pull-left[
![](https://www.ntirety.com/wp-content/uploads/2017/05/database-schema-1895779_1280-1080x675.png)]

.pull-right[

D’un point de vue physique, les données sont inscrites dans des tables et reliées entre elles par un schéma et des identifiants uniques. Cela permet de traiter de plus grands volumes, de développer des données plus complexes et d'éviter des erreurs de saisie.
]

---
### Le tableur (1979) : *data to the people*

En 1979, Dan Bricklin, un ancien analyste financier exaspéré par les techniques de calcul encore manuelles, a imaginé une technique de calcul visible (« *Visible Calculator* »). 

Son logiciel "Visicalc", .red[démocratise la production des données] en proposant le système de la feuille de calcul sur laquelle les données peuvent être directement manipulées : 

> "La facilité d’utilisation de Visicalc provenait du fait que l’utilisateur n’avait pas besoin de connaitre de langage de programmation. Sur cet aspect, Visicalc était **l’équivalent du traitement de texte** dans lequel un utilisateur arrange directement l’impression de la page, à l’opposé des systèmes d’écriture où l’utilisateur devait inscrire un ensemble d’inscriptions pour mettre en page le texte." ([Campbell-Kelly, 2007](http://www.oxfordscholarship.com/view/10.1093/acprof:oso/9780198508410.001.0001/acprof-9780198508410))
---

### Le tableur (1979) : *data to the people*

.center[ Dan Bricklin et Bob Frankston ont inventé le tableur, le premier logiciel de calcul de masse. Découvrez en 5 minutes leur invention : 

<iframe width="560" height="315" src="https://www.youtube.com/embed/2a5ex5QlocQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
]

---

### Exercice : Identifiez autour de vous 3 appareils qui collectent des données 


---

# 2 - Les grands principes de l’ouverture des données


---

### [.red[Les multiples facettes de l'open data ]](https://books.openedition.org/cdf/5005?lang=fr) : la transparence

Aller au-delà du droit d'accès et de la rédition des comptes (_accountability_) : réduire les asymétries d'information en accédant au matériau brut de l'information et du savoir


---

### [.red[Les multiples facettes de l'open data :]](https://books.openedition.org/cdf/5005?lang=fr) la libre circulation de l’information

Dans la lignée de la cybernétique et du logiciel libre, la circulation des données comme valeur essentielle

.reduite.center[![](https://farm7.static.flickr.com/6197/6073305958_19c2bbef40_o.jpg)]

---

###  [.red[Les multiples facettes de l'open data :]](https://books.openedition.org/cdf/5005?lang=fr) la demande de données brutes

Dans la lignée des premières initatives de partage de données scientifiques en génétique ou en astronomie, obtenir les données sous leur forme pré-interprétative pour refaire les calculs

.reduite.center[![](http://images.wisegeek.com/physical-data.jpg)]

---

### [.red[Les multiples facettes de l'open data :]](https://books.openedition.org/cdf/5005?lang=fr) l'industrie de la donnée
Le nouveau pétrole et les promesses démesurées de croissance

.reduite[.center[![](https://images.pexels.com/photos/70362/oil-monahans-texas-sunset-70362.jpeg?cs=srgb&dl=dawn-drill-evening-70362.jpg&fm=jpg)]]

---

### [.red[Les multiples facettes de l'open data :]](https://books.openedition.org/cdf/5005?lang=fr) la modernisation des administrations

Désiloter l'administration et ouvrir l'innovation, collaborer avec la société civile dans l'élaboration et la mise en œuvre des politiques publiques

.reduite[.center[![](http://www.participation-et-democratie.fr/sites/default/files/democratie_ouverte_0.png)]]

---
### 2.a  L'Open data en quelques dates

---
### 2005 : [L'Open Definition](https://opendefinition.org/)

### Une définition juridique des droits de l'usager d'un savoir ouvert
![](https://datactivist.coop/occitanie/img/opendef.png)]


---
### 2007 : [la rencontre de Sebastopol aux États-Unis](https://opengovdata.org/)


**Quoi ?** Une rencontre de l'Open Governement Group à Sebastopol (Californie), siège des éditions O'Reilly

**Pourquoi ?** : Influencer le futur président des Etats Unis pour faire avancer l'open data

**Comment ?** En adoptant une déclaration définissant les grands principes de l'Open Government Data 


![](https://datactivist.coop/dataliteracy/img/photofamille.jpg)

---

### 2.b Principes de l'open data définis pendant la conférence de Sébastopol

---


#### 1. Des données complètes

> **Toutes les données publiques doivent être rendues disponibles dans les limites légales liées à la vie privée ou la sécurité**
---


#### 2. Des données primaires

> **Les données ouvertes sont telles que collectées à la source, non-agrégées avec le plus haut niveau de granularité**

---

#### 3. Des données fraiches (*timely*)

> **Les données doivent être disponibles dès qu'elles sont produites**

---

#### 4. Des données accessibles 

> **Les données doivent être utilisables par le plus grand nombre d’usagers potentiels**

---

#### 5. Des données exploitables par les machines 
> **Les données peuvent être traitées automatiquement par les machines** 

---

#### 6. Des données non discriminatoires 
> **Elles peuvent être utilisées par tous sans réclamer un enregistrement préalable**
> 
---

#### 7. Des données dans un format ouvert

> **Ce format ne doit pas être la propriété d'une organisation en particulier (.xls) et doit être gouverné par ses usagers**

---

#### 8. Des données dans une licence ouverte

> **Idéalement dans le domaine public sinon dans une licence conforme à l'[Open Definition](www.opendefinition.org) : Licence Ouverte (CC-BY) ou ODBL (CC-BY-SA)** 

---
### 2008 : Tim Berners-Lee ["Raw data now"](https://www.ted.com/talks/tim_berners_lee_on_the_next_web?language=fr)
#### La demande de données brutes sous les projecteurs

![](https://datactivist.coop/aaf/img/ted.png)

---
### 2010 : [le modèle en 5 étoiles de Tim Berners-Lee](https://5stardata.info/fr/)

![](https://datactivist.coop/aaf/img/5star.png)

---
### Des principes techniques sans portée politique

>"Il peut être vrai en un sens qu'un régime devient plus ouvert chaque fois qu'il fournit des données ouvertes supplémentaires, même pour les sujets banals et apolitiques, mais il est facile d'imaginer qu'un régime fermé pourrait divulguer de grandes quantités de données conformes à ces huit exigences [de Sébastopol] **sans pour autant accroître sa responsabilité réelle en tant que gouvernement **. 
> Une diffusion électronique des déclarations de propagande faites par les dirigeants politiques de la Corée du Nord, par exemple, pourrait satisfaire à ces huit exigences et ne pas promouvoir une transparence ou une responsabilité supplémentaires de la part d'un régime notoirement fermé et opaque."
>Yu & Robinson (2012) « [The New Ambiguity of Open Government](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2012489) » 
---
## 2.c Vers une portée et des soutiens politiques 

---
### 2011 : [la déclaration pour un gouvernement ouvert](https://www.opengovpartnership.org/d-claration-commune-pour-un-gouvernement-ouvert)

La formation du Partenariat pour un Gouvernement Ouvert a permis d'exposer plusieurs principes fondateurs

![](https://datactivist.coop/aaf/img/declaration.png)
---
### [Le fonctionnement du PGO](http://www.opengovpartnership.org/sites/default/files/OGP_Booklet_20160911_FR.pdf)
.center[.reduite[![](img/opengov.png)]]
---
### Depuis 2010 : l'ère des classements
[![](img/odb.png)](https://opendatabarometer.org/)
---
### Depuis 2010 : l'ère des classements

**[Le baromètre international de l'Open Data](https://index.okfn.org/place/)** est un classement de référence, tout comme l'Open Data Index de l'Open Knowledge Foundation

![baromètre international de l'Open Data](https://datactivist.coop/aaf/img/odb.png)

![Open Data Index de l'Open Knowledge Foundation](https://datactivist.coop/aaf/img/godi.png)
---
### 2013 : la [charte du G8 sur l'open data](https://www.modernisation.gouv.fr/sites/default/files/fichiers-attaches/charte-g8-ouverture-donnees-publiques-fr.pdf)

---
### 2015 : la [charte internationale de l'open data](https://opendatacharter.net/)

![](https://datactivist.coop/aaf/img/odcharter.png)


---

# 3. Éléments du cadre juridique de l'open data

---

### Un appareil législatif étoffé

1. **Loi CADA**, dite Loi Informatique et Libertés du 6 janvier 1978.
1. **Création de la CADA** (Commission d'Accès aux Documents Administratifs)
1. **Création de la CNIL** (Commission Nationale Informatique et Libertés)
1. **Loi pour une République Numérique** (loi Lemaire) du 7 octobre 2016.

---

### 1978 : La loi CADA, vers le "droit de savoir"
* Le fondement : la .red[Déclaration des Droits de l'Homme et du Citoyen de 1789] dans son article 15, "la Société a le droit de demander compte à tout Agent public de son administration." 

* Le droit d'accès des citoyens à l'information publique émerge en **1978 avec la loi dite CADA** du nom de la Commission d'Accès aux Documents Administratifs. 

* La France était le .red[3e pays au monde] après la Suède en 1766 et les Etats-Unis en 1966 avec le Freedom of Information Act (FOIA) en 1966  à accorder un "droit de savoir" avec pour but d'améliorer les relations entre le public et l'administration.

.footnote[Il faudrait maintenant désigner la loi comme le Code des relations entre le public et l'administration (CRPA) qui, dans son [livre 3](https://www.legifrance.gouv.fr/affichCode.do;jsessionid=BDF8EC0BD562E214CCD9A5ADD435D690.tplgfr42s_1?idSectionTA=LEGISCTA000031367685&cidTexte=LEGITEXT000031366350&dateTexte=20190429), codifie le droit d'accès et de réutilisation mais il est encore moins connu que la loi CADA…]

---
### La loi CADA : un point noir dans la transparence de la vie publique

Même si la France est le 3e pays à avoir adopté un droit d'accès, la loi CADA n'est pas un outil fort de la transparence de la vie publique. Ses principaux défauts : l'absence de sanctions et une procédure longue qui décourage les demandeurs et favorise le contournement par les administrations. 
[![](./img/europam.png)](http://europam.eu/?module=country-profile&country=France)

---

## 3.a Que dit la Loi pour une république numérique ?

---
### La loi est promulguée le 7 oct. 2016

Elle a pour objectifs de : 
* Encourager l’innovation et l’économie numérique
* Promouvoir une société numérique protectrice 
* Garantir l’accès de tous au numérique (Haut débit..)

Source : 
http://www.vie-publique.fr/actualite/dossier/loi-internet/republique-numerique-que-change-loi-du-7-octobre-2016.html

---
### Premier principe : l'ouverture des données par défaut

→ Les administrations  devront publier en ligne dans un standard ouvert leurs principaux documents, y compris leurs codes sources, ainsi que leurs bases de données qui présentent un intérêt économique, social, sanitaire ou environnemental. 

→ Cette obligation concerne les administrations d’État, les collectivités locales de plus de 3 500 habitants, les établissements publics et les organismes privés chargés d’un service public 

--- 
### Le périmètre de l'open data par défaut 

L'ouverture concerne un .red[**périmètre très large**] : 
* les documents communiqués suite à des demandes CADA
* les "bases de données"
* les données "dont la publication présente un intérêt économique, social, sanitaire ou environnemental".
Rares sont donc les données publiques qui ne sont pas concernées par cette obligation d'ouverture. 

---

### La définition des données

Le guide CADA-CNIL rappelle la **définition des "bases de données"**

> On entend par base de données un recueil d'œuvres, de données ou d'autres éléments indépendants, disposés de manière systématique ou méthodique, et individuellement accessibles par des moyens électroniques ou par tout autre moyen (art L112-3 du code de la propriété intellectuelle)

> En d’autres termes il s’agit d’un ensemble de données organisé en vue de son utilisation par des programmes correspondant à des applications distinctes et de manière à faciliter l'évolution indépendante des données et des programmes (en anglais : data base)

Le document donne également une **définition de ce qu'est une "donnée"** :

> Une donnée correspond à la représentation d'une information sous une forme conventionnelle destinée à faciliter son traitement (en anglais : data).

---

### Deuxième principe : création d’un service public de la donnée

→ La loi souhaite faciliter la réutilisation des principales bases de données de l’État par les acteurs privés ou publics (entreprises, associations, chercheurs, etc.), en leur garantissant un niveau élevé de qualité de service.

→ La loi propose de mettre à disposition comme “service public” les grandes bases de données de référence de l’État , comme par exemple le répertoire SIRENE des entreprises ou le cadastre. 


---

### Les 9 jeux de données  du Service Public de la Donnée

* Le répertoire des entreprises et des établissements (base Sirene)
* Le répertoire national des associations (RNA),
* Le plan cadastral informatisé (« Cadastre »),
* Le registre parcellaire graphique (RPG)
* Le référentiel à grande échelle (RGE),
* La base adresse nationale (BAN),
* Le répertoire opérationnel des métiers et des emplois (ROME),
* Le référentiel de l’organisation administrative de l’Etat,
* Le code officiel géographique (COG).

Source : https://www.data.gouv.fr/en/reference

---

### Open data = Licence ouverte + Format ouvert

* **Les données sont publiées dans un format ouvert** : Ce format ne doit pas être la propriété d'une organisation en particulier comme Excel ou PDF (Microsoft) 
* **Les données sont publiées dans une licence ouverte** : Idéalement dans le domaine public sinon dans une licence conforme à l'Open Definition : Licence Ouverte (CC-BY) ou ODBL (CC-BY-SA)
* **Les données sont exploitables par les machines** : Les données peuvent être traitées automatiquement par les machines
* **Les données sont non discriminatoires** : Elles peuvent être utilisées par tous sans réclamer un enregistrement préalable sur le site qui les publie
* **Des données primaires** : Les données ouvertes sont telles que collectées à la source, non-agrégées avec le plus haut niveau de granularité

Contre exemple : https://www.data.gouv.fr/fr/datasets/comptage-voyageur-sur-rer/ 


---
### Loi pour une République numérique : une limitation des licences

La loi **limite par décret les licences** qui peuvent être utilisées par les administrations. Le [décret du 27 avril 2017](https://www.legifrance.gouv.fr/eli/decret/2017/4/27/2017-638/jo/texte) autorise deux licences : 

* la Licence Ouverte d'Etalab 

* la licence ODbL (Open Database License).

Ces deux licences offrent **un choix aux administrations** : la licence ouverte étant plus permissive que la licence ODBL qui a été conçue dans une logique de "pot commun" permettant de garantir que les données resteront ouvertes après leur réutilisation.

Utiliser une autre licence impose une **homologation** auprès de la DINSIC avec un exposé des motifs ayant conduit à sortir de la liste fixée dans le décret et une consultation des usagers affectés par la licence proposée. L'homologation doit être faite pour chaque jeu de données même si la licence reste la même.

---

### Zoom sur les licences

![image alt](https://datactivist.coop/aaf/img/licences.png)

---
### Le cas des données personnelles

La prohibition de la communication à des tiers ne porte pas sur les données personnelles en général, mais .red[**sur les données à caractère personnel relevant de la vie privée**] des personnes concernées (âge, coordonnées personnelles, situation patrimoniale et financière, sympathies politiques, les croyances religieuses…)

La mise en ligne de données à caractère personnel sans anonymisation n'est permise que dans .red[**trois cas**] :
1. une disposition législative contraire le prévoit (exemple : [Transparence Santé](https://www.data.gouv.fr/fr/datasets/transparence-sante-1/))
2. si les personnes intéressées ont donné leur accord (consentement au sens de l’article 4 du RGPD)
3. les documents relevant de [l’article D312-3-1 du CRPA](https://www.legifrance.gouv.fr/affichTexte.do;jsessionid=51E99AF738C12521572D6A7F6C8C03E8.tplgfr23s_1?cidTexte=JORFTEXT000037797147&dateTexte=&oldAction=rechJO&categorieLien=id&idJO=JORFCONT000037796937)


Hors de ces cas, il faut .red[**[anonymiser les données](https://github.com/SGMAP-AGD/anonymisation/wiki/Guide-de-l'anonymisation)**] : elles ne doivent plus se référer à une personne réelle (exit les noms, identifiants…) et ne doivent plus être spécifiques à un individu mais communes à un ensemble de personnes. L’indexation de ces données par un moteur de recherche externe est proscrite.

---

# 4 État-Plateforme et Open Gov

---

## Gouvernement Ouvert et Open Data

Rappel : l'open data n'est pas qu'une pratique d'ouverture et de publication de données, c'est également un **mouvement et une philosophie relatif à un meilleur accès à  l'information publique**.

Plus largement, l'open data s'inscrit dans le mouvement du **gouvernement ouvert**, aussi appelé **OpenGov** en anglais. Celui-ci promeut :

+ La plus grande .red[**transparence de l'information**] (notamment à travers l'open data), pour permettre entre autre le suivi des politiques publiques

+ Une plus forte .red[**participation des citoyens**] dans l'élaboration des politiques publiques : à la fois en étant davantage consulté mais aussi en étant acteur dans la construction de celles-ci

+ Une plus forte .red[**collaboration**] au sein des administrations publiques (casser les silos) et à l'extérieur (travailler avec des acteurs associatifs, privés) pour concevoir et mettre en oeuvre les politiques publiques

---
## Gouvernement Ouvert

Ce schéma, réalisé par l'association [DémocratieOuverte](https://democratieouverte.org/), résume bien les différents enjeux autour du gouvernement ouvert :

.center[<img src="https://datactivist.coop/SPoSGL/sections/img/gouvouvert.png" height="400"/>] 


---
## OGP/PGO : Partenariat pour un Gouvernement Ouvert

.center[<img src="https://datactivist.coop/SPoSGL/sections/img/ogp.png" height="380"/>]

En septembre 2011, un partenariat multilatéral s'est créé afin de promouvoir le gouvernement ouvert et traduire ses valeurs en des actions gouvernementales concrètes : **le partenariat pour un gouvernement ouvert** (PGO), aussi appelé **Open Government Partnership** (OGP)

Initialement fondé par 8 pays (Brésil, Indonésie, Mexique, Norvège, Philippines, Afrique du Sud, Royaume-Uni et États-Unis), le PGO en compte désormais 70, dont la France

---
## OGP/PGO : Partenariat pour un Gouvernement Ouvert

Pour rejoindre le partenariat, il faut avoir été "coopté" par des acteurs de la société civile (ex: association type Amnesty International) qui viennent témoigner de la bonne volonté du gouvernement.

Une fois rejoint, les pays doivent rédiger, en concertation avec la société civile, un .red[**plan d'action**] de deux ans dans lequel plusieurs engagements sont inscrits. Ces engagements publics doivent avoir trait à la transparence de l'information, la participation citoyenne et la redevabilité (accountability) de l'action publique.
Par exemple : 
+ Développer un budget participatif représentant X % du budget d'une CT
+ Entamer une démarche open data qui permettent de libérer des données
+ Concerter les citoyens dans le cadre d'un projet de loi...

Ces engagements font ensuite **l'objet de vérifications et d'audit de la part de chercheurs indépendants** (IRM) tant sur la manière dont ils ont été rédigés/conçus que sur leur efficacité et niveau d'avancement réel

---
## OGP/PGO : Partenariat pour un Gouvernement Ouvert

.center[<img src="https://datactivist.coop/SPoSGL/sections/img/pan_france.png" height="200"/>] 

.footnote[[Lire le Plan d'action national pour la France 2018-2020](https://www.etalab.gouv.fr/wp-content/uploads/2018/04/PlanOGP-FR-2018-2020-VF-FR.pdf)]

---

### Une politique Open Data pilotée au niveau national

####  La mission Etalab

**Etalab** coordonne la politique d’ouverture et de partage des données publiques (open data)

**Etalab** coordonne les actions des administrations de l’Etat et leur apporte son appui pour faciliter la diffusion et la réutilisation de leurs informations publiques.

**Etalab** développe et anime la plateforme d’open data data.gouv.fr destinée à rassembler et à mettre à disposition librement l’ensemble des informations publiques de l’Etat, de ses établissements publics et, si elles le souhaitent, des collectivités territoriales et des personnes de droit public ou de droit privé chargées d’une mission de service public.

**Etalab** coordonne le Service Public de la Donnée.

source : https://www.etalab.gouv.fr/

---
## Data.gouv.fr ?

Data.gouv est la plateforme nationale ouverte des données publiques françaises.
Elle a été conçue et inaugurée en 2011, par la mission Etalab, puis refondue en 2013.

.center[<img src="https://datactivist.coop/SPoSGL/sections/img/datagouvfr.png" height="250"/>] 

On y trouve des milliers de jeux de données, provenant principalement de producteurs publics (Ministère de l'intérieur, Agence française de développement, Insee, Ville de Paris, Région Bretagne, CNIL...) mais aussi de producteurs tiers (OpenStreetMap, OpenFoodFacts...)

---
## Au-delà de data.gouv.fr

Data.gouv.fr est la plateforme **nationale** d'open data mais ce n'est pas la seule plateforme publique qui met à disposition des données ouvertes. Il existe :

+ Des plateformes open data gérées par les **collectivités territoriales**. Par exemple, [Paris Data](https://opendata.paris.fr/explore/?sort=modified), [la Région Occitanie](https://data.laregion.fr/pages/accueil/), [l'agglomération de Saint-Malo](https://data.stmalo-agglomeration.fr/page/accueil/)...

+ Des plateformes open data gérées par des **ministères**. Exemple : [data.education.gouv.fr](https://data.education.gouv.fr/pages/accueil/)

+ Des plateformes open data gérées par des **entreprises**. Exemple [DataNova](https://datanova.laposte.fr/page/accueil/) (La Poste)

+ Des jeux de données directement publiés sur le site des producteurs de données, sans plateforme dédiée. Exemple : Insee

---
### Des politiques d'open data "de l'offre"

.pull-left[
### En théorie

#### Toutes les données sont ouvertes sous leur forme brute dès leur production

]
.pull-right[


### En pratique

#### L’administration choisit quelles données ouvrir, comment les ouvrir, quand et ce qu’elles contiennent

]

---
### La réutilisation : un parcours fait de frictions et de déceptions
.pull-left[
[![](img/users.png)](https://thereboot.github.io/moti-personas/)
]
.pull-right[
####  Des données difficiles à trouver, pas ouvertes partout

####  Granularité temporelle et spatiale souvent trop faible

####  Des données souvent inutilisables : manque de documentation

####  Des données pas mises à jour

####  Des portails qui ciblent les développeurs

]

---
### Le problème de la qualité des données

> **Les données des gouvernements sont souvent incomplètes, pas actualisées, de mauvaise qualité et fragmentaires.** 

> Dans la plupart des cas, les catalogues ou portails de données ouvertes sont alimentés manuellement, conséquence d’une approche informelle de la gestion des données. 

> De plus, les procédures, les calendriers et les responsabilités des institutions publiques chargées de leur gestion manquent souvent de clarté. Ainsi, de manière générale, la gestion et la publication des données ouvertes sont fragiles et sujettes à des erreurs multiples.

.footnote[Source : 
[Rapport mondial du 4e Open Data Barometer](https://opendatabarometer.org/4thedition/report/?lang=fr)
]
---
### Des données bien cachées
.pull-left[
![](https://index.okfn.org/images/Datagapsclean.jpg)
]
.pull-right[
"La découvrabilité des données est un défi majeur. Nous avons des portails et des registres de données, mais les organismes gouvernementaux qui relèvent d'un seul gouvernement national publient toujours les données de différentes façons et à différents endroits (...).

**La découvrabilité des données est une condition préalable pour que les données ouvertes réalisent leur potentiel et, actuellement, la plupart des données sont très difficiles à trouver**."]


.footnote[https://index.okfn.org/insights/]

---
### Un exemple de données introuvables

Ce fichier contient tous les signes officiels de la qualité et de l'origine (SIQO) : les AOC et AOP, IGP, Label rouge, spécialité traditionnelle garantie, Agriculture biologique… Très utile mais qui peut le trouver sur data.gouv.fr ?
[![](./img/siqo.png)](https://www.data.gouv.fr/fr/datasets/siqo-publies/)

---
### Un autre exemple de données vraiment introuvables 

Ce jeu de données contient plus de 6000 marchés publics attribués par l'Etat. Mais, malgré mon [signalement](https://www.data.gouv.fr/fr/datasets/aife-de-44785462100045/#discussion-5c5d2857634f41019657c80d-0), tout est fait pour le rendre introuvable !

[.reduite[![](./img/wtfopendata.png)]](https://www.data.gouv.fr/fr/datasets/aife-de-33592022900036-23/)
---

### Le développement de l'open data en France

.reduite.center[![](./img/obsod.png)](http://slides.com/loichay/resultats-odt-oct18#/)

---

### Le développement de l'open data en France

.reduite.center[
[![](./img/carto_obs.png)](https://umap.openstreetmap.fr/fr/map/observatoire-open-data-des-territoires_239529#6/45.806/5.603)
]

---

### Une multitude de portails territoriaux

[![](./img/portailslocaux.gif)](https://airtable.com/shrmZOh5If14Q1PVN/tblwklJPsyayeH5lX?blocks=hide)

---
### Une multitude de portails nationaux

[![](./img/portailsnat.gif)](https://airtable.com/shr3IYfHZW1cVTS3s/tblVtTOudK5Ygpsmj?blocks=hide)


---
### Exemple de données ouvertes : la [base SIRENE](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)

.reduite.center[![](img/sirene.png)]
---
### La base SIRENE : exemple de cas d'utilisation

.reduite[.center[![](img/ruesoif.png)]]
---
### Exemple de données ouvertes : la [base adresse nationale](https://www.data.gouv.fr/fr/datasets/base-adresse-nationale/)
.reduite[.center[![](img/ban.png)]]

---
### Exemple de données ouvertes : les [accidents de la route](https://www.data.gouv.fr/fr/datasets/base-de-donnees-accidents-corporels-de-la-circulation/)
.reduite.center[![](img/accidents.png)]
---
##Les accidents de la route
.reduite.center[![](img/trajetleplussur.png)]
.footnote[Plus d'accidents sur l'A8 mais surtout plus de véhicules…]
---
### Les accidents de la route
.reduite.center[![](img/marsactu.png)]
.footnote[[Carte par Joël Gombin dans Marsactu](https://joelgombin.github.io/marsactu_accidents/chronique.html)]
---
### Exemple de données ouvertes : les [inspections des restaurants](https://www.data.gouv.fr/fr/datasets/resultats-des-controles-officiels-sanitaires-dispositif-dinformation-alimconfiance/)
.reduite.center[![](img/aliminfos.png)]
.footnote[[Résultats des contrôles officiels sanitaires : dispositif d'information « Alim’confiance »](https://www.data.gouv.fr/fr/datasets/resultats-des-controles-officiels-sanitaires-dispositif-dinformation-alimconfiance/)]
---
### Les inspections des restaurants
.reduite[.center[![](img/resto.png)]]
.footnote[[155 établissements dont l'hygiène doit être corrigée de manière urgente ](https://dgal.opendatasoft.com/explore/dataset/export_alimconfiance/table/?disjunctive.filtre&disjunctive.app_libelle_activite_etablissement&disjunctive.ods_type_activite&refine.synthese_eval_sanit=A+corriger+de+mani%C3%A8re+urgente)]
---
### Exemple de données ouvertes : le [répertoire national des élus](https://www.data.gouv.fr/fr/datasets/donnees-du-repertoire-national-des-elus/)

.reduite.center[
![](./img/repelus.png)
]

---
### Exemple de données ouvertes : les [valeurs foncières](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/#_)

![](./img/dvf.png)
---
### Les valeurs foncières

.reduite.center[
[![](./img/meilleursagents.png)](https://www.meilleursagents.com/prix-immobilier/dvf/aix-en-provence-13100/avenue-saint-jerome-1108044769/)
]

---
class: inverse, center, middle

# Le  cycle de l'ouverture des données

---
### Open Data Pipeline : les principales étapes de l'ouverture

.reduite.center[
![](./img/logigramme.png)
]

---
### La circulation des données provoque des frictions


>Chaque mouvement de données à travers une interface a un coût en temps, en énergie et en attention humaine. Chaque interface entre les groupes et les organisations, ainsi qu'entre les machines, représente un point de résistance où les données peuvent être brouillées, mal interprétées ou perdues. 
>Dans les systèmes sociaux, la friction des données consomme de l'énergie et produit de la turbulence et de la chaleur - c'est-à-dire des conflits, des désaccords et des processus indisciplinés et inexacts.

Edwards, P. N. et al. (2011) [‘Science friction: Data, metadata, and collaboration’](https://journals.sagepub.com/doi/abs/10.1177/0306312711413314), _Social Studies of Science_, 41(5)

---
### Identifier

.pull-left[
![](./img/identifier.png)
]

.pull-right[
* Rencontrer les agents

* Etudier les données ouvertes par d'autres collectivités

* Cartographier les données

* Documenter les données

]

---
### L’inventaire : un processus au long cours

.pull-left[
[![](./img/iden_etalab.png)](https://www.data.gouv.fr/fr/datasets/recensement-indicatif-des-donnees-publiques-issues-des-services-publics-de-letat/)
]
.pull-right[
* L’utopie de l’inventaire exhaustif


* Une démarche progressive et exploratoire


* Question : comment qualifier les données ?


* A lier aux processus de plan d’occupation des sols des DSI

]
---
### Les tableaux de gestion des archivistes comme support à l'identification 

![](./img/tableaugestion.png)

---

### S'appuyer sur le recensement pour connaitre données ouvrables

[![](./img/recen.gif)](https://medium.com/datactivist/qui-a-ouvert-quoi-le-recensement-des-donn%C3%A9es-des-villes-est-maintenant-ouvert-b7f697135c1f)

---
### Valider

.pull-left[
![](./img/valider.png)
]

.pull-right[
* Evaluer les jeux de données

* Prioriser l’ouverture 

* Valider l’ouverture par la hiérarchie

]

---
### Quelques “bonnes raisons organisationnelles” de ne pas ouvrir des données

* Des données encastrées dans les systèmes d’information : explorer les bases de données, reconstruire les schémas et extraire les données


* Des données qui peuvent servir à des usagers malveillants : prévoir les risques et les dangers de l’ouverture


* Des données qui n’ont pas été pensées pour l’ouverture : améliorer leur qualité et leur intelligibilité 


* Des données trop “sensibles” pour être ouvertes : la transparence, un mandat à obtenir 

---
### Éditer

.pull-left[
![](./img/editer.png)
]

.pull-right[
_data editing_: les opérations par lesquelles les statisticiens traitent et transforment les données issues des sources administratives (Desrosières 2005) 

* Anonymiser des données 

* Enlever la sensibilité de données qui ne pouvaient pas être publiées

* Rendre intelligible les acronymes 

* Améliorer la qualité des données

]

---
### Le sprint qualité des données de la FING

Petit exercice : en groupe, sélectionnez un jeu de données et essayer d'appliquer 5 points de contrôle 
[![](./img/sprint.png)](https://infolabs.io/sprint-qualite)

---
### [Dataproofer](http://dataproofer.org/) : un outil de contrôle automatique de la qualité

![](./img/dataproofer.png)
---
### [WTFCSV](https://databasic.io/en/wtfcsv/) pour prévisualiser et contrôler un jeu de données

![](./img/wtfcsv.png)
---
### Standardiser

.pull-left[
![](./img/standardiser.png)
]

.pull-right[
* Convertir les données dans un format ouvert (spécifications techniques publiques et sans restriction d'accès ni de mise en œuvre) et lisible par les machines

* Adopter des spécifications partagées : GTFS, DECP, IATI, OCDS, socle commun des données locales…

* Transformer les données

]

---
### Passage en CSV : bien plus que “enregistrer sous”

[![](./img/excel1.png)](http://fr.slideshare.net/christophelibertidf/bonnes-pratiquesexcel-cc27juin2013)

---
### Passage en CSV : bien plus que “enregistrer sous”

[![](./img/excel2.png)](http://fr.slideshare.net/christophelibertidf/bonnes-pratiquesexcel-cc27juin2013)
---
### Passage en CSV : bien plus que “enregistrer sous”

[![](./img/excel3.png)](http://fr.slideshare.net/christophelibertidf/bonnes-pratiquesexcel-cc27juin2013)

---
### Passage en CSV : bien plus que “enregistrer sous”

.reduite.center[![](./img/excel4.png)](http://fr.slideshare.net/christophelibertidf/bonnes-pratiquesexcel-cc27juin2013)

---
### Publier

.pull-left[
![](./img/publier.png)
]

.pull-right[
* Importer les données sur le portail

* Décrire les champs du fichier

* Documenter les métadonnées
]

---
### [Datasheet for Datasets](https://teamopendata.org/t/traduction-et-adaptation-du-modele-de-description-des-donnees-datasheet-for-datasets/1400) : un modèle de documentation des données

.reduite.center[
![](./img/datasheet.png)
]

---
### Mettre à jour

.pull-left[
![](./img/update.png)
]

.pull-right[

* Mettre à jour manuellement ou automatiser l’ouverture

* Conserver les données

* Prendre en compte les retours des usagers

]
---
### Les facteurs clés de succès


- obtenir un soutien au plus haut niveau

- configurer l’organisation pour l’ouverture 

- faciliter la découverte et l’utilisation des données 

- rester à l'écoute et interagir avec les usagers 

---
### Les bénéfices de l'open data

.pull-left[
![](./img/obs.png)
]
.pull-right[
En petits groupes, analysez les [données brutes](https://docs.google.com/spreadsheets/d/1pua5fDx8gtF3R9tce9wE7wmT0ksIFjscOO7DS723iHY/edit#gid=0) et syntéhtisez  : 
* La production d’effets bénéfiques ou d’externalités positives
* L'optimisation de la collecte et du partage des données
* L'amélioration de la qualité des données
* La production d'effets négatifs ou d'impacts contre-productifs
]
---
class: inverse, center, middle

# Merci !