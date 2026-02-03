Questo programma è una semplice simulazione di un distributore automatico di bevande, scritta in Java e utilizzabile da riga di comando.

Struttura generale
Il progetto è composto da due classi principali:
Distributore → gestisce il menu, l’input dell’utente e le operazioni
Bevanda → rappresenta una singola bevanda con le sue caratteristiche

Classe Bevanda
Rappresenta una bibita del distributore.

Attributi
descrizione → nome della bevanda
prezzo → costo della bevanda
disponibile → indica se la bevanda è disponibile (true/false)
indice → identificatore numerico della bevanda
Funzionalità principali

Costruttori (vuoto, completo e di copia)
Getter e setter per tutti gli attributi
Metodo VerificaDisponibilita() che stampa se la bevanda è disponibile o no
Metodo toString() per stampare i dettagli della bevanda

Classe Distributore
Contiene il main ed è il cuore del programma.

Funzionamento
Usa un ArrayList<Bevanda> per memorizzare le bibite
Mostra un menu interattivo che si ripete finché l’utente non sceglie di uscire

Menu disponibile: 

1)Inserire tre bevande
  L’utente inserisce:
    nome
    prezzo
    disponibilità (y/n)
    Ogni bevanda riceve automaticamente un indice
  
2)Stampare tutte le bevande presenti
  Mostra l’elenco completo delle bevande inserite

3)Cercare una bevanda tramite indice
  Permette di trovare una bevanda conoscendo il suo indice

4)Controllare la disponibilità di una bevanda
  Verifica se una bevanda (in base al nome) è disponibile o meno

5)Uscire dal programma
