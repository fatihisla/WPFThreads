# WPFThreads
Realizzare un programma WPF multithreads per visualizzare un conteggio da 0 a 1000 che utilizza il costrutto lock() {}

-Descrizione parti codice WPFThreads:

Nel seguente programma siamo andati a generare un contatore di numeri con l'aiuto dei Threads che al'inizio  aveva causato dei problemi sul programma e poi abbiamo aggiustato aggiungendo uno Sleep e un Lock. Abbiamo creato un counter di giri e una costante di giri così che il programma sapesse gia da dove partire e che oltre quel limite non dovesse andare.

-Threads:
Sono sotto-processi che posso eseguirsi in parallelo o in serie ad'altri. Per far eseguire il codice regolarmente, senza che si blocchi, abbiamo aggiunto un Lock e uno Sleep.

-Sleep:
Questo comando serve per sospendere il thread corrente per i millisecondi che andiamo ad indicare.

![image](https://user-images.githubusercontent.com/116791165/231689093-30ac0959-5e2a-444c-b3f9-f7ae573a50df.png)

-LAMBDA ESPRESSION:
Si usa un'espressione lambda per creare una funzione anonima. Usare l'operatore di dichiarazione lambda => per separare l'elenco di parametri dell'espressione lambda dal corpo. Un'espressione lambda può essere di una delle due forme seguenti:

(input-parameters) => { <sequence-of-statements> }

 (input-parameters) => expression
  
-C#  COSTRUTTORE LOCK
  L'istruzione lock acquisisce il blocco a esclusione reciproca per un oggetto specificato, esegue un blocco di istruzioni e quindi rilascia il blocco. Mentre è attivo un blocco, il thread che contiene il blocco può ancora acquisire e rilasciare il blocco. Gli altri thread non possono acquisire il blocco e devono attendere finché il blocco non viene rilasciato. L'istruzione lock garantisce che un singolo thread abbia accesso esclusivo a tale oggetto.


//le informazioni sono state prese per lo più da professor Maurizio Conti e dal sito microsoft.com
