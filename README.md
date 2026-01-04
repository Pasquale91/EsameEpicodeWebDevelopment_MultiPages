# Portfolio Web Personale – Versione Multi-Pages

Questo repository contiene la **versione multi-pages** del progetto sviluppato come **argomento d’esame di Web Development** durante il mio percorso di studi in **Computer Engineering & AI** presso Epicode Institute of Technology.

Il progetto è stato realizzato considerando le richieste del'esame che ci dava come obbiettivo quello di creare un **sito web personale reale**, applicando le tecnologie e le best practices studiate durante il corso (nello specifico HTML5, CSS3 Grid, Flexbox e funzioni tramite JS).

## Versioni del progetto

Poiché non era stato specificato se il progetto doveva essere multi-pages o single-page ho sviluppato e pubblicato 2 versioni del progetto, la versione **single-page** si trova qui:
👉 https://github.com/Pasquale91/EsameEpicodeWebDevelopment_SinglePage

## Struttura del sito

Il sito è composto da **5 pagine complete**:

- Home
- Chi sono
- Curriculum
- Contatti
- Scarica CV
- **La pagina cv.html**:
  - `cv.html`, è una pagina aggiuntiva dove l'utente può decidere se stampare o salvare in PDF il mio curriculum in formato **A4**. La pagina fa uso delle regole CSS (`@media print`)

### File principali

```
index.html
about.html
resume.html
contact.html
cv.html
contenuti/css/style.css
contenuti/js/script.js
contenuti/img/fotoprofilo.png
```

Ho deciso di usare **nomi in italiano** per classi CSS e ID.

## Funzionalità implementate

### Tema chiaro / scuro

- Pulsante con icone sole/luna
- Salvataggio/Lettura di `localStorage` per salvare o controllare le impostazioni nel caso dovesse riapre la pagina in un secondo momento
- Utilizzo di variabili CSS personalizzate

### Form di contatto

- Validazione email tramite pattern
- Feedback visivo per successo e/o errore
- Sistema **honeypot** (anti-spam)

### Design responsive

- Layout basato su **CSS Grid** e **Flexbox**
- Breakpoint multipli (max-width: 480px, 768px, 1024px)
- Menu hamburger con animazione visibile sui dispositivi mobili

### UX

- Gestione edge cases (es validazione del form)
- Stati “hover” dei link consistenti

## Tecnologie utilizzate

- HTML5
- CSS3 (Grid, Flexbox, Variabili CSS personalizzate, Media Queries)
- JavaScript
- localStorage

## Altro

- Codice commentato
- Compatibilità cross-browser verificata
- SEO:
  - title tag
  - meta description
  - meta keywords
  - utilizzo di tag semantici HTML5
  - gerarchia corretta degli heading (es prima h1 poi h2 e poi h3)
  - attributi `aria-label`
- Inserito link esterni

## Scelte progettuali

### Honeypot

È stato implementato un sistema honeypot come protezione anti-spam.  
Pur essendo una tecnica oggi superata, è stata inserita per ampliare l’esercizio di logica e scrittura di codice JavaScript.
