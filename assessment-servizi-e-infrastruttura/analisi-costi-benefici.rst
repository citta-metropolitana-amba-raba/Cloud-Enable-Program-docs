3.3 Analisi costi-benefici
==============================

Determinare costi e benefici del cloud richiede un approccio sistematico
che tenga in considerazione tutti i fattori diretti ed indiretti che impattano
sulla migrazione.

Per un’analisi efficace è opportuno seguire questi passi:

1. definizione del periodo temporale su cui calcolare il ritorno
   sull’investimento (tipicamente 5 anni)

2. verifica dei costi attuali dell’infrastruttura e loro proiezione sul
   periodo temporale

3. stima dei costi dell’infrastruttura cloud e loro proiezione sul
   periodo temporale

4. stima dei costi di migrazione

5. stima dei costi di post-migrazione

6. valutazione dei costi rispetto ai benefici tangibili ed intangibili

Calcolare il costo totale di un servizio IT e compararlo con il
potenziale ritorno economico di una migrazione al cloud costituisce un
compito arduo, come lo è l’analisi dei costi sul cloud computing.
Un'analisi dettagliata dei
benefici di una migrazione deve includere valutazioni a breve, medio e
lungo termine oltre ai costi di terminazione. A questo riguardo, ci sono
due indicatori chiave da considerare:

**Total Cost of Ownership (TCO)** = Costi iniziali + Costi ricorrenti +
Costi di terminazione

**Ritorno sull’investimento (ROI)** = ((Benefici tangibili + Benefici
intangibili) - TCO) / TCO

I costi nascosti che le organizzazioni potrebbero avere difficoltà a
rilevare in anticipo includono:

-  il costo per un cambio di provider dovuto ad una variazione
   regolatoria o di linea di condotta: per calcolare gli investimenti
   necessari per cambiare piattaforma di cloud, nel caso in cui problemi
   economici o regolatori lo rendano necessario, le organizzazioni
   devono tener conto di diversi fattori, tra cui il pagamento per
   l’estrazione e la validazione dei dati ed il costo di assunzione di
   risorse IT necessarie per compiere questo lavoro

-  le spese inaspettate dovute all’iniziale migrazione di sistemi:
   le amministrazioni pubbliche o le software house, infatti, possono dover
   riscrivere le applicazioni per operare in un ambiente virtualizzato e
   riformattare i dati per adattarli ai formati del SaaS del fornitore

-  il lock-in con uno specifico modello di servizio proprietario: costi
   dovuti al fatto che l’amministrazione non riesce a svincolarsi
   facilmente da una scelta tecnologica precedentemente effettuata (vedi
   capitolo 4.3)
   o debba modificare gli applicativi perché i cloud provider dismette
   o modifica le feature esposte dal servizio acquistato



In generale, è importante considerare a livello economico le diverse
opzioni di migrazione al cloud che si possono avere in base alle
caratteristiche di ciò che si vuole migrare: retain, retire,
re-purchase, re-host, re-platform o re-architect (vedi capitolo 4.1 per
approfondire le strategie di migrazione). Ogni alternativa dovrebbe
essere analizzata in dettaglio per decidere il modello cloud migliore in
base al contesto e alle circostanze in cui l’amministrazione si trova.

3.3.1 Verifica dei costi attuali dell’infrastruttura
--------------------------------------------------------

Per calcolare i costi attuali dell’infrastruttura on-premise è necessario
considerare i suoi costi complessivi di utilizzo e manutezione nel tempo.
Questo calcolo include i costi in capitale ed operativi,
sia direttamente imputabili alla piattaforma che condivisi con altre aree.

I **costi diretti** imputabili alla piattaforma sono solitamente documentati
in fatture e pagamenti. Tra questi:

- investimenti per l'acquisto iniziale di hardware (server fisici, dischi, apparati di rete, ...)
  e servizi di sviluppo software

- costi operativi per la gestione del quotidiano, inclusa la forza lavoro impiegata nell'infrastruttura:

  * gestione e manutenzione dell'hardware e del software, acquisto di componenti danneggiate, ..

  * noleggio macchinari e hardware

  * connettività internet e networking dedicata al progetto, content delivery network, ...

  * acquisti e rinnovi delle licenze delle componenti infrastrutturali come
    sistemi operativi, macchine virtuali, database,
    antivirus, backup, ..

  * acquisti e rinnovi delle licenze degli applicativi (CRM, collaboration suite, software sviluppati ad hoc, ..)

  * manutenzione delle soluzioni di data protection e disaster recovery (DAT, dispositivi
    di archiviazione sostitutiva, infrastrutture replicate, ...)

  * formazione ICT

