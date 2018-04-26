<img class="aligncenter size-full wp-image-8747" alt="markdown" src="http://www.maffucci.it/wp-content/uploads/2013/08/markdown.jpg" width="640" height="108" />

<strong>Cos'è il Markdown?</strong>

Tutto nasce dall'esigenza di poter scrivere in ogni luogo con qualsiasi strumento, in modo rapido, senza vincoli tecnologici legati allo strumetto hardware o software, in breve concentrarsi sul contenuto.

Markdown è un linguaggio di markup creato da <strong>John Gruber</strong> e <strong>Aaron Swartz</strong> che consente a blogger e scrittori di ogni tipo di scrivere testi in maniera veloce utilizzando una sintassi estremamente semplice ed efficace permettendo poi di convertire i testi in (X)HTML immediatamente fruibile senza la paura di dimenticare la chiusura di tag HTML o fare errori di scrittura di tag.

<!--more-->Se questo motivo non vi bastano vi rimando alla brillante e rapidissima spiegazione di Brett Terpstra che con il suo articolo: "<em><a href="http://brettterpstra.com/2011/08/31/why-markdown-a-two-minute-explanation/">Why Markdown? A two-minute explanation</a></em>" ci illustra i suoi motivi, che condivido pienamente:
<ul>
	<li>è semplice;</li>
	<li>è veloce;</li>
	<li>è pulito;</li>
	<li>è mobile;</li>
	<li>è flessibile;</li>
	<li>si adatta ad ogni flusso di lavoro.</li>
</ul>
<strong>Ma come imparare ad usare Markdown?</strong>

Basta andare alla fonte, sul blog <strong>Daring Fireball</strong> (di <strong>John Gruber</strong>), troverete le <a href="http://daringfireball.net/projects/markdown/">basi</a> per imparare in 10 minuti tutto e nella sezione <a href="http://daringfireball.net/projects/markdown/syntax">Syntax</a> la sintassi completa.

Come ho scritto questo post? Usando la notazione Markdown :-)

Di seguito il tutorial tratto dal sito <strong>Daring Fireball</strong>.

<strong>Tutorial</strong>

<strong><em>Markdown:</em></strong>
<pre>Primo livello di intestazione
=============================

Secondo livello di intestazione
-------------------------------

Laoreet accumsan, ullamcorper iriure suscipit commodo dolore
iusto ea blandit accumsan illum amet nostrud autem ipsum
tincidunt at blandit.

Vulputate, nulla enim dolore nostrud qui eu nisl tation facilisi
minim lorem, ut commodo qui. Luptatum augue magna aliquip nonummy
dolore quis eu, ut molestie eum nostrud.

### Header 3

&gt; Questa è una blockquote.
&gt;
&gt; Questo è il secondo paragrafo nel blockquote.
&gt;
&gt; # # Questo è un H2 in un blockquote</pre>
<strong>Risultato</strong>:
<pre>&lt;h1&gt;Primo livello di intestazione&lt;/h1&gt;

&lt;h2&gt;Secondo livello di intestazione&lt;/h2&gt;

&lt;p&gt;Laoreet accumsan, ullamcorper iriure suscipit commodo
dolore iusto ea blandit accumsan illum amet nostrud autem
ipsum tincidunt at blandit.
&lt;/p&gt;

&lt;p&gt;Vulputate, nulla enim dolore nostrud qui eu nisl
tation facilisi minim lorem, ut commodo qui. Luptatum augue
magna aliquip nonummy dolore quis eu, ut molestie
eum nostrud.&lt;/p&gt;

&lt;h3&gt;Header 3&lt;/h3&gt;

&lt;blockquote&gt;
&lt;p&gt;questo è un blockquote.&lt;/p&gt;

&lt;p&gt;Questo è il secondo paragrafo del blockquote.&lt;/p&gt;

&lt;h2&gt;Questo è un H2 nel blockquote.&lt;/h2&gt;
&lt;/blockquote&gt;</pre>
<strong>Enfatizzare</strong>

Markdown usa asterischi e sottolineato per enfatizzare il testo

