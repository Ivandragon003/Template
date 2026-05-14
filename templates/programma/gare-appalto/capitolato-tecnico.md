# Capitolato Tecnico d'Appalto

**Ente appaltante:** {{string:ente_appaltante}}  
**Codice gara:** {{string:codice_gara}}  
**Data pubblicazione:** {{date:data_pubblicazione}}

---

## 1. Informazioni Generali

| Campo | Dettaglio |
| ----- | --------- |
| Oggetto dell'appalto | {{text:oggetto_appalto}} |
| Importo a base d'asta IVA esclusa | {{currency:importo_base}} |
| Durata contratto | {{integer:durata_contratto_mesi}} mesi |
| Luogo di esecuzione | {{string:luogo_esecuzione}} |
| Responsabile del procedimento | {{string:responsabile_procedimento}} |
| Scadenza presentazione offerte | {{date:data_scadenza_offerte}} |
| Criterio di aggiudicazione | {{string:criterio_aggiudicazione}} |

---

## 2. Requisiti Tecnici Obbligatori

| ID | Requisito | Obbligatorio |
| -- | --------- | ------------ |
| RT-01 | Architettura microservizi o a moduli | {{boolean:rt_01_obbligatorio}} |
| RT-02 | API RESTful con documentazione OpenAPI 3.0 | {{boolean:rt_02_obbligatorio}} |
| RT-03 | Autenticazione OAuth2 / JWT | {{boolean:rt_03_obbligatorio}} |
| RT-04 | Database relazionale PostgreSQL ≥ 14 | {{boolean:rt_04_obbligatorio}} |
| RT-05 | Backup automatico giornaliero | {{boolean:rt_05_obbligatorio}} |

---

## 3. Penali Contrattuali

| Inadempienza | Penale | Massimale |
| ------------ | ------ | --------- |
| Ritardo consegna milestone | {{percentage:penale_ritardo_milestone}} dell'importo contrattuale al giorno | {{percentage:massimale_ritardo_milestone}} dell'importo |
| Mancato rispetto SLA critico | {{currency:penale_sla_critico}} per evento | {{percentage:massimale_sla_critico}} dell'importo |
| Indisponibilità sistema superiore a 4 ore | {{currency:penale_indisponibilita}} per evento | {{percentage:massimale_indisponibilita}} dell'importo |

---

_Capitolato redatto da {{string:responsabile_procedimento}} — {{string:ente_appaltante}}_
