## Počítačová grafika  
## ve vědě

---?image=assets/eli_logo.jpg&size=auto 90%

---

### ELI Beamlines

Součástí evropského projektu ELI (Extreme Light Infrastructure)

Několik pracovišť na území České republiky, Maďarska a Rumunska

Zkoumání interakce světla s hmotou při nejvyšších intenzitách a nejkratších časových rozpětích

Note:
Největší vedecký projekt ČR v historii - 7.5 mld Kč (85% z EU)

---

### ELI Beamlines

Molekulární a biomedicínské aplikace

Zdroje ultrakrátkých pulzů tvrdého rengenového záření

Fyzika plazmata a exotické fyzika

Urychlování iontů

Undulátorový rentgenový zdroj

Note:
E1 - studium vlastností materiálů a biologických vzorků
E2 - studium vzorků, které nechceme ničit destruktivnímí metodami
E3 - teplá husta hmota, plazmová fyzika
E4 - protonová terapie rakoviny
E5 - studium malých struktur - velikost atomů 

---?image=assets/eli_budova.jpg

---

### Video E3 render FIXME:

---

### Virtual Beam Lines

Kompletní životní cyklus laserového experimentu a budovy ELI  

Design experimentů, výuková pomůcka, PR  

Unity vs. WebGL  

TODO: demo na telefonu?

Note:
Design experimentu (vbl)
Simulace (externí sw)
Vizualizace simulací (vbl) 
Podklady pro reálny experiment (externí sw)
Vizualizace výsledků (vbl)
Transformace dat (Jupyter notebook)

---

### Problémy

Enormní velikost modelu  
@size[0.6em](60 mil tri, 31 mil vert, 3500+ unikátních objektů)

LOD  
@size[0.6em](Automatické generování má různorodé výsledky)

Zdrojová data
@size[0.6em](Každý pes jiná ves)

Note:
Každý konstruktér (autor modelů) má jiný bordel v modelu

---

### Problémy

Tradeoffs  
@size[0.6em](Paměť, CPU, síť)

Optimalizace  
@size[0.6em](Never ending story)

UX  
@size[0.6em](Složitost navigace, velký rozptyl typů uživatelů)

Note:
Index + vertex buffer cca 600MB holá data
3500 draw callu na telefonu je v pohodě, ale setování uniformů je brutálně drahé

---

TODO: maly tym
TODO: nabidka prace