Ci sono poi i **costi indiretti**, ossia condivisi con altre strutture o progetti
e che solitamente vengono ripartiti tra diverse aree o dipartimenti:

   -  manutenzione delle strutture di hosting,
      come gli immobili ed il personale necessario alla loro gestione

   -  manutenzione dell'infrastruttura di alimentazione (gruppi
      continuità, generatori, quadri comandi, ecc.) e di raffreddamento

   -  costi di connettività ad internet condivisi con altre aree/dipartimenti
      (tipo connessione, banda minima
      garantita, fallback in caso di fallimento, ecc.)

   -  costi amministrativi necessari per mantenere e amministrare il
      dipartimento IT. Questi possono includere le risorse da altri
      dipartimenti del proprio ente - personale, acquisti, ragioneria,
      ecc. - che sono dedicati a gestire lo staff IT interno ed esterno

A questi si aggiungono una serie di costi "nascosti"
che possono cubare una fetta importante dei costi complessivi dell’IT, inclusi:

  - i costi legati al rischio di mancata adeguatezza delle soluzioni on-premise
    alle evoluzioni normative o ai requisiti sicurezza

  - la mancata produttività causata dall'indisponibilità dell'infrastruttura IT
    che è direttamente proporzionale al numero di utenti interni o esterni

  - i costi legati a infortuni connessi alla manutenzione delle infrastrutture fisiche.



3.3.2 Stima dei costi dell’infrastruttura cloud
---------------------------------------------------

Partendo dai costi attuali dell'infrastruttura on-premise e dalla loro ripartizione,
vanno stimati i costi dell'infrastruttura cloud.
Questo lavoro è in parte semplificato dal fatto che molti cloud provider
pubblicano online dei calcolatori utili a fare delle stime - che solitamente
sono indicative e non sostituiscono un preventivo vero e proprio.

Alcuni di questi calcolatori includono anche i presunti costi dell'on-premise
come la forza lavoro impiegata o l'energia elettrica e permettono di scaricare
delle analisi comparative tra cloud e on-premise:
anche se la valutazione dei costi dell'infrastruttura attuale non può essere
demandata ai calcolatori esposti dai CSP,
confrontare i valori ed i riparti ritornati con quelli preventivamente
stimati può essere utile.

Utilizzare i calcolatori dei prezzi dei CSP qualificati da ACN nel
Cloud Marketplace, laddove disponibili.

Nel caso più semplice di uno IaaS, dove basta approvvigionarsi di server
e storage, possiamo stimare il costo di una infrastruttura cloud analoga
inserendo in un generico calcolatore queste informazioni:

-  **server**:

   -  tipo di server

   -  numero di macchine virtuali

   -  core della CPU

   -  memoria in GB

   -  hypervisor, sistema operativo guest e motore DB, se si immette un
      tipo di server

-  **storage**:

   -  tipo di storage

   -  capacità di archiviazione grezza (raw)

   -  percentuale di storage ad accesso sporadico


Calcolatori più avanzati permettono di dettagliare meglio server e storage
differenziando per tipologia di carico (eg. ETL, HPC, DB, ...)
oppure includono i servizi SaaS e PaaS come:

- database as a service

- servizi di machine learning

- identity e account management.



3.3.3 Stima dei costi di migrazione al cloud
------------------------------------------------

Il passo successivo è la stima dei costi da sostenere per la
migrazione degli applicativi nel cloud. Vanno considerati i costi di:

-  **spostamento dei dati nel cloud**: è un passaggio cruciale.
   A parte i costi che i CSP solitamente addebitano per il consumo di banda,
   sono da considerare costi per manodopera e automazione necessaria a sincronizzare
   i dati dell'infrastruttura attuale con quella in cloud.
   E’ necessaria una conversione degli schemi o dei formati?
   Quanto si perde nella conversione?
   Vanno scritte procedure di allineamento per far coesistere per il tempo necessario
   l'infrastruttura esistente e quella in cloud?
   Queste sono solo alcune delle domande che possono aiutare a stimare questi costi;

-  **integrazione e test delle app**: deve essere possibile migrare
   le applicazioni su cloud e testare tutte le funzionalità.

   Non tutte le applicazioni sono pronte per il cloud.
   La migrazione di software legacy e mainframe, sistemi ERP (`enterprise resource planning <https://it.wikipedia.org/wiki/Enterprise_resource_planning>`_),
   applicazioni nate per l'on-premise
   è un processo complesso, difficilmente testabile e a volte impraticabile.
   Bisogna mappare le interazioni delle applicazioni con tutte le componenti delle infrastrutture,
   individuare le modifiche necessarie al funzionamento
   sul cloud e quelle necessarie per il testing di tutte le funzionalità a valle della migrazione.

