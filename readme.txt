Titolo del progetto:
Sito web di un'Agenzia di Viaggi – Homework 1

Descrizione dell'esercizio:
Questo progetto consiste nella realizzazione di un sito web statico dedicato a un'agenzia di viaggi. 
L'obiettivo dell'esercizio è mettere in pratica le basi di XHTML e CSS viste nelle prime lezioni, 
creando un sito composto da più pagine collegate tra loro e strutturate in modo semanticamente corretto.

Riferimenti alle slide:
Il progetto fa riferimento agli esercizi presenti nelle slide introduttive su:
- Struttura di un documento XHTML
- Utilizzo corretto dei tag semantici
- Creazione di collegamenti ipertestuali
- Inserimento di immagini e liste
- Fogli di stile CSS di base

Caratteristiche XHTML messe alla prova:
- Struttura XHTML valida (html, head, body)
- Liste ordinate per presentare contenuti
- Collegamenti interni tra le varie pagine del sito
- Inserimento di immagini 
- Tabelle per organizzare informazioni strutturate

Caratteristiche CSS messe alla prova:
- Selettori di base
- Gestione dei colori e dei font
- Margini, padding e bordi
- Layout semplice tramite display, width, height
- Stile coerente tra le varie pagine

Pagine del sito:
- Home.xhtml — Pagina principale dell’agenzia
- destinazioni.xhtml — Elenco delle destinazioni proposte
- itinerario.xhtml — Esempio di itinerario di viaggio
- Chi_siamo.xhtml — Presentazione dell’agenzia e del team
- Last_minut.xhtml — Offerte last minute disponibili

Problemi riscontrati:
1.  I riquadri .card2 non avevano la stessa altezza perchè il contenuto era diverso e il contenitore usava flex che allinea gli elementi in base al contenuto. 
    Questo problema è stato risolto mettendo un'altezza standard "height: 650px;".
2.  Per creare la pagina destinazioni.xhtml abbiamo allineato al centro i div con in id="contenuto". 
    All’inizio abbiamo avuto dei problemi perché abbiamo usato div più volte, ma con un'unica struttura di css. Per risolvere la situazione abbiamo scelto di usare un id invece di una classe: in questo modo potevamo applicare uno stile preciso e univoco a quel contenitore, garantendo che l’impaginazione risultasse centrata.

Autori:
- Danila Gatto (https://github.com/danilagatto/HOMEWORK1-LWEB)
- Luca Lauretti (https://github.com/lucalau00/HOMEWORK-1-LWEB)
