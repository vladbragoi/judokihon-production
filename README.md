# A.S.D. Judo Kihon Bovolone - Production Environment

Questo repository contiene esclusivamente i **file compilati e minimizzati** (file statici) per l'ambiente di Produzione del sito web ufficiale.  
Il sito è servito tramite GitHub Pages all'indirizzo ufficiale: **[www.judokihon.it](https://www.judokihon.it)**

⚠️ **ATTENZIONE:** 
Non effettuare mai modifiche manuali a file, immagini o documenti all'interno di questo repository! 

Questo è un repository "figlio" (target di deployment). Tutto il vero codice sorgente, le logiche React, le configurazioni JSON e le pipeline GitHub Actions risiedono nel repository padre:
👉 **[vladbragoi/judokihon-website](https://github.com/vladbragoi/judokihon-website)**

Ogni volta che una versione viene approvata e inviata sul branch `main` del repository padre, il server compila in automatico il codice e sovrascrive il contenuto di questo repository.
