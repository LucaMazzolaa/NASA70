SUPSI 2026  
Corso d’interaction design, CV429.01  
Docenti: A. Gysin, G. Profeta  

Progetto 1: La conquista dello spazio

# NASA 70
Autore: Luca Mazzola \
[NASA 70](https://lucamazzolaa.github.io/NASA70/)


## Introduzione e tema
Realizzato in occasione del 70º anniversario della NASA nel 2028, il progetto propone una piattaforma web che raccoglie e presenta una serie di esperienze interattive dedicate alla conquista dello spazio. La pagina introduce il tema celebrativo dell’iniziativa e offre l’accesso ai tredici progetti sviluppati dagli studenti a partire da dati, immagini e documenti provenienti dagli archivi pubblici della NASA. Allo stesso tempo, la struttura della piattaforma è pensata per accogliere e organizzare nel tempo anche centinaia di nuovi progetti e contenuti, configurandosi come un archivio in continua espansione.

L’obiettivo è valorizzare il patrimonio informativo e culturale dell’agenzia aerospaziale attraverso forme contemporanee di visualizzazione e narrazione digitale, offrendo agli utenti la possibilità di esplorare prospettive diverse sul tema dell’esplorazione spaziale. Oltre a fungere da archivio e punto di accesso ai contenuti, la piattaforma ospita il logo NASA 70, elemento centrale dell’identità visiva sviluppata per il 70º anniversario della NASA.


## Riferimenti progettuali
<img width="4000" height="667" alt="Immagini" src="https://github.com/user-attachments/assets/5c1da6ed-813e-42a1-92d7-943025bba177" />

Le principali fonti di ispirazione per il progetto derivano da una raccolta di immagini, interfacce e riferimenti visivi analizzati durante la fase di ricerca, molti dei quali provenienti dall’archivio e dai materiali di comunicazione della NASA. In particolare è emersa la ricorrenza di immagini grandangolari, viste panoramiche e forme circolari che richiamano pianeti, superfici planetarie, finestrini delle navicelle spaziali, visiere dei caschi degli astronauti e il logo stesso della NASA. Questi elementi contribuiscono a trasmettere un senso di vastità, osservazione e immersione, caratteristiche che hanno influenzato in modo significativo la progettazione della homepage del sito.


## Design dell’interfaccia e modalità di interazione
L’interfaccia del progetto è organizzata secondo una struttura chiara e minimale, pensata per bilanciare esplorazione immersiva e consultazione ordinata dei contenuti. Tutte le pagine condividono una stessa identità visiva basata su una palette cromatica coerente, ispirata ai colori frequentemente utilizzati nella comunicazione e nell’identità visiva della NASA, e sull’utilizzo uniforme della tipografia Helvetica. La scelta di questo carattere deriva dal suo impiego in diversi contesti comunicativi legati all’ente spaziale e dalla sua presenza in alcuni manuali e documenti storici, qualità che ne rafforzano il legame con l’immaginario aerospaziale. In questo modo si garantiscono continuità, leggibilità e riconoscibilità durante la navigazione. È stato inoltre scelto uno sfondo grigio molto chiaro anziché completamente bianco, una soluzione che permette di distinguere meglio le immagini con sfondo bianco presenti nei contenuti ed evita che queste si fondano visivamente con la pagina.

### Pagine del sito
| N. | File | Pagina | Contenuto |
| :--- | :--- | :--- | :--- |
| 1 | **`index.html`** | NASA 70 | Interfaccia esplorativa immersiva |
| 2 | **`projects.html`** | Projects | Archivio dei progetti consultabile in formato lista con filtri e ricerca |
| 3 | **`about.html`** | About | Sezione informativa dedicata al contesto del progetto |

### Menu globale fisso
<img width="1919" height="81" alt="menu" src="https://github.com/user-attachments/assets/ae9e3bbf-d2e1-4af5-a2de-bebe4aafd672" />

Il menu superiore costituisce l’elemento di navigazione principale e il componente visivo ricorrente dell’intera piattaforma, presente in tutte le pagine per garantire continuità e orientamento durante la navigazione. Esso presenta il nome del progetto sulla sinistra, il logo dedicato al 70º anniversario della NASA al centro, riprendendo la posizione occupata dal marchio nel sito ufficiale dell’agenzia, e le pagine Projects e About sulla destra, assicurando un accesso immediato alle diverse aree del sito.


### Logo
<img width="4000" height="667" alt="logo" src="https://github.com/user-attachments/assets/d7a2509f-6b9e-498a-bc6b-a964cf57abd4" />

Il progetto mantiene il logo storico della NASA come elemento centrale dell’identità visiva, preservandone la riconoscibilità istituzionale e il valore simbolico. Al logo si affianca un 7 geometrico, ispirato al concept del logo realizzato per il 40º anniversario, scelto come riferimento per la sua capacità di sintetizzare celebrazione e chiarezza formale. Questa soluzione permette di costruire un segno grafico coerente con il 70º anniversario, mantenendo un equilibrio tra tradizione e reinterpretazione contemporanea.
Nella mia interpretazione progettuale, il logo celebrativo sostituisce temporaneamente il marchio NASA all’interno del sito ufficiale per tutta la durata delle celebrazioni del 70º anniversario. Questa scelta è coerente con le linee guida del NASA Brand Center, che prevedono la possibilità di sviluppare loghi per campagne e anniversari, a condizione di approvazione da parte dell’Associate Administrator for Communications.


### 1. NASA 70 (index.html)
<img width="4000" height="1994" alt="03" src="https://github.com/user-attachments/assets/eb8c0e9b-03f2-43d5-81ed-6f02b8922474" />

La Homepage si distingue per un approccio immersivo e non convenzionale. Invece di una pagina classica a scroll verticale, l’utente si trova di fronte alle immagini di copertina dei vari progetti, disposte in modo casuale all’interno dello spazio visivo. Questa disposizione introduce una lieve distorsione percettiva dello spazio, contribuendo a un senso di profondità e esplorazione non lineare. Attraverso lo scroll, il trascinamento o l’utilizzo delle frecce della tastiera, è possibile muoversi liberamente all’interno di uno spazio potenzialmente infinito, in cui i progetti possono essere moltiplicati fino a diventare centinaia, trasformando la navigazione in una vera esperienza di esplorazione continua. Attualmente i progetti vengono ripetuti a causa della loro quantità limitata, ma la struttura è pensata per accoglierne un numero molto più ampio. L’unica azione di uscita dall’esperienza è la selezione di un progetto, che conduce direttamente alla relativa pagina dedicata.

In fase di sviluppo è emersa una difficoltà tecnica non risolta: su Chrome, rispetto a Safari, una delle immagini viene renderizzata come nera. Nonostante diversi tentativi, non è stato possibile individuarne la causa e si ipotizza possa trattarsi di un bug del browser.

### 2. Projects (projects.html)
<img width="4000" height="1994" alt="032" src="https://github.com/user-attachments/assets/94819b16-ebe2-4355-8821-644bc98916b3" />

La pagina Projects adotta invece una struttura più tradizionale e funzionale, organizzata come una lista di contenuti consultabili. Questa area permette una navigazione più analitica dei progetti, supportata da strumenti di ricerca, ordinamento e filtraggio che facilitano l’esplorazione dei dati in base a categorie e criteri specifici.

### 3. About (about.html)
<img width="4000" height="1994" alt="033" src="https://github.com/user-attachments/assets/433c5b8a-dfbf-4433-829a-85b9e9474d1d" />

La pagina About è concepita come uno spazio esclusivamente tipografico, dedicato alla spiegazione dell’iniziativa e delle sue finalità. Qui vengono presentati il contesto del progetto e le informazioni necessarie per comprenderne la struttura e il contesto generale, offrendo una lettura chiara e diretta dell’intero sistema.


## Tecnologia usata
Il progetto poggia su una solida architettura front-end nativa, sviluppata in **HTML5, CSS3 e JavaScript (ES6)**. HTML definisce la struttura semantica dell’interfaccia, mentre CSS ne gestisce l'estetica attraverso un design system responsivo basato su variabili, calcoli fluidi e tipografia personalizzata. JavaScript funge da motore logico dell’applicazione: orchestra il DOM, gestisce gli eventi dell’utente e sincronizza l’interfaccia con i dati e le librerie esterne.<br>

Di seguito vengono presentati tre estratti di codice chiave tratti dal file **`index.html`**, che rappresenta la pagina più complessa e tecnicamente articolata del progetto. In questa sezione si concentra infatti la maggior parte della logica interattiva, con la gestione dell’esperienza esplorativa principale, delle animazioni e dei meccanismi di navigazione che regolano l’accesso alle altre parti del sistema.

### 1. Rendering avanzato e Shader distorsivi (Three.js e GLSL)
Per ottenere l’effetto di profondità e curvatura della griglia visiva, si è optato per l’utilizzo di materiali basati su shader personalizzati (`ShaderMaterial`). Il codice GLSL iniettato a livello di vertice calcola la distanza dal centro dello schermo e altera la posizione sull’asse Z, creando una deformazione a lente parabolica che viene calcolata direttamente dalla GPU.

**HTML**
```html
<div id="viewport">
    <div id="canvas"></div>
</div>
```

**CSS**
```css
#viewport { 
    position: fixed
    top: 0
    left: 0
    width: 100vw
    height: 100vh
    z-index: 1
    overflow: hidden
}

#canvas { 
    position: absolute
    top: 0
    left: 0
    width: 100%
    height: 100%
}
```

**JavaScript**
```javascript
const s = String.fromCharCode(59)

const vertexShader = `
    varying vec2 vUv ${s}
    void main() {
        vUv = uv ${s}
        vec4 mvPosition = modelViewMatrix * vec4(position, 1.0) ${s}
        
        float dist = length(mvPosition.xy) ${s}
        mvPosition.z += dist * dist * 0.015 ${s} 
        
        gl_Position = projectionMatrix * mvPosition ${s}
    }
`

// Assegnazione del materiale custom ai piani della griglia
const material = new THREE.ShaderMaterial({
    uniforms: {
        tDiffuse: { value: currentData.tex },
        uPickingColor: { value: new THREE.Color(imageId) },
        uIsPicking: { value: 0.0 }
    },
    vertexShader: vertexShader,
    fragmentShader: fragmentShader,
    side: THREE.DoubleSide
})
```


### 2. Fetch dati e Texturing dinamico (API e CanvasTexture)
L’architettura carica i riferimenti progettuali in modo asincrono da un endpoint JSON esterno. Parallelamente, per visualizzare la tipografia all’interno dello spazio 3D, un nastro di testo scorrevole viene disegnato dinamicamente su un elemento nativo HTML Canvas e convertito in una `CanvasTexture` continua, applicata poi come rivestimento ai modelli geometrici.

**HTML**
```html
<script>
    const fontRoman = new FontFace('HelveticaFallback', 'url("assets/helvetica/HelveticaLTStd-Roman.otf")', { weight: '400' })
    const fontMedium = new FontFace('HelveticaFallback', 'url("assets/helvetica/HelveticaLTStd-Roman.otf")', { weight: '500' })
    const fontBold = new FontFace('HelveticaFallback', 'url("assets/helvetica/HelveticaLTStd-Bold.otf")', { weight: '600' })

    fontRoman.load().then(f => document.fonts.add(f)).catch(e => console.warn("Font 400 locale assente"))
    // [...]
</script>

<script type="module">
    import * as THREE from 'https://cdn.skypack.dev/three@0.136.0'
    // [...] Modulo principale dell'applicazione
</script>
```

**JavaScript**
```javascript
fetch('https://ixd-supsi.github.io/n70api/data.json')
    .then(res => res.json())
    .then(data => {
        let projects = []
        data.forEach(p => {
            // [...] Logica di parsing ed estrazione immagini omessa per brevità
            projects.push({ 
                file: imgFilename, 
                url: p.url || '#'
            })
        })
        initThree(projects)
    })

// Generazione texture tipografica dinamica
const textCanvas = document.createElement('canvas')
textCanvas.width = textWidth
textCanvas.height = 128
const ctx = textCanvas.getContext('2d')
ctx.font = '40px "Helvetica", "HelveticaFallback", sans-serif'
ctx.fillStyle = '#888888' 
ctx.fillText(textStr, 0, 64)

const textTexture = new THREE.CanvasTexture(textCanvas)
textTexture.wrapS = THREE.RepeatWrapping
textTexture.wrapT = THREE.RepeatWrapping
```


### 3. Griglia infinita e interazione Pixel-Perfect (WebGLRenderTarget)
La navigazione fluida e sconfinata è ottenuta matematicamente riposizionando gli elementi che escono dal campo visivo sul lato opposto della scena durante il ciclo di rendering (`requestAnimationFrame`). Per gestire l’interazione del cursore si è implementato un sistema di "Color Picking": la scena viene fotografata fuori schermo assegnando un colore univoco a ciascun elemento per identificare l’oggetto puntato analizzando le coordinate del pixel selezionato.

**HTML**
```html
<header>
    <div class="header-left">
        <span class="site-title hover-target" onclick="window.location.href='index.html'">NASA 70</span>
    </div>
    <div class="logo-container">
        <img src="assets/logo.svg" alt="N70 Logo" class="hover-target">
    </div>
    <nav>
        <a href="projects.html" class="hover-target">Projects</a>
        <a href="about.html" class="hover-target">About</a>
    </nav>
</header>
```

**CSS**
```css
header { 
    position: fixed
    top: 0
    left: 0
    width: 100%
    padding: 20px 20px 20px 20px
    display: grid
    grid-template-columns: 1fr auto 1fr
    align-items: center
    z-index: 10000
    background: #000000
    pointer-events: auto
}

nav a { 
    text-decoration: none
    color: #ffffff !important
    font-size: 16px
    font-weight: 500
    transition: color 0.3s var(--ease)
    cursor: pointer
}
```

**JavaScript**
```javascript
function getHoveredObject(clientX, clientY) {
    planes.forEach(p => {
        if (p.material.uniforms.uIsPicking) {
            p.material.uniforms.uIsPicking.value = 1.0
        }
    })
    
    camera.setViewOffset(window.innerWidth, window.innerHeight, clientX, clientY, 1, 1)
    
    renderer.setRenderTarget(pickingTexture)
    renderer.clear()
    renderer.render(scene, camera)
    
    camera.clearViewOffset()
    renderer.readRenderTargetPixels(pickingTexture, 0, 0, 1, 1, pixelBuffer)
    renderer.setRenderTarget(null)
    
    // [...] Ripristino shader omesso per brevità
    
    const id = (pixelBuffer[0] << 16) | (pixelBuffer[1] << 8) | pixelBuffer[2]
    return planes.find(p => p.userData.id === id)
}

function animate() {
    requestAnimationFrame(animate)

    scrollX += (targetScrollX - scrollX) * 0.05
    scrollY += (targetScrollY - scrollY) * 0.05

    group.position.x = scrollX
    group.position.y = scrollY

    // Logica spaziale di riposizionamento continuo
    planes.forEach(plane => {
        const globalX = plane.position.x + scrollX
        const globalY = plane.position.y + scrollY

        if (globalX > limitX) plane.position.x -= totalWidth
        if (globalX < -limitX) plane.position.x += totalWidth

        if (globalY > limitY) plane.position.y -= totalHeight
        if (globalY < -limitY) plane.position.y += totalHeight
    })

    renderer.render(scene, camera)
}
```


## Target e contesto d’uso
Il progetto è rivolto a un pubblico generalista internazionale, proveniente da diverse aree geografiche del mondo, interessato allo spazio, alla divulgazione scientifica e alle modalità contemporanee di visualizzazione dei dati. L’interfaccia è pensata per essere accessibile a utenti di età eterogenea, indicativamente da adolescenti e studenti fino a un pubblico adulto, senza richiedere competenze tecniche o scientifiche specifiche.

Il contesto ideale di fruizione è quello digitale e quotidiano, principalmente attraverso computer, poiché l’interfaccia è stata progettata e ottimizzata per questo tipo di dispositivo e risulta solo parzialmente adattabile a finestre più piccole. Il progetto può comunque essere consultato anche in ambienti educativi e culturali come scuole, università e spazi espositivi legati alla scienza e alla ricerca.
