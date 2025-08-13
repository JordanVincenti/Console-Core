# ConsoleCore

**ConsoleCore** è un plugin per **Minecraft 1.19.4** scritto in **Java** che funge da *core admin tool*, permettendo di eseguire **comandi della console direttamente in game** e includendo un set completo di comandi amministrativi, gestione giocatori, controllo mondo, gestione server e utilità varie.

---

## ✨ Funzionalità principali
- Esecuzione comandi console in game.
- Gestione completa di giocatori, mondo e server.
- Comandi rapidi e scorciatoie per funzioni comuni.
- Sistema di permessi avanzato.

---

## 📜 Comandi, descrizioni e permessi

| Comando | Descrizione | Permesso |
|---------|-------------|----------|
| `/console <comando>` | Esegue qualsiasi comando come console. | `console.console` |
| `/sudo <giocatore> <comando>` | Forza un giocatore a eseguire un comando o messaggio. | `console.sudo` |
| `/kick <giocatore> [motivo]` | Espelle un giocatore. | `console.kick` |
| `/ban <giocatore> [motivo]` | Banna un giocatore. | `console.ban` |
| `/tempban [-s] <giocatore> [tempo]` | Banna temporaneamente un giocatore. | `console.tempban` |
| `/unban <giocatore>` | Rimuove un ban. | `console.unban` |
| `/mute <giocatore> [tempo]` | Silenzia un giocatore. | `console.mute` |
| `/unmute <giocatore>` | Rimuove il silenziamento. | `console.unmute` |
| `/tp <giocatore>` | Teletrasporto verso un giocatore. | `console.tp` |
| `/tphere <giocatore>` | Teletrasporta un giocatore a sé. | `console.tphere` |
| `/tpall` | Teletrasporta tutti a sé. | `console.tpall` |
| `/freeze <giocatore>` | Blocca un giocatore sul posto. | `console.freeze` |
| `/invsee <giocatore>` | Visualizza inventario di un giocatore. | `console.invsee` |
| `/clearinv [giocatore]` | Svuota l’inventario di un giocatore. | `console.clearinv` |
| `/endersee <giocatore>` | Visualizza Ender Chest di un giocatore. | `console.endersee` |
| `/speed <1-10>` | Modifica la velocità di camminata/volo. | `console.speed` |
| `/vanish` | Rende invisibile agli altri giocatori. | `console.vanish` |
| `/time set <giorno / notte / valore>` | Imposta l’orario. | `console.time` |
| `/time add <tick>` | Aggiunge tempo al mondo. | `console.time` |
| `/weather <sole / pioggia / temporale>` | Cambia il meteo. | `console.weather` |
| `/gamerule <regola> <valore>` | Modifica le gamerule. | `console.gamerule` |
| `/day` | Imposta giorno. | `console.day` |
| `/night` | Imposta notte. | `console.night` |
| `/sun` | Meteo sereno. | `console.sun` |
| `/storm` | Pioggia/temporale. | `console.storm` |
| `/killall <tipo>` | Rimuove entità specifiche. | `console.killall` |
| `/setspawn` | Imposta spawn globale. | `console.setspawn` |
| `/spawn` | Teletrasporta allo spawn. | `console.spawn` |
| `/worldtp <mondo>` | Cambia mondo. | `console.worldtp` |
| `/stopserver` | Arresta il server. | `console.stopserver` |
| `/reloadserver` | Ricarica il server. | `console.reloadserver` |
| `/listplayers` | Mostra giocatori online. | `console.listplayers` |
| `/serverinfo` | Mostra TPS, memoria e uptime. | `console.serverinfo` |
| `/broadcast <messaggio>` | Messaggio globale. | `console.broadcast` |
| `/msg <giocatore> <messaggio>` | Messaggio privato. | `console.msg` |
| `/reply <messaggio>` | Risponde all’ultimo messaggio. | `console.reply` |
| `/heal [giocatore]` | Cura un giocatore. | `console.heal` |
| `/feed [giocatore]` | Riempie la fame. | `console.feed` |
| `/fly [giocatore] <on/off>` | Attiva/disattiva volo. | `console.fly` |
| `/god [giocatore] <on/off>` | Invincibilità. | `console.god` |
| `/hat` | Indossa oggetto in mano come cappello. | `console.hat` |
| `/repair` | Ripara oggetto in mano. | `console.repair` |
| `/repairall` | Ripara tutti gli oggetti. | `console.repairall` |
| `/enchant <incantesimo> <livello>` | Applica incantesimo. | `console.enchant` |
| `/give <giocatore> <item> [quantità]` | Dai oggetti. | `console.give` |
| `/more` | Riempie stack in mano. | `console.more` |
| `/workbench` | Apre crafting virtuale. | `console.workbench` |
| `/anvil` | Apre incudine virtuale. | `console.anvil` |
| `/enderchest` | Apre propria Ender Chest. | `console.enderchest` |
| `/back` | Torna alla posizione precedente. | `console.back` |

---

## 💸 Prezzo
- **Plugin base:** 5€  
- **Plugin base + modifiche:** 7€  
- **Plugin completamente modificato:** 10€  

⚠️ **Attenzione:** Le modifiche saranno apportate **solo ed esclusivamente al plugin richiesto**.  
Se si richiedono modifiche al plugin X, **non** si può chiedere di modificare anche il plugin Y senza pagare una nuova modifica.  
Non è possibile richiedere modifiche troppo eccessive (es: trasformare il plugin X in un plugin Y completamente diverso).

---

## ⚕️ Termini di Servizio (TOS)

### Licenza e utilizzo
Il plugin acquistato è concesso in licenza per **uso personale** o sul **proprio server**.  
Non puoi rivendere, condividere o distribuire il plugin senza il mio permesso scritto.

### Garanzia e supporto
Il plugin è fornito *"così com'è"*, senza garanzie esplicite o implicite.  
Offro supporto tecnico limitato via [email/forum/discord], ma **non garantisco** la compatibilità con tutte le versioni di Minecraft o altri plugin.

### Aggiornamenti
Gli aggiornamenti sono a mia discrezione e possono essere gratuiti o a pagamento.  
Non sono obbligato a rilasciare aggiornamenti o correzioni.

### Responsabilità
Non sono responsabile per danni diretti o indiretti derivanti dall’uso del plugin, inclusa la perdita di dati o malfunzionamenti del server.

### Restituzioni e rimborsi
Non prevedo rimborsi dopo l’acquisto, salvo casi di plugin non funzionante e verificabile entro **7 giorni** dall’acquisto.

### Modifiche ai termini
Mi riservo il diritto di modificare questi termini in qualsiasi momento.  
L’uso continuato del plugin implica l’accettazione delle nuove condizioni.
