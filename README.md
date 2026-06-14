SUPSI 2026  
Corso d’interaction design, CV429.01  
Docenti: A. Gysin, G. Profeta  

Progetto 1: La conquista dello spazio

# NASA70
Autore: Luca Mazzola \
[NASA70](https://lucamazzolaa.github.io/NASA70/)


## Introduzione e tema
Realizzato in occasione del 70º anniversario della NASA nel 2028, il progetto propone una piattaforma web che raccoglie e presenta una serie di esperienze interattive dedicate alla conquista dello spazio. La pagina introduce il tema celebrativo dell’iniziativa e offre l’accesso ai tredici progetti sviluppati dagli studenti a partire da dati, immagini e documenti provenienti dagli archivi pubblici della NASA. Allo stesso tempo, la struttura della piattaforma è pensata per accogliere e organizzare nel tempo anche centinaia di nuovi progetti e contenuti, configurandosi come un archivio in continua espansione.

L’obiettivo è valorizzare il patrimonio informativo e culturale dell’agenzia aerospaziale attraverso forme contemporanee di visualizzazione e narrazione digitale, offrendo agli utenti la possibilità di esplorare prospettive diverse sul tema dell’esplorazione spaziale. Oltre a fungere da archivio e punto di accesso ai contenuti, la piattaforma ospita il logo NASA 70, elemento centrale dell'identità visiva sviluppata per il settantesimo anniversario della NASA.


## Riferimenti progettuali
Le principali fonti di ispirazione per il progetto derivano da una raccolta di immagini, interfacce e riferimenti visivi analizzati durante la fase di ricerca. In particolare è emersa la ricorrenza di immagini grandangolari, viste panoramiche e forme circolari che richiamano pianeti, superfici planetarie, finestrini delle navicelle spaziali, visiere dei caschi degli astronauti e il logo stesso della NASA. Questi elementi contribuiscono a trasmettere un senso di vastità, osservazione e immersione, caratteristiche che hanno influenzato in modo significativo la progettazione della homepage del sito.


## Design dell’interfaccia e modalità di interazione
L’interfaccia del progetto è organizzata secondo una struttura chiara e minimale, pensata per bilanciare esplorazione immersiva e consultazione ordinata dei contenuti. Tutte le pagine condividono una stessa identità visiva basata su una palette cromatica coerente e sull’utilizzo uniforme della tipografia, così da garantire continuità e riconoscibilità durante la navigazione. È stato inoltre scelto uno sfondo grigio molto chiaro anziché completamente bianco, una soluzione che permette di distinguere meglio le numerose immagini con sfondo bianco presenti nei contenuti ed evita che queste si fondano visivamente con la pagina.

### Pagine del sito
| N. | File | Pagina | Contenuto |
| :--- | :--- | :--- | :--- |
| 1 | **`index.html`** | NASA 70 | Interfaccia esplorativa immersiva |
| 2 | **`projects.html`** | Projects | Archivio dei progetti consultabile in formato lista con filtri e ricerca |
| 3 | **`about.html`** | About | Sezione informativa dedicata al contesto del progetto |

### Menu globale fisso
Il menu superiore costituisce l’elemento di navigazione principale e presenta il nome del progetto sulla sinistra, il logo dedicato al 70º anniversario della NASA al centro, riprendendo la posizione occupata dal marchio nel sito ufficiale dell’agenzia, e le sezioni Projects e About sulla destra, garantendo un accesso immediato alle diverse aree della piattaforma.

### Logo
Il progetto mantiene il logo storico della NASA come elemento centrale dell’identità visiva, preservandone la riconoscibilità istituzionale e il valore simbolico. Al logo si affianca un 7 geometrico, ispirato al concept del logo realizzato per il 40º anniversario, scelto come riferimento per la sua capacità di sintetizzare celebrazione e chiarezza formale. Questa soluzione permette di costruire un segno grafico coerente con il 70º anniversario, mantenendo un equilibrio tra tradizione e reinterpretazione contemporanea.
Nella mia interpretazione progettuale, il logo celebrativo sostituisce temporaneamente il marchio NASA all'interno del sito ufficiale per tutta la durata delle celebrazioni del 70º anniversario.
<img width="1280" height="848" alt="logo_40_anniversario" src="https://github.com/user-attachments/assets/d53a73bc-6dab-449b-9d76-01930e5fd823" />

### 1. NASA 70 (index.html)
La homepage si distingue per un approccio immersivo e non convenzionale. Invece di una struttura statica, l’utente si trova di fronte a un’unica immagine di copertina che diventa spazio di esplorazione. Attraverso lo scroll o il trascinamento, è possibile navigare all’interno di questa superficie visiva continua, scoprendo progressivamente i diversi progetti senza uscire dalla dimensione principale. L’unica azione di uscita dall’esperienza è la selezione di un elemento, che conduce direttamente alla pagina del progetto scelto.

### 2. Projects (projects.html)
La sezione Projects adotta invece una struttura più tradizionale e funzionale, organizzata come una lista di contenuti consultabili. Questa area permette una navigazione più analitica dei progetti, supportata da strumenti di ricerca e filtraggio che facilitano l’esplorazione dei dati in base a categorie e criteri specifici.

### 3. About (about.html)
La sezione About è concepita come uno spazio prevalentemente tipografico, dedicato alla spiegazione dell’iniziativa e delle sue finalità. Qui vengono presentati il contesto del progetto e le informazioni necessarie per comprenderne la struttura e le modalità di funzionamento, offrendo una lettura chiara e diretta dell’intero sistema.


## Tecnologia usata
Il progetto poggia su una solida architettura front-end nativa, sviluppata in HTML5, CSS3 e JavaScript (ES6). HTML definisce la struttura semantica dell’interfaccia, mentre CSS ne gestisce l’estetica attraverso un design system responsivo basato su variabili, calcoli fluidi e tipografia personalizzata. JavaScript funge da motore logico dell’applicazione: orchestra il DOM, gestisce gli eventi dell’utente e sincronizza l’interfaccia con i dati e le librerie esterne.

Di seguito vengono presentati tre estratti di codice chiave che sono stati fondamentali nello sviluppo del progetto, in quanto determinanti per la costruzione della logica interattiva:


## Target e contesto d’uso
Il progetto è rivolto a un pubblico generalista internazionale, proveniente da diverse aree geografiche del mondo, interessato allo spazio, alla divulgazione scientifica e alle modalità contemporanee di visualizzazione dei dati. L’interfaccia è pensata per essere accessibile a utenti di età eterogenea, indicativamente da adolescenti e studenti fino a un pubblico adulto, senza richiedere competenze tecniche o scientifiche specifiche.

Il contesto ideale di fruizione è quello digitale e quotidiano, attraverso dispositivi personali come computer, tablet o smartphone, ma anche in ambienti educativi e culturali come scuole, università e spazi espositivi legati alla scienza e alla ricerca. Il progetto si presta inoltre a una fruizione autonoma e internazionale, favorendo un’esplorazione libera e immersiva dei contenuti da parte di utenti con background e livelli di esperienza differenti.
