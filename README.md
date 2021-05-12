#IBB CSS - Cascading Style Sheets, Aufbaukurs - Projekt - Zengarden

### Projektvorgaben CSS-Aufbaukurs

Verändern Sie das Design vom CSS Zen Garden ausschließlich via CSS.

Nutzen Sie alle gelernten Inhaltspunkte.

- formatieren Sie Texte und Schriften stilvoll. (Textauszeichnungen)
- Binden Sie mindestens eine Hintergrundgrafik ein.
- Formatieren Sie individuell mindestens eine Liste.
- Laden Sie externe Inhalte via CSS ein.
- Arbeiten Sie mit der Vererbungskaskade
- Positionieren von Elementen
- CSS3 Layout mit Flexbox
- Druckoptimierung
- Alle Formatierungen und Style-Angaben sind ausschließlich mit CSS zu realisieren. Hierzu legen Sie eine oder mehrere separate CSS Dateien an.
- Versuchen Sie Ihre Dokumente sinnvoll zu strukturieren.
- Quelltexte sind so zu formatieren und einzurücken, dass eine übersichtliche Lesbarkeit gewährleistet wird.
- Kürzen Sie Ihre Quelltexte sinnvoll ein.

Alle CSS-Dateien sollten mit dem CSS-Validator (http://jigsaw.w3.org/css-validator) überprüft werden und keine 
Fehler und möglichst keine Warnungen beinhalten.

## 1. Installieren von Docker und Docker Compose

Siehe hierzu: https://github.com/knackw/docker_nginx_php8_mariadb10_phpmyadmin410

## 2. Installation der HTML Entwicklungsumgebung

**1) Webserver erzeugen**

Quellangaben:

PHP's development with Docker the easy way: https://stefan-poeltl.medium.com/php-development-with-docker-the-easy-way-13621ec5d39b

Mit dem unten angegeben Terminal Kommando wird Entwicklungsumgebung generiert 
und anschließen der Service (Server) gestartet. Du musst Dich im Verzeichnis des Projektes befinden, 
indem sich die Datei docker-compose.yml befindet.

`docker-compose up`

Sollte ein Fehler aufgetreten sein und am Setup Anpassungen vorgenommen haben musst Du folgenden Befehl ausführen.

`docker-compose up --build`

Zum Beenden des Services gibst du

`docker-compose down`

ein.

## 3. Linksammlung

**CSS Validator** 

http://jigsaw.w3.org/css-validator

**Screencheck von Cyber Crab** - Onlinetool zum Testen von responsive Design:

http://responsivetesttool.com

**Styling Reset von GitHub Repo**

https://github.com/csstools/normalize.css/blob/master/normalize.css

**Icons Font Awesome** 

https://fontawesome.com

**Google Fonts** 

https://fonts.google.com

**Frei Color Palettes**  

https://coolors.co/palettes/trending
https://color.adobe.com/de/create/color-wheel

### a) Design Pattern

**Responsive Webdesign und »Mobile First« - kulturbanause® blog** 

https://blog.kulturbanause.de/2014/08/responsive-webdesign-und-mobile-first/

**Stil mit Stil – Webseiten mit Javascript, HTML und CSS** 

https://www.mediaevent.de/

**Layouten mit CSS**

https://de.learnlayout.com/position.html

### b) General HTML, CSS and JS

**HTML5-Handbuch - Webkompetenz** 

http://webkompetenz.wikidot.com/docs:html-handbuch

**SELFHTML-Wiki** 

https://wiki.selfhtml.org/

**W3Schools Online Web Tutorials** 

https://www.w3schools.com/

### c) CSS allgemein

**CSS 4 you - die deutsche Seite für Cascading Stylesheets (CSS)** 

http://www.css4you.de

**PXtoEM.com- PX to EM conversion made simple** 

http://pxtoem.com/

**d) CSS Attribut-Selector**

**CSS Attribut-Selektor - mediaevent.de** 

https://www.mediaevent.de/css/css-selektor-attributselektor.html

**CSS Diner - Where we feast on CSS Selectors!** 

https://flukeout.github.io/

**CSS Kontext-Selektoren Kind, Nachfahre, Nachbar mediaevent.de** 

https://www.mediaevent.de/css/css-selektor-kontextselektor.html

**Teil 2 - Alle CSS3 Selektoren im Detail - Strukturpseudoklassen (Structural pseudo-classes) - Weitere Inhalte - Workshop HTML5**  

https://h5c3.de/inhalte/alle-css3-selektoren-im-detail-strukturpseudoklassen/

**CSS Tools: Reset CSS**

https://meyerweb.com/eric/tools/css/reset/

**CSS-Wertetypen-Zahlen, Maße und Maßeinheiten – SELFHTML-Wiki**

https://wiki.selfhtml.org/wiki/CSS/Wertetypen/Zahlen,_Ma%C3%9Fe_und_Ma%C3%9Feinheiten

**-nth Tester**

https://css-tricks.com/examples/nth-child-tester/#

**PXtoEM.com- PX to EM conversion made simple-**

http://pxtoem.com/

### d) CSS Cascading

**Kaskadierung und Vererbung - Webkompetenz** 

http://webkompetenz.wikidot.com/html-handbuch:kaskadierung-vererbung

### e) CSS --before und --after content

**CSS --before und --after content - mediaevent.de** 

https://www.mediaevent.de/css/generated.html

### f) CSS Position

**CSS -Position** 

https://de.learnlayout.com/position.html

### g) CSS Counter

**CSS Zähler mit Counter- Nummerieren - mediaevent.de** 

https://www.mediaevent.de/css/counter-increment-counter-reset.html

### h) CSS Rule

**CSS-Regeln (Rules) - Webkompetenz** 

