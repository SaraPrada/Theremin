SUPSI 2022-23  
Corso d’interaction design, CV427.01  
Docenti: A. Gysin, G. Profeta  

Elaborato 2: Antologia a due mani

# Theremin
Autore: Sara Prada
[MediaPipe demo-ES6](https://saraprada.github.io/Theremin/)

## Introduzione e tema
Il progetto consiste nella realizzazione di una ricerca testuale su un oggetto, a scelta dalla lista assegnata, che ha come principale punto di forza l’interazione con le mani. Dopo aver compreso e finalizzato la ricerca e aver creato una struttura di contenuti, il progetto richiedeva l’impaginazione di quest’ultimi all’interno di una pagina web one - scroll, cercando di dare dei rimandi all’oggetto attraverso dettagli estetici e di interazione con lo scopo di valorizzarlo. L’oggetto protagonista di questa ricerca è il Theremin, uno strumento musicale molto particolare grazie al caratteristico tipo di interazione macchina - uomo.

## Riferimenti progettuali
Come riferimento progettuale posso dire che graficamente ho preso spunto proprio dal design caratteristico del Theremin, mentre, per il contenuto testuale ho preso spunto da vari siti che mi hanno spiegato molto bene tutta la storia del Theremin e le sue caratteristiche di interazione.

[Rai cultura](https://www.raicultura.it/musica/articoli/2021/04/Il-theremin-24d174af-8cb0-4163-b468-eefd4f7eb41c.html) <br>
[Emastereted](https://emastered.com/it/blog/how-the-theremin-works)<br>
[Giorgionecordi](http://www.giorgionecordi.it/theremin/come-e-fatto/)<br>
[Wikipedia](https://it.wikipedia.org/wiki/Theremin)<br>
[Reverb](https://reverb.com/news/the-theremins-century)<br>
[Cineblog](https://www.cineblog.it/post/14-film-che-hanno-usato-il-theremin-nella-colonna-sonora)<br>
[Rockit](https://www.rockit.it/articolo/theremin-strumento-musicale)


## Design dell’interfaccia e dell’interazione
Graficamente parlando la pagina web ha piccoli dettagli che hanno il compito di rinviare al Theremin: il colore beige è stato scelto in quanto solitamente lo strumento ha come materiale il legno. L’utilizzo di un font sinuoso come il Rubik e del codice per arrotondare gli angoli delle immagini è dovuto al design tipico del Theremin, morbido e curvo. La scelta di utilizzare due scroll, verticale e orizzontale, ha il motivo preciso di ricordare il tipo di interazione sia sull’asse della “X” che sull’asse della “Y”. Oltre a questo l’interazione della pagina ha due modalità di visualizzazione in quanto può anche essere letta anche solo scrollando in verticale oppure scrollare anche a destra per leggere o vedere i contenuti extra riguardante il capitolo.

## Tecnologia usata
La difficoltà tecnica di questo progetto consiste proprio nel realizzare un layout con due scroll diversi.

```css
section {
	overflow-x: scroll;
	display: grid;
	grid-template-columns: 100vw 100vw;
    border-top: 10em solid white;
}
```

La pagina ha un layout costituito da 2 colonne in cui all’interno di quella di sinistra sono presenti altre 3 colonne che suddividono gli elementi: immagini, testi e la "linguetta".

```css
.col2 {
	display: grid;
	grid-template-columns: 1fr 1fr 1fr;
	grid-column-gap: 2em;
}
```
## Target e contesto d’uso

Un ipotetico target del progetto sono gli appassionati di musica e affascinati dal Theremin vogliono saperne di più riguardo ad esso. Esso può essere una introduzione di un museo che da un incipit di tutto quello che riguarda il Theremin per far incuriosire gli utenti e far capir loro cos’è il Theremin.