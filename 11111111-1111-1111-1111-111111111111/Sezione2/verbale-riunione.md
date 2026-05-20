# Verbale di Riunione Tecnica

**Progetto:** {{string:progetto:120:true}}  
**Codice progetto / commessa:** {{string:codice_progetto:50:true}}  
**Cliente:** {{string:nome_cliente:150:true}}  
**Data riunione:** {{date:data_riunione:10:true}}  
**Orario:** {{string:ora_inizio:5:true}} – {{string:ora_fine:5:true}}  
**Luogo / Piattaforma:** {{string:luogo_riunione:150:true}}  
**Verbalizzatore:** {{string:verbalizzatore:120:true}}  
**Tipologia riunione:** {{list:tipologia_riunione:80:true:tipologie_riunione:Kick-off,Stato avanzamento,Revisione tecnica,Decisionale,Retrospettiva}}

---

## 1. Informazioni Generali

### 1.1 Contesto della riunione

| Campo | Dettaglio |
| --- | --- |
| Obiettivo della riunione | {{text:obiettivo_riunione:1000:true}} |
| Periodo di riferimento | {{string:periodo_riferimento:120:true}} |
| Sprint / Milestone di riferimento | {{string:sprint_milestone_riferimento:120:true}} |
| Stato generale progetto | {{list:stato_generale_progetto:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| Livello urgenza | {{list:livello_urgenza:120:true:livelli_urgenza:Bassa,Media,Alta,Critica}} |

### 1.2 Documenti di riferimento

| ID | Documento | Versione | Responsabile | Stato |
| --- | --- | --- | --- | --- |
| DOC-01 | {{string:documento_1_nome:120:true}} | {{string:documento_1_versione:120:true}} | {{string:documento_1_responsabile:120:true}} | {{list:documento_1_stato:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| DOC-02 | {{string:documento_2_nome:120:true}} | {{string:documento_2_versione:120:true}} | {{string:documento_2_responsabile:120:true}} | {{list:documento_2_stato:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| DOC-03 | {{string:documento_3_nome:120:false}} | {{string:documento_3_versione:120:false}} | {{string:documento_3_responsabile:120:false}} | {{list:documento_3_stato:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |

---

## 2. Partecipanti

### 2.1 Elenco partecipanti

| Nome | Ruolo | Azienda | Presenza | Note |
| --- | --- | --- | --- | --- |
| {{string:partecipante_1_nome:120:true}} | {{string:partecipante_1_ruolo:120:true}} | {{string:partecipante_1_azienda:150:true}} | {{list:partecipante_1_presenza:80:true:presenze_partecipanti:Presente,Assente,Da remoto}} | {{text:partecipante_1_note:800:false}} |
| {{string:partecipante_2_nome:120:true}} | {{string:partecipante_2_ruolo:120:true}} | {{string:partecipante_2_azienda:150:true}} | {{list:partecipante_2_presenza:80:true:presenze_partecipanti:Presente,Assente,Da remoto}} | {{text:partecipante_2_note:800:false}} |
| {{string:partecipante_3_nome:120:false}} | {{string:partecipante_3_ruolo:120:false}} | {{string:partecipante_3_azienda:150:false}} | {{list:partecipante_3_presenza:80:false:presenze_partecipanti:Presente,Assente,Da remoto}} | {{text:partecipante_3_note:800:false}} |
| {{string:partecipante_4_nome:120:false}} | {{string:partecipante_4_ruolo:120:false}} | {{string:partecipante_4_azienda:150:false}} | {{list:partecipante_4_presenza:80:false:presenze_partecipanti:Presente,Assente,Da remoto}} | {{text:partecipante_4_note:800:false}} |
| {{string:partecipante_5_nome:120:false}} | {{string:partecipante_5_ruolo:120:false}} | {{string:partecipante_5_azienda:150:false}} | {{list:partecipante_5_presenza:80:false:presenze_partecipanti:Presente,Assente,Da remoto}} | {{text:partecipante_5_note:800:false}} |

### 2.2 Ruoli decisionali

| Ruolo | Nominativo | Azienda | Abilitato ad approvare |
| --- | --- | --- | --- |
| Referente cliente | {{string:referente_cliente:150:true}} | {{string:azienda_referente_cliente:150:true}} | {{boolean:referente_cliente_approva:5:true}} |
| Referente tecnico | {{string:referente_tecnico:120:true}} | {{string:azienda_referente_tecnico:150:true}} | {{boolean:referente_tecnico_approva:5:true}} |
| Project manager | {{string:project_manager:120:true}} | {{string:azienda_project_manager:150:true}} | {{boolean:project_manager_approva:5:true}} |
| Responsabile fornitore | {{string:responsabile_fornitore:150:true}} | {{string:azienda_responsabile_fornitore:150:true}} | {{boolean:responsabile_fornitore_approva:5:true}} |

---

## 3. Ordine del Giorno

### 3.1 Punti previsti

| ID | Punto | Durata stimata | Relatore |
| --- | --- | --- | --- |
| ODG-01 | Stato avanzamento lavori | {{integer:durata_odg_1_minuti:4:true}} minuti | {{string:relatore_odg_1:120:true}} |
| ODG-02 | Analisi criticità aperte | {{integer:durata_odg_2_minuti:4:true}} minuti | {{string:relatore_odg_2:120:true}} |
| ODG-03 | Decisioni tecniche da approvare | {{integer:durata_odg_3_minuti:4:false}} minuti | {{string:relatore_odg_3:120:false}} |
| ODG-04 | Pianificazione prossime attività | {{integer:durata_odg_4_minuti:4:false}} minuti | {{string:relatore_odg_4:120:false}} |
| ODG-05 | Varie ed eventuali | {{integer:durata_odg_5_minuti:4:false}} minuti | {{string:relatore_odg_5:120:false}} |

### 3.2 Punti aggiunti durante la riunione

| ID | Punto aggiunto | Proposto da | Motivazione |
| --- | --- | --- | --- |
| EXTRA-01 | {{text:punto_extra_1:1000:true}} | {{string:proponente_extra_1:120:true}} | {{text:motivazione_extra_1:1000:true}} |
| EXTRA-02 | {{text:punto_extra_2:1000:false}} | {{string:proponente_extra_2:120:false}} | {{text:motivazione_extra_2:1000:false}} |

---

## 4. Stato Avanzamento Lavori

### 4.1 Avanzamento per area

| Area | Stato | Avanzamento | Note |
| --- | --- | --- | --- |
| Analisi funzionale | {{list:stato_analisi_funzionale:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_analisi_funzionale:5:true}} | {{text:note_analisi_funzionale:800:false}} |
| Backend | {{list:stato_backend:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_backend:5:true}} | {{text:note_backend:800:false}} |
| Frontend | {{list:stato_frontend:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_frontend:5:true}} | {{text:note_frontend:800:false}} |
| Integrazioni | {{list:stato_integrazioni:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_integrazioni:5:true}} | {{text:note_integrazioni:800:false}} |
| Test e collaudo | {{list:stato_test:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_test:5:true}} | {{text:note_test:800:false}} |
| Documentazione | {{list:stato_documentazione:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_documentazione:5:true}} | {{text:note_documentazione:800:false}} |
| Deploy / rilascio | {{list:stato_deploy:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{percentage:avanzamento_deploy:5:true}} | {{text:note_deploy:800:false}} |

### 4.2 Milestone

| ID | Milestone | Scadenza prevista | Stato | Rischio ritardo |
| --- | --- | --- | --- | --- |
| MS-01 | {{string:milestone_1_nome:120:true}} | {{date:milestone_1_scadenza:10:true}} | {{list:milestone_1_stato:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{boolean:milestone_1_rischio_ritardo:5:true}} |
| MS-02 | {{string:milestone_2_nome:120:true}} | {{date:milestone_2_scadenza:10:true}} | {{list:milestone_2_stato:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{boolean:milestone_2_rischio_ritardo:5:true}} |
| MS-03 | {{string:milestone_3_nome:120:false}} | {{date:milestone_3_scadenza:10:false}} | {{list:milestone_3_stato:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} | {{boolean:milestone_3_rischio_ritardo:5:false}} |

---

## 5. Sintesi della Discussione

### 5.1 Punti discussi

| Tema | Sintesi |
| --- | --- |
| Stato generale | {{text:sintesi_stato_generale:1000:true}} |
| Aspetti tecnici | {{text:sintesi_aspetti_tecnici:1000:true}} |
| Aspetti organizzativi | {{text:sintesi_aspetti_organizzativi:1000:true}} |
| Aspetti economici | {{text:sintesi_aspetti_economici:1000:true}} |
| Note del cliente | {{text:note_cliente:800:false}} |
| Note del fornitore | {{text:note_fornitore:800:false}} |

### 5.2 Criticità emerse

| ID | Criticità | Impatto | Responsabile analisi | Necessita escalation |
| --- | --- | --- | --- | --- |
| CRIT-01 | {{text:criticita_1:1000:true}} | {{list:impatto_criticita_1:80:true:livelli_impatto:Basso,Medio,Alto,Critico}} | {{string:responsabile_criticita_1:120:true}} | {{boolean:criticita_1_escalation:5:true}} |
| CRIT-02 | {{text:criticita_2:1000:true}} | {{list:impatto_criticita_2:80:true:livelli_impatto:Basso,Medio,Alto,Critico}} | {{string:responsabile_criticita_2:120:true}} | {{boolean:criticita_2_escalation:5:true}} |
| CRIT-03 | {{text:criticita_3:1000:false}} | {{list:impatto_criticita_3:80:false:livelli_impatto:Basso,Medio,Alto,Critico}} | {{string:responsabile_criticita_3:120:false}} | {{boolean:criticita_3_escalation:5:false}} |

---

## 6. Decisioni Prese

### 6.1 Decision log

| ID | Decisione | Motivazione | Approvata da | Data decisione |
| --- | --- | --- | --- | --- |
| DEC-01 | {{text:decisione_1:1000:true}} | {{text:motivazione_decisione_1:1000:true}} | {{string:approvatore_decisione_1:120:true}} | {{date:data_decisione_1:10:true}} |
| DEC-02 | {{text:decisione_2:1000:false}} | {{text:motivazione_decisione_2:1000:false}} | {{string:approvatore_decisione_2:120:false}} | {{date:data_decisione_2:10:false}} |
| DEC-03 | {{text:decisione_3:1000:false}} | {{text:motivazione_decisione_3:1000:false}} | {{string:approvatore_decisione_3:120:false}} | {{date:data_decisione_3:10:false}} |

### 6.2 Decisioni rimandate

| ID | Decisione da rimandare | Motivo rinvio | Responsabile | Nuova data prevista |
| --- | --- | --- | --- | --- |
| PEND-01 | {{text:decisione_rimandata_1:1000:true}} | {{text:motivo_rinvio_1:1000:true}} | {{string:responsabile_rinvio_1:120:true}} | {{date:data_prevista_rinvio_1:10:true}} |
| PEND-02 | {{text:decisione_rimandata_2:1000:true}} | {{text:motivo_rinvio_2:1000:true}} | {{string:responsabile_rinvio_2:120:true}} | {{date:data_prevista_rinvio_2:10:true}} |

---

## 7. Action Items

### 7.1 Attività assegnate

| ID | Azione | Responsabile | Priorità | Scadenza | Stato |
| --- | --- | --- | --- | --- | --- |
| AI-01 | {{text:azione_1:1000:true}} | {{string:owner_1:120:true}} | {{list:priorita_1:80:true:priorita_action_item:Bassa,Media,Alta,Critica}} | {{date:scadenza_1:10:true}} | {{list:stato_azione_1:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| AI-02 | {{text:azione_2:1000:true}} | {{string:owner_2:120:true}} | {{list:priorita_2:80:true:priorita_action_item:Bassa,Media,Alta,Critica}} | {{date:scadenza_2:10:true}} | {{list:stato_azione_2:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| AI-03 | {{text:azione_3:1000:false}} | {{string:owner_3:120:false}} | {{list:priorita_3:80:false:priorita_action_item:Bassa,Media,Alta,Critica}} | {{date:scadenza_3:10:false}} | {{list:stato_azione_3:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| AI-04 | {{text:azione_4:1000:false}} | {{string:owner_4:120:false}} | {{list:priorita_4:80:false:priorita_action_item:Bassa,Media,Alta,Critica}} | {{date:scadenza_4:10:false}} | {{list:stato_azione_4:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| AI-05 | {{text:azione_5:1000:false}} | {{string:owner_5:120:false}} | {{list:priorita_5:80:false:priorita_action_item:Bassa,Media,Alta,Critica}} | {{date:scadenza_5:10:false}} | {{list:stato_azione_5:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |

### 7.2 Attività chiuse dalla riunione precedente

| ID | Azione chiusa | Responsabile | Data chiusura | Note |
| --- | --- | --- | --- | --- |
| DONE-01 | {{text:azione_chiusa_1:1000:true}} | {{string:owner_azione_chiusa_1:120:true}} | {{date:data_chiusura_1:10:true}} | {{text:note_chiusura_1:800:false}} |
| DONE-02 | {{text:azione_chiusa_2:1000:true}} | {{string:owner_azione_chiusa_2:120:true}} | {{date:data_chiusura_2:10:true}} | {{text:note_chiusura_2:800:false}} |

---

## 8. Rischi, Issue e Dipendenze

### 8.1 Registro RAID

| ID | Tipo | Descrizione | Impatto | Probabilità | Responsabile |
| --- | --- | --- | --- | --- | --- |
| RAID-01 | {{list:tipo_raid_1:80:true:tipi_raid:Rischio,Assunzione,Issue,Dipendenza}} | {{text:descrizione_raid_1:1000:true}} | {{list:impatto_raid_1:80:true:livelli_impatto:Basso,Medio,Alto,Critico}} | {{percentage:probabilita_raid_1:5:true}} | {{string:responsabile_raid_1:120:true}} |
| RAID-02 | {{list:tipo_raid_2:80:false:tipi_raid:Rischio,Assunzione,Issue,Dipendenza}} | {{text:descrizione_raid_2:1000:false}} | {{list:impatto_raid_2:80:false:livelli_impatto:Basso,Medio,Alto,Critico}} | {{percentage:probabilita_raid_2:5:false}} | {{string:responsabile_raid_2:120:false}} |
| RAID-03 | {{list:tipo_raid_3:80:false:tipi_raid:Rischio,Assunzione,Issue,Dipendenza}} | {{text:descrizione_raid_3:1000:false}} | {{list:impatto_raid_3:80:false:livelli_impatto:Basso,Medio,Alto,Critico}} | {{percentage:probabilita_raid_3:5:false}} | {{string:responsabile_raid_3:120:false}} |

### 8.2 Azioni di mitigazione

| ID RAID | Azione di mitigazione | Scadenza | Stato |
| --- | --- | --- | --- |
| RAID-01 | {{text:mitigazione_raid_1:1000:true}} | {{date:scadenza_mitigazione_raid_1:10:true}} | {{list:stato_mitigazione_raid_1:80:true:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| RAID-02 | {{text:mitigazione_raid_2:1000:false}} | {{date:scadenza_mitigazione_raid_2:10:false}} | {{list:stato_mitigazione_raid_2:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |
| RAID-03 | {{text:mitigazione_raid_3:1000:false}} | {{date:scadenza_mitigazione_raid_3:10:false}} | {{list:stato_mitigazione_raid_3:80:false:stati_operativi:Non avviato,In corso,Completato,Bloccato,In ritardo}} |

---

## 9. Change Request

### 9.1 Richieste di modifica discusse

| ID | Descrizione richiesta | Impatto economico stimato | Impatto temporale stimato | Da approvare |
| --- | --- | --- | --- | --- |
| CR-01 | {{text:change_request_1:1000:true}} | {{list:impatto_economico_cr_1:80:true:livelli_impatto:Basso,Medio,Alto,Critico}} | {{list:impatto_temporale_cr_1_giorni:50:true:livelli_impatto:Basso,Medio,Alto,Critico}} giorni | {{boolean:cr_1_da_approvare:5:true}} |
| CR-02 | {{text:change_request_2:1000:true}} | {{list:impatto_economico_cr_2:80:false:livelli_impatto:Basso,Medio,Alto,Critico}} | {{list:impatto_temporale_cr_2_giorni:50:false:livelli_impatto:Basso,Medio,Alto,Critico}} giorni | {{boolean:cr_2_da_approvare:5:false}} |
| CR-03 | {{text:change_request_3:1000:false}} | {{list:impatto_economico_cr_3:80:false:livelli_impatto:Basso,Medio,Alto,Critico}} | {{list:impatto_temporale_cr_3_giorni:50:false:livelli_impatto:Basso,Medio,Alto,Critico}} giorni | {{boolean:cr_3_da_approvare:5:false}} |

### 9.2 Esito valutazione change request

| ID | Esito | Motivazione | Prossimo passo |
| --- | --- | --- | --- |
| CR-01 | {{list:esito_cr_1:80:true:esiti_change_request:Approvata,Respinta,Da valutare,Rimandata}} | {{text:motivazione_cr_1:1000:true}} | {{text:prossimo_passo_cr_1:1000:true}} |
| CR-02 | {{list:esito_cr_2:80:false:esiti_change_request:Approvata,Respinta,Da valutare,Rimandata}} | {{text:motivazione_cr_2:1000:false}} | {{text:prossimo_passo_cr_2:1000:false}} |
| CR-03 | {{list:esito_cr_3:80:false:esiti_change_request:Approvata,Respinta,Da valutare,Rimandata}} | {{text:motivazione_cr_3:1000:false}} | {{text:prossimo_passo_cr_3:1000:false}} |

---

## 10. Pianificazione Prossime Attività

### 10.1 Piano operativo

| Periodo | Attività prevista | Responsabile | Output atteso |
| --- | --- | --- | --- |
| {{string:periodo_attivita_1:120:true}} | {{text:attivita_prevista_1:1000:true}} | {{string:responsabile_attivita_1:120:true}} | {{text:output_atteso_1:1000:true}} |
| {{string:periodo_attivita_2:120:true}} | {{text:attivita_prevista_2:1000:true}} | {{string:responsabile_attivita_2:120:true}} | {{text:output_atteso_2:1000:true}} |
| {{string:periodo_attivita_3:120:false}} | {{text:attivita_prevista_3:1000:false}} | {{string:responsabile_attivita_3:120:false}} | {{text:output_atteso_3:1000:false}} |

### 10.2 Vincoli operativi

| Vincolo | Descrizione | Bloccante |
| --- | --- | --- |
| Disponibilità ambienti | {{text:vincolo_ambienti:1000:true}} | {{boolean:vincolo_ambienti_bloccante:5:true}} |
| Accessi e credenziali | {{text:vincolo_accessi:1000:true}} | {{boolean:vincolo_accessi_bloccante:5:true}} |
| Approvazioni cliente | {{text:vincolo_approvazioni:1000:true}} | {{boolean:vincolo_approvazioni_bloccante:5:true}} |
| Dipendenze esterne | {{text:vincolo_dipendenze_esterne:1000:true}} | {{boolean:vincolo_dipendenze_bloccante:5:true}} |

---

## 11. Prossima Riunione

### 11.1 Dettagli proposta

| Campo | Dettaglio |
| --- | --- |
| Data proposta | {{date:prossima_riunione_data:10:true}} |
| Orario proposto | {{string:prossima_riunione_orario:50:true}} |
| Piattaforma / Luogo | {{string:prossima_riunione_luogo:150:true}} |
| Durata stimata | {{integer:prossima_riunione_durata_minuti:4:true}} minuti |
| Partecipanti richiesti | {{text:prossima_riunione_partecipanti:1000:true}} |

### 11.2 Argomenti previsti

| ID | Argomento | Responsabile |
| --- | --- | --- |
| NEXT-01 | {{text:argomento_prossima_riunione_1:1000:true}} | {{string:responsabile_argomento_next_1:120:true}} |
| NEXT-02 | {{text:argomento_prossima_riunione_2:1000:false}} | {{string:responsabile_argomento_next_2:120:true}} |
| NEXT-03 | {{text:argomento_prossima_riunione_3:1000:false}} | {{string:responsabile_argomento_next_3:120:false}} |

---

## 12. Approvazione Verbale

### 12.1 Stato approvazione

| Campo | Valore |
| --- | --- |
| Approvazione richiesta | {{boolean:approvazione_richiesta:5:true}} |
| Termine osservazioni | {{integer:termine_osservazioni_ore:4:true}} ore |
| Approvato dal cliente | {{boolean:approvato_cliente:5:true}} |
| Approvato dal fornitore | {{boolean:approvato_fornitore:5:true}} |
| Note approvazione | {{text:note_approvazione:800:false}} |

### 12.2 Firme

| Ruolo | Nome | Data | Firma |
| --- | --- | --- | --- |
| Cliente | {{string:referente_cliente:150:true}} | {{date:data_firma_cliente:10:true}} | ____________ |
| Fornitore | {{string:responsabile_fornitore:150:true}} | {{date:data_firma_fornitore:10:true}} | ____________ |
| Verbalizzatore | {{string:verbalizzatore:120:true}} | {{date:data_riunione:10:true}} | ____________ |

---

_Verbale redatto da {{string:verbalizzatore:120:true}} per il progetto {{string:progetto:120:true}} — osservazioni entro {{integer:termine_osservazioni_ore:4:true}} ore dalla ricezione._