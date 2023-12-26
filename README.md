# Ansible

Script Ansible per la configurazione rapida del serverr



## Include Task

Per fare in modo di riutilizzare i playbook che si scrivono occorre utilizzare l'opzione `import_task`, se si fa in questo modo occorre che i file che si vanno ad importare tramite questo abbiano una struttura precisa ovvero siano solamente un elenco di tasks.


## Prompt Interattivi

E' possibile attraverso ansible realizzare dei prompt interattivi per fornire
gli input da riga di comando, quindi potrebbe essere un idea andare a setuppare
le variabili in questo modo e poi lanciare lo script di configurazione

`vars_prompt`
