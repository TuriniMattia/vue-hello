# Introduction
 -Vue è un framework JavaScript usato per costruire interfaccie utente, basato su HTML, CSS e JavaScript.
 Le due funzionalità base consistono in:
  1. Declarative Rendering:estende l'HTML con un modello che ci permette di descrivere l'output HTML in base allo stato JavaScript;
  2. Reactivity: tiene traccia dei cambiamenti JavaScript e aggiorna il DOM automaticamente.
 A seconda del caso d'uso, Vue può essere utilizzato in diversi modi:
  1.  Miglioramento dell'HTML statico senza una fase di creazione
  2.  Incorporamento come componenti Web in qualsiasi pagina
  3.  Applicazione a pagina singola (SPA)
  4.  Full Stack/Rendering lato server (SSR)
  5.  Jamstack/Generazione di siti statici (SSG)
  6.  Targeting per desktop, dispositivi mobili, WebGL e persino terminale.
 La logica JavaScript, modello HTML e stile CSS venfono racchiusi nel SFC(Single-File Component), tutto in un formato simil HTML.
 I componenti Vue possono essere creati in due diversi stili API: Options API e Composition API.
 Con Options API la logica viene definita con un oggetto di opzioni, dove le proprietà sono esposte in un THIS dentro una funzione.
 Con Composition API invece la logica viene definita usando API importate.

# Template Syntax