# Come funziona
---
La rete di Tor usa una topologia a maglia: ogni utente connesso consiste in un **nodo anche detto relay**. Un nodo può
anche fungere da **nodo di uscita (exit node, exit relay)**, ovvero prende i pacchetti originati da altri nodi e li spedisce al
reale destinatario fuori dalla rete Tor (ad esempio un sito web).

![](tor1.png)

* Alice recupera la lista dei **nodi** della rete Tor da un **directory server**.
* Alice si collega direttamente a uno dei **nodi** della rete Tor.


![](tor2.png)

* Il client Tor di Alice sceglie un percorso per raggiungere la destinazione dei dati.
* I collegamenti **in verde** sono **crittografati** mentre quelli in rosso sono **non necessariamenti protetti**.





