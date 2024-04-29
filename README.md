# progetto_GEP

REQUISITI

problemi:


1- caricamento della propria musica

2- promozione della propria musica

3- guadagno tramite l’app

4- login



soluzioni:


1- chi carica una o più canzoni deve associare una o più etichette ad ogni canzone, che va a rappresentare il genere musicale.

2- chiunque voglia cercare un genere musicale andrà a cercarlo tramite il menù delle etichette; oppure se si ha già in mente un artista o una canzone ci sarà presente una barra di ricerca.

3- se sei un emergente e necessiti di caricare canzoni, hai a disposizione 3 caricamenti gratuiti, dopodichè sarai costretto a pagare 3 euro al mese (se vuoi continuare a caricare).

4- per il login sarà necessario iscriversi usando e-mail e password, solo la prima volta che si usa l'applicazione



UML PTOGETTO:

[utente]>(login)

(login)<(registrazione)

(login)-(ricerca canzoni)

(login)-(ascolta canzoni)

(login)-(carica canzoni)

(login)-(salva canzoni)

(carica canzoni)<(abbonati)

(abbonati)>(assegna abbonamento)

[azienda]>(assegna abbonamento)



VALUE PROPOSITION:


DYM (Discovery your Music)

![logo](https://github.com/cesatag0/progetto_GEP/assets/101175014/bfa924b0-f27c-4793-98d9-95d4ae12eff5)

1- Promuovi la tua musica

2- Scopri nuovi talenti

3- Raggiungi il TOP



User Story:


Ascoltatore occasionale:

In quanto ascoltatore occasionale, voglio poter trovare facilmente brani che potrebbero piacermi, tramite etichette e generi musicali differenti.


Ascoltatore abituale:

In quanto utente abituale, voglio ricevere avvisi e annunci basati sulla mia cronologia di ascolto e gli artisti che mi piacciono, in modo tale da scoprire nuove canzoni e artisti che potrebbero piacermi.


Emergente:

In quanto emergente, voglio poter promuovere la mia musica in modo facile, e arrivare nelle home page di piu persone possibili


Pivot:

Visti i recenti problemi con il possibile guadagno dall'applicazione ho deciso di modificare il modello di business

 - 1 tipo (user - creator)
 - Freemium: ascolto con publicità
 - Premium 4,99€/mese: ascolto senza pubblicità

Il guadagno deriverà dalle pubblicità e dagli abbonamenti, senza dover far pagare gli artisti per pubblicare il proprio materiale