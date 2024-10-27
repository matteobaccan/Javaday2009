# Javaday2009

Le mie slide portate al Javaday 2009

## Riassunto

- Relatore: Matteo Baccan
- Data: Roma 24/1/2009
- Target: Programmatori PHP, Java e semplici curiosi
- Difficoltà: Media-Bassa

PHP e Java sono due linguaggi che possono tranquillamente convivere  all’interno di applicazioni web.

Vedremo come è possibile utilizzare librerie Java all’interno di pagine PHP e come è possibile utilizzare PHP all’interno di application server Java, utilizzando un interprete scritto anch’esso in Java.

In questo modo è possibile sfruttare il meglio dei due mondi, e sfruttare i propri skill php anche in ambienti nati per altri linguaggi

Tutto questo in 40 minuti :)

## Di cosa parlo?

Questo documento presenta una panoramica sull'integrazione di PHP e Java negli ambienti di sviluppo web.

L'obiettivo è illustrare come sfruttare i punti di forza di entrambi i linguaggi all'interno delle applicazioni web.

Il documento esplora due approcci principali:

● PHP/Java Bridge:  Questa soluzione utilizza una classe PHP per stabilire una comunicazione basata su socket con un server Java. Questo consente agli sviluppatori PHP di utilizzare librerie Java all'interno delle loro pagine PHP.

- Viene descritta l'esecuzione standalone del server JavaBridge.
- Viene fornito un esempio di codice per la creazione di un oggetto StringBuffer in Java e la sua manipolazione in PHP.
- Vengono illustrate diverse modalità di esecuzione del codice: tramite PHP, Java e all'interno di server applicativi come Tomcat e JBoss.

● Quercus: Questa tecnologia, sviluppata da Caucho, è un'implementazione Pure Java di PHP 5. Quercus consente l'esecuzione di codice PHP all'interno di un ambiente Java, offrendo l'accesso a funzionalità Java come connection pool e sessioni clusterizzate.

- Viene spiegata l'esecuzione di Quercus all'interno di Tomcat e la configurazione necessaria, inclusi i file di configurazione e le librerie.
- Viene presentato un esempio di utilizzo di PHPMyAdmin eseguito tramite Quercus.

Il documento conclude con una discussione sull'utilità e la stabilità di queste configurazioni.
