SUPSI 2026  
Corso d’interaction design, CV429.01  
Docenti: A. Gysin, G. Profeta  

Progetto 1: La conquista dello spazio

# NASA70
Autore: Luca Mazzola \
[NASA70](https://lucamazzolaa.github.io/NASA70/)


## Introduzione e tema
Realizzato in occasione del 70° anniversario della NASA, il progetto propone una piattaforma web che raccoglie e presenta una serie di esperienze interattive dedicate alla conquista dello spazio. La pagina introduce il tema celebrativo dell'iniziativa e offre l'accesso ai tredici progetti sviluppati dagli studenti a partire da dati, immagini e documenti provenienti dagli archivi pubblici della NASA. Allo stesso tempo, la struttura della piattaforma è pensata per accogliere e organizzare nel tempo anche centinaia di nuovi progetti e contenuti, configurandosi come un archivio in continua espansione.

L'obiettivo è valorizzare il patrimonio informativo e culturale dell'agenzia aerospaziale attraverso forme contemporanee di visualizzazione e narrazione digitale, offrendo agli utenti la possibilità di esplorare prospettive diverse sul tema dell'esplorazione spaziale. Oltre a fungere da archivio e punto di accesso ai contenuti, la piattaforma ospita il logo NASA 70, elemento centrale dell'identità visiva dell'evento celebrativo.


## Riferimenti progettuali



## Design dell’interfaccia e modalità di interazione
Le principali fonti di ispirazione per il progetto derivano da una raccolta di immagini, interfacce e riferimenti visivi analizzati durante la fase di ricerca. In particolare è emersa la ricorrenza di fotografie con inquadrature grandangolari, viste panoramiche e forme circolari che richiamano pianeti, superfici planetarie, finestrini delle navicelle spaziali, visiere dei caschi degli astronauti e il logo stesso della NASA. Questi elementi contribuiscono a trasmettere un senso di vastità, osservazione e immersione, caratteristiche che hanno influenzato in modo significativo la progettazione della homepage del mio sito.



## Tecnologia usata
Nunc consequat interdum varius sit amet mattis vulputate. Vehicula ipsum a arcu cursus vitae congue. Odio ut sem nulla pharetra. Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus. Nunc aliquet bibendum enim facilisis gravida neque convallis a. Lacus sed turpis tincidunt id aliquet risus feugiat.


```JavaScript
const image = new Image();
image.onload = () => {
	gl.bindTexture(gl.TEXTURE_2D, texture);
	gl.texImage2D(
		gl.TEXTURE_2D,
		level,
		internalFormat,
		srcFormat,
		srcType,
		image
	);
	if (isPowerOf2(image.width) && isPowerOf2(image.height)) {
		gl.generateMipmap(gl.TEXTURE_2D);
	} else {
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_WRAP_S, gl.CLAMP_TO_EDGE);
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_WRAP_T, gl.CLAMP_TO_EDGE);
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_MIN_FILTER, gl.LINEAR);
	}
};
image.src = url;
```

## Target e contesto d’uso
Sed enim ut sem viverra aliquet eget sit. Iaculis at erat pellentesque adipiscing commodo. Et pharetra pharetra massa massa ultricies mi quis hendrerit dolor. At tempor commodo ullamcorper a lacus vestibulum sed arcu. Ipsum faucibus vitae aliquet nec ullamcorper sit. Tempus quam pellentesque nec nam aliquam sem et tortor. Turpis egestas sed tempus urna et pharetra pharetra massa. Ridiculus mus mauris vitae ultricies leo integer malesuada nunc vel.

[<img src="doc/munari.jpg" width="300" alt="Supplemento al dizionario italiano">]()
