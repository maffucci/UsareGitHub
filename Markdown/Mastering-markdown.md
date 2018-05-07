<img class="aligncenter size-full wp-image-8747" alt="markdown" src="http://www.maffucci.it/wp-content/uploads/2013/08/markdown.jpg" width="640" height="108" />

Markdown è una sintassi molto snella e semplice, viene utilizzata per dare lo stile al testo a tutte le forme di scrittura che possono essere utilizzate su GitHub.

### Cosa imparerai:

* In che modo il formato Markdown rende facile la modifica del testo in maniera collaborativa
* In che modo Markdown differisce dai tradizionali approcci alla formattazione del testo
* Come usare Markdown per formattare il testo
* Come sfruttare il rendering automatico del Markdown di GitHub
* Come applicare le estensioni Markdown offerte da GitHub

# Cos'è il Markdown?

[Markdown](https://daringfireball.net/projects/markdown/) permette l’applicazione dello stile al testo che viene prodotto per documentare su web. E’ possibile controllare la modalità di presentazione del testo, la formattazione in grassetto o in corsivo, l'aggiunta di immagini e la creazione di elenchi e molto altro. Per lo più, Markdown è un testo puro normale con pochi caratteri non alfabetici, come # o * utilizzati come tag per assegnare lo stile al testo.

Su GitHub puoi usare Markdown in diverse occasioni

* [Gists](https://gist.github.com/)
* Commenti  e Pull Requests
* Files con estensione `.md` o `.markdown` 

Per maggiori informazioni consultare “[Writing on GitHub](https://help.github.com/categories/writing-on-github/)” nella sezione *GitHub Help*.

## Esempi

### Testo

<pre>
E’ molto semplice scrivere delle parole in **grassetto** ed altre parole in *italico* con Markdown.
Puoi anche <span>[fare un link a Google!](http://google.com)</span>
</pre>

E’ molto semplice scrivere delle parole in **grassetto** ed altre parole in *italico* con Markdown. Puoi anche [fare un link a Google!](http://google.com)

### Liste

<pre>
Potresti aver necessità di una lista numerata:

1. Uno
2. Due
3. Tre

Oppure di una lista puntata:

* Incomincia la riga con un asterisco
* Ed ancora un’alta riga

In modo diverso,

- I trattini funzionano altrettanto bene
- E se una lista secondaria, inserisci due spazi davanti al trattino o all’asterisco:
  - Come questo
  - Oppure questo
</pre>

Potresti aver necessità di una lista numerata:

1. Uno
2. Due
3. Tre

Oppure di una lista puntata:

* Incomincia la riga con un asterisco
* Ed ancora un’alta riga

In modo diverso,

- I trattini funzionano altrettanto bene
- E se una lista secondaria, inserisci due spazi davanti al trattino o all’asterisco:
  - Come questo
  - Oppure questo

### Immagini

<pre>
Se vuoi includere nel testo delle immagini dovrai fare in questo modo:

![Immagine di Yaktocat](https://octodex.github.com/images/yaktocat.png)
</pre>

Se vuoi includere nel testo delle immagini dovrai fare in questo modo:

![Immagine di Yaktocat](https://octodex.github.com/images/yaktocat.png)

### Titoli e citazioni

<pre>
# Documenti strutturati

A volte è utile avere diversi livelli di intestazioni per strutturare i vostri documenti. Poni davanti al testo che vuoi che sia un titolo il carattere `#`. Più `##` in una riga denotano dimensioni di intestazione più piccole.


### Questo è il terzo livello di intestazione

Puoi usare un carattere `#` per identificare la prima dimensione dell’intestazione fino a un massimo di  6 caratteri `######` per definire la dimensione più piccola di intestazione.

Se desiderate citare del testo, usare il carattere > prima della riga:

> Giornale di bordo: Data Stellare 9529.1: Questa è l'ultima crociera dell'Enterprise sotto il mio comando.
> Questa nave e la sua storia tra breve saranno consegnate ad un nuovo equipaggio.
> A loro e ai loro discendenti noi affidiamo il nostro futuro.
> Essi continueranno il viaggio attraverso spazi ancora inesplorati spingendosi con coraggio dove nessun uomo,
> dove nessuno è mai stato prima. (Rotta verso l'ignoto)
>
> Capitano James Tiberius Kirk (Star Trek )

</pre>

### Documenti strutturati

A volte è utile avere diversi livelli di intestazioni per strutturare i vostri documenti. Poni davanti al testo che vuoi che sia un titolo il carattere `#`. Più `##` in una riga denotano dimensioni di intestazione più piccole.


### Questo è il terzo livello di intestazione

Puoi usare un carattere `#` per identificare la prima dimensione dell’intestazione fino a un massimo di  6 caratteri `######` per definire la dimensione più piccola di intestazione.

Se desiderate citare del testo, usare il carattere > prima della riga:

> Giornale di bordo: Data Stellare 9529.1: Questa è l'ultima crociera dell'Enterprise sotto il mio comando.
> Questa nave e la sua storia tra breve saranno consegnate ad un nuovo equipaggio.
> A loro e ai loro discendenti noi affidiamo il nostro futuro.
> Essi continueranno il viaggio attraverso spazi ancora inesplorati spingendosi con coraggio dove nessun uomo,
> dove nessuno è mai stato prima. (Rotta verso l'ignoto)
>
> Capitano James Tiberius Kirk (Star Trek )

### Codice

<pre>

Esistono molti modi diversi per scrivere codice di programmazione con il markdown in GitHub. Se dovete utilizzare blocchi di codice inline, includeteli tra apici inversi: `var esempio = true`. Se avete un blocco di codice più lungo potete indentare con quattro spazi:

    if (condizione){
      return true
    }

GitHub supporta anche qualcosa chiamato “recinzione del codice”, che consente di inserire più linee senza indentazione:

```
if (qualcosa){
  return true
}
```

E desiderate evidenziare con colori una particolare sintassi includete il linguaggio di programmazione usato:

```javascript
if (qualcosa){
  return true
}
```

</pre>

Esistono molti modi diversi per scrivere codice di programmazione con il markdown in GitHub. Se dovete utilizzare blocchi di codice inline, includeteli tra apici inversi: `var esempio = true`. Se avete un blocco di codice più lungo potete indentare con quattro spazi:

    if (condizione){
      return true
    }

GitHub supporta anche qualcosa chiamato “recinzione del codice”, che consente di inserire più linee senza indentazione:

```
if (qualcosa){
  return true
}
```

E desiderate evidenziare con colori una particolare sintassi includete il linguaggio di programmazione usato:

```javascript
if (qualcosa){
  return true
}
```

### Extra

<pre>

GitHub supporta molte funzionalità extra in Markdown che vi aiuteranno a fare riferimenti a persone con link. Se volete fare un commento diretto ad una persona potete far precedere il nome della persona con un carattere @: Ciao @Michele come stai?

Molto utili le liste di attività:

- [x] Questo è un’azione completata
- [ ] Questo è un’azione non completata

Quando includete una lista di attività all’interno del primo commento di un rilascio della versione del vostro lavoro vedrete un’utile nell’elenco dei problemi. Funziona anche in Pull Requests!

E naturalmente potete usare an che gli emoji! :sparkles: :camel: :boom:

</pre>

GitHub supporta molte funzionalità extra in Markdown che vi aiuteranno a fare riferimenti a persone con link. Se volete fare un commento diretto ad una persona potete far precedere il nome della persona con un carattere @: Ciao @Michele come stai?

Molto utili le liste di attività:

- [x] Questo è un’azione completata
- [ ] Questo è un’azione non completata

Quando includete una lista di attività all’interno del primo commento di un rilascio della versione del vostro lavoro vedrete un’utile nell’elenco dei problemi. Funziona anche in Pull Requests!

E naturalmente potete usare an che gli emoji! :sparkles: :camel: :boom:

### Guida alla sintassi

Di seguito una panoramica della sintassi Markdown che potete utilizzare ovunque su GitHub.com o nei vostri file di testo.

### Titoli

<pre>
# Questo è un tag <h1>
## Questo è un tag <h2>
###### Questo è un tag <h6>
</pre>

### Evidenza

<pre>
*Questo è un testo in italico*
_Questo è anche un testo in italico_

**Questo è un testo in grassetto**
__Questo è un testo in grassetto__

_Potete **combinare** le due cose_
</pre>

### Liste

#### Liste non ordinate

<pre>
* Elemento 1
* Elemento 2
  * Elemento 2a
  * Elemento 2b
</pre>

#### Liste ordinate

<pre>
1. Elemento 1
1. Elemento 2
1. Elemento 3
   1. Elemento 3a
   1. Elemento 3b
</pre>

### Immagini

<pre>
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
</pre>

### Link

<pre>
http://github.com - automatic!
[GitHub](http://github.com)
</pre>

### Blockquotes

<pre>
Spock disse:

> Imparerai , forse , che posseder 
> non è così importante come desiderare 
</pre>

### Codice Inline

<pre>
Penso che dovresti usare
In questo punto un elemento `<addr>`.
</pre>

### GitHub Flavored Markdown

GitHub.com utilizza una propria versione della sintassi Markdown che fornisce un set aggiuntivo di funzioni utili, molte delle quali rendono più facile lavorare con i contenuti su GitHub.com.

Nota che alcune funzionalità di GitHub Flavored Markdown sono disponibili solo nelle descrizioni e nei commenti di Issues e nelle Pull Requests. Questi includono @mentions e riferimenti agli hash SHA-1. Gli elenchi attività sono inoltre disponibili nei commenti Gist e nei file Gist Markdown.

### Evidenziazione della sintassi

Ecco un esempio di come puoi utilizzare l'evidenziazione della sintassi con GitHub Flavored Markdown (https://help.github.com/articles/basic-writing-and-formatting-syntax/):

<pre>
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
</pre>

Potete anche indentare il codice con quattro spazi:

<pre>
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
</pre>

Ecco un esempio di codice Python senza evidenziazione della sintassi:

<pre>
def foo():
    if not bar:
        return True
</pre>

### Elenchi di attività

<pre>
- [x] supporto di @mentions, #refs, [links](), **formatting** e <del>tag</del>
- [x] lista (supportato qualsiasi elenco non ordinato o ordinato)
- [x] Questa è un’attività completata
- [ ] Questa è un’attività non completata
</pre>

Se includete un elenco di attività nel primo commento di un rilascio, otterrete un’utile indicatore di progresso nell'elenco dei rilasci. Funziona anche nella Pull Requests!

### Tabelle

Potete creare tabelle unendo un elenco di parole divise con trattini - (per la prima riga) e quindi separando ciascuna colonna con una pipe |:

<pre>
Prima intestazione | Seconda intestazione
------------ | -------------
Contenuta della cella 1 | Contenuta della cellal 2
Contenuto prima colonna | Contenuto seconda colonna
</pre>

diventa

Prima intestazione | Seconda intestazione
------------ | -------------
Contenuta della cella 1 | Contenuta della cellal 2
Contenuto prima colonna | Contenuto seconda colonna

### Riferimenti SHA

Qualsiasi riferimento all'hash SHA-1 di un commit verrà automaticamente convertito in un link a quel commit su GitHub.

Emettere rilasci all'interno di un repository

Qualsiasi numero che fa riferimento a un numero o una richiesta di pull verrà automaticamente convertito in un link.

<pre>
#1
mojombo#1
mojombo/github-flavored-markdown#1
</pre>

### Username @menzione

Digitando un simbolo @, seguito da un nome utente, notificherà quella persona che è stata menzionata nel commento in questo modo l’utente menzionato potrà vedere il commento in cui è stato menzionato. Questo è chiamato "@mention", perché state citando la persona. Potete  anche @menzionare un team all'interno di un'organizzazione.

### Collegamento automatico per URL

Qualsiasi URL (come http://www.github.com/) verrà automaticamente convertito in un link cliccabile.

### Testo barrato

Ogni parola inclusa tra due tilde (come ~~ this ~~) apparirà barrata.

### Emoji

GitHub supporta le emoji!

Per vedere un elenco di tutte le immagini supportate, controlla  l’Emoji Cheat (https://www.webpagefx.com/tools/emoji-cheat-sheet/)
