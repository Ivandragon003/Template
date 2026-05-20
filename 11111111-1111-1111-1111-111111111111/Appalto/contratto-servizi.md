# Contratto di Servizi Professionali

**N. Contratto:** {{string:numero_contratto:50:true}}  
**Data stipula:** {{date:data_stipula:10:true}}  
**CIG / Codice riferimento:** {{string:codice_riferimento:50:true}} 

---

## 1. Parti Contraenti

### Committente

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_cliente:150:true}} |
| Partita IVA | {{string:partita_iva_cliente:30:true}} |
| Codice fiscale | {{string:codice_fiscale_cliente:30:true}} |
| Indirizzo legale | {{text:indirizzo_cliente:1000:true}} |
| Referente | {{string:referente_cliente:150:true}} |
| Email referente | {{string:email_referente_cliente:150:true}} |

### Fornitore

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_fornitore:150:true}} |
| Partita IVA | {{string:partita_iva_fornitore:30:true}} |
| Codice fiscale | {{string:codice_fiscale_fornitore:30:true}} |
| Indirizzo legale | {{text:indirizzo_fornitore:1000:true}} |
| Referente | {{string:referente_fornitore:150:true}} |
| Email referente | {{string:email_referente_fornitore:150:true}} |

---

## 2. Oggetto del Contratto

Il presente contratto disciplina la fornitura di servizi professionali di consulenza, sviluppo software, manutenzione applicativa e supporto tecnico da parte del **Fornitore** nei confronti del **Committente**.

| Campo | Dettaglio |
| ----- | --------- |
| Descrizione sintetica del servizio | {{text:descrizione_servizio:1000:true}} |
| Ambito applicativo | {{text:ambito_applicativo:1000:true}} |
| Tecnologie principali | {{text:tecnologie_principali:1000:true}} |
| Modalità di erogazione | {{list:modalita_erogazione:120:true:modalita_erogazione:Da remoto,In presenza,Ibrida}} |
| Luogo di esecuzione | {{string:luogo_esecuzione:150:true}} |

---

## 3. Attività Incluse

| ID | Attività | Unità | Quantità | Inclusa nel canone |
| -- | -------- | ----- | -------- | ------------------ |
| AS-01 | Sviluppo backend | ore | {{integer:ore_sviluppo_backend:4:true}} | {{boolean:backend_incluso:5:true}} |
| AS-02 | Sviluppo frontend | ore | {{integer:ore_sviluppo_frontend:4:true}} | {{boolean:frontend_incluso:5:true}} |
| AS-03 | Code review e testing | ore | {{integer:ore_testing:4:true}} | {{boolean:testing_incluso:5:true}} |
| AS-04 | Documentazione tecnica | ore | {{integer:ore_documentazione:4:true}} | {{boolean:documentazione_inclusa:5:true}} |
| AS-05 | Supporto e manutenzione | ore/mese | {{integer:ore_supporto_mensile:4:true}} | {{boolean:supporto_incluso:5:true}} |
| AS-06 | Ore extra oltre soglia | ore | {{integer:soglia_ore_extra:4:false}} | {{boolean:ore_extra_incluse:5:false}} |

---

## 4. Durata e Rinnovo

| Campo | Dettaglio |
| ----- | --------- |
| Data inizio | {{date:data_inizio:10:true}} |
| Data fine | {{date:data_fine:10:true}} |
| Durata contratto | {{integer:durata_contratto_mesi:4:true}} mesi |
| Rinnovo automatico | {{boolean:rinnovo_automatico:5:true}} |
| Preavviso disdetta | {{integer:giorni_preavviso_disdetta:4:true}} giorni |

---

## 5. Corrispettivi Economici

| Voce | Importo | Frequenza | IVA applicata |
| ---- | ------- | --------- | ------------- |
| Canone mensile fisso | {{currency:importo_mensile:20:true}} | Mensile | {{percentage:iva_canone:5:true}} |
| Ore incluse nel canone | {{integer:ore_incluse:4:true}} ore | Mensile | — |
| Tariffa oraria extra | {{currency:costo_ora_extra:20:true}} / h | A consumo | {{percentage:iva_ore_extra:5:false}} |
| Importo totale stimato | {{currency:importo_totale:20:true}} | Totale periodo | {{percentage:iva_importo_totale:5:true}} |

---

## 6. Livelli di Servizio SLA

