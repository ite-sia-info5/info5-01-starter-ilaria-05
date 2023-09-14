# :wave: Le Basi di GitHub 

## 🤓 Panoramica della lezione 

L'obiettivo di questa lezione è fornire una breve introduzione a GitHub. Forniremo anche materiale per un ulteriore apprendimento e alcune idee per iniziare a lavorare sulla piattaforma. 🚀

## :octocat: Git e GitHub

Git è un **Sistema di Controllo Versione Distribuito (VCS)**, ciò significa che è uno strumento utile per monitorare facilmente le modifiche al tuo codice, collaborare e condividere. Con Git puoi tracciare le modifiche che apporti al tuo progetto in modo da avere sempre una registrazione di ciò su cui hai lavorato e puoi facilmente tornare a una versione precedente se necessario. Rende anche più facile lavorare con altri: gruppi di persone possono lavorare insieme sullo stesso progetto e unire le loro modifiche in un singolo sorgente finale!

GitHub è un modo per utilizzare la stessa potenza di Git online con un'interfaccia facile da usare. Viene utilizzato in tutto il mondo del software, e anche in altri contesti, per collaborare e mantenere la storia dei progetti.

GitHub ospita alcune delle tecnologie più avanzate al mondo. Che tu stia visualizzando dati o creando un nuovo gioco, c'è una comunità e un insieme di strumenti su GitHub che possono portarti al passo successivo. Questa lezione inizia con le basi di GitHub, ma approfondiremo il resto in seguito.

## :octocat: Comprendere il flusso di GitHub 

Il flusso di GitHub è un flusso di lavoro leggero che ti permette di sperimentare e collaborare facilmente ai tuoi progetti, senza il rischio di perdere il tuo lavoro precedente.

### Repository

Un repository è dove avviene il lavoro del tuo progetto, pensa ad esso come alla cartella del tuo progetto. Contiene tutti i file e la cronologia delle revisioni del tuo progetto. Puoi lavorare all'interno di un repository da solo o invitare altri a collaborare con te su quei file.

### Clonazione 

