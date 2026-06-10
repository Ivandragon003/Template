# Proposta di Polizza Assicurativa – Bancassicurazione

Il presente documento raccoglie le informazioni necessarie alla predisposizione di una proposta assicurativa collegata a un rapporto bancario. Viene compilato dal consulente di riferimento in collaborazione con il cliente e funge da supporto operativo per la fase precontrattuale, agevolando la lettura delle condizioni, dei costi e delle coperture offerte. Si raccomanda di verificare la completezza dei dati inseriti prima della sottoscrizione.

## Dati del cliente

In questa sezione vengono raccolti i dati anagrafici e di contatto del cliente proponente, necessari per l'emissione della polizza e per ogni successiva comunicazione. Le informazioni devono corrispondere a quelle presenti nei documenti d'identità e nell'archivio della banca.

| Campo | Valore |
|-------|--------|
| Nome e cognome | {{string:nome_cliente:120:true}} |
| Codice fiscale | {{string:codice_fiscale_cliente:16:true}} |
| Data di nascita | {{date:data_nascita_cliente:10:true}} |
| Luogo di nascita | {{string:luogo_nascita_cliente:120:true}} |
| Indirizzo di residenza | {{string:indirizzo_cliente:200:true}} |
| CAP | {{string:cap_cliente:5:true}} |
| Comune | {{string:comune_cliente:120:true}} |
| Provincia | {{string:provincia_cliente:2:true}} |
| Email | {{email:email_cliente:120:true}} |
| Telefono | {{phone:telefono_cliente:30:true}} |
| Rapporto bancario di riferimento | {{string:rapporto_bancario:50:false}} |

## Dati del consulente

La sezione identifica il consulente bancario o assicurativo che ha curato la proposta, consentendo di tracciare la relazione con il cliente e di gestire correttamente le comunicazioni operative e contrattuali.

| Campo | Valore |
|-------|--------|
| Nome e cognome | {{string:nome_consulente:120:true}} |
| Codice consulente | {{string:codice_consulente:30:true}} |
| Filiale / struttura di appartenenza | {{string:filiale_consulente:120:true}} |
| Email aziendale | {{email:email_consulente:120:true}} |
| Telefono diretto | {{phone:telefono_consulente:30:false}} |
| Iscrizione al Registro | {{string:iscrizione_registro:200:false}} |

## Prodotto assicurativo proposto

In questa parte vengono descritte le caratteristiche principali del prodotto assicurativo selezionato, con l'indicazione della tipologia, del ramo di appartenenza e della compagnia emittente, al fine di inquadrare correttamente la natura della copertura offerta.

| Campo | Valore |
|-------|--------|
| Tipologia di polizza | {{string:tipologia_polizza:120:true}} |
| Ramo assicurativo | {{string:ramo_assicurativo:80:true}} |
| Compagnia emittente | {{string:compagnia_emittente:120:true}} |
| Nome commerciale del prodotto | {{string:nome_prodotto:120:true}} |
| Numero di tariffa / edizione | {{string:numero_tariffa:50:false}} |
| Collegamento con il rapporto bancario | {{boolean:collegamento_bancario:5:true}} |

## Finalità della copertura

Viene qui esplicitato lo scopo principale della polizza, in coerenza con le esigenze manifestate dal cliente e con il prodotto scelto. La finalità orienta la lettura delle garanzie e dei massimali previsti dal contratto.

{{text:finalita_copertura:1000:true}}

## Premio e costi

La sezione riepiloga l'importo del premio, la periodicità di pagamento, le eventuali spese accessorie e la ripartizione tra componente pura e caricamenti. È utile per favorire la trasparenza economica della proposta e agevolare il confronto con soluzioni alternative.

| Campo | Valore |
|-------|--------|
| Premio lordo iniziale | {{currency:premio_lordo:12:true}} |
| Premio netto | {{currency:premio_netto:12:true}} |
| Caricamenti | {{currency:caricamenti:12:false}} |
| Imposte | {{currency:imposte:12:false}} |
| Spese di emissione | {{currency:spese_emissione:12:false}} |
| Periodicità del premio | {{list:periodicita_premio:50:true:Periodicità del premio,Unico,Annuale,Semestrale,Trimestrale,Mensile}} |
| Frazionamento | {{string:frazionamento:50:false}} |
| Modalità di pagamento | {{string:modalita_pagamento:120:true}} |
| Addebito su conto corrente | {{boolean:addebito_conto:5:true}} |

## Durata della polizza

Vengono indicati la data di decorrenza prevista, la scadenza e l'eventuale tacito rinnovo, così da definire con chiarezza l'arco temporale di efficacia della copertura assicurativa proposta.