| Priorità | Descrizione | Tempo presa in carico | Tempo risoluzione | Attivo |
| -------- | ----------- | --------------------- | ----------------- | ------ |
| Critica | Sistema completamente non funzionante | {{integer:presa_carico_critica_ore:4:true}} ore | {{integer:risoluzione_critica_ore:4:true}} ore | {{boolean:sla_critica_attiva:5:true}} |
| Alta | Funzionalità principale degradata | {{integer:presa_carico_alta_ore:4:true}} ore | {{integer:risoluzione_alta_ore:4:true}} ore | {{boolean:sla_alta_attiva:5:true}} |
| Media | Funzionalità secondaria non disponibile | {{integer:presa_carico_media_ore:4:true}} ore | {{integer:risoluzione_media_ore:4:true}} ore | {{boolean:sla_media_attiva:5:true}} |
| Bassa | Richiesta di miglioramento o informazione | {{integer:presa_carico_bassa_ore:4:true}} ore | {{integer:risoluzione_bassa_giorni:4:true}} giorni | {{boolean:sla_bassa_attiva:5:true}} |

---

## 7. Penali Contrattuali

| Violazione | Penale | Massimale |
| ---------- | ------ | --------- |
| Mancato rispetto SLA critico | {{currency:penale_sla_critico:20:true}} per ogni ora di ritardo | {{percentage:massimale_sla_critico:5:true}} del canone mensile |
| Disponibilità mensile inferiore a {{percentage:soglia_disponibilita_minima:5:true}} | {{percentage:penale_disponibilita:5:true}} del canone mensile | {{percentage:massimale_disponibilita:5:true}} del canone mensile |
| Ritardo consegna milestone | {{percentage:penale_ritardo_milestone:5:true}} dell'importo della milestone per giorno | {{percentage:massimale_ritardo_milestone:5:true}} dell'importo contrattuale |

---

## 8. Clausole Operative

| Clausola | Valore |
| -------- | ------ |
| È prevista reperibilità fuori orario | {{boolean:reperibilita_fuori_orario:5:true}} |
| È previsto accesso ad ambienti del committente | {{boolean:accesso_ambienti_cliente:5:true}} |
| È previsto trattamento di dati personali | {{boolean:trattamento_dati_personali:5:true}} |
| È richiesta documentazione tecnica finale | {{boolean:documentazione_finale_obbligatoria:5:true}} |
| È richiesta formazione utenti | {{boolean:formazione_utenti_obbligatoria:5:false}} |

---

## 9. Riservatezza e Protezione dei Dati

Le parti si impegnano a mantenere riservate tutte le informazioni tecniche, commerciali, operative e strategiche acquisite nell'ambito del presente contratto.

| Campo | Dettaglio |
| ----- | --------- |
| Durata obbligo di riservatezza dopo la scadenza | {{integer:anni_riservatezza_post_contratto:6:true}} anni |
| Nomina responsabile trattamento dati | {{boolean:nomina_responsabile_trattamento:5:true}} |
| Riferimento DPA / Allegato privacy | {{string:riferimento_allegato_privacy:120:false}} |

---

## 10. Requisiti di Consegna

| ID | Deliverable | Obbligatorio | Scadenza |
| -- | ----------- | ------------ | -------- |
| D-01 | Codice sorgente aggiornato | {{boolean:deliverable_codice_sorgente:5:true}} | {{date:scadenza_codice_sorgente:10:true}} |
| D-02 | Documentazione tecnica | {{boolean:deliverable_documentazione_tecnica:5:true}} | {{date:scadenza_documentazione_tecnica:10:true}} |
| D-03 | Manuale utente | {{boolean:deliverable_manuale_utente:5:false}} | {{date:scadenza_manuale_utente:10:false}} |
| D-04 | Report finale attività | {{boolean:deliverable_report_finale:5:false}} | {{date:scadenza_report_finale:10:false}} |

---

## 11. Legge Applicabile e Foro Competente

Il presente contratto è regolato dalla legge italiana.

| Campo | Valore |
| ----- | ------ |
| Foro competente | {{list:foro_competente:120:true:fori_competenti:Milano,Roma,Napoli,Torino,Bologna,Firenze,Palermo,Genova,Bari}} |
| Tentativo di conciliazione obbligatorio | {{boolean:conciliazione_obbligatoria:5:false}} |

---

## 12. Firme

| Ruolo | Nome | Data | Firma |
| ----- | ---- | ---- | ----- |
| Committente | {{string:referente_cliente:150:true}} | {{date:data_stipula:10:true}} | ____________ |
| Fornitore | {{string:referente_fornitore:150:true}} | {{date:data_stipula:10:true}} | ____________ |

---

_Contratto redatto da {{string:referente_fornitore:150:true}} per {{string:ragione_sociale_cliente:150:true}} — {{date:data_stipula:10:true}}_