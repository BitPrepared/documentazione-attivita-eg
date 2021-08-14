# Mayalinux

## Obiettivi

Mostrare che "dietro" al device, "under the hood", c'è molto altro. Non è magia!

## Attività

L'attività si svolge in due diverse fasi:
### Spiegazione dei comandi del terminale
Chi spiega ha un mouse in mano, ai ragazzi viene chiesto di pensare a **tutte** le cose che si possono fare con un mouse (copia, incolla, taglia, crea nuova cartella, apri file, esegui file (se eseguibile), ecc..). Ciò che dicono i ragazzi verrà segnato su un cartellone (meglio se con lavagna in modo che tutti riescano a vedere).

"Tutte le azioni indicate si possono eseguire anche in altri modi, in particolare vedremo come fare con il terminale!"
		
A questo punto verrà spiegato, per ogni azione indicata dai ragazzi sul cartellone, come questa si può fare con il terminale (es. "a tasto destro del mouse, copia (e incolla), corrisponde il comando cp - ecc..).

### Gioco a Mayalinux

Terminata la spiegazione dei comandi si spiega il gioco.
		
Si consiglia di provare a giocare prima dell'attività in modo da conoscere i comandi e il gioco stesso.

I ragazzi giocheranno tutti alla stessa versione del gioco (l'ultima è Star Wars, la 3).

Il gioco inizierà con un labirinto, il consiglio è di segnarsi i "passi" che si fanno all'interno del labirinto perchè ci sono punti morti dai quali uscire.

E' importante spiegare bene il labirinto! Nel labirinto ci si muoverà cambiando directory (ovvero con il comando "cd" seguito dal nome della cartella nella quale vogliamo andare). I nomi delle cartelle possono essere "a" (avanti), "d" (destra), "s" (sinistra) oppure ".." (indietro); con "cd ..", per esempio, si tornerà indietro e con "cd d" si andrà a destra nel labirinto. Capita che qualcuno scriva "cd.." oppure "cda": specificare che serve lo spazio tra il "cd" e il nome della cartella. Stessa cosa per gli altri comandi (es. "cp spada_laser equipaggiamento" invece di "cpspada_laser equipaggiamento".
	
Nella cartella di ogni livello c'è un file leggimi.txt e un file azione.sh. Il file leggimi.txt spiega il livello corrente e che cosa c'è da fare; azione.sh serve invece per passare al livello successivo. E' quindi importante che si sottolinei, nella spiegazione del gioco, che **all'inizio di ogni livello si deve leggere il file txt** . Per eseguire azione.sh, invece, è necessario usare il comando "source azione.sh" e non "./azione.sh".
	
Il penultimo livello (ore e minuti) è un indovinello; spesso c'è bisogno di aiutare i ragazzi, soprattutto se si nota che impiegano molto tempo a capire il meccanismo. L'idea è: il numero delle ore corrisponde alla posizione nella quale si dovrà usare la lettera nella nuova parola, il numero dei minuti è la posizione della lettera da prendere dalla parola in "archivio". Ad esempio "03:06 obiwankenobi" significa che la terza lettera della parola da comporre sarà "n", perchè in posizione 6 nella parola "obiwankenobi".


