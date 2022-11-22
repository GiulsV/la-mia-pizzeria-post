# la-mia-pizzeria-model

21/11/2022
Ciao ragazzi, andiamo avanti con l�applicazione per gestire la nostra pizzeria. Lo scopo di oggi � quello di rendere dinamici i contenuti che abbiamo come html statico nella pagina con la lista delle pizze.
Creiamo prima un nostro controller chiamato PizzaController e utilizziamo lui d�ora in avanti.
L�elenco delle pizze ora va passato come model dal controller, e la view deve utilizzarlo per mostrare l�html corretto.
Gestiamo anche la possibilit� che non ci siano pizze nell�elenco: in quel caso dobbiamo mostrare un messaggio che indichi all�utente che non ci sono pizze presenti nella nostra applicazione.
Ogni pizza dell�elenco avr� un pulsante che se cliccato ci porter� a una pagina che mostrer� i dettagli di quella singola pizza.
Dobbiamo quindi inviare l�id come parametro dell�URL, recuperarlo con la action, caricare i dati della pizza ricercata e passarli come model.
La view a quel punto li mostrer� all�utente con la grafica che preferiamo.
Ps. visto che abbiamo cambiato il controller sul quale lavoriamo, ricordiamoci di cambiare anche il �mapping di default� dei controller...altrimenti quale pagina viene caricata se richiamo l�url �/� della nostra webapp?