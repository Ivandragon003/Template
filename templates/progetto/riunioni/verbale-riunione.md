# Verbale di Riunione Tecnica

**Progetto:** {{string:progetto}}  
**Codice progetto / commessa:** {{string:codice_progetto}}  
**Cliente:** {{string:nome_cliente}}  
**Data riunione:** {{date:data_riunione}}  
**Orario:** {{string:ora_inizio}} – {{string:ora_fine}}  
**Luogo / Piattaforma:** {{string:luogo_riunione}}  
**Verbalizzatore:** {{string:verbalizzatore}}  
**Tipologia riunione:** {{string:tipologia_riunione}}

---

## 1. Informazioni Generali

### 1.1 Contesto della riunione

| Campo | Dettaglio |
| --- | --- |
| Obiettivo della riunione | {{text:obiettivo_riunione}} |
| Periodo di riferimento | {{string:periodo_riferimento}} |
| Sprint / Milestone di riferimento | {{string:sprint_milestone_riferimento}} |
| Stato generale progetto | {{string:stato_generale_progetto}} |
| Livello urgenza | {{string:livello_urgenza}} |

### 1.2 Documenti di riferimento

| ID | Documento | Versione | Responsabile | Stato |
| --- | --- | --- | --- | --- |
| DOC-01 | {{string:documento_1_nome}} | {{string:documento_1_versione}} | {{string:documento_1_responsabile}} | {{string:documento_1_stato}} |
| DOC-02 | {{string:documento_2_nome}} | {{string:documento_2_versione}} | {{string:documento_2_responsabile}} | {{string:documento_2_stato}} |
| DOC-03 | {{string:documento_3_nome}} | {{string:documento_3_versione}} | {{string:documento_3_responsabile}} | {{string:documento_3_stato}} |

---

## 2. Partecipanti

### 2.1 Elenco partecipanti

| Nome | Ruolo | Azienda | Presenza | Note |
| --- | --- | --- | --- | --- |
| {{string:partecipante_1_nome}} | {{string:partecipante_1_ruolo}} | {{string:partecipante_1_azienda}} | {{string:partecipante_1_presenza}} | {{text:partecipante_1_note}} |
| {{string:partecipante_2_nome}} | {{string:partecipante_2_ruolo}} | {{string:partecipante_2_azienda}} | {{string:partecipante_2_presenza}} | {{text:partecipante_2_note}} |
| {{string:partecipante_3_nome}} | {{string:partecipante_3_ruolo}} | {{string:partecipante_3_azienda}} | {{string:partecipante_3_presenza}} | {{text:partecipante_3_note}} |
| {{string:partecipante_4_nome}} | {{string:partecipante_4_ruolo}} | {{string:partecipante_4_azienda}} | {{string:partecipante_4_presenza}} | {{text:partecipante_4_note}} |
| {{string:partecipante_5_nome}} | {{string:partecipante_5_ruolo}} | {{string:partecipante_5_azienda}} | {{string:partecipante_5_presenza}} | {{text:partecipante_5_note}} |

### 2.2 Ruoli decisionali

| Ruolo | Nominativo | Azienda | Abilitato ad approvare |
| --- | --- | --- | --- |
| Referente cliente | {{string:referente_cliente}} | {{string:azienda_referente_cliente}} | {{boolean:referente_cliente_approva}} |
| Referente tecnico | {{string:referente_tecnico}} | {{string:azienda_referente_tecnico}} | {{boolean:referente_tecnico_approva}} |
| Project manager | {{string:project_manager}} | {{string:azienda_project_manager}} | {{boolean:project_manager_approva}} |
| Responsabile fornitore | {{string:responsabile_fornitore}} | {{string:azienda_responsabile_fornitore}} | {{boolean:responsabile_fornitore_approva}} |

---

## 3. Ordine del Giorno

### 3.1 Punti previsti

| ID | Punto | Durata stimata | Relatore |
| --- | --- | --- | --- |
| ODG-01 | Stato avanzamento lavori | {{integer:durata_odg_1_minuti}} minuti | {{string:relatore_odg_1}} |
| ODG-02 | Analisi criticità aperte | {{integer:durata_odg_2_minuti}} minuti | {{string:relatore_odg_2}} |
| ODG-03 | Decisioni tecniche da approvare | {{integer:durata_odg_3_minuti}} minuti | {{string:relatore_odg_3}} |
| ODG-04 | Pianificazione prossime attività | {{integer:durata_odg_4_minuti}} minuti | {{string:relatore_odg_4}} |
| ODG-05 | Varie ed eventuali | {{integer:durata_odg_5_minuti}} minuti | {{string:relatore_odg_5}} |

