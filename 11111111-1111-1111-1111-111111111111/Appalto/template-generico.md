# Project Charter

## 1. Titolo e informazioni generali del progetto

Questa sezione raccoglie gli elementi identificativi essenziali del progetto, utili per distinguere chiaramente l'iniziativa all'interno del portafoglio e per favorire la tracciabilità documentale. È opportuno indicare il nome ufficiale, un codice identificativo univoco, la versione del documento, la data di redazione, il nome dello sponsor e del project manager, oltre all'unità organizzativa di riferimento. Questi dati costituiscono il riferimento iniziale per ogni successiva comunicazione, decisione o aggiornamento del charter e sono coerenti con le pratiche di avvio progetto descritte nel PMBOK.

| Campo | Valore |
|-------|--------|
| Titolo del progetto | {{string:titolo_progetto:200:true:Inserire il nome ufficiale del progetto.}} |
| Codice progetto | {{string:codice_progetto:50:true:Inserire un identificativo univoco del progetto.}} |
| Versione del documento | {{string:versione_documento:20:true:Inserire la versione del charter, ad esempio 1.0.}} |
| Data di redazione | {{date:data_redazione:10:true:Inserire la data di emissione del documento nel formato GG/MM/AAAA.}} |
| Sponsor del progetto | {{string:sponsor_progetto:150:true:Inserire il nome e il ruolo dello sponsor.}} |
| Project Manager | {{string:project_manager:150:true:Inserire il nome e il ruolo del project manager.}} |
| Unità organizzativa | {{string:unita_organizzativa:150:true:Inserire la struttura aziendale di riferimento del progetto.}} |
| Stato del progetto | {{list:stato_progetto:50:true:Stato del progetto,In avvio,In pianificazione,In esecuzione,In chiusura,Concluso,Sospeso}} |

## 2. Descrizione del progetto

In questa sezione viene presentata una sintesi chiara e discorsiva del progetto, utile a trasmettere a tutti gli stakeholder una visione condivisa dell'iniziativa. La descrizione dovrebbe illustrare il contesto, la natura del lavoro da svolgere, le aree aziendali o i clienti coinvolti e il risultato finale atteso. Un buon livello di dettaglio facilita l'allineamento tra gli attori e riduce il rischio di incomprensioni nelle fasi successive, in linea con le raccomandazioni del PMBOK sull'avvio di progetto.

{{text:descrizione_progetto:2000:true:Descrivere in modo discorsivo il contesto, la natura e le finalità del progetto, evidenziando le aree coinvolte e il risultato complessivo atteso.}}

## 3. Business case o motivazione del progetto

Il business case espone le ragioni strategiche, economiche e operative che giustificano l'avvio del progetto. Deve chiarire il problema o l'opportunità che ha dato origine all'iniziativa, il valore atteso per l'organizzazione e l'allineamento con gli obiettivi strategici. È una sezione fondamentale per dimostrare la convenienza dell'investimento e per supportare le decisioni di prioritizzazione del portafoglio, come previsto dalle pratiche ufficiali del PMI.

{{text:business_case:2000:true:Descrivere la motivazione strategica e operativa del progetto, il problema o l'opportunità affrontata e il valore complessivo generato per l'organizzazione.}}

## 4. Obiettivi del progetto

Gli obiettivi rappresentano i traguardi specifici che il progetto intende raggiungere e devono essere formulati in modo chiaro, misurabile e coerente con gli obiettivi strategici dell'organizzazione. È opportuno distinguere tra obiettivi di risultato e obiettivi di prestazione, indicando per ciascuno un criterio di misurazione. Questa sezione supporta la successiva definizione dei criteri di successo e agevola il monitoraggio dei progressi.

{{table:obiettivi_progetto:-1:true:Obiettivo|string|obiettivo_descrizione;Criterio di misurazione|string|criterio_misurazione;Priorità|list|priorita_obiettivo}}
- Priorità valori ammessi: {{list:priorita_obiettivo:50:true:Priorità,Alta,Media,Bassa}}

## 5. Benefici attesi

In questa sezione vengono elencati i benefici concreti che l'organizzazione si attende dal progetto, distinguendo tra benefici quantificabili, come risparmi economici o incremento di fatturato, e benefici qualitativi, come il miglioramento dell'immagine aziendale o della soddisfazione del cliente. I benefici devono essere collegati agli obiettivi e costituiscono un elemento di riferimento per la valutazione del successo a posteriori.

