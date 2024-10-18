# Riflessioni sparse

Ciao,  
io non ho fatto la sperimentale negli anni scorsi.  
Parlo quindi per idee che mi sono fatto, mettendo insieme l'esperienza dei corsi Python che ho fatto all'università verso le scuole superiori (circa 15 edizioni dal 2020), il corso regionale Engim di Tecnico Sviluppo Software in cui sono docente Java (dal 2019), il corso regionale Tecnico Sviluppo Web in cui ho insegnato Javascript (dal 2023), l'esperienza in TIN l'anno scorso e quanto ho visto nella sperimentale 3S in cui sto facendo informatica ora.  

Ne ho un po' parlato anche con altri/e colleghi/e, sono dell'idea che abbiamo una grossa opportunità per sperimentare.  
La mia idea è che sarebbe ottimale raggiungere come obiettivo la possibilità che al termine dei quattro anni i ragazzi possano avere l'opportunità di essere presi a fare un tirocinio in azienda informatica, ITS o per i più portati l'università.  

Con l'idea che non tutti debbano fare l'università, credo che l'ideale sarebbe di dare **l'opportunità anche a quei ragazzi di livello intermedio di poter già lavorare**. Per riuscire a raggiungere questo obiettivo quindi credo che la scuola dovrebbe essere più vicina al trend delle **tecnologie moderne**.  
Tralascerei momentaneamente il discorso dei lavori moderni che esistono che non includono la programmazione (creazione di siti web tramite CMS, Social media manager, SEO strategist, ecc).  

Scrivo qui un po' di idee sparse che ho trovato, magari possono alimentare la discussione e aiutare a farsi un'idea.

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
Nei corsi orientamento per DipInfo riesco in 15 ore a fare da zero agli oggetti con Python. Con C penso che arriverei ai puntatori.  
Su Java, nonostante sia il mio linguaggio nativo, ho come l'impressione che farà la fine di Php. Anche Java è un bel linguaggio perché fortemente tipizzato, quindi aiuta ad essere precisi e a creare la forma mentis giusta, ma è indubbio che stia cominciando a perdere di popolarità. Php nella classifica è 11esimo.  

Se dovessi fare un progetto oggi penso che farei backend Python oppure NodeJS e frontend React senza pensarci due volte.  

PHP vive ancora grazie ai CMS, che hanno comunque una buona quota di mercato dei siti web.  

- il 68% dei siti utilizza un CMS, di cui Wordpress ha la quota maggiore (63%) (fonte : [qui](https://www.wpbeginner.com/research/cms-market-share-report-latest-trends-and-usage-stats/) e [qui](https://codexpert.io/cms-market-share/)). A seguire Shopify (9%), Wix e Squarespace (3%), Joomla (2,4%), Drupal (1,8%).

È però anche vero che in 5 anni che uso Wordpress in modo professionale (per clienti), avrò fatto copia e incolla di php di un paio di righe da internet un paio di volte per attivare qualcosa. Il 90% dei task si risolve con un Builder o con Javascript.  

Ora dirò cose un po' impopolari, accetto insulti :) , ma queste riflessioni sul **mio uso personale** (che quindi non possono essere prese come regola) e sulle statistiche, mi farebbero mettere in discussione anche PHP oltre a C.  
E la seconda prova informatica non cita mai PHP, dice "Utilizzando linguaggi a scelta client e server".  

In sostanza, dopo tutti questi ragionamenti, mi sentirei di dire che la mia idea sarebbe la seguente: 

- assolutamente introdurre git sia nei progetti di informatica che nei progetti collaborativi (che magari si potrebbero fare in GPOI). Lo utilizza il 93% dei sviluppatori, non possono uscire da qui che non sanno usarlo. **Deve essere installato nativamente (e non portable version) in ogni macchina presente a scuola**, laboratori portatili compreso. Deve essere installato configurando anche le impostazioni del proxy. In modo che ogni ragazzo, in qualsiasi laboratorio si trovi possa fare una clone e continuare a lavorare. Anche se purtroppo viene assegnato in B20 :) Magari dalla seconda S in poi, ma poi devono esercitarsi 3 anni ad usarlo. Le consegne dovrebbero essere fatte tramite commit. Basta zip volanti che si dimenticano di salvare, che hanno lasciato in C23 ma ora siamo in B26 ecc. Eventualmente installare un software che aiuti nell'utilizzo di git tipo Sublime Merge. Sia questo che la gestione di Git da Code funziona solo con git nativo. Git portable non viene riconosciuto. Nei laboratori con linux deve essere installato anche un gestore delle credenziali di git (gcm).
- assolutamente devono uscire da qui che sanno usare Javascript. È un linguaggio standard di fatto per il front end, anche utilizzato per il back end.
- devono sapere SQL, molto utilizzato e fa parte dell'esame di Stato.
- c'è da scegliere tra Python e C. In python si riesce anche a fare molto bene la parte di backend. In C viene molto bene la parte di fork e join. Nei quattro anni si potrebbe anche fare entrambi, è da capire quando fare cosa, e chi.
- darei la parte di requisiti SW, documentazione SW, gestione del progetto (TPSI di terza e quarta fine libro che io per esempio non riesco mai a fare) a GPOI che ora ha più anni. TPSI con meno carico magari potrebbe insegnare C insieme alle fork e quella parte. Quindi rimarrebbe Python come linguaggio primario in informatica per iniziare a programmare e poi Javascript subito dopo, con obiettivo in quarta S di mettere tutto insieme, fare una full stack application con SQL, Python, React e progetti integrati anche con GPOI.  
Quindi potrebbe essere: 1° Python, 2° Javascript, 3° React, 4° tutto insieme.
- Sottolineerei l'importanza nell'imparare l'utilizzo delle AI in modo costruttivo e consapevole. Se lo usano per generare le consegne nessuno li assumerà, basta usare ChatGPT. Se lo usano per imparare, farsi spiegare invece è utile.
- Utilizzerei la metodologia PRIMM per insegnare le parti più difficili: https://fablab.unitn.it/sperimentazione-primm/ 

Ovviamente ho escluso come da premessa tutti gli altri lavori (sistemista e quindi gli argomenti di sistemi e reti, CMS ecc) per concentrarmi solo sui linguaggi di programmazione, che mi pare già essere un post molto lungo.  

Non so se qualcuno veramente può essere arrivato a leggersi questo pippozzo fino a qui :) So di aver detto cose anche impopolari perché sono diverse da quanto si fa oggi nelle classi normali