### 3.2 Punti aggiunti durante la riunione

| ID | Punto aggiunto | Proposto da | Motivazione |
| --- | --- | --- | --- |
| EXTRA-01 | {{text:punto_extra_1}} | {{string:proponente_extra_1}} | {{text:motivazione_extra_1}} |
| EXTRA-02 | {{text:punto_extra_2}} | {{string:proponente_extra_2}} | {{text:motivazione_extra_2}} |

---

## 4. Stato Avanzamento Lavori

### 4.1 Avanzamento per area

| Area | Stato | Avanzamento | Note |
| --- | --- | --- | --- |
| Analisi funzionale | {{string:stato_analisi_funzionale}} | {{percentage:avanzamento_analisi_funzionale}} | {{text:note_analisi_funzionale}} |
| Backend | {{string:stato_backend}} | {{percentage:avanzamento_backend}} | {{text:note_backend}} |
| Frontend | {{string:stato_frontend}} | {{percentage:avanzamento_frontend}} | {{text:note_frontend}} |
| Integrazioni | {{string:stato_integrazioni}} | {{percentage:avanzamento_integrazioni}} | {{text:note_integrazioni}} |
| Test e collaudo | {{string:stato_test}} | {{percentage:avanzamento_test}} | {{text:note_test}} |
| Documentazione | {{string:stato_documentazione}} | {{percentage:avanzamento_documentazione}} | {{text:note_documentazione}} |
| Deploy / rilascio | {{string:stato_deploy}} | {{percentage:avanzamento_deploy}} | {{text:note_deploy}} |

### 4.2 Milestone

| ID | Milestone | Scadenza prevista | Stato | Rischio ritardo |
| --- | --- | --- | --- | --- |
| MS-01 | {{string:milestone_1_nome}} | {{date:milestone_1_scadenza}} | {{string:milestone_1_stato}} | {{boolean:milestone_1_rischio_ritardo}} |
| MS-02 | {{string:milestone_2_nome}} | {{date:milestone_2_scadenza}} | {{string:milestone_2_stato}} | {{boolean:milestone_2_rischio_ritardo}} |
| MS-03 | {{string:milestone_3_nome}} | {{date:milestone_3_scadenza}} | {{string:milestone_3_stato}} | {{boolean:milestone_3_rischio_ritardo}} |

---

## 5. Sintesi della Discussione

### 5.1 Punti discussi

| Tema | Sintesi |
| --- | --- |
| Stato generale | {{text:sintesi_stato_generale}} |
| Aspetti tecnici | {{text:sintesi_aspetti_tecnici}} |
| Aspetti organizzativi | {{text:sintesi_aspetti_organizzativi}} |
| Aspetti economici | {{text:sintesi_aspetti_economici}} |
| Note del cliente | {{text:note_cliente}} |
| Note del fornitore | {{text:note_fornitore}} |

### 5.2 Criticità emerse

| ID | Criticità | Impatto | Responsabile analisi | Necessita escalation |
| --- | --- | --- | --- | --- |
| CRIT-01 | {{text:criticita_1}} | {{string:impatto_criticita_1}} | {{string:responsabile_criticita_1}} | {{boolean:criticita_1_escalation}} |
| CRIT-02 | {{text:criticita_2}} | {{string:impatto_criticita_2}} | {{string:responsabile_criticita_2}} | {{boolean:criticita_2_escalation}} |
| CRIT-03 | {{text:criticita_3}} | {{string:impatto_criticita_3}} | {{string:responsabile_criticita_3}} | {{boolean:criticita_3_escalation}} |

---

## 6. Decisioni Prese

### 6.1 Decision log

| ID | Decisione | Motivazione | Approvata da | Data decisione |
| --- | --- | --- | --- | --- |
| DEC-01 | {{text:decisione_1}} | {{text:motivazione_decisione_1}} | {{string:approvatore_decisione_1}} | {{date:data_decisione_1}} |
| DEC-02 | {{text:decisione_2}} | {{text:motivazione_decisione_2}} | {{string:approvatore_decisione_2}} | {{date:data_decisione_2}} |
| DEC-03 | {{text:decisione_3}} | {{text:motivazione_decisione_3}} | {{string:approvatore_decisione_3}} | {{date:data_decisione_3}} |

