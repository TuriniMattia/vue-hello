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
La sintassi  "Mustache" (baffi) è la forma base di cattura del testo, che consiste nell'uso delle doppie graffe <span>message : {{ msg}}</span>.
Il tag mustache verrà sostituito con il valore della proprietà msg dell'istanza del componente corrispondente e verrà aggiornato ogni volta che la proprietà cambia.
La  v-html directive serve per produrre HTML reale. Le direttive hanno il v- per indicare che sono attributi specifici di vue.
I baffi non possono essere utilizzati all'interno di attributi HTML e di conseguenza va usato il v-bind.
Vue supporta tutta la potenza delle espressioni JavaScript all'interno di tutte le associazioni di dati.
Nei modelli Vue, le espressioni JavaScript possono essere utilizzate nelle seguenti posizioni:
1. Interpolazioni del testo interno (baffi);
2. Nel valore dell'attributo di qualsiasi direttiva Vue (attributi speciali che iniziano con v-).
Il compito di una direttiva è applicare in modo reattivo gli aggiornamenti al DOM quando cambia il valore della sua espressione.
Alcune direttive possono accettare un "argomento", indicato da due punti dopo il nome della direttiva. 
È anche possibile utilizzare un'espressione JavaScript in un argomento direttivo racchiudendola tra parentesi quadre.
È previsto che gli argomenti dinamici restituiscano una stringa, ad eccezione di null. Il valore speciale nullpuò essere utilizzato per rimuovere esplicitamente l'associazione.
I modificatori sono suffissi speciali indicati da un punto, che indicano che una direttiva dovrebbe essere vincolata in qualche modo speciale. 
