# Riflessioni sparse

Ciao a tutti,  
io non ho insegnato nella sperimentale negli anni scorsi.  
Vorrei condividere con voi la visione che ho riguardo questo argomento, che deriva mettendo insieme l'esperienza dei corsi Python insegnati all'università verso le scuole superiori (circa 17 edizioni dal 2020), il corso regionale Engim di Tecnico Sviluppo Software in cui sono docente Java (dal 2019), il corso regionale Tecnico Sviluppo Web in cui ho insegnato Javascript (dal 2023), l'esperienza in TIN l'anno scorso e quanto ho visto nella sperimentale 3S in cui sto facendo informatica ora.  

Ne ho un po' parlato anche con altri/e colleghi/e, e siamo dell'idea che abbiamo una grossa opportunità per proporre qualcosa di innovativo. 
L'obiettivo da raggiungere è che al termine dei quattro anni i ragazzi possano avere l'opportunità di essere presi a fare un tirocinio in azienda informatica, ITS o per i più portati essere pronti per l'università.  
Non tutti però faranno l'università. Credo quindi che l'ideale sarebbe di dare **l'opportunità anche a quei ragazzi di livello intermedio di poter lavorare**. Per riuscire a raggiungere questo obiettivo credo che la scuola dovrebbe essere più vicina ai trend delle **tecnologie moderne**.  
Tralascerei momentaneamente il discorso dei lavori moderni che esistono che non includono la programmazione (creazione di siti web tramite CMS, Social media manager, SEO specialist, ecc).  

Vi riporto un po' di idee che ho trovato, e che magari possono alimentare la discussione.

