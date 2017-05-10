---
layout: default
---

## Descrizione  
Il corso, partendo dai concetti di **clustering** e **orchestrazione** di container, propone una visione complessiva sulla **modalità Swarm** di Docker. Con un taglio DevOps affronteremo sia la configurazione e l'amministrazione del cluster, sia le pratiche per eseguire e aggiornare i vostri servizi applicativi. 

### Livello: Base

### Durata: 3 sessioni
 
### Svolgimento delle sessioni:  
Le sessioni on site sono previste nei giorni:  

- **mercoledì 26 aprile dalle 19:00 alle 21:00.**   
- **mercoledì 03 maggio dalle 19:00 alle 21:00.**  
- **mercoledì 10 maggio dalle 19:00 alle 21:00.** 

Per la natura del corso è consigliato frequentare tutte le sessioni.
Ogni sessione, della durata di 2 ore, prevede questi momenti formativi:

- una presentazione in cui vengono introdotti e descritti i nuovi concetti  
- una dimostrazione pratica degli strumenti e dei comandi descritti  
- l'assegnazione di esercitazioni pratiche individuali o a piccoli gruppi  
- Un momento di revisione delle esercitazioni assegnate

### Tools:

- Le esercitazioni pratiche sono svolte utilizzando la piattaforma [GitHub Classroom](https://classroom.github.com){:target="_blank"} che consente di creare un ambiente di lavoro dedicato per ogni studente e semplifica la verifica. **Richiedi l'accesso al Docente!**    
- E' presente una chat dedicata per il corso [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/LOG-ED/docker-swarm?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)  
- L'editor consigliato è [Visual Studio Code](https://code.visualstudio.com/){:target="_blank"}. 

### Requisiti:
 
E' preferibile una conoscenza base di Docker.  
Porta il tuo pc, il corso è molto pratico!

## Docenti

### Federico Minzoni

- fminzoni@enter.eu 
- https://github.com/f-minzoni

Sono un programmatore e smanettone della prima ora. Appassionato da sempre di Git, MongoDB, Rich Internet Application, IOT, Cloud Computing, da diversi mesi ho aggiunto alla lista, Docker e le architetture a Microservizi. Due temi che, insieme, stanno rivoluzionando l'intero processo di sviluppo e rilascio delle applicazioni sul Cloud. Ambito in cui lavoro da oltre 3 anni, in Enter, occupandomi della piattaforma [Enter Cloud Suite](http://www.entercloudsuite.com){:target="_blank"}.

### Mattia Scalvini

- mscalvini@enter.eu 
- https://github.com/Matsca09

## Agenda

### Prima sessione
 
**Clusterizzazione e Orchestrazione.** Dopo un'iniziale presentazione del corso, ripercorreremo insieme lo sviluppo della componente Swarm di Docker, da progetto standalone a modalità built-in del Docker Engine.  
In questa prima sessione vedremo quali sono le caratteristiche (in termini di funzionalità e tecnologie) di un orchestratore e quali di queste sono fornite da Docker Swarm.

#### Materiali

- [Docker Swarm Standalone](https://github.com/docker/swarm)
- [Raft](http://thesecretlivesofdata.com/raft/)
- [SwarmKit](https://github.com/docker/swarmkit)

### Seconda sessione

**Funzionalità di Docker Swarm** Con un recap iniziale, ripercorreremo tutti i concetti visti finora, step-by-step, per avviare i servizi con Docker Swarm e per valutarne il funzionamento. Vedremo come utilizzare la funzionalità di deploy specifica per Swarm e le logiche di scheduling e networking.

#### Materiali

- [Swarm Mode](https://docs.docker.com/engine/swarm/)
- [Example App](https://github.com/docker/example-voting-app)
- [Compose file format](https://docs.docker.com/compose/compose-file/)

### Terza sessione

**Docker per la produzione.** In questa terza sessione, dopo il classico recap iniziale, vedremo come amministrare un cluster Docker affrontando problematiche legate all'alta affidabilità e alla sicurezza, necessarie per la produzione. Insieme proveremo una delle ultime funzionalità introdotte per la gestione dei secrets.

- [Deploy services to a Swarm](https://docs.docker.com/engine/swarm/services/)
- [Deploy Configuration](https://docs.docker.com/compose/compose-file/#deploy)
- [Docker Secrets](https://docs.docker.com/engine/swarm/secrets/#simple-example-get-started-with-secrets)

