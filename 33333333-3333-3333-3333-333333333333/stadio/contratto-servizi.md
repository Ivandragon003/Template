# Contratto di Servizi Professionali

**N. Contratto:** {{string:numero_contratto:50:true}}  
**Data stipula:** {{date:data_stipula:10:true}}  
**CIG / Codice riferimento:** {{string:codice_riferimento:50:false}}

---

## 1. Parti Contraenti

### Committente

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_cliente:150:true}} |
| Partita IVA | {{string:partita_iva_cliente:20:true}} |
| Codice fiscale | {{string:codice_fiscale_cliente:20:false}} |
| Indirizzo legale | {{text:indirizzo_cliente:300:true}} |
| Comune | {{list:comune_cliente:100:true:comuni:Milano,Roma,Napoli,Torino,Bologna,Firenze,Palermo,Genova,Bari}} |
| Referente | {{string:referente_cliente:100:true}} |
| Email referente | {{string:email_referente_cliente:120:true}} |

### Fornitore

| Campo | Valore |
| ----- | ------ |
| Ragione sociale | {{string:ragione_sociale_fornitore:150:true}} |
| Partita IVA | {{string:partita_iva_fornitore:20:true}} |
| Codice fiscale | {{string:codice_fiscale_fornitore:20:false}} |
| Indirizzo legale | {{text:indirizzo_fornitore:300:true}} |
| Comune | {{list:comune_fornitore:100:true:comuni:Milano,Roma,Napoli,Torino,Bologna,Firenze,Palermo,Genova,Bari}} |
| Referente | {{string:referente_fornitore:100:true}} |
| Email referente | {{string:email_referente_fornitore:120:true}} |

---

## 2. Oggetto del Contratto

Il presente contratto disciplina la fornitura di servizi professionali di consulenza, sviluppo software, manutenzione applicativa e supporto tecnico da parte del **Fornitore** nei confronti del **Committente**.

| Campo | Dettaglio |
| ----- | --------- |
| Descrizione sintetica del servizio | {{text:descrizione_servizio:1000:true}} |
| Ambito applicativo | {{text:ambito_applicativo:800:true}} |
| Tecnologie principali | {{text:tecnologie_principali:500:false}} |
| Modalità di erogazione | {{list:modalita_erogazione:80:true:modalita_erogazione:Da remoto,In presenza,Ibrida}} |
| Luogo di esecuzione | {{string:luogo_esecuzione:150:true}} |

---

## 3. Durata del Contratto

| Campo | Valore |
| ----- | ------ |
| Data inizio attività | {{date:data_inizio_attivita:10:true}} |
| Data fine attività | {{date:data_fine_attivita:10:false}} |
| Durata in mesi | {{integer:durata_mesi:3:true}} |
| Rinnovo automatico | {{boolean:rinnovo_automatico:5:false}} |
| Preavviso disdetta giorni | {{integer:preavviso_disdetta_giorni:3:false}} |

---

## 4. Corrispettivo Economico

| Campo | Valore |
| ----- | ------ |
| Importo complessivo | {{currency:importo_complessivo:20:true}} |
| IVA inclusa | {{boolean:iva_inclusa:5:true}} |
| Modalità di pagamento | {{list:modalita_pagamento:100:true:modalita_pagamento:Bonifico bancario,Ri.Ba,Pagamento elettronico}} |
| Termini pagamento giorni | {{integer:termini_pagamento_giorni:3:true}} |
| Penale per ritardo pagamento | {{percentage:penale_ritardo_pagamento:5:false}} |

---

## 5. Livelli di Servizio

| Campo | Valore |
| ----- | ------ |
| SLA previsto | {{boolean:sla_previsto:5:true}} |
| Tempo massimo presa in carico ore | {{integer:tempo_presa_in_carico_ore:3:false}} |
| Tempo massimo risoluzione ore | {{integer:tempo_risoluzione_ore:4:false}} |
| Canale assistenza | {{list:canale_assistenza:100:true:canali_assistenza:Email,Telefono,Portale ticket,Chat aziendale}} |
| Fascia oraria supporto | {{list:fascia_oraria_supporto:100:true:fasce_supporto:Orario ufficio,24x7,Weekend incluso}} |

---

## 6. Riservatezza e Trattamento Dati

| Campo | Valore |
| ----- | ------ |
| Clausola riservatezza applicata | {{boolean:clausola_riservatezza:5:true}} |
| Trattamento dati personali previsto | {{boolean:trattamento_dati_personali:5:true}} |
| Nomina responsabile trattamento | {{boolean:nomina_responsabile_trattamento:5:false}} |
| Note privacy | {{text:note_privacy:800:false}} |

---

## 7. Recesso e Risoluzione

| Campo | Valore |
| ----- | ------ |
| Recesso anticipato ammesso | {{boolean:recesso_anticipato:5:true}} |
| Giorni preavviso recesso | {{integer:giorni_preavviso_recesso:3:true}} |
| Penale recesso anticipato | {{currency:penale_recesso_anticipato:20:false}} |
| Cause di risoluzione | {{text:cause_risoluzione:1000:true}} |

---

## 8. Foro Competente

Per ogni controversia relativa alla validità, interpretazione, esecuzione o risoluzione del presente contratto sarà competente in via esclusiva il foro di {{list:foro_competente:100:true:fori_competenti:Milano,Roma,Napoli,Torino,Bologna,Firenze,Palermo,Genova,Bari}}.

---

## 9. Firma delle Parti

| Parte | Nome firmatario | Ruolo | Data firma |
| ----- | --------------- | ----- | ---------- |
| Committente | {{string:firmatario_cliente:100:true}} | {{string:ruolo_firmatario_cliente:100:true}} | {{date:data_firma_cliente:10:false}} |
| Fornitore | {{string:firmatario_fornitore:100:true}} | {{string:ruolo_firmatario_fornitore:100:true}} | {{date:data_firma_fornitore:10:false}} |