### 6.2 Decisioni rimandate

| ID | Decisione da rimandare | Motivo rinvio | Responsabile | Nuova data prevista |
| --- | --- | --- | --- | --- |
| PEND-01 | {{text:decisione_rimandata_1}} | {{text:motivo_rinvio_1}} | {{string:responsabile_rinvio_1}} | {{date:data_prevista_rinvio_1}} |
| PEND-02 | {{text:decisione_rimandata_2}} | {{text:motivo_rinvio_2}} | {{string:responsabile_rinvio_2}} | {{date:data_prevista_rinvio_2}} |

---

## 7. Action Items

### 7.1 Attività assegnate

| ID | Azione | Responsabile | Priorità | Scadenza | Stato |
| --- | --- | --- | --- | --- | --- |
| AI-01 | {{text:azione_1}} | {{string:owner_1}} | {{string:priorita_1}} | {{date:scadenza_1}} | {{string:stato_azione_1}} |
| AI-02 | {{text:azione_2}} | {{string:owner_2}} | {{string:priorita_2}} | {{date:scadenza_2}} | {{string:stato_azione_2}} |
| AI-03 | {{text:azione_3}} | {{string:owner_3}} | {{string:priorita_3}} | {{date:scadenza_3}} | {{string:stato_azione_3}} |
| AI-04 | {{text:azione_4}} | {{string:owner_4}} | {{string:priorita_4}} | {{date:scadenza_4}} | {{string:stato_azione_4}} |
| AI-05 | {{text:azione_5}} | {{string:owner_5}} | {{string:priorita_5}} | {{date:scadenza_5}} | {{string:stato_azione_5}} |

### 7.2 Attività chiuse dalla riunione precedente

| ID | Azione chiusa | Responsabile | Data chiusura | Note |
| --- | --- | --- | --- | --- |
| DONE-01 | {{text:azione_chiusa_1}} | {{string:owner_azione_chiusa_1}} | {{date:data_chiusura_1}} | {{text:note_chiusura_1}} |
| DONE-02 | {{text:azione_chiusa_2}} | {{string:owner_azione_chiusa_2}} | {{date:data_chiusura_2}} | {{text:note_chiusura_2}} |

---

## 8. Rischi, Issue e Dipendenze

### 8.1 Registro RAID

| ID | Tipo | Descrizione | Impatto | Probabilità | Responsabile |
| --- | --- | --- | --- | --- | --- |
| RAID-01 | {{string:tipo_raid_1}} | {{text:descrizione_raid_1}} | {{string:impatto_raid_1}} | {{percentage:probabilita_raid_1}} | {{string:responsabile_raid_1}} |
| RAID-02 | {{string:tipo_raid_2}} | {{text:descrizione_raid_2}} | {{string:impatto_raid_2}} | {{percentage:probabilita_raid_2}} | {{string:responsabile_raid_2}} |
| RAID-03 | {{string:tipo_raid_3}} | {{text:descrizione_raid_3}} | {{string:impatto_raid_3}} | {{percentage:probabilita_raid_3}} | {{string:responsabile_raid_3}} |

### 8.2 Azioni di mitigazione

| ID RAID | Azione di mitigazione | Scadenza | Stato |
| --- | --- | --- | --- |
| RAID-01 | {{text:mitigazione_raid_1}} | {{date:scadenza_mitigazione_raid_1}} | {{string:stato_mitigazione_raid_1}} |
| RAID-02 | {{text:mitigazione_raid_2}} | {{date:scadenza_mitigazione_raid_2}} | {{string:stato_mitigazione_raid_2}} |
| RAID-03 | {{text:mitigazione_raid_3}} | {{date:scadenza_mitigazione_raid_3}} | {{string:stato_mitigazione_raid_3}} |

---

## 9. Change Request

### 9.1 Richieste di modifica discusse