<strong>Markdown:</strong>
<pre>Alcune di queste parole *sono enfatizzate*.
Anche queste parole _sono enfatizzate_.</pre>
<pre>Usa due asterischi per **scrivere in grassetto**.
o se preferisci, __usa due underscore__.</pre>
<strong>Risultato:</strong>
<pre>&lt;p&gt;Alcune di queste parole &lt;em&gt;sono enfatizzate&lt;/em&gt;.
Anche queste parole &lt;em&gt;sono enfatizzate&lt;/em&gt;.&lt;/p&gt;

&lt;p&gt;Usa due asterischi per &lt;strong&gt;scrivere in grassetto&lt;/strong&gt;.

o se preferisci, &lt;strong&gt;usa due underscore&lt;/strong&gt;.&lt;/p&gt;</pre>
<strong>Liste</strong>

Per realizzare le liste non ordinate (liste puntate) usa asterischi, segno + o trattino (*, + e -) come marker. Questi tre simboli sono interscambiabili:
<pre>* Candy.
* Gum.
* Booze.</pre>
Oppure:
<pre>+ Candy.
+ Gum.
+ Booze.</pre>
Oppure:
<pre>- Candy.
- Gum.
- Booze.</pre>
Tutti producono lo stesso risultato:
<pre>&lt;ul&gt;
&lt;li&gt;Candy.&lt;/li&gt;
&lt;li&gt;Gum.&lt;/li&gt;
&lt;li&gt;Booze.&lt;/li&gt;
&lt;/ul&gt;</pre>
Le liste ordinate (ordinate) usano come marker numeri seguiti da un punto:
<pre>1. Red
2. Green
3. Blue</pre>
Risultato:
<pre>&lt;ol&gt;
&lt;li&gt;Red&lt;/li&gt;
&lt;li&gt;Green&lt;/li&gt;
&lt;li&gt;Blue&lt;/li&gt;
&lt;/ol&gt;</pre>
Se inserite righe vuote tra gli elementi inserirete un paragrafo &lt;p&gt; tra gli elementi. E' possibile creare un lista di paragrafi identando con 4 spazio oppure un tab ogni singolo elemento della lista
<pre>* un elemento della lista.

  Con più paragrafi.

* un altro elemento della lista.</pre>
Risultato:
<pre>&lt;ul&gt;
&lt;li&gt;&lt;p&gt;un elemento della lista.&lt;/p&gt;
&lt;p&gt;Con più paragrafi.&lt;/p&gt;&lt;/li&gt;
&lt;li&gt;&lt;p&gt;un altro elemento della lista.&lt;/p&gt;&lt;/li&gt;
&lt;/ul&gt;</pre>
Markdown supporta due stili per la creazione di link: <em>inline</em> e <em>reference</em>. Con entrambi gli stili, è possibile utilizzare le parentesi quadre per delimitare il testo che si desidera trasformare in un link.

Lo stile <em>inline</em> dei link usa le parentesi immediatamente dopo il testo del link.

