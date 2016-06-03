# Limitazioni e Problemi
---
##Punti deboli
---
Tor presenta una serie di punti deboli che vanno considerati da ogni utilizzatore del programma:
* Gli **exit node** possono leggere tutto il traffico di tutti gli utenti tor che li usano agendo effettivamente da **man in the middle** per la natura stessa del protocollo.
* Tor viene convenzionalmente usato per mascherare l'origine del traffico HTTP, però un utente inesperto potrebbe **abilitare vari plugin del browser** che sono in grado di **comunicare in rete liberamente** (ad esempio **Adobe Flash** e **Microsoft Silverlight**) e dunque finirebbero per **contattare direttamente il destinatario senza passare per Tor** rendendo potenzialmente vani i tentativi di preservare l'anonimato.
* Un sito web potrebbe includere tra i propri script delle subroutine (sottoprogramma) in grado di **ottenere informazioni sul sistema client** compromettendo l'anonimato.
* Un utente potrebbe **lasciare indizi sulla propria identità** durante la normale navigazione sul web tramite Tor.
<br/>
Queste considerazione non comprendono la possibilità di attacchi mirati al controllo della rete Tor che rischierebbero di compromettere l'anonimato e la privacy di tutti gli utenti.
##Lentezza
---
La rete Tor è **estremamente lenta** perché:
* ogni nodo deve sottoporre ogni pacchetto a grande quantità di operazioni di crittografia.
* è impossibile stabilire il contenuto dei pacchetti e dunque è impossibile scartare quelli inutili o pericolosi.
* i pacchetti sono incapsulati in numerosi strati crittografici, che aumentano di molto la dimensione dei dati da inviare.
* potrebbe essere necessario ricalcolare spesso il percorso di routing a causa dell'instabilità dei nodi.
Per questi motivi è anche possibile **saturare la rete con dati inutili come deterrente per gli utenti di Tor.**
##Exit node monitoring
---
Operando un **Exit Node** è possibile catturare tutto il traffico degli utenti **Tor** poichè come visto prima, **Tor** protegge il traffico solo fino all'**exit node**. Se il traffico dall'**exit node** alla destinazione finale non è crittografato, l'**exit node** può leggere il traffico senza problemi.