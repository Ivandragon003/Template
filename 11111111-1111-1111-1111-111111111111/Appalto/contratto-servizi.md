# Contratto di Servizi Professionali

**N. Contratto:** {{string:numero_contratto}}  
**Data stipula:** {{date:data_stipula}}  
**CIG / Codice riferimento:** {{string:codice_riferimento}} ciao

---

## 1. Parti Contraenti

### Committente

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_cliente}} |
| Partita IVA | {{string:partita_iva_cliente}} |
| Codice fiscale | {{string:codice_fiscale_cliente}} |
| Indirizzo legale | {{text:indirizzo_cliente}} |
| Referente | {{string:referente_cliente}} |
| Email referente | {{string:email_referente_cliente}} |

### Fornitore

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_fornitore}} |
| Partita IVA | {{string:partita_iva_fornitore}} |
| Codice fiscale | {{string:codice_fiscale_fornitore}} |
| Indirizzo legale | {{text:indirizzo_fornitore}} |
| Referente | {{string:referente_fornitore}} |
| Email referente | {{string:email_referente_fornitore}} |

---

## 2. Oggetto del Contratto

Il presente contratto disciplina la fornitura di servizi professionali di consulenza, sviluppo software, manutenzione applicativa e supporto tecnico da parte del **Fornitore** nei confronti del **Committente**.

| Campo | Dettaglio |
| ----- | --------- |
| Descrizione sintetica del servizio | {{text:descrizione_servizio}} |
| Ambito applicativo | {{text:ambito_applicativo}} |
| Tecnologie principali | {{text:tecnologie_principali}} |
| Modalità di erogazione | {{string:modalita_erogazione}} |
| Luogo di esecuzione | {{string:luogo_esecuzione}} |

---

## 3. Attività Incluse

| ID | Attività | Unità | Quantità | Inclusa nel canone |
| -- | -------- | ----- | -------- | ------------------ |
| AS-01 | Sviluppo backend | ore | {{integer:ore_sviluppo_backend}} | {{boolean:backend_incluso}} |
| AS-02 | Sviluppo frontend | ore | {{integer:ore_sviluppo_frontend}} | {{boolean:frontend_incluso}} |
| AS-03 | Code review e testing | ore | {{integer:ore_testing}} | {{boolean:testing_incluso}} |
| AS-04 | Documentazione tecnica | ore | {{integer:ore_documentazione}} | {{boolean:documentazione_inclusa}} |
| AS-05 | Supporto e manutenzione | ore/mese | {{integer:ore_supporto_mensile}} | {{boolean:supporto_incluso}} |
| AS-06 | Ore extra oltre soglia | ore | {{integer:soglia_ore_extra}} | {{boolean:ore_extra_incluse}} |

---

## 4. Durata e Rinnovo

| Campo | Dettaglio |
| ----- | --------- |
| Data inizio | {{date:data_inizio}} |
| Data fine | {{date:data_fine}} |
| Durata contratto | {{integer:durata_contratto_mesi}} mesi |
| Rinnovo automatico | {{boolean:rinnovo_automatico}} |
| Preavviso disdetta | {{integer:giorni_preavviso_disdetta}} giorni |

---

## 5. Corrispettivi Economici

| Voce | Importo | Frequenza | IVA applicata |
| ---- | ------- | --------- | ------------- |
| Canone mensile fisso | {{currency:importo_mensile}} | Mensile | {{percentage:iva_canone}} |
| Ore incluse nel canone | {{integer:ore_incluse}} ore | Mensile | — |
| Tariffa oraria extra | {{currency:costo_ora_extra}} / h | A consumo | {{percentage:iva_ore_extra}} |
| Importo totale stimato | {{currency:importo_totale}} | Totale periodo | {{percentage:iva_importo_totale}} |

---

## 6. Livelli di Servizio SLA

