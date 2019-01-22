LAMBDAFORGE README

Stand: 2018-10-19

info@design-frischgepresst.de




!BEWARE!
 
- Die Seite lädt styles-min.css.

- Für Änderungen zunächst styles.css laden und dort Änderungen vornehmen.

- Dann minifyen und wieder styles-min.css einbinden.




LAYOUT

Layout allgemein:

- Header mit Logo und Sprachnavigation

- Main für alle Inhalte

- Footer

- Nav

- Container-Klasse legt maximale Breite für Desktop fest.


Layout Home

- Main ist unterteilt in Sections mit IDs (sec-01, ...). 

- Diese können über die Hauptnavigation (nav-primary) angesteuert werden.



GRID

- Grid-Container einfügen <div class="grid-02"> ... </div>

- Spaltenzahl festlegen: grid-02, grid-03, grid-04

- Entsprechende Anzahl divs für Spalten anlegen:
	<div class="grid-02">
		<div class="grid-col"> ... </div>
		<div class="grid-col"> ... </div>
	</div>



CARDS

- einfügen mit <div class="card-horiz shade-01-bg">

- Ausrichtung festlegen: card-horiz, card-vert

- Hintergrundfarbe festlegen: shade-01-bg, shade-02-bg, shade-03-bg



COLORED SQUARES

- einfügen durch <figure class="square-green e"></figure>

- Hintergrundfarbe wählen: square-red, square-green, square-blue

- Buchstaben wählen: abc ... xyz



ICONS

- icons einfügen durch <i class="icon-m clojure"></i>

- Größe festlegen durch Klassen icon-s, icon-m, icon-l, icon-xl

- Icon auswählen: 
	.amazonwebservices
	.android            
	.angularjs          
	.apache             
	.atlassian          
	.atom               
	.c-programming      
	.cplusplus          
	.clojure            
	.css                
	.docker             
	.git                
	.github             
	.gitlab             
	.globe              
	.html               
	.java               
	.javascript         
	.kafka              
	.link               
	.linkedin           
	.linux              
	.nodejs             
	.opengl             
	.postqrsql          
	.python             
	.rails              
	.react              
	.swift              
	.twitter
	


TEXT

- Überschriften nach semantischer Struktur vergeben (h1, ... , h6)

- Stylen mit Klassen .hero, .headline, .sec-headline