Quando un repository viene creato con GitHub, è memorizzato in remoto nel cloud ☁️. Puoi clonare un repository per creare una copia locale sul tuo computer e poi usare Git per sincronizzare i due. Ciò rende più facile risolvere problemi, aggiungere o rimuovere file e effettuare commit di dimensioni maggiori. Puoi anche usare lo strumento di modifica che preferisci al posto dell'interfaccia utente di GitHub. Clonare un repository scarica anche tutti i dati del repository che GitHub ha in quel momento, inclusa ogni versione di ogni file e cartella per il progetto! Questo può essere utile se sperimenti con il tuo progetto e poi ti rendi conto che preferivi una versione precedente. 
Per saperne di più sulla clonazione, leggi ["Clonare un Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Fare commit e push
**Fare commit** e **push** sono i modi per aggiungere le modifiche che hai fatto sulla tua macchina locale al repository remoto in GitHub. In questo modo il tuo insegnante e/o i tuoi compagni possono vedere il tuo lavoro più recente quando sei pronto a condividerlo. Puoi fare un commit quando hai apportato modifiche al tuo progetto che vuoi "contrassegnare". Puoi anche aggiungere un **messaggio di commit** utile per ricordare a te stesso o ai tuoi compagni quale lavoro hai fatto (ad es. "Aggiunto un README con informazioni sul nostro progetto").

Una volta che hai un commit o più commit che sei pronto ad aggiungere al tuo repository, puoi usare il comando push per aggiungere quelle modifiche al tuo repository remoto. Fare commit e push potrebbe sembrare nuovo all'inizio, ma ti promettiamo che ti ci abituerai 🙂

## 💻 Termini di GitHub da conoscere 

### Repository 
Abbiamo già parlato dei repository, sono il luogo dove avviene il lavoro del tuo progetto, ma parliamo un po' di più dei dettagli! Man mano che lavori di più su GitHub avrai molti repository, che potrebbero sembrare confusi all'inizio. Fortunatamente, la tua ["dashboard di GitHub"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) aiuta a navigare facilmente verso i tuoi repository e a vedere informazioni utili su di essi. Assicurati di aver effettuato l'accesso per vederlo!

I repository contengono anche **README**. Puoi aggiungere un file README al tuo repository per dire ad altre persone perché il tuo progetto è utile, cosa possono fare con il tuo progetto e come possono usarlo. Stiamo usando proprio un README ora, per insegnarti Git e GitHub. 😄 
Per saperne di più sui repository leggi ["Creare, Clonare e Archiviare Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Informazioni sui README"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branch
Puoi usare i branch su GitHub per isolare il lavoro che non vuoi ancora unire nel tuo progetto finale. I branch ti permettono di sviluppare funzionalità, correggere bug o sperimentare in sicurezza con nuove idee in una parte contenuta del tuo repository. Tipicamente, potresti creare un nuovo branch dal branch predefinito del tuo repository (che si chiama `main`). Questo crea una nuova copia del tuo repository con cui puoi sperimentare. Una volta che le tue nuove modifiche sono state esaminate da un compagno di squadra, o sei soddisfatto di esse, puoi unire le tue modifiche nel branch predefinito del tuo repository.
Per saperne di più sui branch, leggi ["Informazioni sui Branch"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Fork
Un fork è un altro modo per copiare un repository, ma viene solitamente utilizzato quando si desidera contribuire al progetto di qualcun altro. Fare il fork di un repository ti permette di sperimentare liberamente con le modifiche senza influenzare il progetto originale ed è molto popolare quando si contribuisce ai progetti software open source!
Per saperne di più sul forking, leggi ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull requests
Quando lavori con i branch, puoi utilizzare una pull request per informare gli altri delle modifiche che desideri apportare e chiedere il loro feedback. Una volta aperta una pull request, puoi discutere e rivedere le possibili modifiche con i collaboratori e aggiungere altre modifiche se necessario. Puoi aggiungere persone specifiche come revisori della tua pull request, mostrando che desideri il loro feedback sulle tue modifiche! Una volta che una pull request è pronta per essere utilizzata, può essere unita al tuo branch principale.
Per saperne di più sulle pull request, leggi ["Informazioni sulle Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issue
Gli issue sono un modo per tenere traccia di miglioramenti, compiti o bug per il tuo lavoro su GitHub. Gli issue sono un ottimo modo per tenere traccia di tutti i compiti su cui desideri lavorare per il tuo progetto e far sapere agli altri quello che prevedi di fare. Puoi anche utilizzare gli issues per informare gli sviluppatori di un progetto open source in merito a un bug che hai trovato o una funzionalità che sarebbe bello aggiungere!

Per progetti più grandi, puoi tenere traccia di molti issue su una bacheca del progetto. I progetti GitHub ti aiutano a organizzare e dare priorità al tuo lavoro e puoi saperne di più su di essi [in questo documento "Informazioni sulle bacheche di progetto"](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Probabilmente non avrai bisogno di una bacheca di progetto per i tuoi compiti, ma una volta che passerai a progetti ancora più grandi, sono un ottimo modo per organizzare il lavoro del tuo team!
Puoi anche collegare le pull request e gli issue per mostrare che una correzione è in corso e per chiudere automaticamente l'issue quando qualcuno unisce la pull request.
Per saperne di più sugli issues e su come collegarli alle tue pull request, leggi ["Informazioni sugli Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Il tuo profilo utente

La pagina del tuo profilo racconta alle persone la storia del tuo lavoro attraverso i repository di cui ti interessa, i contributi che hai fatto e le conversazioni che hai avuto. Puoi anche offrire al mondo una visione unica di chi sei con il tuo README di profilo. Puoi utilizzare il tuo profilo per far sapere ai futuri datori di lavoro tutto su di te!
Per saperne di più sul tuo profilo utente e su come aggiungere e aggiornare il tuo README di profilo, leggi ["Gestione del tuo Profilo README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Utilizzo del markdown su GitHub

Potresti averlo già notato, ma puoi aggiungere alcuni stili divertenti ai tuoi issue, pull request e file. Il ["Markdown"](https://guides.github.com/features/mastering-markdown/) è un modo semplice per stilizzare i tuoi issue, pull request e file con una sintassi semplice. Questo può essere utile per organizzare le tue informazioni e renderle più facili da leggere. Puoi anche inserire gif e immagini per aiutare a trasmettere il tuo punto di vista!
Per saperne di più sull'utilizzo del markdown di GitHub, leggi ["Sintassi di Scrittura e Formattazione di Base"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interagire con la community di GitHub

La community di GitHub è vasta. Ci sono molti tipi di persone che utilizzano GitHub nella loro vita quotidiana: studenti come te, sviluppatori professionisti, appassionati che lavorano su progetti open source e sperimentatori che stanno appena iniziando nel mondo dello sviluppo software da soli. Ci sono molti modi in cui puoi interagire con la più ampia community di GitHub, ma ecco tre posti dove puoi iniziare.

#### Stelline ai repository

Se trovi interessante un repository o vuoi tenerne traccia, dagli una stellina! Quando dai una stellina a un repository, viene anche utilizzato come segnale per mostrare migliori raccomandazioni su github.com/explore. Se desideri tornare ai tuoi repository con stellina, puoi farlo tramite il tuo profilo utente.
Per saperne di più sul dare stelline ai repository, leggi ["Salvare i Repository con Stelle"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars).

#### Seguire gli utenti

Puoi seguire persone su GitHub per ricevere notifiche sulla loro attività e scoprire progetti nelle loro community. Quando segui un utente, la sua attività pubblica su GitHub apparirà sulla tua dashboard in modo da poter vedere tutte le cose interessanti su cui stanno lavorando.
Per saperne di più sul seguire gli utenti, leggi ["Seguire le persone"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Esplorare GitHub Explore

GitHub Explore è un ottimo posto per fare proprio questo... esplorare :smile: Puoi trovare nuovi progetti, eventi e sviluppatori con cui interagire.

Puoi dare un'occhiata al sito web di GitHub Explore [su github.com/explore](https://github.com/explore). Più interagisci con GitHub, più la tua vista di Explore sarà personalizzata.

## 📝 Passi successivi

* Apri una pull request e informa il tuo insegnante che hai completato questo corso.
* Crea un nuovo file markdown in questo repository. Fai sapere a tutti cosa hai imparato e su cosa hai ancora dubbi! Sperimenta con stili diversi!
* Crea il tuo README di profilo. Fai sapere al mondo un po' di più su di te! Cosa ti interessa imparare? Su cosa stai lavorando? Qual è il tuo hobby preferito? Scopri di più sulla creazione del tuo README di profilo nel documento, ["Gestione del tuo Profilo README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Vai alla tua dashboard utente e crea un nuovo repository. Sperimenta con le funzioni all'interno di quel repository per familiarizzare con esse.
* [Facci sapere cosa ti è piaciuto o non ti è piaciuto del contenuto di questo corso](https://support.github.com/contact/education). Cosa ti piacerebbe vedere di più? Cosa sarebbe interessante o utile per il tuo percorso di apprendimento?

## 📚 Risorse
* [Un breve video che spiega cos'è GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Risorse di apprendimento su Git e GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Comprendere il flusso di GitHub](https://guides.github.com/introduction/flow/)
* [Come utilizzare i branch di GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiali di formazione interattivi su Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [Il Laboratorio di Apprendimento di GitHub](https://lab.github.com/)
* [Forum della comunità educativa](https://education.github.community/)
* [Forum della comunità di GitHub](https://github.community/)