- Per quanto riguarda il lavoro di programmatore *[questi](https://survey.stackoverflow.co/2024/technology#most-popular-technologies-language)* sono i linguaggi più utilizzati nel 2024.  
Al primo posto c'è Javascript, che però ritorna di nuovo al quinto posto con TypeScript. HTML e CSS sono insieme a JS. Quindi in tre posizioni tra le prime cinque abbiamo i linguaggi del web. In effetti, tra le professioni più praticate ci sono i Full stack developer (fonte: [qui](https://survey.stackoverflow.co/2024/developer-profile/#developer-roles)). [Qui](https://octoverse.github.com/2022/top-programming-languages) altra statistica da github ferma al 2022.
- Il corso professionalizzante Tecnico sviluppo sw (corso per disoccupati regionale che riesce a far trovare lavoro a molti partecipanti) insegna Java (Spring), Javascript, React, PHP (accenno), Python (accenno), SQL.
- All'Università di Torino, al Dipartimento di Informatica, hanno smesso di insegnare Java come primo linguaggio degli esami Programmazione I e Programmazione II e sono passati a C.
- Il 61% dei programmatori usa l'AI (fonte: [qui](https://survey.stackoverflow.co/2024/ai/)).
- Secondo uno studio di StackOverFlow, il 93% degli sviluppatori utilizza git (fonte 2023: [qui](https://stackoverflow.blog/2023/01/09/beyond-git-the-other-version-control-systems-developers-use/)).
- PHP non viene insegnato al Dipartimento di Informatica nei corsi obbligatori, solo in un corso a scelta.

Mettendo insieme tutte queste informazioni, noto due possibili filoni da percorrere: quella dell'insegnamento di un linguaggio rigoroso (C, come la scelta del DipInfo), in cui per scrivere un for con un array bisogna far attenzione a tantissime nozioni, puntatori, malloc ecc oppure quella di provare a insegnare linguaggi molto facilmente spendibili sul mondo del lavoro (JavaScript e Python).  

Io sono combattuto su quale sia la scelta giusta. La mia esperienza passata è stata questa: ho fatto alle superiori Java, all'università Java + C solo per un esame, da auto didatta python, Javascript al terzo anno, React in un esame magistrale. Php mai visto.  
In 13 anni di programmazione oltre all'esame di C non ho mai dovuto scrivere una riga di C. Non so però dire se grazie a C (e le sue sofferenze) sono riuscito ad imparare Python da autodidatta.  
Nei corsi Python di orientamento per il Dipartimento di Informatica dell'Università, in 15 ore riusciamo a spiegare da zero agli oggetti. Con C penso che si arriverebbe malapena ai puntatori nello stesso tempo. 
Su Java, nonostante sia il mio linguaggio nativo, ho come l'impressione che farà la fine di Php. Anche Java è un bel linguaggio perché fortemente tipizzato, quindi aiuta ad essere precisi e a creare la forma mentis giusta, ma credo che stia cominciando a perdere di popolarità. Php nella classifica è 11esimo.  

Se dovessi fare un progetto oggi, penso quindi che userei backend Python oppure NodeJS e frontend React senza pensarci due volte.  

PHP vive ancora grazie ai CMS, che hanno comunque una buona quota di mercato dei siti web.  

- il 68% dei siti utilizza un CMS, di cui Wordpress ha la quota maggiore (63%) (fonte : [qui](https://www.wpbeginner.com/research/cms-market-share-report-latest-trends-and-usage-stats/) e [qui](https://codexpert.io/cms-market-share/)). A seguire Shopify (9%), Wix e Squarespace (3%), Joomla (2,4%), Drupal (1,8%).

È però anche vero che in 5 anni che uso Wordpress in modo professionale (per clienti), avrò fatto copia e incolla di php di un paio di righe da internet un paio di volte per attivare qualcosa. Il 90% dei task si risolve con un Builder o con Javascript.  

Queste riflessioni sul **mio uso personale** (che quindi possono essere sbagliate e non sono da prendere come regola) e sulle statistiche succitate, mi farebbero mettere in discussione anche PHP oltre a C.  
E la seconda prova informatica non cita mai PHP, dice "Utilizzando linguaggi a scelta client e server".  

In sostanza, dopo tutti questi ragionamenti, mi sentirei di dire che la mia idea sarebbe la seguente: 

- introdurre git sia nei progetti di informatica che nei progetti collaborativi (che magari si potrebbero fare in GPOI). Lo utilizza il 93% dei sviluppatori, credo sia molto utile per loro uscire da qui che lo conoscano. **Sarebbe auspicabile che sia installato nativamente (e non portable version) in ogni macchina presente a scuola**, laboratori portatili compreso, anche configurando le impostazioni del proxy. In modo che ogni ragazzo, in qualsiasi laboratorio si trovi possa fare una clone e continuare a lavorare. Anche se purtroppo viene assegnato in B20 :) Magari introdurlo dalla seconda S in poi, in modo da dar loro 3 anni per esercitarsi ad usarlo. Le consegne, a mio parere, dovrebbero essere fatte tramite commit, evitando così zip volanti che si dimenticano di salvare, che hanno lasciato in C23 ma ora siamo in B26 ecc... Eventualmente installare un software che aiuti nell'utilizzo di git tipo Sublime Merge. Sia questo che la gestione di Git da Code funziona solo con git nativo. Git portable non viene riconosciuto. Nei laboratori con linux c'è la necessità che sia installato anche un gestore delle credenziali di git (gcm).
- a mio parere è molto importante che escano dalla scuola che sappiano usare Javascript. È un linguaggio standard di fatto per il front end, anche utilizzato per il back end.
- dovrebbero imparare SQL, molto utilizzato e fa parte dell'esame di Stato.
- c'è da scegliere tra Python e C. In python si riesce anche a fare molto bene la parte di backend. In C viene molto bene la parte di fork e join. Nei quattro anni si potrebbe anche fare entrambi, è da capire quando fare cosa, e chi.
- darei la parte di requisiti SW, documentazione SW, gestione del progetto (TPSI di terza e quarta fine libro che io per esempio non riesco mai a fare) a GPOI che ora ha più anni. TPSI con meno carico magari potrebbe insegnare C insieme alle fork e quella parte. Quindi rimarrebbe Python come linguaggio primario in informatica per iniziare a programmare e poi Javascript subito dopo, con obiettivo in quarta S di mettere tutto insieme, fare una full stack application con SQL, Python, React e progetti integrati anche con GPOI.  
Quindi potrebbe essere: 1° Python, 2° Javascript, 3° React, 4° tutto insieme.
- Sottolineerei ai ragazzi l'importanza nell'imparare l'utilizzo delle AI in modo costruttivo e consapevole. Se lo usano per generare le consegne nessuno li assumerà, sono facilmente sostituibili da ChatGPT e non imparano nulla. Se lo usano invece per imparare, usarlo come spiegazione invece è utile.
- Utilizzerei la metodologia PRIMM per insegnare le parti più difficili: https://fablab.unitn.it/sperimentazione-primm/ 

In questo messaggio, ho escluso come da premessa tutti gli altri lavori (sistemista e quindi gli argomenti di SER, CMS ecc) per concentrarmi solo sui linguaggi di programmazione.

Ci tenevo a condividere con voi queste riflessioni, perché penso che possano essere utili ai nostri studenti e perché ho a cuore il loro futuro: in un momento in cui stanno nascendo nuovi strumenti (tipo ChatGPT) penso sia importante aiutarli ad essere il più allineati possibili con le richieste che il mondo del lavoro di oggi chiede. Spero che possano nascere delle riflessioni costruttive e mi piacerebbe sapere cosa ne pensate anche voi.