{{table:benefici_attesi:-1:true:Beneficio|string|beneficio_descrizione;Tipologia|list|tipologia_beneficio;Indicatore di misurazione|string|indicatore_beneficio;Valore stimato|currency|valore_beneficio}}
- Tipologia valori ammessi: {{list:tipologia_beneficio:80:true:Tipologia di beneficio,Economico,Operativo,Strategico,Reputazionale,Qualitativo}}

## 6. Ambito preliminare del progetto

L'ambito preliminare definisce i confini del progetto, indicando ciò che rientra nel lavoro da svolgere e ciò che ne resta escluso. Una descrizione accurata dell'ambito contribuisce a prevenire espansioni non autorizzate e a gestire le aspettative degli stakeholder. È opportuno descrivere le principali aree funzionali, i processi interessati, le sedi o i mercati coinvolti, nonché le esclusioni esplicite.

{{text:ambito_preliminare:2000:true:Descrivere i confini del progetto, indicando le aree, i processi e le entità incluse, oltre alle principali esclusioni.}}

## 7. Deliverable principali

I deliverable rappresentano i prodotti, servizi o risultati tangibili e verificabili che il progetto si impegna a produrre. L'elenco dei deliverable principali supporta la pianificazione operativa e fornisce una base di riferimento per la validazione finale. Per ciascun deliverable è utile indicare una breve descrizione, il responsabile e la fase di consegna prevista.

{{table:deliverable_principali:-1:true:Deliverable|string|deliverable_descrizione;Descrizione|text|deliverable_dettaglio;Responsabile|string|deliverable_responsabile;Fase di consegna|string|deliverable_fase}}

## 8. Milestone principali

Le milestone sono eventi significativi che segnano il completamento di fasi o di deliverable rilevanti. In questa sezione vengono elencate le milestone principali con la data prevista, consentendo un primo inquadramento temporale del progetto. L'elenco delle milestone è utile per il monitoraggio dei progressi e per la comunicazione verso gli stakeholder, in coerenza con le pratiche di project management.

{{table:milestone_principali:-1:true:Milestone|string|milestone_descrizione;Data prevista|date|milestone_data;Criterio di completamento|string|milestone_criterio}}

## 9. Stakeholder principali

Gli stakeholder sono tutti i soggetti, interni o esterni, che hanno un interesse nel progetto o che possono influenzarne o esserne influenzati l'esecuzione. Identificare i principali stakeholder sin dall'avvio del progetto consente di definire strategie di coinvolgimento e comunicazione efficaci. Per ciascuno è opportuno indicare il ruolo, l'interesse, l'influenza e il livello di coinvolgimento atteso.

{{table:stakeholder_principali:-1:true:Stakeholder|string|stakeholder_nome;Ruolo|string|stakeholder_ruolo;Interesse|string|stakeholder_interesse;Influenza|list|stakeholder_influenza;Strategia di coinvolgimento|string|stakeholder_strategia}}
- Influenza valori ammessi: {{list:stakeholder_influenza:50:true:Influenza,Alta,Media,Bassa}}

## 10. Ruoli e responsabilità iniziali

Questa sezione descrive i ruoli principali previsti nella fase di avvio del progetto e le relative responsabilità, in coerenza con la struttura di governo del progetto. L'assegnazione dei ruoli supporta la chiarezza organizzativa e facilita il processo decisionale. È opportuno indicare per ciascun ruolo il nome del referente, le principali aree di responsabilità e i poteri associati.

{{table:ruoli_responsabilita:-1:true:Ruolo|string|ruolo_nome;Referente|string|ruolo_referente;Responsabilità|text|ruolo_responsabilita;Poteri decisionali|string|ruolo_poteri}}

## 11. Requisiti di alto livello

I requisiti di alto livello descrivono le esigenze fondamentali che il progetto deve soddisfare, in termini di funzionalità, qualità, prestazioni, conformità normativa o integrazione con altri sistemi. Una definizione chiara dei requisiti di alto livello riduce il rischio di rework e facilita la successiva analisi dettagliata. Per ciascun requisito è utile indicare la priorità e il principale stakeholder di riferimento.

