# Project Charter

## Titolo e informazioni generali del progetto
In questa sezione vengono riportati i dati identificativi essenziali del progetto, utili per il riferimento unico e la tracciabilità all'interno dell'organizzazione. Il titolo deve essere chiaro, descrittivo e privo di ambiguità. Le informazioni generali includono il codice progetto, la data di redazione del charter, il nome del sponsor e del project manager assegnato, nonché il dipartimento o l'unità organizzativa responsabile. Questi elementi costituiscono l'intestazione formale del documento e devono essere compilati con precisione per garantire l'allineamento con i processi di governance del progetto secondo il PMBOK® Guide – Seventh Edition.

{{string:titolo_progetto:120:true:Inserire il titolo ufficiale del progetto, chiaro e descrittivo.}}
{{string:codice_progetto:20:true:Inserire il codice unico assegnato al progetto (es. PROJ-2025-001).}}
{{date:data_redazione:10:true:Inserire la data di redazione del Project Charter (GG/MM/AAAA).}}
{{string:nome_sponsor:100:true:Inserire il nome e cognome dello sponsor esecutivo del progetto.}}
{{string:nome_project_manager:100:true:Inserire il nome e cognome del project manager assegnato.}}
{{string:unita_responsabile:100:true:Inserire il dipartimento, unità organizzativa o business unit responsabile del progetto.}}
{{string:contatto_sponsor:120:false:Inserire email o telefono di contatto dello sponsor (opzionale).}}
{{string:contatto_pm:120:false:Inserire email o telefono di contatto del project manager (opzionale).}}

## Descrizione del progetto
Questa sezione fornisce una narrazione sintetica ma completa del progetto, spiegando cosa si intende realizzare, perché è necessario e in che modo si inserisce nella strategia organizzativa. La descrizione deve essere comprensibile anche a stakeholder non tecnici e deve evitare dettagli operativi eccessivi, concentrandosi invece sul contesto, lo scopo e il valore atteso. Deve rispondere alle domande: cosa si sta facendo, per chi, e quale bisogno o opportunità affronta. Secondo il PMBOK®, questa descrizione costituisce la base per l'allineamento delle aspettative e la definizione del scope preliminare.

