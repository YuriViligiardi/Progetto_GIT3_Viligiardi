# Git - Working with Remotes

* I repository remoti sono versioni del tuo progetto che sono ospitate su internet
* La collaborazioni con altri programmatori implica la gestione di questi repository remoti e il push e il pull di dati
  
Fondamentale è sapere **sincronizzare il nostro lavoro locale con un repository remoto.**

*Comandi principali:*

<pre> git remote -v </pre> --> visualizza i server remoti collegati al nostro repository

## Aggiungere o rimuovere un repositori remoto

<pre> **git remote add <nome> <url>** </pre>

## Caricare il lavoro locale sul repository remoto

<pre> git push <remote> <ramo-locale> </pre>

## Aggiornare la copia locale del repository, alliniandola con la versione remota

<pre> git pull <remote> <ramo-locale> </pre>
