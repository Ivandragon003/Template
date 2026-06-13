# Scheda di Consulenza e Proposta Bancaria

## 1. Informazioni generali della pratica

| Campo | Valore |
| --- | --- |
| Codice pratica | {{string:codice_pratica:20:true}} |
| Data consulenza | {{date:data_consulenza:10:true}} |
| Agenzia | {{string:agenzia:100:true}} |
| Consulente bancario | {{string:consulente_bancario:100:true}} |
| Tipologia richiesta | {{string:tipologia_richiesta:100:true}} |
| Canale di contatto | {{string:canale_contatto:50:true}} |

## 2. Dati anagrafici del cliente

| Campo | Valore |
| --- | --- |
| Nome e cognome | {{string:nome_cognome:100:true}} |
| Codice fiscale | {{string:codice_fiscale:20:true}} |
| Data e luogo di nascita | {{string:data_luogo_nascita:50:true}} |
| Indirizzo di residenza | {{string:indirizzo_residenza:150:true}} |
| Telefono | {{phone:telefono:30:true}} |
| Email | {{email:email:120:true}} |
| Documento identificativo | {{string:documento_identificativo:50:true}} |
| Stato civile | {{string:stato_civile:30:true}} |
| Componenti nucleo familiare | {{integer:componenti_nucleo_familiare:2:true}} |

## 3. Profilo economico e professionale

| Voce | Valore dichiarato | Note |
| --- | --- | --- |
| Professione | {{string:professione:100:true}} | {{text:note_professione:200:false}} |
| Datore di lavoro | {{string:datore_di_lavoro:100:true}} | {{text:note_datore_lavoro:200:false}} |
| Reddito annuo lordo | {{currency:reddito_annuo_lordo:12:true}} | {{text:note_reddito:200:false}} |
| Patrimonio finanziario stimato | {{currency:patrimonio_finanziario_stimato:12:true}} | {{text:note_patrimonio:200:false}} |
| Impegni finanziari mensili | {{currency:impegni_finanziari_mensili:12:true}} | {{text:note_impegni:200:false}} |
| Entrate ricorrenti mensili | {{currency:entrate_ricorrenti_mensili:12:true}} | {{text:note_entrate:200:false}} |

## 4. Esigenze dichiarate dal cliente
- {{text:esigenza_1:300:true}}
- {{text:esigenza_2:300:true}}
- {{text:esigenza_3:300:true}}
- {{text:esigenza_4:300:true}}
- {{text:esigenza_5:300:true}}

## 5. Prodotti e servizi proposti

| Prodotto/servizio | Caratteristiche principali | Costo/Importo | Motivazione proposta |
| --- | --- | --- | --- |
| {{string:prodotto_1:100:true}} | {{text:caratteristiche_1:300:true}} | {{string:costo_1:30:true}} | {{text:motivazione_1:200:true}} |
| {{string:prodotto_2:100:true}} | {{text:caratteristiche_2:300:true}} | {{string:costo_2:30:true}} | {{text:motivazione_2:200:true}} |
| {{string:prodotto_3:100:true}} | {{text:caratteristiche_3:300:true}} | {{string:costo_3:30:true}} | {{text:motivazione_3:200:true}} |
| {{string:prodotto_4:100:true}} | {{text:caratteristiche_4:300:true}} | {{string:costo_4:30:true}} | {{text:motivazione_4:200:true}} |
| {{string:prodotto_5:100:true}} | {{text:caratteristiche_5:300:true}} | {{string:costo_5:30:true}} | {{text:motivazione_5:200:true}} |

## 6. Profilo di rischio e adeguatezza preliminare

| Voce | Valore |
| --- | --- |
| Orizzonte temporale prevalente | {{string:orizzonte_temporale_prevalente:30:true}} |
| Propensione al rischio dichiarata | {{string:propensione_al_rischio_dichiarata:30:true}} |
| Esperienza finanziaria | {{string:esperienza_finanziaria:100:true}} |
| Obiettivo principale | {{string:obiettivo_principale:150:true}} |
| Capacità di sostenere perdite | {{string:capacita_sostenere_perdite:100:true}} |
| Esito valutazione preliminare | {{string:esito_valutazione_preliminare:150:true}} |

