# Laborator 8 - WebXR 

În acest laborator veți învăța mai multe despre [WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Fundamentals) și veți implementa o aplicație web XR simplă urmând tutorialul [acesta](https://beprosto.github.io/webxr-tutorial/).

## init 0

1. Citiți [primul capitol](https://beprosto.github.io/webxr-tutorial/tutorial1) din tutorial și urmați pașii pentru a crea o pagină html simplă ce va sta la baza aplicației pe care o veți crea azi.

## recap: webgl2? matrici? 

2. Mai țineți minte WebGL2? Dacă ați ezitat înainte să răspundeți, [capitolul următor](https://beprosto.github.io/webxr-tutorial/tutorial2) poate funcționa ca o scurtă recapitulare. Dacă nu ați uitat WebGl2, puteți trece direct la [capitolul 3](https://beprosto.github.io/webxr-tutorial/tutorial3) unde este definită o clasă pentru o crea o abstractizare WebGL2 pentru vârfuri, buffere, shaders, și texturi ce va fi folosită în restul tutorialului (pentru a ascunde codul de WebGL, punând accentul pe codul particular componentei de XR).

3. Dar de calculul cu matrici pentru aplicarea de transformări afine vă mai amintiți? În [capitolul patru](https://beprosto.github.io/webxr-tutorial/tutorial4) puteți revedea câteva concepte importante și necesare pentru aplicarea transformărilor în restul tutorialului. Mai puteți citi și [aici](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Geometry) despre elemente de geometrie utile pentru WebXR.

## webXR, finally.

4. Suntem gata să scriem cod pentru componenta XR. Citiți [capitolul următor](https://beprosto.github.io/webxr-tutorial/tutorial5) și urmați pașii descriși pentru a inițializa sesiunea XR. Puteți citi mai multe despre pornirea și oprirea sesiunilor XR [aici](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Startup_and_shutdown).

5. Și acum, să creăm o scenă 3D! Urmați pașii din [capitolul 6](https://beprosto.github.io/webxr-tutorial/tutorial6) pentru a adăuga un model 3D la alegere (poate fi și cubul din exemplu, dar vă sugerez să încărcați alt model .obj). Pentru a înțelege mai bine codul din tutorial, puteți citi mai multe despre [spații de referință](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Geometry#reference_spaces), [spatial tracking](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Spatial_tracking) și [descrierea unei poziții relativ la un spațiu](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Spatial_tracking#describing_a_position_relative_to_a_space) folosind obiecte *Pose* (mai ales de tip [viewer pose](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Spatial_tracking#viewer_poses)), [XR frames](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Rendering#webxr_frames) și [frame animation callbacks](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Rendering#drawing_the_scene) pentru randarea scenelor 3D. 

## advanced: camera & controllers 

6.  Exemplul nostru e (cam) static. [Cum mișcăm camera? Există o cameră?](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Cameras). Și cum ne mișcăm în XR? Puteți citi [aici](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Movement_and_motion) un exemplu despre cum utilizatorul se poate mișca folosind un headset ori tastatura și/sau mouse-ul. De asemenea, puteți vedea în capitolele [7](https://beprosto.github.io/webxr-tutorial/tutorial7) și [8](https://beprosto.github.io/webxr-tutorial/tutorial8) din tutorial cum putem folosi controllerele unui headset (pentru a testa codul, aveți nevoie de un emulator – [chrome](https://chromewebstore.google.com/detail/immersive-web-emulator/cgffilbpcibhmcfbgggfhfolhkfbhmik), [firefox](https://addons.mozilla.org/en-US/firefox/addon/webxr-api-emulator/)). 

## extra: sunet 3D

7. Sunteți curioși cum putem adăuga sunet tridimensional lumii noastre virtuale? Puteți citi [aici](https://beprosto.github.io/webxr-tutorial/tutorial10) despre cum putem folosi biblioteca [resonance audio](https://resonance-audio.github.io/resonance-audio/) pentru a include sunete 3D. Have fun testând [codul din tutorial](https://github.com/beProsto/webxr-tutorial/tree/main/projects/tutorial10)!
