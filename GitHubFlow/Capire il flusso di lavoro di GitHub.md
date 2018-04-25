GitHub è un sistema di controllo di versione che permette di di aggiornare file senza dover sovrascrivere le versioni precedenti, offre con estrema facilità la possibilità di tornare indietro nello storico delle variazioni di un file per recuperare una precedente versione.

**GitHub** nasce per gestire lo sviluppo di progetti software, è basato sul software *open source* Git (ideato e sviluppato da [Linus Torvalds](https://it.wikipedia.org/wiki/Linus_Torvalds).

[**GitHub**](https://github.com/) è una piattaforma di **hosting web** che offre la possibilità di conservare i propri file ed eventualmente condividerli con altre persone. GitHub offre piani hosting gratuiti per progetti software *open source* e a pagamento per progetti software privati.

Con **GitHub** è possibile gestire non solo file scritti in un qualsiasi linguaggio di programmazione, ma anche realizzare documentazione o libri di cui si vuol e mantenere lo storico delle variazioni eseguite.

![flusso](immagini/flusso.jpeg)

#### Creare un branch

Quando lavorate ad un progetto, avrete da gestire in un dato momento parecchie funzionalità e idee di sviluppo alcune delle quali potranno essere immediatamente implementate ed altre ancora no. Al flusso del progetto è possibile aggiungere dei rami (branch) che descrivono alternative o correzioni che potranno poi essere integrati all'interno del progetto originale.

Quando create un ramo nel vostro progetto state realizzando un nuovo ambiente in cui state provando nuove idee e le modifiche apportate ad un ramo non influiscono sul ramo principale `master` , quindi sarete liberi di sperimentare e fare modifiche con la certezza che il vostro ramo non verrà unito al principale fino a quando non sarà pronto per essere esaminato da qualcuno con cui state collaborando.

#### Suggerimento

La ramificazione è un concetto fondamentale in Git e l'intero flusso di GitHub è basato su di esso. C'è una sola regola: qualsiasi cosa nel ramo principale `master`  può essere sempre distribuita (resa definitiva per la distribuzione)

Per questo motivo è estremamente importante che il nuovo ramo venga creato fuori dal master quando si lavora su una funzione o una correzione. Il nome del vostro ramo dovrebbe essere descrittivo (ad es.  `refactor-authentication`, `user-content-cache-key`, `make-retina-avatars`), in modo che altri possano vedere su cosa state lavorando.