| ID | Descrizione richiesta | Impatto economico stimato | Impatto temporale stimato | Da approvare |
| --- | --- | --- | --- | --- |
| CR-01 | {{text:change_request_1}} | {{currency:impatto_economico_cr_1}} | {{integer:impatto_temporale_cr_1_giorni}} giorni | {{boolean:cr_1_da_approvare}} |
| CR-02 | {{text:change_request_2}} | {{currency:impatto_economico_cr_2}} | {{integer:impatto_temporale_cr_2_giorni}} giorni | {{boolean:cr_2_da_approvare}} |
| CR-03 | {{text:change_request_3}} | {{currency:impatto_economico_cr_3}} | {{integer:impatto_temporale_cr_3_giorni}} giorni | {{boolean:cr_3_da_approvare}} |

### 9.2 Esito valutazione change request

| ID | Esito | Motivazione | Prossimo passo |
| --- | --- | --- | --- |
| CR-01 | {{string:esito_cr_1}} | {{text:motivazione_cr_1}} | {{text:prossimo_passo_cr_1}} |
| CR-02 | {{string:esito_cr_2}} | {{text:motivazione_cr_2}} | {{text:prossimo_passo_cr_2}} |
| CR-03 | {{string:esito_cr_3}} | {{text:motivazione_cr_3}} | {{text:prossimo_passo_cr_3}} |

---

## 10. Pianificazione Prossime Attività

### 10.1 Piano operativo

| Periodo | Attività prevista | Responsabile | Output atteso |
| --- | --- | --- | --- |
| {{string:periodo_attivita_1}} | {{text:attivita_prevista_1}} | {{string:responsabile_attivita_1}} | {{text:output_atteso_1}} |
| {{string:periodo_attivita_2}} | {{text:attivita_prevista_2}} | {{string:responsabile_attivita_2}} | {{text:output_atteso_2}} |
| {{string:periodo_attivita_3}} | {{text:attivita_prevista_3}} | {{string:responsabile_attivita_3}} | {{text:output_atteso_3}} |

### 10.2 Vincoli operativi

| Vincolo | Descrizione | Bloccante |
| --- | --- | --- |
| Disponibilità ambienti | {{text:vincolo_ambienti}} | {{boolean:vincolo_ambienti_bloccante}} |
| Accessi e credenziali | {{text:vincolo_accessi}} | {{boolean:vincolo_accessi_bloccante}} |
| Approvazioni cliente | {{text:vincolo_approvazioni}} | {{boolean:vincolo_approvazioni_bloccante}} |
| Dipendenze esterne | {{text:vincolo_dipendenze_esterne}} | {{boolean:vincolo_dipendenze_bloccante}} |

---

## 11. Prossima Riunione

### 11.1 Dettagli proposta

| Campo | Dettaglio |
| --- | --- |
| Data proposta | {{date:prossima_riunione_data}} |
| Orario proposto | {{string:prossima_riunione_orario}} |
| Piattaforma / Luogo | {{string:prossima_riunione_luogo}} |
| Durata stimata | {{integer:prossima_riunione_durata_minuti}} minuti |
| Partecipanti richiesti | {{text:prossima_riunione_partecipanti}} |

### 11.2 Argomenti previsti

| ID | Argomento | Responsabile |
| --- | --- | --- |
| NEXT-01 | {{text:argomento_prossima_riunione_1}} | {{string:responsabile_argomento_next_1}} |
| NEXT-02 | {{text:argomento_prossima_riunione_2}} | {{string:responsabile_argomento_next_2}} |
| NEXT-03 | {{text:argomento_prossima_riunione_3}} | {{string:responsabile_argomento_next_3}} |

---

## 12. Approvazione Verbale

### 12.1 Stato approvazione

| Campo | Valore |
| --- | --- |
| Approvazione richiesta | {{boolean:approvazione_richiesta}} |
| Termine osservazioni | {{integer:termine_osservazioni_ore}} ore |
| Approvato dal cliente | {{boolean:approvato_cliente}} |
| Approvato dal fornitore | {{boolean:approvato_fornitore}} |
| Note approvazione | {{text:note_approvazione}} |

### 12.2 Firme

| Ruolo | Nome | Data | Firma |
| --- | --- | --- | --- |
| Cliente | {{string:referente_cliente}} | {{date:data_firma_cliente}} | ____________ |
| Fornitore | {{string:responsabile_fornitore}} | {{date:data_firma_fornitore}} | ____________ |
| Verbalizzatore | {{string:verbalizzatore}} | {{date:data_riunione}} | ____________ |

---

_Verbale redatto da {{string:verbalizzatore}} per il progetto {{string:progetto}} — osservazioni entro {{integer:termine_osservazioni_ore}} ore dalla ricezione._