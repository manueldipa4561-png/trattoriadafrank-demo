# Trattoria da Frank — concept demo

Concept website non commissionato per **Trattoria da Frank**, ristorante/trattoria a Chieti Scalo. Progetto realizzato da **Punto Due Studio** come dimostrazione della fascia **Crescita — €700**.

> Concept dimostrativo non commissionato. Trattoria da Frank non ha approvato né commissionato questo progetto.

## Repository

`manueldipa4561-png/trattoriadafrank-demo`

## Business rappresentato

- **Nome:** Trattoria da Frank
- **Categoria:** trattoria / ristorante di cucina abruzzese
- **Indirizzo:** Via Pasquale de Virgiliis 4, 66100 Chieti CH
- **Telefono:** +39 334 848 5783
- **Email pubblica:** fra.salvatore@live.it
- **Instagram:** `@trattoriadafrank`
- **Menu digitale:** https://www.leggimenu.it/menu/trattoriadafrank
- **Presenza web attuale:** pagina DISH / Metro
- **Prenotazione:** telefono e WhatsApp tramite il numero pubblico verificato
- **Orari pubblici verificati:** 12:00–15:00 e 19:30–23:00, lunedì–domenica

Gli orari possono cambiare in occasione di festività o variazioni operative: prima della pubblicazione reale andrebbero riconfermati con il titolare.

## Direzione del concept

L'obiettivo non è creare una trattoria “rustica generica”, ma trasformare il linguaggio già coerente con l'attività in un'esperienza digitale più riconoscibile e professionale.

La direzione visiva utilizza:

- carta calda / kraft;
- terracotta e verde oliva;
- tipografia editoriale da trattoria;
- composizioni ispirate a tovagliette, menu e tavola;
- illustrazioni CSS originali di piatto, posate, brace e arrosticini;
- micro-interazioni leggere;
- layout mobile-first.

## Architettura

Il progetto resta volutamente su **una sola pagina**, coerentemente con lo scope Crescita e con la quantità di informazioni realmente utili.

Sezioni principali:

1. Hero / posizionamento
2. La trattoria
3. I piatti
4. La brace / arrosticini
5. Menu del giorno
6. Recensioni pubbliche
7. Contatti, orari e prenotazione

È presente anche una pagina `404.html` personalizzata.

## Informazioni verificate usate nel sito

Sono state utilizzate soltanto informazioni supportate da fonti pubbliche, tra cui:

- cucina tipica abruzzese;
- arrosticini di carne e di fegato;
- pallotte cac e ov;
- chitarra all'abruzzese con polpettine;
- pizza fritta mista;
- agnello cac e ov;
- servizio pranzo e cena;
- prenotazione;
- telefono e WhatsApp;
- menu digitale;
- delivery tramite piattaforma esterna;
- indirizzo e contatti;
- reputazione pubblica su Tripadvisor / Google aggregata da fonti terze.

Non sono stati inventati storia aziendale, data di apertura, ingredienti non pubblicati, prezzi diversi da fonti correnti, riconoscimenti diversi da quelli verificati, informazioni legali o servizi non documentati.

## Fonti pubbliche

Principali fonti consultate durante la realizzazione:

- Pagina ufficiale DISH / Metro: https://trattoriadafrank.metro.bar/?lang=it
- Tripadvisor: https://www.tripadvisor.it/Restaurant_Review-g194737-d23601545-Reviews-Trattoria_da_Frank-Chieti_Province_of_Chieti_Abruzzo.html
- Menu digitale Leggimenu: https://www.leggimenu.it/menu/trattoriadafrank
- Deliveroo: https://deliveroo.it/it/menu/chieti/chieti-centro/trattoria-da-frank
- Restaurant Guru: https://restaurantguru.com/Trattoria-da-Frank-Chieti

Le fonti terze possono cambiare nel tempo. Prima di una pubblicazione ufficiale, dati operativi, orari e menu devono essere confermati direttamente con l'attività.

## Stack

- HTML5
- CSS3
- JavaScript vanilla
- nessun framework
- nessuna dipendenza runtime
- nessun backend
- nessun database

Questo mantiene il progetto leggero e semplice da distribuire su Netlify.

## Crescita — funzionalità dimostrate

- design custom-feeling;
- layout responsive e mobile-first;
- navigazione accessibile;
- CTA telefoniche;
- WhatsApp verificato;
- Google Maps / indicazioni;
- menu digitale esterno;
- collegamento delivery esterno;
- link Instagram;
- metadata SEO e social;
- dati strutturati `Restaurant` basati su dati pubblici;
- favicon personalizzata;
- custom 404;
- security headers per Netlify;
- `prefers-reduced-motion`;
- focus states e touch target mobile;
- disclosure del concept demo.

## Funzionalità Evoluzione intenzionalmente escluse

Non sono stati implementati:

- backend;
- area clienti;
- CRM;
- loyalty program;
- booking engine proprietario;
- pagamenti online;
- dashboard;
- POS integration;
- automazioni SMS/email;
- app mobile;
- database menu.

Questi elementi potrebbero essere valutati in una futura fascia Evoluzione, ma non fanno parte di questa demo Crescita.

## Sviluppo locale

Non serve una build.

È possibile aprire il progetto tramite un semplice server statico, per esempio:

```bash
python -m http.server 8000
```

Poi visitare:

`http://localhost:8000`

## Deploy Netlify

Il progetto è statico e può essere importato direttamente da GitHub.

Impostazioni consigliate:

- **Base directory:** vuota
- **Build command:** vuoto
- **Publish directory:** `.`
- **Functions directory:** vuota

Il file `_headers` aggiunge header di sicurezza compatibili con Netlify.

Dopo il primo deploy, il dominio Netlify definitivo dovrebbe essere inserito nei metadata canonical / Open Graph URL prima di una pubblicazione reale.

## SEO

Sono inclusi:

- title e meta description;
- Open Graph base;
- Twitter card base;
- gerarchia H1/H2;
- alt/ARIA dove appropriato;
- structured data Restaurant;
- `robots.txt`.

Un `sitemap.xml` e un canonical URL definitivo vanno aggiunti quando esiste un dominio di produzione stabile.

## Accessibilità

Il concept include:

- skip link;
- semantic HTML;
- heading hierarchy;
- focus visibile;
- menu mobile utilizzabile da tastiera;
- chiusura menu con Escape;
- touch target adeguati;
- contrasto controllato;
- supporto `prefers-reduced-motion`.

## Prima di un lancio ufficiale

Servirebbe ancora:

- approvazione formale del cliente;
- conferma di orari, contatti e servizi;
- autorizzazione all'uso di immagini ufficiali;
- dominio definitivo;
- verifica delle informazioni fiscali / legali richieste;
- eventuale privacy policy basata sugli strumenti realmente utilizzati;
- QA sul dominio finale Netlify / custom domain.