{{table:requisiti_alto_livello:-1:true:Requisito|string|requisito_descrizione;Tipologia|list|requisito_tipologia;Priorità|list|requisito_priorita;Stakeholder di riferimento|string|requisito_stakeholder}}
- Tipologia valori ammessi: {{list:requisito_tipologia:80:true:Tipologia requisito,Funzionale,Non funzionale,Tecnico,Normativo,Di qualità,Di integrazione}}
- Priorità valori ammessi: {{list:requisito_priorita:50:true:Priorità,Alta,Media,Bassa}}

## 12. Assunzioni

Le assunzioni sono condizioni considerate vere per la pianificazione del progetto, anche se non ancora verificate. Una gestione trasparente delle assunzioni consente di individuare i punti di attenzione e di pianificare le opportune verifiche. In questa sezione vanno elencate le principali assunzioni relative a risorse, tempi, tecnologie, normative o disponibilità degli stakeholder, indicando per ciascuna l'area di impatto e la data prevista di verifica.

{{table:assunzioni:-1:true:Assunzione|string|assunzione_descrizione;Area di impatto|string|assunzione_area;Data di verifica|date|assunzione_data_verifica;Responsabile della verifica|string|assunzione_responsabile}}

## 13. Vincoli

I vincoli rappresentano i limiti o le restrizioni che condizionano le scelte del progetto, come budget massimo, scadenze imposte, normative di settore, standard tecnologici o vincoli organizzativi. Identificare con chiarezza i vincoli permette di valutare la fattibilità delle soluzioni e di negoziare eventuali deroghe. Per ciascun vincolo è opportuno indicarne la natura, l'origine e l'effetto sulle decisioni di progetto.

{{table:vincoli:-1:true:Vincolo|string|vincolo_descrizione;Tipologia|list|vincolo_tipologia;Origine|string|vincolo_origine;Effetto sulle decisioni|string|vincolo_effetto}}
- Tipologia valori ammessi: {{list:vincolo_tipologia:80:true:Tipologia vincolo,Di budget,Di tempo,Di ambito,Di qualità,Normativo,Tecnologico,Organizzativo,Contrattuale}}

## 14. Rischi iniziali

I rischi iniziali sono gli eventi incerti che, se si verificano, possono avere un impatto positivo o negativo sugli obiettivi del progetto. Una prima identificazione dei rischi consente di definire risposte preliminari e di attivare il monitoraggio. Per ciascun rischio è opportuno descrivere la causa, la conseguenza, la probabilità, l'impatto e la strategia di risposta iniziale.

{{table:rischi_iniziali:-1:true:Rischio|string|rischio_descrizione;Probabilità|list|rischio_probabilita;Impatto|list|rischio_impatto;Strategia di risposta|list|rischio_strategia;Responsabile|string|rischio_responsabile}}
- Probabilità valori ammessi: {{list:rischio_probabilita:50:true:Probabilità,Molto bassa,Bassa,Media,Alta,Molto alta}}
- Impatto valori ammessi: {{list:rischio_impatto:50:true:Impatto,Molto basso,Basso,Medio,Alto,Molto alto}}
- Strategia di risposta valori ammessi: {{list:rischio_strategia:80:true:Strategia di risposta,Evitare,Trasferire,Mitigare,Accettare,Esplorare}}

## 15. Budget preliminare

Il budget preliminare fornisce una prima stima delle risorse economiche necessarie per avviare il progetto e per raggiungere i principali deliverable. L'accuratezza di questa stima può essere di alto livello nelle fasi iniziali, ma deve comunque consentire una prima valutazione di fattibilità economica. È opportuno indicare il valore complessivo, le principali voci di costo e le fonti di finanziamento previste.