http://webkompetenz.wikidot.com/html-handbuch:css-regeln#toc8

### i) SS value types-numbers, measures, and units of measurement

**SS-Wertetypen-Zahlen, Maße und Maßeinheiten – SELFHTML-Wiki** 

https://wiki.selfhtml.org/wiki/CSS/Wertetypen/Zahlen,_Ma%C3%9Fe_und_Ma%C3%9Feinheiten

### j) CSS printing

**Cascading Style Sheets { Tutorials - Drucklayouts mit CSS }** 

http://thestyleworks.de/tut-art/layout_print.shtml

**CSS-Tutorials-Print-CSS-Seitenformate – SELFHTML-Wiki** 

https://wiki.selfhtml.org/wiki/CSS/Tutorials/Print-CSS/Seitenformate#page-break-after

### k) CSS forms

**Formular-Chef** 

http://www.formular-chef.de/

**HTML-Tutorials-Formulare-input – SELFHTML-Wiki** 

https://wiki.selfhtml.org/wiki/HTML/Tutorials/Formulare/input#Typen

### l) CSS block and inline

**Blockelemente - Webkompetenz** 

http://webkompetenz.wikidot.com/html-handbuch:html-elementreferenz-blockelemente

**Inline-Elemente - Webkompetenz** 

http://www.css4you.de/

**CSS 4 You - The Finest in Stylesheets** 

http://webkompetenz.wikidot.com/html-handbuch:html-elementreferenz-inlineelemente

### m) CSS shadow

**Box Shadow CSS Generator - CSSmatic** 

https://www.cssmatic.com/box-shadow

### n) CSS fonts

**@font-face – Fonts in Webseiten einbetten – Stil mit Stil** 

https://www.mediaevent.de/font-face-schrift-in-webseiten-laden/

**CloudConvert** 

https://cloudconvert.com/

**CSS3 Text Effects - CSS3gen** 

https://css3gen.com/css3-text-effects/

****DaFont - Schriftarten zum Download** 

https://www.dafont.com/de/

**Font Squirrel - Free Fonts! Legit Free & Quality** 

https://www.fontsquirrel.com/

**Free Online Font Converter** 

http://www.freefontconverter.com/

**Typografie im Responsive Webdesign - YouTube** 

https://www.youtube.com/watch?v=xb_o-JiJFbA

**Typography in ten minutes - Butterick’s Practical Typography** 

https://practicaltypography.com/typography-in-ten-minutes.html

**Viewport Sized Typography - CSS-Tricks** 

https://css-tricks.com/viewport-sized-typography/

### o) CSS floats

**ilfreiche CSS-Tipps- So bekommst du Floats in den Griff - Elmastudio** 

http://www.elmastudio.de/hilfreiche-css-tipps-so-bekommst-du-floats-in-den-griff/

**Hilfreiche CSS-Tipps- So bekommst du Floats in den Griff - Elmastudio**

http://www.elmastudio.de/hilfreiche-css-tipps-so-bekommst-du-floats-in-den-griff/

### p) HTML Special Characters and Icons

**HTML Sonderzeichen und Icons - mediaevent.de** 

https://www.mediaevent.de/tutorial/sonderzeichen.html

### q) CSS Media Querys

**Media Queries » CSS INTENSIVSTATION** 

http://www.intensivstation.ch/css3/media-queries/

### r) CSS - :nth

:nth Tester 

https://css-tricks.com/examples/nth-child-tester/#

### s) CSS Box

**CSS box-sizing - mediaevent.de** 

https://www.mediaevent.de/css/box-sizing.html

### t) CSS Flexbox

**A Complete Guide to Flexbox - CSS-Tricks** 

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

**A Visual Guide to CSS3 Flexbox Properties ― Scotch.io** 

https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties

**CSS display-flex – Positionieren und Ausrichten - mediaevent.de** 

https://www.mediaevent.de/css/display-flex.html

**CSS Flexbox – Einführung in das Flexible Box Layout Module - kulturbanause® blog** 

https://blog.kulturbanause.de/2013/07/einfuhrung-in-das-flexbox-modell-von-css

**Flexbox Froggy - Ein Spiel, um CSS flexbox zu lernen** 

http://flexboxfroggy.com/#de

**What The Flexbox-! — A simple 20 video course that will help you master CSS Flexbox**

https://flexbox.io/#/

### u) CSS Tables

**Can I use... Support tables for HTML5, CSS3, etc (Can I use... Support tables for HTML5, CSS3, etc**

https://caniuse.com/

### v) CSS Grid

**CSS Grid in vier einfachen Schritten - mediaevent.de** 

https://www.mediaevent.de/css/grid.html

**CSS positionieren mit Grid-Systemen - mediaevent.de** 

https://www.mediaevent.de/tutorial/positionieren.html

**Grid Garden - Ein Spiel, um CSS Grid zu lernen** 

https://cssgridgarden.com/#de

**A Complete Guide to Grid CSS-Tricks**

https://css-tricks.com/snippets/css/complete-guide-grid/

### w) Keyframes

**CSS3 Keyframes Animation Generator**

http://cssanimate.com/

**SVG Animationen mit CSS - mediaevent.de**

https://www.mediaevent.de/tutorial/svg-css-transform.html

### x) Transformation

CSS transform translate, rotate, scale- mediaevent.de

https://www.mediaevent.de/css/transform.html

### y) Transition

**Cheat Sheet für Easing-Funktionen**

https://easings.net/de

**CSS transition • Einfache Animationen - mediaevent.de**

https://www.mediaevent.de/css/transition.html

## 4. Schlussbemerkung

Solltest Du Fehler entdecken, Vorschläge oder Anregungen haben scheu Dich nicht mir ein Ticket zu schreiben. 

Happy coding :)





