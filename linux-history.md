---
title: Linux
author: Thibault Ayanides
theme: white
highlightTheme: stackoverflow-dark
width: 1920
revealOptions:
  transition: "none"
  slideNumber: true
  width: 1920
  height: 1080
---

<style type="text/css">
  .reveal p {
    text-align: left;
  }
  .reveal ul {
    display: block;
  }
  .reveal ol {
    display: block;
  }


.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
}

.column img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.left-corner {
  position: absolute;
  top: -50px;
  left: 0px;
  width: 150px;
}

.right-corner {
  position: absolute;
  top: -50px;
  right: 0px;
  width: 150px;
}

</style>

# Une histoire de l'informatique

## GNU/Linux, l'épopée d'une reconquête révolutionnaire

<br/>
<br/>
<br/>

Thibault Ayanides

---

<video width="1920" height="1080" controls="controls">
<source src="./video/suse_linus_said.mp4" type="video/mp4">
</video>
---

## GNU / Linux

<img src="img/history/tux.jpg" class="right-corner"/>
<img src="img/history/gnu.png" class="left-corner"/>

<div class="row">
  <div class="column">
    <img src="img/history/stallman.png" width=600px/>
    <ul>
      <li> <b>Liberté</b> parce que l'utilisateur est libre de faire ce qu'il veut avec le programme. </li>
      <li> <b>Égalité</b> parce que tous les utilisateurs disposent des mêmes libertés. </li>
      <li> <b>Fraternité</b> parce que chaque utilisateur a la possibilité de partager le programme avec le monde. </li>
    </ul>
    <em> Richard Stallman, créateur du projet GNU </em>
  </div>


  <div class="column">
    <img src="img/history/torvalds.png" width=600px/>
    <ul>
      <li> « Vraiment, je ne suis pas là pour détruire Microsoft. Ça sera juste un effet secondaire tout à fait involontaire. » </li>
      <li> « Software is like sex: it's better when it's free. » </li>
    </ul>
    <em>Linus Torvalds, créateur de Linux</em>
  </div>


</div>

---

## Les logiciels libres

---

## Sommaire

---

## Introduction : l'architecture des ordinateurs modernes

1. Introduction : quelques notions d’informatique
2. D’Unix à GNU/Linux : la naissance du libre
3. L’alliance entre GNU et Linux et l’essor des logiciels libres
4. Windows ou le côté obscur de la force

---

## Introduction : le code source

---

## Introduction : le système d'exploitation

---

## Introduction : Internet

---

## Au commencement était le source

- Entre 1969 et 1971, les 2 briques fondamentales de l’informatique moderne sont créés :
  - Le langage C
  - UNIX
- Les développeurs (hackers) travaillaient en collaboration et s’échangeaient leurs sources, dans le but de produire le meilleur code
- L’ingéniosité de la conception d’UNIX attire les grandes entreprises, IBM, HP, etc.

---

## L'histoire d'UNIX

---

## L'alliance rebelle

- En 1983, le développement d'UNIX se referme.
- En 1983, un hacker décide de s’opposer au verrouillage de l’informatique : c'est Richard Stallman.
- Il crée le concept de logiciel libre.
- Il commence à écrire les composants d’un nouvel UNIX, libre et qu’il nomme GNU à travers la licence GPL.

<!-- .slide: data-background="img/history/rebellion_logo.png" -->
---

## Le carburant du logiciel libre : la licence GPL

- Free software as in freedom.
- liberté d'exécuter le logiciel, pour n'importe quel usage ;
- liberté d'étudier le fonctionnement d'un programme et de l'adapter à ses besoins ;
- liberté de redistribuer des copies ;
- obligation de faire bénéficier à la communauté des versions modifiées. On appelle cela le copyleft

---

## Un nouvel espoir

- En 1991, un étudiant finlandais insatisfait des outils informatiques existants, entreprend d'écrire son propre système d'exploitation.
- Il s'appelle Linus Torvalds.
- En août 1991, il annonce sur Usenet qu'il écrit un système d'exploitation.

