# a-very-sad-project
#Traccia SAD – Taffit 
#
#Si vuole realizzare un sistema software per la gestione di autonoleggi, in particolare si vogliono gestire i parchi auto dei gestori con le relative prenotazioni da parte degli utenti. 
#
#Al fine di effettuare l’accesso al sistema, un gestore di un autonoleggio inserisce i propri dati (codice identificativo/username, password). Il sistema poi verifica la correttezza dei dati inseriti, in caso di riscontro, mostra l’interfaccia utente per il gestore.  
#
#A seguito dell’operazione di login, il gestore vuole visualizzare lo stato del suo parco auto. Nello specifico, il gestore può visualizzare la lista dei veicoli noleggiati e quella dei veicoli disponibili.  
#
#Il gestore dopo essersi autenticato può inserire un nuovo veicolo nel proprio parco auto, specificando i relativi attributi (targa,tipologia,motorizzazione,kilometraggio…). Confermato l’inserimento il database viene aggiornato e il sistema mostra a video un messaggio di conferma.  
#
#Un qualsiasi utente può fare richiesta per il noleggio di un veicolo. Inserendo il periodo di noleggio (data inizio e data fine), attributi del veicolo desiderato (tipologia,motorizzazione,…), luogo di ritiro e consegna (necessariamente stessa sede), il sistema mostrerà a video la lista di veicoli disponibili, permettendo all’utente di noleggiare quello che più si adatta alle proprie esigenze. Per finalizzare il noleggio del veicolo, l’utente deve inserire i propri dati anagrafici, dati della patente e indicare un metodo di pagamento valido. In seguito alla prenotazione il sistema dovrà aggiornare lo stato del veicolo e mostrare a video un messaggio di conferma che conterrà un riepilogo della prenotazione stampabile dall’utente.  
#
#Il sistema periodicamente (una volta al giorno) dovrà controllare le date di fine noleggio delle prenotazioni e aggiornare lo stato dei veicoli qualora una prenotazione sia scaduta. (chiedere alla prof se l’aggiornamento dello stato dell’autovettura è meglio che sia un caso d’uso dell’utente, del gestore o del sistema). 
