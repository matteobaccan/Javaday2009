# Javaday2009
Le mie slide di Javaday2009


Questo documento presenta una panoramica sull'integrazione di PHP e Java negli ambienti di sviluppo web.
L'obiettivo è illustrare come sfruttare i punti di forza di entrambi i linguaggi all'interno delle applicazioni web.
Il documento esplora due approcci principali:
●
PHP/Java Bridge:  Questa soluzione utilizza una classe PHP per stabilire una comunicazione basata su socket con un server Java. Questo consente agli sviluppatori PHP di utilizzare librerie Java all'interno delle loro pagine PHP.
○
Viene descritta l'esecuzione standalone del server JavaBridge.
○
Viene fornito un esempio di codice per la creazione di un oggetto StringBuffer in Java e la sua manipolazione in PHP.
○
Vengono illustrate diverse modalità di esecuzione del codice: tramite PHP, Java e all'interno di server applicativi come Tomcat e JBoss.
●
Quercus: Questa tecnologia, sviluppata da Caucho, è un'implementazione Pure Java di PHP 5. Quercus consente l'esecuzione di codice PHP all'interno di un ambiente Java, offrendo l'accesso a funzionalità Java come connection pool e sessioni clusterizzate.
○
Viene spiegata l'esecuzione di Quercus all'interno di Tomcat e la configurazione necessaria, inclusi i file di configurazione e le librerie.
○
Viene presentato un esempio di utilizzo di PHPMyAdmin eseguito tramite Quercus.
Il documento conclude con una discussione sull'utilità e la stabilità di queste configurazioni.
Oltre a queste informazioni tecniche, il documento include alcuni dettagli sul relatore, Matteo Baccan, e un annuncio di lavoro.
