# Osservazioni — Esercitazione 0

Gruppo:

Componenti (nome, cognome e username GitHub di entrambi):

URL del repository condiviso:

Chi ha usato la tastiera nello step 1 e nello step 2:

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:

gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:

./hello con risultato: Hello, computional physics!

./hello > output.txt con risultato la creazione di un file in cui è riportato l'output di ./hello

Che cosa ho capito su sorgente ed eseguibile:

Diamo dei comando al calcolatore attraverso un file sorgente (in linguagio di programmazione), che viene compilato con i comandi sovrastanti; ne risulta un file che il compilatore è in grado di 'eseguire'(in linguaggio macchina. e' importante ricordare che dopo aver apporto modifiche al file sorgente è necessario compilare nuovamente affinché l'eseguibile le rifletta. (hello.c è sorgente, hello è eseguibile)


Output richiesto e comportamento del programma prima della modifica:



Esito dopo la modifica e spiegazione della correzione:

Modifichiamo il file sorgente e compiliamo nuovamente hello.c con il comando make saltando in questo modo il doppio step altrimenti richiesto; eseguendo ora ./hello  otteniamo l'output modificato

## Step 1 — Git

Quali file ho incluso nel commit e perché:

hello.c e osservazioni.md e commit appena svolta

Come ho verificato che la versione provata sia presente su GitHub:

Confrontare  l'identificativo dell'ultimo commit con quello mostrato da git log.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:

Prima di git pull non c'e cambiamento, dopo c'e, non serve un nuovo clone perché locale repositorio già creato e collegato al server remoto

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