---

## La naissance du noyau (kernel)

- 1991 : il publie son travail sur internet
  - il appelle à lui la communauté des hackers
- 1992 : il place son travail sous licence GPL
- 1994 : le produit est utilisable en production
- 1994 : les interfaces graphiques arrivent
- 1998 : des grandes entreprises annoncent qu’elles proposent un support pour Linux

---

## Le noyau

---

## Les distriubtions Linux

---

## L'exubérance des distributions Linux

---

## Red Hat

- Créée en 1993
- Introduite en bourse en 1999
- En 2000, reçoit le titre du « système d'exploitation de l'année »
- Racheté par IBM en 2019
- Vends la distribution RHEL
- En 2001, sa distribution a été valorisée à :
  - 1 milliard de dollars,
  - 30 millions de lignes de code,
  - 8.000 hommes-années de travail

---

## Centos et Fedora

- Projets basés sur la distribution Redhat
- Fedora version communautaire
- CentOS est exactement construite avec le code source de Redhat

---

## Debian

- Association non commerciale lancée en 1993
- Contrat social passé avec la communauté du logiciel libre qui définit de grands principes auxquels les développeurs adhèrent
- 1000 bénévoles (surtout développeurs)
- Distribution gratuite

---

## Debian : l'évolution

---

## Debian : les versions

---

## Ubuntu

---

## Ubuntu : les versions

---

## Arch Linux (et Manjaro)

- Non destiné aux serveurs
- Distribution communautaire proposant un très large panel de paquets grâce aux AUR
- Prévu pour des utilisateurs avertis qui connaissent leur système

---

## La Wikipédia

- En 1999, Richard Stallman expose l'utilité d'une encyclopédie universelle et libre, et d'une ressource d'apprentissage
- En 2001, l'encyclopédie est créée
- Développement exponentiel
  - 45 millions d'articles, 299 langues (2017)
  - 5e site le plus fréquenté d'internet (2017)
- Inspire des projets similaires :
  - Wiktionnary, Wikisource, Wikiquote, Wikiversité

---

## Google

- Créé dans un garage en 1998
- 900.000 serveurs, tous sous GNU/Linux (en 2011)
- 6,5% du trafic internet mondial (2010)
- 72.100 employés (2017)
- publie Chrome OS et le navigateur Chrome
- soutient les développements de Linux et de multiples logiciels libres (+ hébergement)
- édite également des logiciels propriétaires
- CA de 80Md$, bénéfices de 19Md$ (2016)

---

## Android

- "pile logicielle" open source, basé sur Linux, clef en main, mais n'inclut pas la partie GNU
- Échange de code entre Linux et Android
- Racheté en 2005 par Google
- Pour smartphones, tablettes tactiles, etc..
- Équipe téléviseurs, radio-réveils, montres connectées, autoradios, voitures, ...
- Inclus, propose et vends des applications propriétaires
- Incorpore Google Play, magasin en ligne de Google (achat applications, logiciels, livres, films, musique)

---

## Les environnements graphiques

- Mate
- Gnome3
- KDE Trinity
- KDE 5
- Xfce
- Enlightenment
- Unity
- Cinnamon
- Etc.

---

## KDE5

---

## Trinity

---

## Gnome3

---

## Mate

---

## Xfce

---

## Enlightnement

---

## LXDE

---

## Cinammon

---

## Et pour ceux qui préfèrent quand même les interfaces tout moches

---

## Linux everywhere

---

## Linux everywhere

---

## Linux everywhere

### Un exemple : le studio WETA en Nouvelle Zélande

**Studio de postproduction s'occupant de la conception d'effets spéciaux**

- Data center de 3000 m²,
- 34 baies refroidis par water-cooling à une température de 25°,
- Architecture de 4000 serveurs HP Blades,
- 35 000 cœurs,
- 104 To de RAM,
- Une baie de 2 Po de stockage ,
- Un réseau à 10Go/s.

---

## Linux everywhere

---

## Linux everywhere

---

## Linux everywhere

---

## Linux everywhere

