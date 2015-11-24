# Addin-Ciurmy-Cuby-VBA
Addin in VBA messo a disposizione della piattaforma www.ciurmy.com 
per permettere agli utenti di Ciurmy di interagire con la piattaforma utilizzando Excel.

# Cosa puoi fare con l'Addin per Excel di Ciurmy?
Lo puoi usare per utilizzare il cloud storage di Ciurmy, che noi chiamiamo Cuby:
>* Con Cuby, puoi salvare e tracciare i dati delle tue tabelle excel, inviando a Ciurmy dei dati inseriti all'interno di un range di celle. L'invio viene effettuato immettendo le celle da archiviare all'interno della formula **cuby_set()**, che Cuby mette a disposizione, e nominando il cubo di dati con un identificativo scelto dall'utente
>* Con Cuby, puoi ricevere i dati archiviati da te in Ciurmy direttamente nelle celle di Excel, usando la formula **cuby_get()**
>* Con Cuby, puoi ricevere i Report di tutti i tuoi Cuby direttamente sulle celle di Excel; il report si realizza immettendo nella formula **cuby_report()** l'identificativo del Cuby di dati immagazzinato in Ciurmy
>* Con Cuby, puoi creare un link per permettere anche ad altri utenti di scaricare il tuo Cuby direttamente su Excel usando la formula **cuby_from_link()**. Il link si crea tramite la formula **cuby_create_link**, dove si indica l'identificativo del Cuby di dati, il proprio nome utente e la propria password di accesso a Ciurmy

Lo puoi usare per comprare potenza computazionale in Ciurmy:
>* Puoi acquistare la potenza di calcolo che ti serve per i tuoi algoritmi che richiedono molta potenza computazionale. Il codice deve essere inviato a Ciurmy usando l'upload presente nella pagina 'Miei Codici' (visibile dopo il login) o facendo riferimento al codice pubblicato nello store. Il codice deve essere obbligatoriamente in javascript
>* La formula per comprare potenza di calcolo è **ciurmy_buy()** e vanno imputati i parametri relativi all'ordine. Per maggiori informazioni andare nella FAQ "Comprare da remoto"
>* Puoi ricevere i risultati dell'elaborazione direttamente in Excel. Per visualizzarli si deve utilizzare la formula **ciurmy_result()**
>* Puoi vedere il report del calcolo in atto come acquirente, tramite l'utilizzo della formula **ciurmy_report()**

