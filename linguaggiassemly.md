## Linguaggio assembly
Il linguaggio assembly è un linguaggio di programmazione di basso livello che si pone tra il linguaggio macchina e i linguaggi di programmazione di alto livello.
Le istruzioni in assembly sono strettamente correlate all'architettura del processore su cui si sta programmando, quindi non esiste un solo linguaggio assembly ma un linguaggio assembly per ciascuna architettura del processore. 
Ogni istruzione assembly corrisponde direttamente a un'istruzione di linguaggio macchina specifica, quindi vi è una corrispondenza uno-a-uno tra le istruzioni in linguaggio macchina e quelle del linguaggio assembly.
A ciascun codice operativo del linguaggio macchina viene associato, nei linguaggi assembly, un codice mnemonico.
Ad esempio al codice operativo dell'operatore di addizione viene associato il codice menemonioco ADD, in questo modo il programmatore non dovrà scrivere istruzioni in binario.
Ecco un esempio di codice Assembly, che è un linguaggio di programmazione di basso livello strettamente correlato al linguaggio macchina e più comprensibile per gli sviluppatori umani:

```assembly
MOV AX, 5   ; Carica il valore 5 nel registro AX
ADD AX, 3   ; Aggiungi 3 al valore nel registro AX
```

Questo è un esempio semplificato, ma dimostra come le istruzioni **Assembly** siano più comprensibili rispetto al linguaggio macchina puro. 
Un programma scritto in assembly non è direttamente eseguibile dal processore, ma deve essere tradotto in binario attraverso uno specifico programma detto **Assembler**.
Va notato che i linguaggi assembly sono specifici di ciascuna architettura, quindi, il codice assembly scritto per un'architettura non sarà direttamente eseguibile su un'architettura differente senza modifiche significative.

I **linguaggi assembly** hanno le seguenti caratteristiche:
- richiedono, da parte del programmatore, una conoscenza approfondita dell'architettura del processore
- consentono di realizzare software particolarmente performante utilizzando appieno le caratteristiche del processore
- non sono portabili in quanto il linguaggio assembly è specifico di ciascuna architettura del processore, quindi un codice assembly scritto per una particolare architettura deve essere nuovamente riscritto per una architettura diversa 
  
