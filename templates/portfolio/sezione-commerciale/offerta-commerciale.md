# Offerta Commerciale

**N. Offerta:** {{string:numero_offerta}}  
**Data offerta:** {{date:data_offerta}}  
**Valida fino al:** {{date:validita_offerta}}  
**Codice cliente:** {{string:codice_cliente}}

---

## Destinatario

| Campo | Valore |
| ----- | ------ |
| Cliente | {{string:nome_cliente}} |
| Partita IVA / Codice fiscale | {{string:partita_iva_cliente}} |
| Referente cliente | {{string:referente_cliente}} |
| Email referente | {{string:email_referente_cliente}} |
| Referente commerciale | {{string:referente_commerciale}} |

---

## 1. Riepilogo Esecutivo

In risposta alla Vostra richiesta, siamo lieti di presentare la seguente offerta commerciale per la fornitura di servizi di sviluppo software, consulenza tecnologica e supporto operativo.

| Campo | Dettaglio |
| ----- | --------- |
| Oggetto dell'offerta | {{text:oggetto_offerta}} |
| Obiettivo del progetto | {{text:obiettivo_progetto}} |
| Ambito di intervento | {{text:ambito_intervento}} |
| Modalità di erogazione | {{string:modalita_erogazione}} |
| Durata stimata attività | {{integer:durata_stimata_giorni}} giorni |

---

## 2. Listino Servizi

| ID | Servizio | Descrizione | Unità | Prezzo unitario | Quantità | Totale |
| -- | -------- | ----------- | ----- | --------------- | -------- | ------ |
| OF-01 | Dev Backend | Sviluppo API NestJS / Node.js | ora | {{currency:prezzo_backend}} | {{integer:qty_backend}} | {{currency:tot_backend}} |
| OF-02 | Dev Frontend | Sviluppo React / TypeScript | ora | {{currency:prezzo_frontend}} | {{integer:qty_frontend}} | {{currency:tot_frontend}} |
| OF-03 | DevOps / CI-CD | Pipeline, Docker, deploy | ora | {{currency:prezzo_devops}} | {{integer:qty_devops}} | {{currency:tot_devops}} |
| OF-04 | UX/UI Design | Wireframe, prototyping e design system | ora | {{currency:prezzo_design}} | {{integer:qty_design}} | {{currency:tot_design}} |
| OF-05 | QA & Testing | Test automatizzati e manuali | ora | {{currency:prezzo_qa}} | {{integer:qty_qa}} | {{currency:tot_qa}} |
| OF-06 | Tech Lead | Architettura, code review e coordinamento tecnico | ora | {{currency:prezzo_techlead}} | {{integer:qty_techlead}} | {{currency:tot_techlead}} |

---

## 3. Servizi Opzionali

| ID | Servizio opzionale | Incluso | Importo |
| -- | ------------------ | ------- | ------- |
| OP-01 | Manutenzione evolutiva post-rilascio | {{boolean:manutenzione_inclusa}} | {{currency:importo_manutenzione}} |
| OP-02 | Formazione utenti | {{boolean:formazione_inclusa}} | {{currency:importo_formazione}} |
| OP-03 | Documentazione tecnica avanzata | {{boolean:documentazione_avanzata_inclusa}} | {{currency:importo_documentazione_avanzata}} |
| OP-04 | Supporto al deploy in produzione | {{boolean:supporto_deploy_incluso}} | {{currency:importo_supporto_deploy}} |

---

## 4. Riepilogo Economico

| Voce | Importo |
| ---- | ------- |
| Totale servizi di sviluppo | {{currency:subtotale_sviluppo}} |
| Totale servizi opzionali | {{currency:subtotale_opzionali}} |
| Sconto commerciale | {{percentage:sconto_percentuale}} |
| Importo sconto | - {{currency:importo_sconto}} |
| **Totale netto** | **{{currency:totale_netto}}** |
| IVA applicata | {{percentage:aliquota_iva}} |
| Importo IVA | {{currency:importo_iva}} |
| **Totale con IVA** | **{{currency:totale_ivato}}** |

---

## 5. Condizioni Commerciali

| Campo | Dettaglio |
| ----- | --------- |
| Condizioni di pagamento | {{text:condizioni_pagamento}} |
| Acconto iniziale richiesto | {{percentage:percentuale_acconto}} |
| Importo acconto | {{currency:importo_acconto}} |
| Saldo a completamento attività | {{currency:importo_saldo}} |
| Data di consegna stimata | {{date:data_consegna}} |
| Validità offerta | {{integer:giorni_validita_offerta}} giorni |

---

## 6. Assunzioni e Vincoli

| ID | Assunzione / Vincolo | Applicabile |
| -- | -------------------- | ----------- |
| AV-01 | Il cliente fornirà accessi, credenziali e documentazione tecnica necessari | {{boolean:accessi_cliente_richiesti}} |
| AV-02 | Le attività saranno svolte da remoto salvo diverso accordo | {{boolean:lavoro_remoto_previsto}} |
| AV-03 | Eventuali modifiche fuori perimetro saranno quotate separatamente | {{boolean:extra_scope_quotato_separatamente}} |
| AV-04 | Il rilascio in produzione richiede approvazione formale del cliente | {{boolean:approvazione_cliente_richiesta}} |

---

## 7. Tempi di Esecuzione

| Fase | Descrizione | Durata stimata | Obbligatoria |
| ---- | ----------- | -------------- | ------------ |
| Fase 1 | Analisi requisiti e setup progetto | {{integer:durata_analisi_giorni}} giorni | {{boolean:fase_analisi_obbligatoria}} |
| Fase 2 | Sviluppo e integrazione | {{integer:durata_sviluppo_giorni}} giorni | {{boolean:fase_sviluppo_obbligatoria}} |
| Fase 3 | Test, collaudo e correzioni | {{integer:durata_test_giorni}} giorni | {{boolean:fase_test_obbligatoria}} |
| Fase 4 | Rilascio e supporto iniziale | {{integer:durata_rilascio_giorni}} giorni | {{boolean:fase_rilascio_obbligatoria}} |

---

## 8. Accettazione dell'Offerta

L'accettazione della presente offerta dovrà avvenire entro la data di validità indicata. Decorso tale termine, le condizioni economiche e operative potranno essere soggette a revisione.

| Ruolo | Nome | Data | Firma |
| ----- | ---- | ---- | ----- |
| Cliente | {{string:referente_cliente}} | {{date:data_accettazione}} | ____________ |
| Fornitore | {{string:referente_commerciale}} | {{date:data_offerta}} | ____________ |

---

_Offerta preparata da {{string:referente_commerciale}} per {{string:nome_cliente}} — Valida fino al {{date:validita_offerta}}_