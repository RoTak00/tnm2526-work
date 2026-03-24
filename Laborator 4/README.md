# Laborator 4 - Pure Data. Sound

În acest laborator veți descoperi limbajul Pure Data: îl veți instala, veți scrie un program "hello world" și veți învăța despre principalele caracteristici ale limbajului. Înainte de asta, trebuie însă să vă readuceți aminte ce este sunetul (reprezentat ca undă sinusoidală) și cum definim anumite caracteristici importante ale acestuia.


## Ce este sunetul?

1. Citiți despre [sunet](https://www.open.edu/openlearn/science-maths-technology/engineering-technology/sound-music-technology-an-introduction/content-section-0?intro=1) ca undă sinusoidală și ce reprezintă amplitudinea, lungimea de undă, frecvența și perioada, faza, viteza și presiunea sunetului. E util să citiți și despre câteva elemente de psihoacustică: pitch (înălțime), loudness (tărie), mărimi ale tăriei (decibeli, LUFS) și intervalul de frecvențe ale sunetului ce pot fi percepute de oameni.

## Pure Data sau Max/MSP? Install & run 

2.  Vizitați paginile celor două limbaje din familia "patcher" și decideți ce limbaj vreți să învățați și folosiți pentru această materie: 

- [Pure Data](https://puredata.info/) 

- [Max/MSP](https://cycling74.com/products/max)

Odată ce ați ales limbajul, downloadați toolul și instalați-l pe calculatorul vostru. 

Dacă ați ales Max/MSP, urmați tutorialele de [aici](https://docs.cycling74.com/learn/series/max-tutorials/). (ask for help: întrebați-mă ce ar fi util să citiți din fiecare tutorial).

Dacă ați ales Pure Data, urmați exercițiile următoare din laborator.

## Hello world! in Pd

Dacă nu ați fost la curs, citiți această [scurtă introducere](http://www.pd-tutorial.com/english/ch01.html) în Pd.

3. Urmați pașii din [capitolul doi](http://www.pd-tutorial.com/english/ch02.html) al tutorialului pentru a scrie primul patch "hello world!". Ce se întâmplă dacă în entitatea de tip mesaj în care am scris "1" înlocuim valoarea cu "0.5"?

3. Citiți despre primul tip de data flow în Pd: [control flow](http://www.pd-tutorial.com/english/ch02s02.html) și apoi rezolvați din exercițiile propuse în tutorial:

-  Creați două melodii aleatoare care rulează simultan. 

- Creați un patch în care două *bang-uri* selectează două intervale diferite la alegere (pornind de la exemplul cu două bang-uri/ două frecvențe).

- Creați un metronom cu ritmuri neregulate aleatorii (cu un tempo mediu ajustabil). 


## Audio Basics

4. Citiți [capitolul 3](http://www.pd-tutorial.com/english/ch03.html) despre pitch și volum și rezolvati din exercițiile propuse: 

- Creați o gamă cu sferturi de ton.

- Creați un patch în care volumul de la un input de microfon controlează pitchul unui oscilator. 
