RUNNING MANAGER — versione PWA

CONTENUTO
- index.html: applicazione
- manifest.webmanifest: impostazioni installazione
- service-worker.js: cache offline
- icon-192.png / icon-512.png: icone

PUBBLICAZIONE
Questa cartella deve essere pubblicata su un hosting statico con HTTPS. Non basta aprire index.html come file locale: il service worker richiede un sito HTTPS (oppure localhost per test).
Non è stata effettuata alcuna pubblicazione online.

PRIMO AVVIO
1. Pubblica tutti i file mantenendo la stessa cartella e struttura.
2. Apri l'indirizzo HTTPS una prima volta con Internet attivo e attendi il caricamento completo.
3. Su iPhone: apri il sito in Safari > Condividi > Aggiungi alla schermata Home.
4. Su Mac: apri il sito in Safari o Chrome; usa il comando di installazione/Aggiungi al Dock se disponibile.
5. Apri l'app almeno una volta online. Dopo che la cache è stata installata, l'interfaccia può aprirsi offline.

DATI E BACKUP
I dati rimangono nel browser/dispositivo e non vengono sincronizzati automaticamente.
Il backup JSON dell'app è il metodo per trasferire l'archivio tra Mac e iPhone. Prima di cambiare browser, cancellare dati del sito o reinstallare, esporta un backup.
L'archivio eventualmente salvato nella vecchia versione aperta come file locale non viene trasferito automaticamente alla versione HTTPS: esporta il backup dalla vecchia versione e importalo nella nuova.

NOTA
Questa è una prima confezione PWA basata sul prototipo esistente. Prima di affidarle dati importanti, verifica su entrambi i dispositivi: aggiunta atleta, salvataggio allenamento, backup e ripristino, riapertura offline.