---

## Les acteurs du logiciel libre

| Associatifs            | Entreprises       |
| ---------------------- | ----------------- |
| Linus Torvalds         | Red Hat           |
| Debian                 | SuSe              |
| GNU                    | Intel             |
| FSF et Linux Fondation | Novell            |
| Ubuntu                 | IBM               |
| Slackware              | Texas Instruments |
| APRIL et AFUL          | Broadcom          |
|                        | Nokia             |
|                        | Samsung           |
|                        | Oracle            |
|                        | Google            |
|                        | Canonical         |
|                        | Microsoft         |

---

## Les grandes entreprises ou institutions qui utilisent massivement GNU/Linux

---

## L'économie du logiciel libre

- Pour le noyau Linux :
  - plus de 8000 développeurs
  - 800 sociétés différentes
  - 75 % du développement Linux est effectué par des développeurs payés par leur entreprise
- Pour les logiciels libres
  - Basé sur le service, le support, la vente de licences ou de fonctionnalités supplémentaires
  - Utilise parfois le financement participatif (dons, crowfunding, ...)

---

## Les gros logiciels libres

---

## Les serveurs Linux

- 92 % des machines instanciées sur le Cloud Amazon (AWS) sont des serveurs Linux (2015)
- Plus de 50 % du cloud Microsoft (Azure) tourne sur Linux
- En données relatives\* :
  - 68 % de serveurs sous UNIX, GNU/Linux ou BSD (dont environ 40% sous GNU/Linux)
  - 32 % de serveurs Windows.

---

## Les superordinateurs (2019)

| Rang | Rmax (Pflops\*) |    Nom     | Fabricant  |  Nb cœurs  |   Pays    | O.S.  |
| :--: | :-------------: | :--------: | :--------: | :--------: | :-------: | :---: |
|  1   |      148.6      |   Summit   |    IBM     | 2,414,592  |    USA    | Linux |
|  2   |      96.6       |   Sierra   | IBM/Nvidia | 1,572,480  |    USA    | Linux |
|  3   |       93        | TaihuLight |    NRPC    | 10,649,600 |   Chine   | Linux |
|  4   |       61        | Thianhe-2  |    NUDT    | 4,981,760  |   Chine   | Linux |
|  5   |       21        |  Fronteri  |    Dell    |  448,448   |    USA    | Linux |
|  6   |       20        | Piz Daint  |    Cray    |  387,872   |  Suisse   | Linux |
|  7   |       20        |  Trinity   |    Cray    |  979,072   |   Japon   | Linux |
|  8   |       19        |    ABCI    |  Fujitsu   |   391,68   |   Japon   | Linux |
|  9   |      19.5       |  SuperMUC  |   Lenovo   |  305,856   | Allemagne | Linux |
|  10  |       18        |   Lassen   | IBM/Nvidia |  288,288   |    USA    | Linux |

---

## Les 500 premiers superordinateurs (novembre 2016 et novembre 2017)

---

## Les superordinateurs

---

---

# Mais pourquoi Linux n'a-t-il pas percé sur le desktop ?

---

## Pourquoi GNU/Linux reste minoritaire sur le desktop ?

- La réputation geek de GNU/Linux
- L'ombre de Mac OS X
- Tous les PC sont vendus avec Windows préinstallé
- La domination de longue date du marché par Microsoft

---

# Pourquoi et comment Microsoft domine-t-il le marché ?

---

---

## Ballmer et l'Iphone

---

## L'écran bleu de la mort (blue screen of death)

---

## L'écran bleu de la mort (blue screen of death)

---

## L'interface et l'ergonomie

---

## La vie privée et les données personnelles

- Le premier à collaborer avec PRISM depuis 2007
- Windows 10 et son CLUF (Contrat de Licence Utilisateur Final)

---

---

## La sécurité

- Obligation d’utiliser un antivirus
- Délai de correction
- Failles vieilles comme Mathusalem
- Défaut de conception
- Introduction de nouvelles failles prétendant boucher d’autres

---

## Un système en retard