| Campo | Valore |
|-------|--------|
| Budget totale preliminare | {{currency:budget_totale:15:true:Inserire il valore complessivo stimato del progetto.}} |
| Valuta | {{string:valuta_budget:10:true:Inserire la valuta di riferimento, ad esempio EUR.}} |
| Fonte di finanziamento | {{string:fonte_finanziamento:200:true:Inserire la fonte di finanziamento del progetto.}} |
| Anno fiscale di riferimento | {{integer:anno_fiscale:4:false:Inserire l'anno fiscale di riferimento del budget, ad esempio 2026.}} |

## 16. Criteri di successo

I criteri di successo definiscono le condizioni che devono essere soddisfatte per considerare il progetto pienamente riuscito. Sono strettamente collegati agli obiettivi e ai benefici attesi e forniscono una base oggettiva per la valutazione finale. È opportuno definire criteri misurabili, indicando per ciascuno l'indicatore, il valore target e la data di valutazione prevista.

{{table:criteri_successo:-1:true:Criterio di successo|string|criterio_successo_descrizione;Indicatore di misurazione|string|criterio_indicatore;Valore target|string|criterio_target;Data di valutazione|date|criterio_data}}

## 17. Autorità del project manager

Questa sezione definisce l'autorità conferita al project manager per la gestione del progetto, in coerenza con le pratiche del PMI. L'autorità riguarda le decisioni operative, la gestione delle risorse, la negoziazione con gli stakeholder e la gestione delle variazioni di ambito, tempi e costi entro i limiti concordati. Definire con chiarezza i limiti decisionali contribuisce a un governo efficace del progetto.

| Campo | Valore |
|-------|--------|
| Livello di autorità decisionale | {{list:livello_autorita:80:true:Autorità,Operativa,Tattica,Strategica,Piena}} |
| Autorità sulla gestione risorse | {{string:autorita_risorse:500:true:Descrivere l'autorità del project manager sulla selezione, allocazione e gestione delle risorse di progetto.}} |
| Autorità sulle variazioni di ambito | {{string:autorita_ambito:500:true:Descrivere l'autorità del project manager sulle variazioni di ambito, incluse le soglie di approvazione autonoma.}} |
| Autorità sulle variazioni di tempi e costi | {{string:autorita_tempi_costi:500:true:Descrivere l'autorità del project manager sulle variazioni di tempi e costi, incluse le soglie di approvazione autonoma.}} |
| Limiti e soglie di escalation | {{string:limiti_escalation:500:true:Descrivere i limiti di autorità e le soglie oltre le quali è richiesta l'approvazione dello sponsor o del comitato di direzione.}} |

## 18. Approvazioni finali

La sezione di approvazioni finali raccoglie le firme degli stakeholder autorizzati che sanciscono l'avvio formale del progetto. Le approvazioni costituiscono il momento di chiusura della fase di avvio e abilitano l'avvio delle attività operative. È opportuno indicare per ciascun firmatario il nome, il ruolo, la data di approvazione e un campo per la firma o l'evidenza digitale dell'approvazione.

| Ruolo | Nome e cognome | Data di approvazione | Esito |
|-------|----------------|----------------------|-------|
| Sponsor del progetto | {{string:approvazione_sponsor_nome:150:true:Inserire il nome completo dello sponsor.}} | {{date:approvazione_sponsor_data:10:true:Inserire la data di approvazione nel formato GG/MM/AAAA.}} | {{list:approvazione_sponsor_esito:50:true:Esito approvazione,Approvato,Approvato con riserva,Respinto}} |
| Project Manager | {{string:approvazione_pm_nome:150:true:Inserire il nome completo del project manager.}} | {{date:approvazione_pm_data:10:true:Inserire la data di accettazione nel formato GG/MM/AAAA.}} | {{list:approvazione_pm_esito:50:true:Esito approvazione,Accettato,Accettato con riserva,Rifiutato}} |
| Comitato di direzione | {{string:approvazione_comitato_nome:150:true:Inserire il nome del rappresentante del comitato di direzione.}} | {{date:approvazione_comitato_data:10:true:Inserire la data di approvazione nel formato GG/MM/AAAA.}} | {{list:approvazione_comitato_esito:50:true:Esito approvazione,Approvato,Approvato con riserva,Respinto}} |
| Referente funzionale principale | {{string:approvazione_funzionale_nome:150:true:Inserire il nome del referente funzionale principale.}} | {{date:approvazione_funzionale_data:10:true:Inserire la data di approvazione nel formato GG/MM/AAAA.}} | {{list:approvazione_funzionale_esito:50:true:Esito approvazione,Approvato,Approvato con riserva,Respinto}} |

## Note operative per la compilazione

Questo charter deve essere compilato nella fase di avvio del progetto e approvato formalmente prima dell'avvio delle attività operative. Si raccomanda di aggiornare il documento ogni qualvolta intervengano variazioni significative di ambito, obiettivi, risorse o governance, registrando versione e data di aggiornamento. La coerenza con il PMBOK e con le pratiche ufficiali del PMI è garantita dalla struttura del template, che riflette i processi di avvio e le aree di conoscenza rilevanti per la fase iniziale del progetto.