# Rubiks Cube

Ik heb gekozen om voor dit project een rubiks cube te maken. Ik heb hier voor gekozen omdat de 2 leukste opdrachten de vuurwerkshow en de rubiks cube waren. Nu weet (denk) ik dat ik wel goed ben in CSS en zo leek de Rubiks cube mij ook een grotere uitdaging dan de vuurwerkshow.

de uitdaging hier bij mij ligt in het werken met perspectieven en het proberen te gebruiken maken van variabelen voor de grootte van de kubus. Daarnaast is het gebruik van :checked en labels op deze manier nieuw voor me en zie ik dit dus ook als een uitdaging om zo min mogelijk knoppen te hebben voor de functies.

## Week 1

### Wat heb ik gedaan?

In deze week heb ik in de weinig tijd die we nog over hadden voor het eindproject er voor gezorgd dat ik 27 kubussen goed had gepositioneerd, meer was nog niet gelukt deze week.

### Waar liep ik tegen aan?

Deze week liep ik alleen aan tegen het goed zetten van het perspectief, waar ik helaas nog geen oplossing voor kon vinden.

## Week 2

### Wat heb ik gedaan deze week?

In week 1 is het mij gelukt om een kubus te maken, deze 26x te kopieren en ze ook goed te positioneren, waardoor het op een rubiks cube lijkt. Hier kwam ik al een paar uitdagingen tegen waar ik tegen aan liep, waardoor dit alles is wat ik deze week kon doen.

### Waar liep ik tegen aan?

* Perspectief

Tijdens het maken van de kubus begon ik, misschien niet al te slim, meteen met 27 kubussen (Ik voegde die in het midden ook toe, voor de zekerheid). als snel kreeg ik hierdoor problemen met perspective.

<img src="./images/perspectief1.png" WIDTH="400px">

zoals je boven op de foto zit had ik moeite met het perspectief in het midden te krijgen, wat ik heel raar vond. Na een paar uur meer proberen zat ik uiteindelijk met dit hoopje chaos:

<img src="./images/perspectiefChaos.png" WIDTH="400px">

Op dit moment koos ik er ook voor het hele bestand te verwijderen en gewoon opnieuw te beginnen. Dit loste al mijn problemen op ik een half uurtje.


* Transform Origin

Een ander probleem waar ik tegen aan liep was Transform Origin. Omdat ik vanaf links boven was begonnen draaide de kubus we rond, maar niet in het midden. Hierdoor draaide de kubus met de voorkant als transform origin. Tijdens een feedback gesprek met Sanne kreeg ik een goude tip om dit op te lossen.


## Week 3

### Wat heb ik gedaan deze week?

Deze week is het mij gelukt om het transform origin op de goede positie te krijgen door de goude tip van Sanne. Om dit op te lossen heb ik alle kubussen 1 positie naar voren verplaatst, zo werd de middelste rij daadwerkelijk het midden.

naast het transform origin heb ik geprobeerd om een 1 keer de kubus te draaien. Wat uiteindelijk gelukt is na een paar pogingen. Ook heb ik deze week ervoor gezorgd dat je de kubus 360 graden kon draaien, maar dit was alleen op de X-as

Ook was het mij deze week gelukt om met 1 knop (stiekem 4 die display none en unset krijgen) de kubus 4x rond te draaien.

### Waar liep ik tegen aan?

* Draaien van 1 kant

Het eerste waar ik deze week tegen aan liep was het draaien van 1 kant van de kubus. Zoals Sanne had verteld was het handig om te beginnen met het roteren van de kubus om hem daarna pas te verplaatsen.

<img src="./images/turn.png">

Waar ik al snel achter kwam was dat wanneer je een kubus draait, deze niet hetzelfde blijft translaten. Wat voorheen dus uit mijn perspectief naar onder verplaatsen was, werd nu dan bijvoorbeeld naar achter. Toen ik dit eenmaal door had ging het eigenlijk wel redelijk soepel.

* Input:checked en Labels

Waar ik ook enorm veel tijd aan kwijt was was het werken met input:checked, voornamelijk hoe 'input:checked ~' werkte om het juiste te selecteren. Omdat ik nooit Radio buttons heb gebruikt wat het concept for="" ook nieuw voor me, maar deze werd gelukkig snel duidelijk.

Waar ik pas echt tegen aan liep was dat ik 2 verschille radio buttons wilde voor opzij draaien en omhoog/omlaag draaien. Omdat ik gebruik maaktte van animaties ging 1 van de animaties niet meer af als de andere radiobutton al aan stond. 

## Week 4

### Wat heb ik gedaan?

...

### Waar liep ik tegen aan?