| Campo | Valore |
|-------|--------|
| Data di decorrenza | {{date:data_decorrenza:10:true}} |
| Data di scadenza | {{date:data_scadenza:10:true}} |
| Durata in anni | {{integer:durata_anni:3:true}} |
| Tacito rinnovo | {{boolean:tacito_rinnovo:5:true}} |
| Periodo di carenza | {{text:periodo_carenza:400:false}} |

## Beneficiario della polizza

In questa sezione si individua il soggetto che percepirà le prestazioni previste dal contratto in caso di evento assicurato. È opportuno verificare attentamente i dati identificativi per evitare errori nella designazione.

| Campo | Valore |
|-------|--------|
| Tipologia di beneficiario | {{list:tipologia_beneficiario:80:true:Tipologia di beneficiario,Cliente stesso,Coerede,Persona fisica,Società,Altri soggetti}} |
| Nome e cognome / Ragione sociale | {{string:beneficiario_nome:200:true}} |
| Codice fiscale / Partita IVA | {{string:beneficiario_codice:16:true}} |
| Data di nascita | {{date:beneficiario_data_nascita:10:false}} |
| Legame con il contraente | {{string:legame_beneficiario:200:false}} |
| Quota di spettanza | {{percentage:quota_beneficiario:5:true}} |
| Referente per la liquidazione | {{string:referente_liquidazione:200:false}} |

## Condizioni principali della polizza

La sezione raccoglie le clausole contrattuali rilevanti, con particolare attenzione alle modalità di attivazione della copertura, ai criteri di liquidazione, alle ipotesi di recesso e all'eventuale presenza di condizioni sospensive. La descrizione consente al cliente di comprendere il funzionamento essenziale del contratto.

{{text:condizioni_principali:2000:true}}

## Rischi coperti e garanzie

Vengono elencati i rischi coperti dalla polizza, con i relativi massimali e le specifiche previsioni di indennizzo. La tabella che segue agevola la lettura sinottica delle garanzie, consentendo un confronto immediato tra le diverse prestazioni offerte.

| Garanzia | Massimale | Franchigia / Scoperto | Note |
|----------|-----------|------------------------|------|
| {{string:garanzia_1:120:true}} | {{currency:massimale_1:12:true}} | {{string:franchigia_1:120:false}} | {{text:note_garanzia_1:400:false}} |
| {{string:garanzia_2:120:false}} | {{currency:massimale_2:12:false}} | {{string:franchigia_2:120:false}} | {{text:note_garanzia_2:400:false}} |
| {{string:garanzia_3:120:false}} | {{currency:massimale_3:12:false}} | {{string:franchigia_3:120:false}} | {{text:note_garanzia_3:400:false}} |

## Esclusioni e limitazioni

La sezione riporta le principali cause di esclusione e le limitazioni previste dal contratto, evidenziando i casi in cui la copertura non opera o risulta ridotta. È opportuno che il cliente ne prenda visione prima della sottoscrizione, anche attraverso la lettura del set informativo del prodotto.

{{text:esclusioni:2000:true}}

## Dichiarazioni del cliente

Il cliente è invitato a confermare la veridicità delle informazioni fornite e a prendere atto delle dichiarazioni richieste dalla compagnia, con particolare riferimento allo stato di salute, alle attività svolte e ad eventuali altri elementi rilevanti per la valutazione del rischio.

{{text:dichiarazioni_cliente:2000:true}}

## Autorizzazioni e consensi

In questa sezione vengono raccolti i consensi necessari al trattamento dei dati personali, anche a fini assicurativi, e le eventuali autorizzazioni relative a comunicazioni commerciali, profilazione o cessione a terzi. Il cliente può liberamente esprimere la propria posizione su ciascuna voce.

| Consenso | Espressione |
|----------|-------------|
| Trattamento dati per finalità contrattuali | {{boolean:consenso_trattamento_contrattuale:5:true}} |
| Trattamento dati per finalità commerciali | {{boolean:consenso_trattamento_commerciale:5:false}} |
| Profilazione e analisi del rischio | {{boolean:consenso_profilazione:5:false}} |
| Comunicazioni marketing | {{boolean:consenso_marketing:5:false}} |
| Cessione dei dati a terzi partner | {{boolean:consenso_cessione_terzi:5:false}} |

## Firma e sottoscrizione

La proposta si intende perfezionata con la sottoscrizione del cliente e del consulente. Si invita a verificare la data di sottoscrizione e a conservare copia del documento unitamente al set informativo consegnato.

| Soggetto | Nome e cognome | Data | Firma |
|----------|----------------|------|-------|
| Cliente | {{string:firma_cliente_nome:120:true}} | {{date:firma_cliente_data:10:true}} | {{string:firma_cliente_firma:120:true}} |
| Consulente | {{string:firma_consulente_nome:120:true}} | {{date:firma_consulente_data:10:true}} | {{string:firma_consulente_firma:120:true}} |