Esempio:
<pre>Questo è un [esempio di link](http://example.com/).</pre>
Risultato:
<pre>&lt;p&gt;Questo è un &lt;a href="http://example.com/"&gt;
esempio di link&lt;/a&gt;.&lt;/p&gt;</pre>
Opzionalmente, potete includere l'attributo <em>title</em> tra le parentesi tonde dopo il link:
<pre>Questo è un [esempio di link](http://example.com/ "Con un titolo").</pre>
Risultato:
<pre>&lt;p&gt;Questo è un &lt;a href="http://example.com/" title="Con un titolo"&gt;
esempio di link&lt;/a&gt;.&lt;/p&gt;</pre>
Lo stile <em>reference</em> dei link consente di fare riferimento al link con dei nomi definiti in un altro punto del documento:
<pre>Fai la tua sceltra tra: [Google][1], 
[Yahoo][2] o [MSN][3].

[1]: http://google.com/ "Google"
[2]: http://search.yahoo.com/ "Yahoo Search"
[3]: http://search.msn.com/ "MSN Search"</pre>
Risultato:
<pre>&lt;p&gt;Fai la tua sceltra tra: &lt;a href="http://google.com/"
title="Google"&gt;Google&lt;/a&gt;, &lt;a href="http://search.yahoo.com/"
title="Yahoo Search"&gt;Yahoo&lt;/a&gt; o &lt;a href="http://search.msn.com/"
title="MSN Search"&gt;MSN&lt;/a&gt;.&lt;/p&gt;</pre>
L'attributo "<em>title</em>" è facoltativo. I nomi dei collegamenti possono contenere lettere, numeri e spazi, ma non sono case sensitive:
<pre>Incomincio la mia giornata con una tazza di caffè e il 
[The New York Times][NY Times].

[ny times]: http://www.nytimes.com/</pre>
Risultato:
<pre>&lt;p&gt;Incomincio la mia giornata con una tazza di caffè e il 
&lt;a href="http://www.nytimes.com/"&gt;The New York Times&lt;/a&gt;.&lt;/p&gt;</pre>
<strong>Immagini</strong>

La sintassi per le immagini è molto simile a quella dei link.

Inline (i titoli sono opzionali):
<pre>![alt text](/path/to/img.jpg "Titolo")</pre>
Reference-style:
<pre>![alt text][id]

[id]: /path/to/img.jpg "Titolo"</pre>
Entrambi gli esempi di cui sopra producono lo stesso output:
<pre>&lt;img src="/path/to/img.jpg" alt="alt text" title="Titolo" /&gt;</pre>
<strong>CODE</strong>

In un paragrafo normale, è possibile creare una sezione codice includendo il testo tra virgolette inverse. E commerciali (&amp;) e le parentesi angolari (&lt;o&gt;) saranno automaticamente tradotte in entità HTML. Ciò facilita la scrittura di codice HTML in Markdown ad esempio:
<pre>Consiglio vivamente l'uso dei tag `&lt;blink&gt;`.

Usare la notazione `&amp;mdash;` invece che quella decimale: `&amp;#8212;`.</pre>
Risultato:
<pre>&lt;p&gt;Consiglio vivamente l'uso dei tag
&lt;code&gt;&amp;lt;blink&amp;gt;&lt;/code&gt;.&lt;/p&gt;

&lt;p&gt;Usare la notazione
&lt;code&gt;&amp;amp;mdash;&lt;/code&gt; iinvece che quella decimale: &lt;code&gt;&amp;amp;#8212;&lt;/code&gt;.&lt;/p&gt;</pre>
Per specificare un intero blocco di codice pre-formattato, rientrate per ogni riga di 4 spazi o 1 tab.

<strong>Markdown</strong>:
<pre>Se desiderate che la vostra pagina sia valida in XHTML 1.0 Strict,
inserite il blocco paragrafo nel blocco blockquote.

    &lt;blockquote&gt;
        &lt;p&gt;Per esempio.&lt;/p&gt;
    &lt;/blockquote&gt;</pre>
Risultato:
<pre>&lt;p&gt;Se si desidera che la vostra pagina sia valida in XHTML 1.0 Strict,
inserite il blocco paragrafo nel blocco blockquote.&lt;/p&gt;

&lt;pre&gt;&lt;code&gt;&amp;lt;blockquote&amp;gt;
    &amp;lt;p&amp;gt;Per esempio.&amp;lt;/p&amp;gt;
&amp;lt;/blockquote&amp;gt;
&lt;/code&gt;&lt;/pre&gt;</pre>
Cosa uso?
<ul>
	<li>Per Mac, iPad, iPhone: <a href="http://bywordapp.com">byword</a></li>
	<li>Plug-In per Wordpress: <a href="http://wordpress.org/plugins/wp-markdown/">WP-Markdown</a></li>
	<li>On-line: <a href="http://daringfireball.net/projects/markdown/dingus">Dingus</a></li>
</ul>

Esempi

Testo

<pre>
E’ molto semplice scrivere delle parole in **grassetto** ed altre parole in *italico* con Markdown. Puoi anche <span>[fare un link a Google!](http://google.com)</span>
</pre>

E’ molto semplice scrivere delle parole in **grassetto** ed altre parole in *italico* con Markdown. Puoi anche [fare un link a Google!](http://google.com)
