# Laborator 5 - Pure Data#2 

În acest laborator veți învăța mai multe despre digital sound și limbajul Pure Data: câteva elemente de teorie despre reprezentarea sunetului în Pd, cum măsurăm pitchul și volumul sunetului, și o foarte scurtă introducere în sound synthesis. Vom prespune că ați citit deja [capitolul 2.2](http://www.pd-tutorial.com/english/ch02s02.html) despre nivelul de control al Pd. 

## Cum măsurăm sunetul?

1. Citiți în [capitolul 3](http://www.pd-tutorial.com/english/ch03.html) despre cum măsurăm [pitch-ul](http://www.pd-tutorial.com/english/ch03.html#chapt3.1.1) și [volumul](http://www.pd-tutorial.com/english/ch03.html#id420457) unui sunet. 
Rezolvați din exercițiile propuse: 

a) Creați o gamă cu sferturi de ton.

b) Creați un patch în care volumul de la un input de microfon controlează pitchul unui oscilator. 

##  Cum producem sunete?

### Harmonics: There is no pure sound

2. Citiți despre serii armonice și frecvența fundamentală ca să înțelegeți cum putem crea sunete folosind [additive synthesis](http://www.pd-tutorial.com/english/ch03s02.html). Implementați ultimul patch din capitol și reduceți amplitudinea frecvenței fundamentale la 0. Ce observați când ascultați sunetul compus doar din overtones? 

### Filtre

3. Citiți despre white și pink noise în capitolul 3.3
 despre [substractive synthesis](http://www.pd-tutorial.com/english/ch03s03.html). 

a) Implementați cele două patchuri pentru producerea zgomotelor albe și roz și ascultați sunetele produse. Ce observați? Care zgomot pare mai "aleator"? 

b) Citiți despre cele trei tipuri de filtre (lowpass, highpass, band-pass) și implementați patchurile pentru fiecare tip. 

c) Implementați patchul pentru filtrul de "telefon" și testați-l. 

# Sampling

4. Citiți despre [cum putem salva sunete](http://www.pd-tutorial.com/english/ch03s04.html#id424588) în fișiere și modificați patchul pentru filtrul de "telefon" pentru a salva un mesaj pentru mesageria vocală într-un fișier .wav.

5. Citiți despre buffere, array-uri și table-uri și cum putem încărca fișiere audio în Pd în [capitolul 3.4](http://www.pd-tutorial.com/english/ch03s04.html).

6. Testați sampler-ul *simple sampler* și urmăriți cum poate fi dezvoltat în [capitolul 3.4.2](http://www.pd-tutorial.com/english/ch03s04.html#id426491). Apoi citiți despre generatoare de loopuri și testați patch-ul pentru simularea efectului de reverb. Combinați patchul cu filtrul de telefon și cel pentru reverb pentru înregistrarea unui mesaj telefonic... cu ecou.