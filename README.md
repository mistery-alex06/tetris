Tetris Arcade

Una reinterpretazione moderna, leggera e fedele del classico **Tetris**, sviluppata interamente da zero in puro JavaScript, HTML5 Canvas e CSS3, senza dipendenze o librerie esterne.

Architettura e Funzionalità: 
- Motore di gioco nativo in Canvas 2D: Rendering fluido basato su una griglia di gioco strutturata di 12 colonne per 20 righe.
- Sistema di rotazione e collisioni (Wall Kick System base): Gestione precisa delle collisioni perimetrali e delle tessere già posizionate, con correzione automatica della posizione durante la rotazione dei tetramini.
- Sette Tetramini standard: Implementazione completa delle forme canoniche (I, J, L, O, S, T, Z), ciascuna caratterizzata da una propria matrice geometrica e tonalità cromatica.
- Pulizia automatica delle linee (Line Clear & Gravity): Controllo iterativo della saturazione delle righe orizzontali, svuotamento dinamico e traslazione verso il basso della griglia con incremento progressivo della difficoltà temporale.
- Controlli da tastiera reattivi: Mappatura ottimizzata per la gestione in tempo reale dei movimenti laterali, della rotazione e della discesa accelerata della tessera attiva.

Struttura del Progetto:  
Il codice sorgente è organizzato in modo modulare:
- `index.html`: Struttura del DOM, canvas di gioco e interfaccia utente di base.
- `style.css`: Stili dedicati al layout arcade, centraggio e palette cromatica coerente.
- `script.js`: Logica di loop temporale (`requestAnimationFrame`), gestione dello stato dei pezzi, controlli di collisione e calcolo della matrice di gioco.

Quick Start
Clona la repository e avvia il progetto aprendo il file `index.html` direttamente nel browser o tramite un server di sviluppo locale:

```bash
git clone [https://github.com/mistery-alex06/tetris.git](https://github.com/mistery-alex06/tetris.git)
cd tetris
# Apri index.html con il tuo browser o avvia un server locale