- La défragmentation
- Les redémarrages
- Boulimie en ressources matérielles
- Aspect multi-utilisateur défectueux

---

## Les mises à jour

---

## Mais alors comment Microsoft est-il devenu si riche et si puissant ?

---

## Le côté obscur de la Force

---

## Les biens immatériels

- Bien non tangible.
- Ne doit pas être confondu avec un service qui réclame du travail.
- Coût marginal quasi nul.
- Durée de vie illimitée, ne se dégrade pas.
- Comment Microsoft est devenu aussi riche ?

---

## Les dates clés

- 1981 : lancement de MS-DOS
- 1990 : lancement de Windows 3.0
- 1992 : lancement de Windows 3.1
- 1992 : lancement d’Office 3.0
- 1995 : lancement de Windows 95
- 1996 : lancement d’Internet Explorer 3.0
- 2001 : lancement de Windows XP
- 2001 : lancement de la Xbox
- 2011 : rachat de Skype
- 2014 : rachat de Nokia mobile OY et rachat de Mojang AB
- 2016 : rachat de LinkedIn
- 2018 : rachat de GitHub
- 2020 : rachat de Bethesda

---

## Les logiciels fermés

---

## De l'usage du Klingon comme arme de domination mondiale.doc

- Obsolescence programmée de Word :
- Augmentation du chiffre d’affaire
- Captivité des données et donc des utilisateurs
- Taxe monopoliste
- Conversion vers un format ouvert très difficile
- Laisser pirater Word dans les années 90 dans les universités

---

## Offensive sur la matière grise

---

## Affaires judiciaires

- Procès Anti-trust aux États-Unis
  - Accusation de pratiques monopolistes

---

## Affaires judiciaires

- Procès européen sur la concurrence
  - Procès Anti-trust suivant celui des États-Unis

---

## Aujourd'hui

---

# Pourquoi et comment adopter les logiciels libres ?

---

## Des exemples de migrations réussies sous GNU/Linux

En Europe, depuis 2002, beaucoup d’exemples de migration vers GNU/Linux ont lieu : dans l’éducation, dans la gendarmerie, et même à l’Assemblée !

---

## Équivalents logiciels libres/logiciels propriétaires

---

---

---

## Que faut-il retenir de tout ça ?

- Ce qu’est un logiciel libre et la différence avec un logiciel propriétaire
- La différence entre GNU et Linux
- La notion de distribution sous Linux et les principales (Redhat, Debian, Ubuntu)
- Où est utilisé Linux aujourd’hui ? (serveurs, superordinateurs, objets connectés, …)
- Comment sont financés les logiciels libres et Linux ?

---

## Pour finir ...

- Licence
  Copyleft J. Philippe, Thibault et Pierre Ayanides 2017
  Les images et documents rapportés sont la propriété de leurs ayants-droits respectifs. Le reste de cette présentation est diffusée sous licence Creative Comons BY-SA.

---

---

## Remerciements

- Je remercie tout d'abord les créateurs d'UNIX et du C, K. Thomson, D. Ritchie, sans qui tout cela n'aurait pas été possible,
- Je remercie R. Stallman et la FSF pour son combat pour la prédominance des logiciels libres,
- Je remercie évidemment Linus Torvalds pour son acharnement sur la création du noyau Linux,
- Je remercie Mark Shuttleworth pour sa fondation Canonical et sa distribution Ubuntu créée avec ses propres moyens et dont il ne tire quasiment aucun profit,
- Je remercie également la totalité des développeurs, contributeurs, entreprises et utilisateurs Linux pour leur participation à cette grande aventure qu'est GNU/Linux...

---

## Sources

### Liens internet

