---
layout: post
title:  "Frågor och Svar del 1"
date:   2018-11-13 04:27:15 -´+0100
categories: jekyll update
---

Här kommer Frågor 
Frågorna är urspungligen på engelska och jag har översatt dem till svenska.
Vissa ord har jag valt att ha kvar i engelska termen och dem är i kursiv stil. 


1.vad tänker du om _pre-comepiling_ din CSS <br>
För att För-kompilera koden har jag använt mig av pre-processorn Sass.
Det är ett sätt att skriva data på ett sätt som sedan skriv över till en annan data. 
Man skriver koden I sass och sedan skrivs den över till CSS. 

* Jämför med vanlig CSS <br>
Om man jämför med Sass och CSS så går det snabbare att skriva, tänk att man skriver förkortningar för kod som annars är längre i CSS. 
Man kan använda sig av variabler och göra uträkningar i Sass koden.

* Vilka tekniker har du använt?<br>
Jag har använt mig av variabler som teknik, och dels har jag satt en gradient varibel som heter Background-image som sätter bakgrunden till en gradient till exempel. 
Sedan har jag även testat på och ändrat och korrigerat befintliga varibaler på sidan.  
<br>
Jag har själv inte provat på nesting men ser att det förekommer i temat och filen _base.scss. Nesting handlar om i hur man skriver css i en ordning som används i html strukturen.

* Fördelar & Nackdelar<br>
+ Man får snabbt en överblick då det är mindre kod 
+ Man kan sätta och använda variabler i koden vilket är smidigt
+ Det är även en bättre organiserad kod med exempelvis nesting där man kan skriva CSS i en ordning som man ser i HTML koden för att lättare skriva , läsa och förstå koden. 

- En nackdel som jag upplevde med Sass är att det är många filer att hålla reda på, men det kan bara är i början. 
-  Det skiljer sig vid debugging på linjerna mellan webben och källan, så felet kan peka på fel rad vilket man bör vara vaksam på. 

2.Vad tänker du om _static site generators_?<br>
Static site generators skapar en statisk sida med html utav text , mallar och html.
En fördel mad att använda static site generators är att man kan använda en webbserver 
En fördel är det går fort att generera sidan. 
Det som är tråkigt med static site generators är som namnet antyder, att det är statiska sidor som byggs i föväg och uppdateras inte med live data. 

3.Vilken typ av project är ovannämda menade för?<br>
Jag skulle säga att typen project kan var exempelvis bloggar eller portfolio sidor 
som är lämpliga. De är plattformar som oftast har ett förarbetat matrial som man vill dela med sig av. 
