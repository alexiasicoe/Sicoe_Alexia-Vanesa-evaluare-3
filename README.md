# Sicoe_Alexia-Vanesa-evaluare-3
1. Poziționarea Produsului
a. Oportunitatea și Problema:
Problema: Utilizatorii de internet sunt inundați de informații și au dificultăți în a găsi, organiza și vizualiza idei creative pentru proiectele lor personale (design interior, rețete, modă), pierzând link-uri sau salvând poze dezorganizat în telefon.
Oportunitatea: Crearea unui motor de descoperire vizuală care permite nu doar căutarea, ci și organizarea vizuală a ideilor.
Poziționarea: Pinterest este un "motor de descoperire vizuală" destinat oamenilor creativi și planificatorilor, care oferă o modalitate intuitivă de a descoperi și organiza inspirația, spre deosebire de Google Images care oferă doar rezultate brute fără context sau organizare.
b. Stakeholders vs. Utilizatori:
Stakeholders (Părțile interesate):
Echipa de dezvoltare (Devs, QA).
Investitorii / Managementul Pinterest.
Advertiserii (companiile care plătesc reclame).
Creatorii de conținut (bloggerii).
Utilizatori (Users):
Utilizatori obișnuiți (Căutătorii de inspirație).
Business accounts (Branduri care își expun produsele).
c. Sumar al capabilităților produsului (High-level features):
Organizare: Crearea de panouri publice sau secrete.
Descoperire: Feed personalizat bazat pe interese.
Salvare: Extensie de browser pentru a salva imagini de oriunde de pe web ("Pin it").
Căutare Vizuală: Posibilitatea de a căuta produse similare pornind de la o poză (Pinterest Lens).
2. Specificații Software (SRS - Software Requirements Specification)
Specificație Funcțională:
Descriere: Sistemul trebuie să permită utilizatorului autentificat să salveze o imagine ("Pin") într-un panou ("Board") existent sau să creeze un panou nou în momentul salvării.
Specificație de Interfață (UI/UX):
Descriere: Pagina principală (Feed) trebuie să utilizeze un layout de tip "Masonry Grid" (cărămizi inegale), care să se adapteze dinamic la lățimea ecranului și să permită "infinite scroll" (încărcare continuă) fără paginare vizibilă.
Specificație de Sistem (Non-funcțională/Performanță):

Descriere: Motorul de recomandare trebuie să actualizeze feed-ul utilizatorului în mai puțin de 200ms după ce acesta dă click pe un Pin, pentru a afișa conținut similar (Related Pins).