-  **spese di consulenza**: se l’organizzazione non dispone di
   tutte le competenze necessarie per eseguire autonomamente una
   migrazione al cloud può attingere a competenze esterne, ad esempio
   per sviluppare una strategia, pianificare un'architettura
   cloud, o eseguire il processo di migrazione.

   Le spese di consulenze sono determinate dalle competenze necessarie,
   dal numero di esperti da coinvolgere e dalla durata della migrazione;
   per stimarle serve aver chiari i criteri di selezione per i consulenti,
   conoscere approfonditamente quali sono le competenze ed i punti di forza e di debolezza
   dell’organizzazione in materia di cloud.

-  **licenze:** è importante eseguire una valutazione dei costi-benefici
   associati alla migrazione in cloud di software on-premise sotto
   licenza. Per informazioni più dettagliate si rimanda al capitolo 3.4
   Gestione delle licenze software in cloud.


Ricordiamo che il framework di lavoro del programma di
abilitazione al Cloud delle PA prevede centri di competenza sul
territorio, ovvero dei soggetti aggregatori di tecnici, esperti e
managers dell’IT per consolidare e potenziare le competenze, il *know
how* e l’esperienza relativa alla gestione dei servizi cloud nelle
amministrazioni. Questi centri saranno il punto di riferimento per le
pubbliche amministrazioni che si apprestano ad iniziare il proprio
percorso verso il cloud.

3.3.4 Stima dei costi post-migrazione
-----------------------------------------

Che cosa si deve pagare dopo aver completato la migrazione al cloud? I
costi di infrastruttura mensili che sono stati calcolati nel secondo
passaggio di analisi (vedi sezione 3.3.2), ovviamente.

Tuttavia, è necessario tenere in considerazione anche i costi diretti e
indiretti necessari per mantenere e migliorare il nuovo ambiente cloud,
in quanto molti di questi continueranno a essere pagati anche dopo il
completamento della migrazione iniziale.

In questa voce ricadono, tra gli altri, i costi di:

- evoluzione delle operation, come l'aumento dello spazio dedicato
  al monitoraggio delle risorse, l'acquisto di nuovi servizi
  necessari alla crescita della piattaforma
  o degli strumenti di CI/CD;
- gestione delle pratiche amministrative e legali per assicurare
  il rinnovo dei contratti
  o la conformità alle ultime normative sulla data protection;
- monitoraggio dei livelli di servizio concordati
  e delle soluzioni di sicurezza adottate dal CSP;
- formazione necessaria per far operare il personale su 
  infrastrutture più moderne e articolate.

  
3.3.5 Valutazione dei costi rispetto ai benefici tangibili ed intangibili
-----------------------------------------------------------------------------

Dopo aver calcolato tutti i costi, si potrebbe arrivare ad un numero
elevato rispetto a quanto si pensava o ad eventuali costi attuali
(tipicamente solo diretti) che si hanno in mente. Eppure è probabile che
quel numero sia più piccolo di tutti i costi che si stanno attualmente
pagando per l'infrastruttura on-premise.

Ma oltre ai risparmi sui costi, il cloud porta anche un elevato numero
di benefici immateriali che possono essere difficili da misurare
direttamente. Consente ad un’organizzazione di essere più flessibile e
agile in modo da poter testare e lanciare i servizi più velocemente e
reagire meglio alle mutevoli condizioni del mercato. Non ci si deve più
preoccupare di acquistare e configurare nuovi server per gestire la
domanda elevata, dato che è possibile scalare automaticamente i server
cloud istantaneamente. E si ha la tranquillità che la probabilità di un
down degli applicativi è minima grazie all'elevata disponibilità, al
bilanciamento del carico e alle funzionalità di backup dei fornitori
cloud.

Alcuni di questi benefici sono già stati trattati nel capitolo 1.2, ma
approfondiamo qui quelli da tenere in particolare considerazione durante
l’esecuzione di un’analisi costi-benefici.

3.3.5.1 Differenziale dei costi sul cloud rispetto ai costi on-premise
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Confrontando i valori dei costi sul cloud e dei costi on-premise sul
periodo considerato, si può identificare il beneficio tangibile creato
dall’ eliminazione dei canoni di manutenzione richiesti dall’hardware di
proprietà e dei periodici acquisti per il rinnovo degli asset, dallo
snellimento delle attività sia tecniche (verifica funzionamento,
segnalazione malfunzionamenti, verifica apparecchiature obsolete) che
amministrative (gare, impegni di spesa, liquidazioni fatture, ecc.),
dalla riduzione dei costi di energia elettrica e tutte le altre voci
impattate dalla migrazione.

3.3.5.2 Dimensionamento reale o elasticità reale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Le soluzioni on premise sono tipicamente dimensionate rispetto alla
capacità necessaria per gestire il massimo carico previsto, sia esso
dovuto ad una crescita del servizio o a situazioni temporanee di picco.
Il provisioning delle macchine virtuali, della banda, della memoria e
della CPU o della spazio di storage sono dimensionati sulla base di
questi valori massimi che si prevedono di dover gestire.

