# REACT
## JSX
JSX (JavaScript XML) è una sintassi estensione di JavaScript utilizzata principalmente con React per descrivere come l'interfaccia utente dovrebbe apparire. JSX permette di scrivere codice simile a HTML all'interno di file JavaScript, rendendo la definizione delle interfacce utente più intuitiva e leggibile.
## DESCRIVERE L'INTERFACCIA UTENTE (https://react.dev/learn/describing-the-ui)
### Importare ed esportare COMPONENTI
### Scrivere markup con JSX
### Javascript in JSX con le parentesi graffe
### Passare le proprietà ad un componente
### Renderizzamento condizionale
### Renderizzamento di liste

## AGGIUNGERE INTERATIVITA' (https://react.dev/learn/adding-interactivity)
### Rispondere agli eventi (event handlers)
### Lo stato: una memoria per i componenti(useState hook)
 Quando usi useState, crei uno stato che è legato al ciclo di vita del componente, ma gestito da React in modo più globale. Quando aggiorni lo stato con la funzione setter fornita da useState (ad esempio, setIndex se lo stato è [index, setIndex] = useState(0)), React sa che lo stato del componente è cambiato e quindi decide di **ri-renderizzare il componente**. Inoltre, **lo stato persiste tra i rendering** perché React lo conserva in una gestione interna dello stato dei componenti, che è separata dalla reinizializzazione delle variabili locali a ogni render.
 ### Trigger, render e commit(comportamento interno di react per gestire e mostrare i componenti)
 ### Accodare una serie di aggiornamenti dello stato
 ### Aggiornare variabili di stato oggetto (valutare l'uso della libreria Immer per aggiornare lo stato di variabili di stato oggetto molto annidate)
 ### Aggiornare variabili di stato array

## GESTIONE DELLO STATO (https://react.dev/learn/managing-state)
### Reagire agli input con lo stato
### Scegliere la struttura degli stati
### Condividere gli stati tra i componenti

## SOLUZIONI ALTERNATIVE (https://react.dev/learn/escape-hatches)