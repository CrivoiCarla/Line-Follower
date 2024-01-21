# Proiect Line Follower: Performanță și Inovație

## Descriere
Acest proiect prezintă crearea unui robot line follower, care combină ingeniozitatea ingineriei cu precizia programării. Scopul a fost de a dezvolta un robot capabil să urmeze linii cu eficiență și precizie, demonstrând astfel potențialul tehnologiilor autonome.

### Componente Principale:
- **Arduino Uno**: Creierul robotului, coordonează toate componentele.
- **2 Motoare**: Asigură mișcarea și manevrabilitatea robotului.
- **Senzor Infraroșu**: Detectează linia și ajută la navigare.
- **Baterie LiPo**: Oferă o alimentare fiabilă și eficientă.
- **Placă Personalizată**: Utilizată pentru structura robotului, echilibrând rezistența și greutatea.
- **L293D motor driver**: Extinde capabilitățile digitale ale Arduino Uno.

### Caracteristici Unice:
- **Calibrare Automată**: Permite robotului să se adapteze la diferite condiții de iluminare și texturi ale suprafeței.
- **Traseu Complex**: Robotul a demonstrat abilitatea de a naviga un traseu dificil, finalizându-l în aproximativ 18.5 secunde.

## Implementare
Implementarea acestui proiect a implicat un echilibru între hardware robust și software adaptabil. Fiecare componentă a fost selectată și integrată cu scopul de a optimiza performanța și fiabilitatea.

## Sistemul PID
În acest proiect, am aplicat un sistem de control PID (Proportional-Integral-Derivative) pentru a regla mișcarea robotului. Acest sistem este esențial în obținerea unei navigări precise și eficiente.

- **KP (Proportional)**: Ajustarea acestei valori ne-a ajutat să controlăm răspunsul robotului la abateri de la traseu. O valoare mai mare de KP înseamnă o reacție mai rapidă la abateri.
- **KD (Derivative)**: Utilizarea KD ne-a permis să reducem oscilațiile și să stabilizăm mișcarea robotului, oferind o navigare mai lină și mai precisă.

Am ales să nu utilizăm componenta KI (Integral) în acest proiect, deoarece am găsit că ajustările KP și KD au fost suficiente pentru a atinge performanța dorită.

### Calibrare Automată
Sistemul de calibrare automată a fost o inovație cheie, permițând robotului să opereze eficient în condiții variate, fără intervenția manuală.

## Viziunea echipei
### Cum își imaginează băieții că va arăta proiectul:
<img src="designe_boy.png" alt="Line Follower Robot Boys" width="300"/>

### Cum își imaginează fetele că va arăta proiectul:
<img src="designe_girl.png" alt="Line Follower Robot Girl" width="300"/>

### Cum a arătat de fapt:
<img src="setup.jpeg" alt="Line Follower Robot" width="300"/>


## Demonstratie Video
Pentru o demonstrație video a robotului nostru line follower, vizitați linkul nostru de YouTube: [Demo Line Follower](https://youtu.be/7I6eCeHwWuQ)

## Echipa
<img src="team_ph_1.jpeg" alt="Team Photo 1" width="300" height="400"/> <img src="teasm_ph_2.jpeg" alt="Team Photo 2" width="300" height="400"/>
## Concluzii
Proiectul nostru demonstrează nu doar abilitățile tehnice necesare pentru construirea unui robot line follower eficient, dar și inovația în gândirea de design și programare. Este un exemplu clar al potențialului roboticii autonome și al aplicabilității sale în diferite domenii.