- https://web.archive.org/web/20081115035654/http://www.protegetonordi.com/rub_fiches/default.html
- http://linuxfr.org/news/microsoft-en-campagne-contre-le-piratage
- http://forum.framasoft.org/viewtopic.php?t=17902
- http://mrpogson.com/2014/04/14/growth-of-debian-gnulinux
- http://www.generation-nt.com/linux-noyau-contribution-microsoft-actualite-1563751.html + Gandy (first they laught, then they fight you, then you win)
- http://branchez-vous.com/2014/06/04/etes-vous-pret-imprimer-votre-propre-robot
- http://ascendances.files.wordpress.com/2011/10/timeline_debian_1993_20111.png
- http://img.clubic.com/00C3009205635868-c1-photo-ubuntu-phone.jpg Ubuntu touch
- http://royal.pingdom.com/2012/04/16/linux-kernel-development-numbers
- http://en.wikipedia.org/wiki/TOP500
- http://en.wikipedia.org/wiki/History_of_Linux
- http://www.journaldunet.com/solutions/expert/51207/l-ecrasante-domination-de-linux-dans-le-cloud---vers-90--de-part-de-marche.shtml
- http://www.silicon.fr/linux-deux-fois-plus-utilise-que-windows-82907.html

---

## Sources

### Liens internet

- http://www.tomshardware.com/news/linux-windows-microsoft-android-ios,20220.html
- http://www.silicon.fr/dossier-linux-monde-des-affaires-81984.html
- http://www.ginjfo.com/actualites/logiciels/linux/steam-linux-spectre-du-monopole-inquiete-20140526
- http://www.netmarketshare.com
- http://www.netmarketshare.com/report.aspx'qprid=11&qpaf=&qpcustom=Linux&qpcustomb=0&qpsp=2013&qpnp=1&qptimeframe=Y
- http://linuxgizmos.com/worlds-first-emotional-robot-runs-linux
- http://mashable.com/2011/09/17/happy-20th-birthday-linux
- http://www.tecmint.com/big-companies-and-devices-running-on-gnulinux
- http://mylinuxbook.com/awesome-devices-powered-by-linux
- http://www.extremetech.com/extreme/155392-international-space-station-switches-from-windows-to-linux-for-improved-reliability
- http://arstechnica.com/gadgets/2013/01/17000-linux-powered-rifle-brings-auto-aim-to-the-real-world
- http://168hours.wordpress.com/2008/08/10/10-coolest-devices-running-linux/
- http://linuxgizmos.com/linux-based-in-vehicle-infotainment-on-the-rise/

---

## Sources

### Liens internet

- http://www.linuxinsider.com/story/72867.html why toyota choose freedom
- http://fr.wikipedia.org/wiki/Fichier:Linux_kernel_map.png
- http://en.wikipedia.org/wiki/Mark_Shuttleworth
- http://www.theregister.co.uk/2014/06/09/torvalds_no_mandatory_coding_education/
- http://www.commentcamarche.net/forum/affich-2275151-les-avantages-de-linux
- http://fr.wikipedia.org/wiki/Bien_immat%C3%A9riel
- http://www.tomsguide.fr/article/windows-mac-guerre,2-1083-2.html
- http://fr.wikipedia.org/wiki/Enfermement_propri%C3%A9taire
- http://blogs.mediapart.fr/blog/jean-lucien-hardy/060214/bill-gates-requin-capitaliste-plutot-que-genie-informatique
- http://fr.wikipedia.org/wiki/DR-DOS
- http://en.wikipedia.org/wiki/Linux_adoption
- https://web.archive.org/web/20081115035654/http://www.protegetonordi.com/rub_fiches/default.html

---

## Sources

### Liens internet

- http://linuxfr.org/news/microsoft-en-campagne-contre-le-piratage
- http://forum.framasoft.org/viewtopic.php?t=17902
- http://google.image
- http://linuxfr.org/news/faites-une-bonne-action-contactez-vos-elus-territoriaux
- http://www.cours-ordinateur.fr/ballmer-demission/
- http://fr.slideshare.net/jtouzi/comparatif-windowslinux

---

### Livres

- Il était une fois Linux... de Linus Torvalds
- Le Hold Up planétaire : la face cachée de Microsoft de Roberto Di Cosmo
- Piège dans le Cyberespace de Roberto Di Cosmo
- La Cathédrale et le bazar de Éric Raymond

---

# Questions ?
