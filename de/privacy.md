# Datenschutz und Datenverarbeitung — IFG Returns & Withdrawals

<div class="lang-switcher" markdown="1">
[<img src="../assets/flags/gb.svg" alt="" class="flag-icon"> English](../privacy.html) · [<img src="../assets/flags/it.svg" alt="" class="flag-icon"> Italiano](../it/privacy.html) · <img src="../assets/flags/de.svg" alt="" class="flag-icon"> **Deutsch** · [<img src="../assets/flags/fr.svg" alt="" class="flag-icon"> Français](../fr/privacy.html) · [<img src="../assets/flags/es.svg" alt="" class="flag-icon"> Español](../es/privacy.html)
</div>

Diese Seite beschreibt, wie die App selbst Daten erfasst, verwendet und aufbewahrt. Sie dokumentiert das technische Verhalten der App — sie ersetzt nicht die unternehmensweite Datenschutzerklärung von IFG eCommerce und stellt keine Rechtsberatung dar.

## Welche Daten erfasst werden

Wenn ein Kunde über das Rückgabeformular im Storefront eine Rückgabe einreicht: Vorname, Nachname, Lieferadresse, E-Mail-Adresse, Bestellnummer sowie optional Telefonnummer und Anmerkungen. Die App liest zudem Bestelldaten von Shopify (Bestellnummer, E-Mail-Adresse, Bestelldatum, Fulfillmentstatus), um die Echtheit der Anfrage zu prüfen.

Händler geben während des Onboardings außerdem die rechtlichen Angaben ihres Unternehmens sowie ihre Rücksendeadresse an; diese werden verwendet, um konforme Widerrufserklärungen und Belege zu erstellen.

## Warum diese Daten erfasst werden

- Um zu überprüfen, dass eine Rückgabeanfrage einer echten Bestellung entspricht (Betrugsprävention).
- Um die Rückgabe bzw. Erstattung zu bearbeiten und Bestätigungs-E-Mails sowie PDF-Belege zu erstellen.
- Um die Pflichten aus dem EU-Verbraucherrecht zu erfüllen (Richtlinie 2011/83/EU und ihre Änderung 2023/2673), die eine Identifizierung des Kunden und des Vertrags erfordern.

## An wen die Daten weitergegeben werden

- **Shopify** — zur Überprüfung von Bestellungen und, bei berechtigten Plänen, zur direkten Ausführung von Erstattungen (Shopify Admin API).
- **E-Mail-Versand** (Nodemailer / Resend) — zum Versand der Bestätigungs-, Beleg- und Status-Update-E-Mails an den Kunden.
- **KI-Anbieter (Anthropic – Claude; alternativ Google – Gemini)** — betreiben den Support-Chat in der App, den Händler nutzen, um Fragen zur App zu stellen. Sie verarbeiten den Text der Support-Fragen des Händlers (nicht die Bestelldaten der Kunden), um Antworten zu generieren. Dies kann eine Verarbeitung außerhalb der EU (USA) im Rahmen geeigneter vertraglicher Garantien (Standardvertragsklauseln) einschließen.

Daten werden nicht verkauft oder für Werbezwecke verwendet.

## Aufbewahrung

Deinstalliert ein Händler die App oder beantragt er eine Löschung, werden die personenbezogenen Daten des Kunden (Name, E-Mail, Telefonnummer, Anmerkungen) anonymisiert. Buchhalterische Felder auf Bestellebene (Bestellnummer, Ergebnis, Beträge) werden anonymisiert aufbewahrt, da dies eine übliche steuerliche Aufbewahrungspflicht ist (bis zu 10 Jahre) — die anonymisierten Datensätze lassen sich danach keiner Person mehr zuordnen.

## Sicherheit

- Der Zugriff auf Shopify erfolgt über ablaufende Offline-Access-Tokens, die automatisch erneuert werden — es gibt keine dauerhaft gültigen Zugangsdaten.
- Die Datenbank (Firestore) ist ausschließlich über die eigene Backend-Serviceidentität der App erreichbar; es gibt keinen öffentlichen Lese- oder Schreibzugriff.

## Fragen oder Anfragen

Um ein Auskunfts- oder Löschungsersuchen geltend zu machen, wenden Sie sich an den Händler, bei dem Sie die Bestellung aufgegeben haben, oder schreiben Sie an [info@ifgecommerce.com](mailto:info@ifgecommerce.com).