| Priorità | Descrizione | Tempo presa in carico | Tempo risoluzione | Attivo |
| -------- | ----------- | --------------------- | ----------------- | ------ |
| Critica | Sistema completamente non funzionante | {{integer:presa_carico_critica_ore}} ore | {{integer:risoluzione_critica_ore}} ore | {{boolean:sla_critica_attiva}} |
| Alta | Funzionalità principale degradata | {{integer:presa_carico_alta_ore}} ore | {{integer:risoluzione_alta_ore}} ore | {{boolean:sla_alta_attiva}} |
| Media | Funzionalità secondaria non disponibile | {{integer:presa_carico_media_ore}} ore | {{integer:risoluzione_media_ore}} ore | {{boolean:sla_media_attiva}} |
| Bassa | Richiesta di miglioramento o informazione | {{integer:presa_carico_bassa_ore}} ore | {{integer:risoluzione_bassa_giorni}} giorni | {{boolean:sla_bassa_attiva}} |

---

## 7. Penali Contrattuali

| Violazione | Penale | Massimale |
| ---------- | ------ | --------- |
| Mancato rispetto SLA critico | {{currency:penale_sla_critico}} per ogni ora di ritardo | {{percentage:massimale_sla_critico}} del canone mensile |
| Disponibilità mensile inferiore a {{percentage:soglia_disponibilita_minima}} | {{percentage:penale_disponibilita}} del canone mensile | {{percentage:massimale_disponibilita}} del canone mensile |
| Ritardo consegna milestone | {{percentage:penale_ritardo_milestone}} dell'importo della milestone per giorno | {{percentage:massimale_ritardo_milestone}} dell'importo contrattuale |

---

## 8. Clausole Operative

| Clausola | Valore |
| -------- | ------ |
| È prevista reperibilità fuori orario | {{boolean:reperibilita_fuori_orario}} |
| È previsto accesso ad ambienti del committente | {{boolean:accesso_ambienti_cliente}} |
| È previsto trattamento di dati personali | {{boolean:trattamento_dati_personali}} |
| È richiesta documentazione tecnica finale | {{boolean:documentazione_finale_obbligatoria}} |
| È richiesta formazione utenti | {{boolean:formazione_utenti_obbligatoria}} |

---

## 9. Riservatezza e Protezione dei Dati

Le parti si impegnano a mantenere riservate tutte le informazioni tecniche, commerciali, operative e strategiche acquisite nell'ambito del presente contratto.

| Campo | Dettaglio |
| ----- | --------- |
| Durata obbligo di riservatezza dopo la scadenza | {{integer:anni_riservatezza_post_contratto}} anni |
| Nomina responsabile trattamento dati | {{boolean:nomina_responsabile_trattamento}} |
| Riferimento DPA / Allegato privacy | {{string:riferimento_allegato_privacy}} |

---

## 10. Requisiti di Consegna

| ID | Deliverable | Obbligatorio | Scadenza |
| -- | ----------- | ------------ | -------- |
| D-01 | Codice sorgente aggiornato | {{boolean:deliverable_codice_sorgente}} | {{date:scadenza_codice_sorgente}} |
| D-02 | Documentazione tecnica | {{boolean:deliverable_documentazione_tecnica}} | {{date:scadenza_documentazione_tecnica}} |
| D-03 | Manuale utente | {{boolean:deliverable_manuale_utente}} | {{date:scadenza_manuale_utente}} |
| D-04 | Report finale attività | {{boolean:deliverable_report_finale}} | {{date:scadenza_report_finale}} |

---

## 11. Legge Applicabile e Foro Competente

Il presente contratto è regolato dalla legge italiana.

| Campo | Valore |
| ----- | ------ |
| Foro competente | {{string:foro_competente}} |
| Tentativo di conciliazione obbligatorio | {{boolean:conciliazione_obbligatoria}} |

---

## 12. Firme

| Ruolo | Nome | Data | Firma |
| ----- | ---- | ---- | ----- |
| Committente | {{string:referente_cliente}} | {{date:data_stipula}} | ____________ |
| Fornitore | {{string:referente_fornitore}} | {{date:data_stipula}} | ____________ |

---

_Contratto redatto da {{string:referente_fornitore}} per {{string:ragione_sociale_cliente}} — {{date:data_stipula}}_