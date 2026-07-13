# Changelog — IFG Returns & Withdrawals

<div class="lang-switcher" markdown="1">
[<img src="../assets/flags/gb.svg" alt="" class="flag-icon"> English](../changelog.html) · <img src="../assets/flags/it.svg" alt="" class="flag-icon"> **Italiano** · [<img src="../assets/flags/de.svg" alt="" class="flag-icon"> Deutsch](../de/changelog.html) · [<img src="../assets/flags/fr.svg" alt="" class="flag-icon"> Français](../fr/changelog.html) · [<img src="../assets/flags/es.svg" alt="" class="flag-icon"> Español](../es/changelog.html)
</div>

Un registro continuo delle novità e dei miglioramenti. L'app viene aggiornata di frequente man mano che perfezioniamo il flusso di gestione dei resi e del diritto di recesso UE.

## 0.3.207 – 0.3.220 — Luglio 2026
- **Aggiunto** — La chat di assistenza integrata nell'app ora funziona con una vera intelligenza artificiale conversazionale (Claude, con Gemini come fallback), ricorda la conversazione invece di rispondere messaggio per messaggio e risponde nella lingua in cui scrivi.
- **Aggiunto** — Quando chiedi di parlare con una persona, la conversazione resta aperta e la risposta del commerciante ora appare direttamente nella stessa chat — non più un "ti risponderemo via email".
- **Migliorato** — La pagina di assistenza è stata riprogettata attorno a 20 FAQ spiegate chiaramente (rispetto alle 10 precedenti), tradotte integralmente in tutte le 30 lingue; la chat ora si trova solo nel widget flottante, disponibile da ogni pagina.
- **Aggiunto** — Nuova impostazione per stabilire chi copre il costo della spedizione di reso (cliente o commerciante), comunicata automaticamente al cliente nel modulo di reso e nell'email di conferma.
- **Aggiunto** — Un promemoria legale ora calcola la scadenza del rimborso UE a partire dalla data della richiesta originale del cliente, non da quando il commerciante la approva.
- **Corretto** — Un ordine con più colli non blocca più la finestra di recesso solo perché un collo è ancora in transito; la finestra ora si avvia quando tutti i colli sono arrivati.
- **Corretto** — Le richieste di reso su ordini meno recenti (finestre di recesso superiori a 60 giorni) vengono ora verificate correttamente invece di mostrare "ordine non trovato".
- **Modificato** — Le nuove installazioni dell'app partono ora in inglese per impostazione predefinita, anche durante l'onboarding guidato; la lingua dell'interfaccia e delle email può comunque essere cambiata in qualsiasi momento tra le 30 lingue supportate.

## 0.3.206 — Luglio 2026
- **Migliorato** — La panoramica Analytics è stata riprogettata in un riepilogo più chiaro a 6 schede: numero di resi, tasso di approvazione, tempo medio di elaborazione, rimborsi emessi, valore medio articolo e suddivisione tra resi totali/parziali.

## 0.3.205 — Luglio 2026
- **Corretto** — Risolto un problema che impediva a una pagina di caricarsi correttamente durante l'aggiornamento della sessione integrata nell'Admin Shopify.
- **Corretto** — I pulsanti relativi ad azioni già completate ora diventano visibilmente inattivi invece di restare con un colore che suggerisce un'azione disponibile.
- **Migliorato** — Affinato il testo del riferimento legale che descrive il diritto di recesso UE nell'app e nel modulo dello storefront.
- **Corretto** — Un grafico con una sola categoria nella pagina Analytics non viene più mostrato come un'unica barra sovradimensionata; il layout e i tag di categoria prodotto ora vanno a capo correttamente sugli schermi piccoli.

## 0.3.203 – 0.3.204 — Luglio 2026
- **Migliorato** — Il modulo di reso dello storefront è ora disponibile ovunque per gli acquirenti, con la stessa logica di 30 lingue e testo legale applicata in modo coerente.
- **Corretto** — Perfezionata la dicitura legale nel modulo per citare con precisione la direttiva UE sul diritto di recesso e il suo emendamento del 2026.

## 0.3.198 – 0.3.202 — Giugno–Luglio 2026
- **Aggiunto** — Flusso di revisione dei casi riprogettato: Approva richiesta → Conferma ricezione merce → seleziona articoli e importo → Rimborsa, con un passaggio di conferma prima dell'emissione di qualsiasi rimborso.
- **Aggiunto** — Colori di stato distinti per ogni fase (in attesa, approvato, parzialmente approvato, rimborsato, parzialmente rimborsato, rifiutato) mostrati in modo coerente nella dashboard, nell'elenco dei casi e nella vista di dettaglio del caso.
- **Migliorato** — Analytics ricostruita con schede di riepilogo più chiare e ripartizioni per stato/motivo.
- **Migliorato** — L'assistente di supporto ora risponde nella stessa lingua in cui scrive il commerciante.

## Versioni precedenti
Hanno introdotto il nucleo dell'app: onboarding guidato con configurazione dei dati legali dell'azienda e dell'indirizzo di reso, i tre blocchi di reso per lo storefront (incorporato, pop-up e flottante), rimborsi diretti in-app sui piani idonei, ricevute PDF ed esportazione CSV, Restrizioni Prodotto, e localizzazione completa in 30 lingue — incluso il layout da destra a sinistra per arabo ed ebraico.

---
IFG Returns & Withdrawals — realizzato da IFG eCommerce. Domande su una versione specifica? [info@ifgecommerce.com](mailto:info@ifgecommerce.com)