Questo è legato al fatto che le infrastrutture on-premise sono poco
elastiche, ovvero risulta complesso aumentare o diminuirne il
dimensionamento: i tempi per aumentare le risorse a disposizione sono
significativi ed una volta acquisite nuove risorse non è tipicamente
vantaggioso rilasciarle, in particolare se solo per un periodo. Questo
rende l’infrastruttura on premise non dimensionata sul bisogno attuale.

Grazie alla facilità ed alla rapidità di allocazione di nuove risorse su
una piattaforma cloud, il dimensionamento deve essere effettuato sulle
correnti necessità, aumentando o diminuendo le risorse allocate solo in
caso di necessità.

Analizzare l’utilizzo effettivo delle risorse è quindi cruciale per un
corretto dimensionamento della soluzione in cloud. Per questo tipo di
analisi consultare metriche di utilizzo o utilizzare strumenti di
mercato che forniscono questo tipo di analisi.

3.3.5.3 Riduzione dei rischi di disservizio operativo, perdita dati e del rischio reputazionale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Gli applicativi in cloud godono di alta disponibilità, ovvero la
probabilità che i servizi siano indisponibili per problemi
infrastrutturali è molto bassa. Grazie alla possibilità di fare
provisioning delle risorse in tempi molto rapidi è anche possibile
rispondere a situazioni di carico non previste in modo tempestivo. Ciò
impatta il rischio di disservizio con i costi che questo ha associati.

Il rischio di perdita di dati per problemi infrastrutturali come la
rottura di un dispositivo sono altresì praticamente inesistenti,
azzerando i costi, tipicamente molto ingenti, legati alla perdita di
dati.

Grazie ai servizi di backup e ripristino disponibili in cloud è anche
possibile ritornare ad una situazione funzionante con minima perdita di
dati in tempi molto rapidi, nel caso vi siano motivi applicativi o di
violazione dei sistemi di sicurezza che causano una perdita di dati.

Il rischio reputazionale per l’ente causato dai problemi sopra elencati
ed il costo ad esso associato, anche se di difficile quantificazione
economica ma tipicamente elevato nel tempo, è quindi anch’esso ridotto
significativamente.

3.3.5.4 Semplificazione del disaster recovery
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

L’allestimento di un sito di disaster recovery in cloud è molto semplice
ed i suoi costi sono legati al suo utilizzo effettivo. In base
all’architettura dell’applicativo in cloud, ridondato su più data
center, tale sistema potrebbe diventare implicito.

3.3.5.5 Disponibilità di aggiornamenti, bugfix e miglioramenti più rapida
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Il passaggio in cloud permette aggiornamenti dell’applicativo più rapidi
e questo impatta le attività rendendo sempre disponibile la versione più
aggiornata ed affidabile dell’applicativo senza costi per
l’organizzazione.

Può essere utile valutare anche l’impatto economico di problemi
verificatisi in passato a causa di mancata tempestività nella
risoluzione o opportunità non colte in passato per il medesimo motivo.

3.3.5.6 Adeguamenti normativi su sicurezza e privacy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Amministrare le infrastrutture IT comporta responsabilità di sicurezza e
di protezione dei dati personali. Le recenti normative in materia di
privacy e di sicurezza informatica impongono anche alle pubbliche
amministrazioni l’adozione di misure tecniche e organizzative adeguate a
garantire la sicurezza del trattamento dei dati.

Molti provider di servizi cloud offrono un’ampia gamma di criteri,
tecnologie e controlli che rafforzano la sicurezza complessiva, grazie
alla protezione dei dati (che possono essere criptati con i più alti
livelli di sicurezza del mercato), dell’applicazione e dell’
infrastruttura da minacce potenziali.

Questo permette agli enti di utilizzare soluzioni complete, già mature e
disponibili o, a volte, trarne vantaggio in modo del tutto trasparente
in quanto soluzioni applicate in modo totalmente trasparente dal cloud
provider, senza dover investire soluzioni ad hoc e nelle competenze
necessarie per capire di quello di cui si necessita.

3.3.5.7 Miglioramento del servizio (percezione dell’utente finale)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sfruttando le potenzialità del cloud, le pubbliche amministrazioni hanno
l’opportunità di migliorare la qualità dei propri servizi, siano questi
ad uso interno o ad uso del cittadino.

Grazie al cloud, l’amministrazione può gestire i servizi in maniera più
efficiente ed efficace, riuscendo a concentrarsi maggiormente sulle
funzionalità da offrire ai propri utenti. Questo ha un ritorno economico
in termini di efficacia, efficienza e reputazione dei servizi.
