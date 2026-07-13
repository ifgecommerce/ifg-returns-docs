---
title: IFG Returns & Withdrawals
description: Documentazione, FAQ e pagine legali per l'app Shopify IFG Returns & Withdrawals.
---

# Privacy e gestione dei dati

[← Centro Assistenza](index.html)

<div class="lang-switcher">
  <a class="lang-item" href="../"><img src="../assets/flags/gb.svg" alt="" class="flag-icon">English</a>
  <span class="lang-item lang-current"><img src="../assets/flags/it.svg" alt="" class="flag-icon">Italiano</span>
  <a class="lang-item" href="../de/"><img src="../assets/flags/de.svg" alt="" class="flag-icon">Deutsch</a>
  <a class="lang-item" href="../fr/"><img src="../assets/flags/fr.svg" alt="" class="flag-icon">Français</a>
  <a class="lang-item" href="../es/"><img src="../assets/flags/es.svg" alt="" class="flag-icon">Español</a>
</div>

Questa pagina descrive come l'app stessa raccoglie, utilizza e conserva i dati. Documenta il comportamento tecnico dell'app — non sostituisce la politica sulla privacy aziendale di IFG eCommerce e non costituisce consulenza legale.

## Cosa viene raccolto

Quando un cliente invia un reso tramite il modulo dello storefront: nome, cognome, indirizzo di spedizione, email, numero d'ordine e, facoltativamente, numero di telefono e note. L'app legge inoltre i dati dell'ordine da Shopify (numero d'ordine, email, data dell'ordine, stato di evasione) per verificare che la richiesta sia autentica.

I commercianti forniscono inoltre i propri dati legali aziendali e l'indirizzo di reso durante l'onboarding, utilizzati per generare comunicazioni di recesso e ricevute conformi.

## Perché viene raccolto

- Per verificare che una richiesta di reso corrisponda a un ordine reale (prevenzione delle frodi).
- Per elaborare il reso/rimborso e generare le email di conferma e le ricevute PDF.
- Per rispettare gli obblighi UE in materia di diritti dei consumatori (Direttiva 2011/83/UE e il relativo emendamento 2023/2673), che richiedono di identificare il cliente e il contratto.

## Con chi viene condiviso

- **Shopify** — per verificare gli ordini e, sui piani idonei, per emettere rimborsi diretti (Shopify Admin API).
- **Invio email** (Nodemailer / Resend) — per inviare al cliente le email di conferma, ricevuta e aggiornamento di stato.
- **Fornitori di intelligenza artificiale (Anthropic – Claude; in alternativa Google – Gemini)** — alimentano la chat di assistenza integrata nell'app, usata dai commercianti per porre domande sull'app. Elaborano il testo della domanda di assistenza del commerciante (non i dati degli ordini dei clienti) per generare le risposte. Questo può comportare un trattamento al di fuori dell'UE (Stati Uniti) nell'ambito di adeguate garanzie contrattuali (Clausole Contrattuali Standard).

I dati non vengono venduti né utilizzati a fini pubblicitari.

## Conservazione

Se un commerciante disinstalla l'app, o richiede la cancellazione, i dati personali del cliente (nome, email, telefono, note) vengono anonimizzati. I campi contabili a livello di ordine (numero d'ordine, esito, importi) vengono conservati, in forma anonimizzata, poiché la loro conservazione è un obbligo contabile fiscale standard (fino a 10 anni) — i record anonimizzati non possono più essere ricollegati a una persona.

## Sicurezza

- L'accesso a Shopify utilizza token di accesso offline a scadenza, rinnovati automaticamente — nessuna credenziale a lunga durata.
- Il database (Firestore) è raggiungibile solo tramite l'identità del servizio backend dell'app; non esiste alcun accesso pubblico in lettura/scrittura.

## Domande o richieste

Per esercitare una richiesta di accesso o cancellazione dei dati, contatta il commerciante presso il cui negozio hai effettuato l'ordine, oppure scrivi a [info@ifgecommerce.com](mailto:info@ifgecommerce.com).