{{text:descrizione_progetto:1500:true:Fornire una descrizione chiara e contestualizzata del progetto, includendo il contesto organizzativo, lo scopo, il bisogno o l'opportunità che affronta e il suo allineamento con gli obiettivi strategici. Evitare dettagli tecnici di implementazione.}}

## Business case o motivazione del progetto
Il business case giustifica l'investimento nel progetto dimostrando la sua convenienza economica, strategica o operativa. Deve includere un'analisi dei benefici attesi rispetto ai costi, facendo riferimento a studi di fattibilità, analisi di mercato, valutazioni di ritorno sull'investimento (ROI), analisi del punto di pareggio o altri metodi di valutazione finanziaria e non finanziaria. Anche se in questa fase preliminare il business case può essere sintetico, deve comunque fornire elementi sufficienti per supportare la decisione di avvio. Deve essere allineato con i processi di selezione e priorizzazione dei progetti descritti nel PMBOK® e nelle pratiche PMI.

{{text:business_case:1500:true:Descrivere la motivazione del progetto, includendo benefici attesi (tangibili e intangibili), analisi di convenienza (es. ROI, NPV, payback period), allineamento con la strategia aziendale e riferimenti a studi di fattibilità o analisi preliminari. Se non disponibile in forma completa, indicare le fonti o i piani per il suo sviluppo.}}

## Obiettivi del progetto
Gli obiettivi del progetto devono essere chiari, misurabili, raggiungibili, rilevanti e temporizzati (SMART). Questa sezione elenca gli obiettivi principali che il progetto si propone di raggiungere, espressi in termini di risultati attesi piuttosto che di attività da svolgere. Ogni obiettivo deve essere collegabile a un beneficio o a un requisito strategico. Secondo il PMBOK®, gli obiettivi ben definiti sono fondamentali per la misurazione del successo e per evitare lo scope creep. Si prevedono almeno 6 obiettivi per garantire copertura anche in progetti complessi.

{{table:obiettivi_progetto:-1:true:Obiettivo|string|obiettivo;Descrizione|text|descrizione_obiettivo;Priorità|list|priorita_obiettivo;Stato|list|stato_obiettivo}}
{{list:priorita_obiettivo:50:true:Priorità,Alta,Media,Bassa}}
{{list:stato_obiettivo:50:true:Stato,Da definire,In corso,Raggiunto,Non raggiunto}}

## Benefici attesi
I benefici rappresentano il valore positivo derivante dalla realizzazione del progetto, che può essere tangibile (es. aumento dei ricavi, riduzione dei costi) o intangibile (es. miglioramento della reputazione, soddisfazione del cliente, rafforzamento del brand). Questa sezione elenca i benefici attesi, classificandoli per tipo e indicando, se possibile, una stima preliminare o un indicatore di misurazione. Deve essere chiaro a chi e in che modo il beneficio si manifesta. Secondo le pratiche PMI, i benefici devono essere tracciabili e collegabili agli obiettivi e al business case. Si prevedono almeno 5 benefici per assicurare una visione completa anche in iniziative di piccole dimensioni.

{{table:benefici_attesi:-1:true:Beneficio|string|beneficio;Descrizione|text|descrizione_beneficio;Tipo|list|tipo_beneficio;Misurazione|string|misurazione_beneficio;Stato|list|stato_beneficio}}
{{list:tipo_beneficio:50:true:Tipo,Tangibile,Intangibile}}
{{list:stato_beneficio:50:true:Stato,Identificato,In corso di realizzazione,Realizzato,Non realizzato}}

## Ambito preliminare del progetto
L'ambito preliminare definisce ciò che è incluso e ciò che è escluso dal progetto in questa fase iniziale. Deve essere descritto a livello alto, senza entrare nei dettagli delle specifiche tecniche, ma sufficientemente chiaro per distinguere il lavoro da svolgere da quello esterno al progetto. L'ambito aiuta a prevenire fraintendimenti e costituisce una base per la successiva elaborazione dello scope dettagliato. Deve includere una breve dichiarazione di inclusione ed esclusione, coerente con il modello di scope statement del PMBOK®.

{{text:ambito_incluso:1000:true:Descrivere a livello preliminare cosa è incluso nel progetto, in termini di funzionalità, risultati, prodotti o servizi da realizzare.}}
{{text:ambito_escluso:1000:true:Descrivere a livello preliminare cosa è escluso dal progetto, per evitare ambiguità e gestire le aspettative degli stakeholder.}}

## Deliverable principali
I deliverable sono gli output tangibili o intangibili che il progetto si impegna a produrre e consegnare. Questa sezione elenca i deliverable principali, ovvero quelli di maggior rilievo per il successo del progetto e per la soddisfazione degli stakeholder. Ogni deliverable deve essere descritto brevemente, con indicazione di responsabilità preliminare e stato previsto. Si prevedono almeno 8 deliverable per garantire adeguata rappresentazione anche in progetti articolati.

{{table:deliverable_principali:-1:true:Nome_deliverable|string|deliverable;Descrizione|text|descrizione_deliverable;Responsabile_preliminare|string|responsabile_deliverable;Stato|list|stato_deliverable}}
{{list:stato_deliverable:50:true:Stato,Da produrre,In lavorazione,Consegnato,Approvato}}

## Milestone principali
Le milestone rappresentano eventi significativi o punti di controllo nel ciclo di vita del progetto, spesso associati al completamento di una fase o di un deliverable chiave. Non hanno durata, ma segnano un avanzamento importante. Questa sezione elenca le milestone principali, con nome, data prevista, descrizione opzionale e stato. Si prevedono almeno 6 milestone per coprire adeguatamente anche progetti con fasi distinte.

{{table:milestone_principali:-1:true:Nome|string|milestone;Data prevista|date|data_milestone;Descrizione|text|descrizione_milestone;Stato|list|stato_milestone}}
{{list:stato_milestone:50:true:Stato,Pianificata,In corso,Completata,Rinviata}}

## Stakeholder principali
Gli stakeholder sono individui, gruppi o organizzazioni che possono influenzare, essere influenzati o percepire di essere influenzati da una decisione, attività o risultato del progetto. Questa sezione identifica gli stakeholder principali, classificandoli per tipo (interno/esterno), livello di interesse e influenza, e includendo informazioni di contatto e ruolo previsto. Si prevedono almeno 5 stakeholder per rappresentare adeguatamente anche contesti organizzativi semplici.

{{table:stakeholder_principali:-1:true:Nome|string|stakeholder;Ruolo_o_organizzazione|string|ruolo_stakeholder;Tipo|list|tipo_stakeholder;Interesse|list|interesse_stakeholder;Influenza|list|influenza_stakeholder;Contatto|string|contatto_stakeholder}}
{{list:tipo_stakeholder:50:true:Tipo,Interno,Esterno}}
{{list:interesse_stakeholder:50:true:Interesse,Basso,Medio,Alto}}
{{list:influenza_stakeholder:50:true:Influenza,Bassa,Media,Alta}}

## Ruoli e responsabilità iniziali
Questa sezione definisce i ruoli chiave nel progetto e le relative responsabilità assegnate in fase di avvio. Non sostituisce la matrice RACI dettagliata, ma fornisce una prima assegnazione di responsabilità per funzioni chiave come sponsor, project manager, team lead, responsabile qualità, ecc. Ogni ruolo deve essere associato a una descrizione sintetica delle responsabilità principali. Si prevedono almeno 6 ruoli per garantire copertura anche in strutture di progetto complesse.

{{table:ruoli_responsabilita:-1:true:Ruolo|string|ruolo;Responsabilità_principali|text|responsabilita_ruolo;Persona_o_unita_assegnata|string|assegnatario_ruolo;Stato|list|stato_ruolo}}
{{list:stato_ruolo:50:true:Stato,Da assegnare,In carica,Sostituito,Non necessario}}

## Requisiti di alto livello
I requisiti di alto livello descrivono le caratteristiche o le capacità che il prodotto, servizio o risultato del progetto deve soddisfare, senza entrare nei dettagli tecnici di implementazione. Sono espressi in linguaggio orientato al business e devono essere tracciabili agli obiettivi e ai benefici. Questa sezione elenca i requisiti principali, con priorità (utilizzando la scala MoSCoW: Must Have, Should Have, Could Have, Won't Have) e stato. Si prevedono almeno 10 requisiti per assicurare adeguata copertura anche in progetti con bisogni complessi.

{{table:requisiti_alto_livello:-1:true:ID|string|id_requisito;Descrizione|text|descrizione_requisito;Priorità|list|priorita_requisito;Stato|list|stato_requisito;Nota|text|note_requisito}}
{{list:priorita_requisito:50:true:Priorità,Must Have,Should Have,Could Have,Won't Have}}
{{list:stato_requisito:50:true:Stato,Da definire,Approvato,In revisione,Respinto}}

## Assunzioni
Le assunzioni sono fattori che si considerano veri, reali o certi per poter procedere con la pianificazione del progetto, nonostante manchino di prova dimostrata. Questa sezione elenca le assunzioni principali relative a risorse, tempi, tecnologia, normative o comportamento degli stakeholder. L'identificazione delle assunzioni è critica perché, se rivelate false, possono impattare significativamente il progetto. Si prevedono almeno 6 assunzioni per rappresentare adeguatamente anche contesti con incertezze moderate.

{{table:assunzioni:-1:true:Descrizione|text|descrizione_assunzione;Impatto_se_falsa|list|impatto_assunzione;Probabilità_di_veridicità|list|probabilita_assunzione;Nota|text|note_assunzione}}
{{list:impatto_assunzione:50:true:Impatto,Basso,Medio,Alto,Critico}}
{{list:probabilita_assunzione:50:true:Probabilità,Molto bassa,Bassa,Media,Alta,Molto alta}}

## Vincoli
I vincoli sono limitazioni o restrizioni che influenzano le opzioni disponibili per la gestione del progetto, come budget prefissato, date obbligatorie, risorse limitate, normative o politiche organizzative. Questa sezione elenca i vincoli principali che devono essere considerati nella pianificazione. Si prevedono almeno 6 vincoli per rappresentare adeguatamente anche contesti organizzativi regolamentati o con risorse scarse.

{{table:vincoli:-1:true:Descrizione|text|descrizione_vincolo;Tipo|list|tipo_vincolo;Impatto_sul_progetto|list|impatto_vincolo;Nota|text|note_vincolo}}
{{list:tipo_vincolo:50:true:Tipo,Tecnico,Organizzativo,Economico,Legale,Operativo,Fornitore}}
{{list:impatto_vincolo:50:true:Impatto,Basso,Medio,Alto,Critico}}

## Rischi iniziali
I rischi sono eventi incerti che, se si verificano, possono avere un effetto positivo o negativo sugli obiettivi del progetto. Questa sezione elenca i rischi iniziali identificati in fase di avvio, con descrizione, categoria, probabilità di occorrenza, impatto previsto e stato di gestione. Si prevedono almeno 8 rischi per rappresentare adeguatamente anche progetti con esposizione moderata all'incertezza.

{{table:rischi_iniziali:-1:true:ID|string|id_rischio;Descrizione|text|descrizione_rischio;Categoria|list|categoria_rischio_rischio;Probabilità|list|probabilita_rischio;Impatto|list|impatto_rischio;Stato_di_gestione|list|stato_gestione_rischio}}
{{list:categoria_rischio:50:true:Categoria,Tecnico,Organizzativo,Economico,Legale,Operativo,Fornitore}}
{{list:probabilita_rischio:50:true:Probabilità,Molto bassa,Bassa,Media,Alta,Molto alta}}
{{list:impatto_rischio:50:true:Impatto,Basso,Medio,Alto,Critico}}
{{list:stato_gestione_rischio:50:true:Stato,Da identificare,In analisi,Pianificato,In corso di mitigazione,Monitorato,Chiuso}}

## Budget preliminare
Il budget preliminare fornisce una stima iniziale dei costi previsti per realizzare il progetto. Deve essere espresso in unità monetaria e può includere voci di spesa principali come personale, forniture, tecnologia, formazione e contingente. Anche se in questa fase non è dettagliato, deve fornire un'indicazione sufficiente per supportare la decisione di avvio e l'allocazione delle risorse. Secondo il PMBOK®, questa stima è di tipo analogico o parametrico e deve essere raffinata durante la pianificazione.

{{currency:budget_preliminare:15:true:Inserire il budget preliminare stimato per il progetto (es. 150000.00 EUR).}}
{{text:note_budget:1000:false:Inserire note sulle fonti di stima, inclusione di contingente, ipotesi di costo o riferimenti a preventivi preliminari.}}

## Criteri di successo
I criteri di successo definiscono le condizioni che devono essere soddisfatte affinché il progetto possa essere considerato riuscito. Sono legati agli obiettivi, ai benefici e ai requisiti, e devono essere misurabili e verificabili. Questa sezione elenca i criteri principali, con indicazione di metodo di verifica e soglia di accettazione. Devono essere allineati con le aspettative dello sponsor e degli stakeholder chiave.

{{table:criteri_successo:-1:true:Descrizione|text|descrizione_criterio;Metodo_di_verifica|string|metodo_verifica;Soglia_di_accettazione|string|soglia_accettazione;Stato|list|stato_criterio}}
{{list:stato_criterio:50:true:Stato,Da definire,Definito,In verifica,Raggiunto,Non raggiunto}}

## Autorità del Project Manager
Questa sezione descrive il livello di autorità assegnato al project manager in termini di gestione delle risorse, presa di decisione, spesa del budget e modifiche allo scope. Secondo il PMBOK®, l'autorità del project manager può variare da basso a alto a seconda della struttura organizzativa (funzionale, matriciale, progettuale). Deve essere chiaramente definita per evitare conflitti di ruolo e garantire l'efficacia della leadership.

{{list:autorita_pm:50:true:Autorità del Project Manager,Bassa,Media,Alta,Completa}}
{{text:note_autorita_pm:1000:false:Inserire dettagli sulle limitazioni o estensioni dell'autorità (es. necessità di approvazione per spese oltre una certa soglia, diritto di veto su modifiche allo scope, ecc.).}}

## Approvazioni finali
Questa sezione registra le approvazioni formali del Project Charter da parte degli enti o individui autorizzati, tipicamente lo sponsor, il comitato di direzione o il PMO. Ogni approvazione include il nome, il ruolo, la data e lo stato (in attesa, approvato, respinto). Si prevedono almeno 4 approvazioni per rappresentare adeguatamente anche contesti con più livelli di governance.

{{table:approvazioni_finali:-1:true:Nome|string|nome_approvatore;Ruolo|string|ruolo_approvatore;Data|date|data_approvazione;Stato|list|stato_approvazione}}
{{list:stato_approvazione:50:true:Stato,In attesa,Approvato,Respinto}}