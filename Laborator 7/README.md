# Laborator 7 - Pure Data#4 

În acest laborator veți învăța despre aplicații ale transformatei Fourier (filtre, compresoare), metode de corecție a amplitudinii, și cum putem crea patchuri cu elemente vizuale.  

## measure twice, cut once.

1. În laboratorul trecut ați învățat despre transformata Fourier și cum putem face [analiză Fourier în Pd](http://www.pd-tutorial.com/english/ch03s08.html). Citiți în continuare despre aplicații ale transformatei Fourier: [filtre](http://www.pd-tutorial.com/english/ch03s08.html#id432343), [compresoare](http://www.pd-tutorial.com/english/ch03s08.html#id432343) și [tunere](http://www.pd-tutorial.com/english/ch03s08.html#id432668). Jucați-vă cu pitch follower-ul din 3.8.3.4: de exemplu, puteți adăuga un delay, reverb, ori o variație armonică – go wild.

#### extra 
Puteți citi mai multe despre ferestre Hanning și cum le folosim cu FFT [aici](https://www.numberanalytics.com/blog/hanning-hamming-blackman-windows-guide). 

## off with their head!

2. Citiți despre cum putem face corecții ale amplitudinii în [capitolul 3.9](http://www.pd-tutorial.com/english/ch03s09.html), folosind limiters și compresoare. 

3. Pentru a înțelege mai bine cum funcționează compresoarele, citiți despre [envelopes](https://en.wikipedia.org/wiki/Envelope_(music)) și urmăriți video-ul [acesta](https://www.youtube.com/watch?v=ZyMqoDhk6uE) care explică cum sunt folosite acestea în compresoare. 

- Implementați patch-ul pentru vizualizarea envelope-ului descris în acest [video](https://www.youtube.com/watch?v=Ic91c0fSe_Y).

- Puteți vedea mai multe exemple de patchuri care construiesc envelopes complexe [aici](https://www.youtube.com/watch?v=sjQzw-TOZSY). Iar [aici](https://charlesneimog.github.io/Awesome-Pd/objects/envelopes/) o listă de obiecte Pd relevante pentru envelopes.

## push the button!

4. Știați că putem 'cânta' live cu Pd? Citiți cum putem folosi mouse-ul și tastatura pentru a controla un patch în capitolul [4.3](http://www.pd-tutorial.com/english/ch04s03.html).

## let's go visual!

5. Citiți despre cum puteți folosi elemente vizuale pentru a realiza patch-uri grafice în capitolul [5.2](http://www.pd-tutorial.com/english/ch05s02.html).

## extra-extra

Exemple de proiecte interesante legate de Pd:

- [Envion](https://github.com/aveniridm/envion) ecosistem envelope-first pentru compoziție muzicală algoritmică și procedurală 
- Pd for mobile: for [Android](https://droidparty.net/), for [iOS](https://danomatika.com/code/pdparty), for [both](https://danieliglesia.com/mobmuplat/)
- [share your patch on the web](https://github.com/cuinjune/PdWebParty) V [run it on the web](https://github.com/sebpiq/WebPd)
