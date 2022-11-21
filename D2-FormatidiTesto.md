# Codifica del Testo
## Codifica

La **codifica** è quel processo che ci permette di:

> *esprimere informazioni e messaggi mediante le regole e i simboli di un sistema convenzionale (il codice) stabilito concordemente dall’emettitore e dal ricevitore dei messaggi allo scopo di trasmettere o elaborare automaticamente le informazioni* - **Treccani**

Nei calcolatori il **testo è memorizzato come sequenza binaria,** la codifica del testo si occupa di **definire** la **corrispondenza** tra una sequenza binaria e il corrispondente carattere alfanumerico.

Prendiamo ad esempio la codifica *Windows-1252*, Il carattere “é” è salvato in memoria usando la sequela binaria che in esadecimale corrisponde al valore “E9”, mentre per la codifica DOS latin-1 il valore “E9” corrisponde al carattere “Ú”

La difficoltà è quindi duplice:

- È necessario **scegliere** con cura, a seconda dell'applicazione di destinazione, la **codifica da utilizzare** quando si salva un testo 
- Quando è il momento di visualizzare un testo, è necessario **poter determinare la codifica utilizzata**

## Codifica ASCII 

Quantità di informazione da rappresentare (considerando l’alfabeto inglese): 26 lettere + le 26 lettere maiuscole + 10 cifre decimali + 30 caratteri circa di uso comune (., *, %, etc.) + alcuni caratteri di controllo (spazi, interruzione di riga) ovvero 120 caratteri circa ‣ Numero di BIT necessari: bastano 7 bit poiché 27 = 128 > 120 ‣ Su questa base è stato creato il codice ASCII, basato appunto sull’uso di 7 bit per ogni carattere