## 7. Condizioni economiche riepilogative

| Voce | Importo/condizione | Periodicità | Note |
| --- | --- | --- | --- |
| Canone conto | {{currency:canone_conto:12:true}} | {{string:periodicita_canone_conto:20:true}} | {{text:note_canone_conto:200:false}} |
| Bonifici SEPA online | {{currency:bonifici_sepa_online:12:true}} | {{string:periodicita_bonifici_sepa:20:true}} | {{text:note_bonifici_sepa:200:false}} |
| Prelievi ATM gruppo | {{currency:prelievi_atm_gruppo:12:true}} | {{string:periodicita_prelievi_atm:20:true}} | {{text:note_prelievi_atm:200:false}} |
| Carta di credito | {{currency:carta_di_credito:12:true}} | {{string:periodicita_carta_credito:20:true}} | {{text:note_carta_credito:200:false}} |
| Deposito vincolato | {{percentage:deposito_vincolato:5:true}} | {{string:periodicita_deposito_vincolato:20:true}} | {{text:note_deposito_vincolato:200:false}} |
| PAC fondi | {{currency:pac_fondi:12:true}} | {{string:periodicita_pac_fondi:20:true}} | {{text:note_pac_fondi:200:false}} |

## 8. Documentazione acquisita

| Documento | Stato | Data acquisizione | Note |
| --- | --- | --- | --- |
| Documento identità | {{string:stato_doc_identita:30:true}} | {{date:data_acq_doc_identita:10:true}} | {{text:note_doc_identita:200:false}} |
| Codice fiscale | {{string:stato_doc_cf:30:true}} | {{date:data_acq_doc_cf:10:true}} | {{text:note_doc_cf:200:false}} |
| Busta paga recente | {{string:stato_doc_busta:30:true}} | {{date:data_acq_doc_busta:10:true}} | {{text:note_doc_busta:200:false}} |
| Informativa privacy | {{string:stato_doc_privacy:30:true}} | {{date:data_acq_doc_privacy:10:true}} | {{text:note_doc_privacy:200:false}} |
| Questionario adeguatezza | {{string:stato_doc_questionario:30:true}} | {{date:data_acq_doc_questionario:10:true}} | {{text:note_doc_questionario:200:false}} |

## 9. Dichiarazioni, privacy e consensi
- [{{boolean:dichiarazione_dati_corretti:5:true}}] Il cliente dichiara che i dati forniti sono corretti e aggiornati.
- [{{boolean:autorizza_trattamento_dati:5:true}}] Il cliente autorizza il trattamento dei dati per finalità contrattuali e obblighi normativi.
- [{{boolean:consenso_commerciale:5:true}}] Il cliente presta consenso al trattamento per finalità commerciali e promozionali.
- [{{boolean:invio_comunicazioni_digitali:5:true}}] Il cliente richiede invio comunicazioni in formato digitale.
- [{{boolean:ricevuto_documento_costi:5:true}}] Il cliente conferma di aver ricevuto il documento informativo sui costi.

## 10. Note del consulente
{{text:note_consulente:500:true}}

## 11. Firme

| Ruolo | Nome | Data | Firma |
| --- | --- | --- | --- |
| Cliente | {{string:nome_cliente:100:true}} | {{date:data_firma_cliente:10:true}} | {{string:firma_cliente:100:true}} |
| Consulente | {{string:nome_consulente:100:true}} | {{date:data_firma_consulente:10:true}} | {{string:firma_consulente:100:true}} |
| Responsabile agenzia | {{string:nome_responsabile:100:true}} | {{date:data_firma_responsabile:10:true}} | {{string:firma_responsabile:100:true}} |

<!-- END_TEMPLATE -->