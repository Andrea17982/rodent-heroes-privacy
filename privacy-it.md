# Rodent Heroes — Informativa privacy

Ultimo aggiornamento: 22 ottobre 2026.

## 1. Titolare e contatti

Titolare del trattamento: Andrea Nastro, Prato, Italia.
Contatto per la privacy: <andreanastro1999@gmail.com>.

Rodent Heroes è un gioco in sviluppo (alpha) e non è ancora pubblicato: questa informativa si applica
all'account di prova e ai dati di gioco creati durante i test.

## 2. Quali dati trattiamo

**Account.** Identificativo dell'account; indirizzo email solo se accedi con Google; indicazione se l'account è
un ospite anonimo; date di creazione, ultima attività, richiesta ed esecuzione dell'eliminazione. Non conserviamo
la password: l'autenticazione è gestita dal fornitore (Google o accesso anonimo).

**Gioco.** Eroi posseduti e loro livelli, equipaggiamento, formazione, saldi e movimenti (oro, braci, materiali,
frammenti), premi riscattati, ripetizioni giornaliere, progresso sui drop, tappe e battaglie in corso con il loro
esito. Le battaglie aperte conservano sul server i semi casuali, necessari a ricostruire l'esito: non sono
mostrati al client.

**Acquisti.** Identificativo del prodotto, tipo, identificativo dell'ordine Play, stato (accreditato o revocato),
date e un'impronta crittografica (SHA-256) del token di acquisto. Non riceviamo né conserviamo i dati della carta
o del metodo di pagamento: il pagamento avviene su Google Play. Il token in chiaro non viene salvato.

**Assistenza.** Compensazioni concesse, con motivo e operatore, e i movimenti corrispondenti.

**Dati tecnici e sicurezza.** Registrazioni tecniche del fornitore di hosting per erogare il servizio e prevenire
abusi; audit anonimo delle eliminazioni (ospite sì/no, giorno della richiesta e dell'eliminazione, movimenti
contabili senza collegamento all'identità).

**Backup.** Copie cifrate del database di test su un disco del titolare, fuori dai servizi cloud, conservate per
al massimo sette giorni. La chiave di cifratura resta nella cartella privata del titolare.

**Annunci rewarded e consenso.** Stiamo integrando Google AdMob e Google User Messaging Platform (UMP);
alla data di questa informativa gli annunci restano disattivati. Quando attivati, gli SDK possono trattare indirizzo
IP, identificatori del dispositivo e pubblicitari, informazioni tecniche e interazioni con gli annunci,
secondo la configurazione e le scelte privacy. UMP raccoglie e conserva le scelte sul dispositivo.
Per verificare un premio, inviamo ad AdMob l'identificativo dell'account nel campo `custom_data`; Google
lo restituisce nella callback firmata. Il server conserva il premio, la data, l'offerta e l'impronta SHA-256
dell'identificativo della transazione, per evitare duplicati e applicare il limite giornaliero.
Il diritto skip consente di riscattare lo stesso premio senza richiedere un video.

Quando richiesto da UMP, **Impostazioni → Scelte sulla privacy** permette di riaprire le opzioni.
Il rifiuto della personalizzazione non impedisce l'accesso al gioco; la disponibilità degli annunci può variare.
Ulteriori informazioni: [come Google usa i dati delle app partner](https://policies.google.com/technologies/partner-sites?hl=it).
Non abbiamo integrato strumenti separati di analisi o crash reporting.

## 3. Finalità e basi giuridiche

- **Erogare il gioco e gestire l'account** (dati di account e di gioco): esecuzione del contratto, art. 6(1)(b) GDPR.
- **Acquisti e assistenza**: esecuzione del contratto e adempimenti contabili/fiscali, art. 6(1)(b) e (c) GDPR.
- **Sicurezza, prevenzione di abusi e frodi, integrità dei saldi**: interesse legittimo, art. 6(1)(f) GDPR.
- **Adempimenti di legge e richieste dell'autorità**: obbligo legale, art. 6(1)(c) GDPR.
- **Annunci e misurazioni (solo se e quando attivati)**: consenso, art. 6(1)(a) GDPR, revocabile.

## 4. Destinatari e trasferimenti

- **Supabase**: database, autenticazione ed esecuzione delle funzioni server. I dati possono essere trattati
  fuori dall'Unione Europea con le garanzie contrattuali del fornitore (clausole contrattuali standard).
- **Google**: accesso con Google, Google Play per acquisti e rimborsi, eventuali annunci AdMob se attivati.
- **GitHub Pages**: ospita questa informativa; non riceve dati di gioco.
- **Autorità**: quando richiesto dalla legge.

Non vendiamo dati personali e non li usiamo per profilazione pubblicitaria senza consenso.

## 5. Conservazione

- Account attivo: i dati restano finché l'account esiste.
- Eliminazione richiesta da un account collegato: 7 giorni per ripensarci; rientrando, la richiesta si annulla.
  Un ospite viene eliminato subito quando esce o lo richiede.
- Alla scadenza, i dati di gioco sono cancellati in cascata; resta solo l'audit anonimo descritto sopra.
- Backup: al massimo 7 copie giornaliere sul disco del titolare; un'eliminazione può ricomparire in un backup
  fino a 7 giorni, poi sparisce con la rotazione.

## 6. Sicurezza

Connessioni cifrate (TLS verificato), accesso al database per ruoli minimi, nessun accesso diretto del client alle
tabelle, saldi e premi calcolati dal server, token di acquisto conservati solo come impronta, backup cifrati
(AES-256-GCM). Nessun sistema è sicuro al 100%: in caso di incidente idoneo a rischio, informeremo gli interessati
e l'autorità come previsto.

## 7. I tuoi diritti

Puoi chiedere accesso, rettifica, cancellazione, limitazione, opposizione e portabilità, e revocare un consenso.
Dal gioco: **Impostazioni → I tuoi dati** per esportare i tuoi dati e chiedere l'eliminazione. Per il resto scrivi
a <andreanastro1999@gmail.com>. Puoi proporre reclamo al Garante per la protezione dei dati personali o all'autorità del
tuo Stato.

## 8. Minori

Il gioco non è destinato a minori di 14 anni. Se un account di un minore fosse creato per errore, scrivi al
contatto sopra per l'eliminazione.

## 9. Modifiche

Versione 1.0, 22 ottobre 2026. Le modifiche sostanziali saranno comunicate nel gioco prima di diventare efficaci.
