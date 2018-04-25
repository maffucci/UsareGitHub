Le pagine GitHub sono pagine Web che possono essere facilmente realizzate e pubblicate tramite GitHub. Il modo più rapido per iniziare a creare pagine è quello di utilizzare il selettore di temi di Jekyll per caricare un tema preimpostato. Sarà possibile modificare il contenuto e lo stile delle pagine  GitHub da remoto tramite Web o localmente sul computer.

![pagina realizzata con GitHub](https://guides.github.com/features/pages/pages-home-page.png)

**Realizzare il primo sito web**

Il primo passo sarà quello di registrarsi su GitHub e creare un nuovo repository.

![creare un nuovo repository](https://guides.github.com/features/pages/create-new-repo-button.png)

Nella schermata che seguirà bisognerà assegnare un nome al repository per generare un nuovo sito web.

![assegnare un nome al nuovo repository](https://guides.github.com/features/pages/create-new-repo-screen.png)

I file del sito web risiederanno su un repository che avrà come indirizzo `username.github.io` (dove "username" è il vostro nome utente su GitHub quello scelto all’atto della registrazione ).

Per incominciare a configurare il sito bisogna aprire la scheda  Settings

![scheda settings](https://guides.github.com/features/pages/create-new-repo-screen.png)

Se andate verso il basso nella pagina delle impostazioni, troverete in basso la sezione **GitHub Pages**, fate click sul pulsante **Choose a them** per la scelta del tema grafico, in questo modo potrete incominciare il processo di creazione del sito.

![creazione del sito](https://guides.github.com/features/pages/launch-theme-chooser.png)

Dopo aver fatto clic sul pulsante, sarete reindirizzati sulla scelta dei temi. Vedrete diverse opzioni del tema e nella parte superiore della pagina potrete selezionarne un tema tra quelli disponibili per vederne un’anteprima applicata alle nostre pagine. Una volta selezionato, fai clic su **Select theme** a destra per andare avanti. Sarà possibile modificare facilmente il tema in una fase successiva.

![scelta del tema grafico](https://guides.github.com/features/pages/theme-chooser.png)

Ora potete scrivere i vostri contenuti. Questa parte richiede un po' più di tempo, ma per ora, se lo desiderate, potrete mantenere il contenuto predefinito.

![pagina iniziale del sito](https://guides.github.com/features/pages/code-editor.png)

Al termine della modifica, andate fino alla fine della pagina e fate click su **Commit changes**.

![conferma dei cambiamenti](https://guides.github.com/features/pages/commit-edits.png)

GitHub farà in modo che i visitatori giungano sul sito all'indirizzo:  `username.github.io`, questa operazione di messa on-line definitiva del sito può richiedere fino ad un massimo di 10 minuti, dopo di che potrete aprire una nuova finestra del vostro browser per andare sul vostro nuovo sito!

**Fare cambiamenti**

Tra le prime attività da eseguire vi è quello di rimozione del titolo predefinito della pagina principale e l'aggiunta di un testo contestuale all’argomento che state sviluppando, questo cambiamento è estremamente veloce e potete farlo dal branch `master`.

Accedendo alla sezione **Code** selezionando il file  `_config.yml`  e poi facendo click sull’icona matita potete modificarne il contenuto.

![modifica pagina](https://guides.github.com/features/pages/edit-file.png)

Appena il sito viene creato non possiede un titolo e per cambiarlo dovrete aggiungere al file `_config.yml` il testo "titolo: Benvenuto nella homepage di Octocat!” o quello che desiderate ad esclusione della modifica del vostro username.

Sotto questo titolo, potete aggiungere un messaggio sullo scopo della pagina e descrivere cosa potranno fare gli utenti. Potrete ad esempio aggiungere con il camo **description** il messaggio: "Sentiti libero di aggiungere questa pagina ai tuoi bookmark per tenere d'occhio gli aggiornamenti del progetto"

![modifica pagina](https://guides.github.com/features/pages/change-title-description.png)

Dopo aver eseguito poche modifiche, andate fino alla fine della pagina per eseguire il secondo commit. Per eseguire il commit dovrete descrivere un titolo comprensibile sulla variazione esguita sulla pagina e in modo facoltativo anche una descrizione più estesa sulle operazioni eseguite sulla pagina.

Quando avete finito, fate click su **Commit changes** e i vostri aggiornamenti verranno pubblicati in pochi secondi!

![pubblicazione della pagina](https://guides.github.com/features/pages/commit-messages-matter.png)