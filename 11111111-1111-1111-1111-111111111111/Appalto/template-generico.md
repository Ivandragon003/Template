# Project Charter Template

## Titolo del Progetto
Spiegazione: Inserire il nome ufficiale del progetto, che deve essere univoco e rappresentativo degli obiettivi principali. Questo titolo sarà utilizzato per identificare il progetto in tutti i documenti e comunicazioni aziendali.  
{{string:titolo_progetto:120:true}}

## Informazioni Generali del Progetto
Spiegazione: Descrivere le caratteristiche basilari del progetto, inclusa la data di inizio prevista, la durata stimata, il team di riferimento e il livello di priorità. Queste informazioni forniscono un quadro generale per il contesto del progetto.  
| Campo | Valore | Note |
|-------|--------|------|
| {{date:data_inizio:10:true}} | {{date:data_fine:10:true}} | Data di inizio e fine previste |
| {{integer:durata_giorni:3:false}} | {{string:livello_priorita:15:true}} | Durata in giorni e priorità (alta/media/bassa) |
| {{string:team_riferimento:80:true}} | {{string:livello_di_rischio:15:true}} | Team responsabile e livello di rischio (alto/media/basso) |

## Descrizione del Progetto
Spiegazione: Dettagliare in modo chiaro e conciso l'obiettivo principale del progetto, il contesto aziendale e il valore aggiunto previsto. Questa sezione deve essere sufficientemente dettagliata per permettere a chiunque di comprendere il ruolo del progetto all'interno dell'organizzazione.  
{{text:descrizione_progetto:1000:true}}

## Business Case o Motivazione del Progetto
Spiegazione: Presentare il motivo per cui il progetto è stato avviato, inclusi i benefici attesi, le opportunità di mercato o le esigenze aziendali non soddisfatte. Questa sezione deve dimostrare la necessità e l'importanza del progetto per l'organizzazione.  
{{text:business_case:1000:true}}

## Obiettivi del Progetto
Spiegazione: Definire gli obiettivi specifici, misurabili e realizzabili del progetto. Gli obiettivi devono essere allineati con le strategie aziendali e fornire un orientamento chiaro per il team.  
{{text:obiettivi_progetto:800:true}}

## Benefici Attesi
Spiegazione: Elencare i benefici principali che il progetto è destinato a generare, sia per l'organizzazione che per gli stakeholder. Questi benefici devono essere quantificabili o misurabili quando possibile.  
{{text:benefici_attesi:800:true}}

## Ambito Prelimineare del Progetto
Spiegazione: Definire i confini del progetto, indicando cosa è incluso e cosa è escluso. Questa sezione è cruciale per evitare ambiguità e garantire che tutti i coinvolgimenti comprendano i limiti del progetto.  
{{text:ambito_preliminare:800:true}}

## Deliverable Principali
Spiegazione: Elencare i prodotti, risultati o consegne principali che il progetto deve produrre. Questi deliverable devono essere descritti in modo chiaro e specifico per facilitare il controllo e la valutazione del progresso.  
| Nome Deliverable | Descrizione | Responsabile |
|------------------|-------------|--------------|
| {{string:deliverable_1:80:true}} | {{text:descrizione_deliverable_1:400:true}} | {{string:responsabile_1:80:true}} |
| {{string:deliverable_2:80:true}} | {{text:descrizione_deliverable_2:400:true}} | {{string:responsabile_2:80:true}} |

## Milestone Principali
Spiegazione: Identificare i punti chiave del progetto che segneranno il progresso verso la consegna finale. I milestone devono essere realistici e allineati con i tempi previsti.  
| Nome Milestone | Data Prevista | Descrizione |
|----------------|---------------|-------------|
| {{string:milestone_1:80:true}} | {{date:data_milestone_1:10:true}} | {{text:descrizione_milestone_1:400:true}} |
| {{string:milestone_2:80:true}} | {{date:data_milestone_2:10:true}} | {{text:descrizione_milestone_2:400:true}} |

## Stakeholder Principali
Spiegazione: Elencare i principali stakeholder coinvolti nel progetto, indicando il loro ruolo e le aspettative. Questa sezione aiuta a gestire le relazioni e le aspettative degli stakeholder.  
{{list:stakeholder:80:true:Stakeholder, Nome, Ruolo, Contatto}}  
{{string:stakeholder_nome_1:80:true}} | {{string:stakeholder_ruolo_1:80:true}} | {{string:stakeholder_contatto_1:80:true}}  
{{string:stakeholder_nome_2:80:true}} | {{string:stakeholder_ruolo_2:80:true}} | {{string:stakeholder_contatto_2:80:true}}

## Ruoli e Responsabilità Iniziali
Spiegazione: Definire i ruoli chiave del progetto e le responsabilità associate, inclusi il project manager, il team di lavoro e i sponsor. Questa sezione stabilisce chi è responsabile di quali attività.  
| Ruolo | Responsabilità | Contatto |
|-------|----------------|----------|
| {{string:ruolo_1:80:true}} | {{text:responsabilita_1:400:true}} | {{string:contatto_1:80:true}} |
| {{string:ruolo_2:80:true}} | {{text:responsabilita_2:400:true}} | {{string:contatto_2:80:true}} |

## Requisiti di Alto Livello
Spiegazione: Indicare i requisiti principali che il progetto deve soddisfare, come standard tecnici, normative o vincoli organizzativi. Questi requisiti devono essere chiari e misurabili.  
{{text:requisiti_alto_livello:800:true}}

## Assunzioni e Vincoli
Spiegazione: Elencare le assunzioni fatte durante la pianificazione del progetto e i vincoli che potrebbero influenzare il successo. Questa sezione aiuta a identificare i fattori esterni o interni che potrebbero richiedere un adattamento.  
| Tipo | Descrizione |
|------|-------------|
| {{string:tipo_assunzione_1:80:true}} | {{text:descrizione_assunzione_1:400:true}} |
| {{string:tipo_vincolo_1:80:true}} | {{text:descrizione_vincolo_1:400:true}} |

## Rischi Principali
Spiegazione: Identificare i rischi più significativi associati al progetto, inclusi i loro impatti potenziali e le misure di mitigazione. Questa sezione è essenziale per la gestione proattiva dei rischi.  
{{list:risko:80:true:Rischio, Descrizione, Impatto, Mitigazione}}  
{{string:risko_nome_1:80:true}} | {{text:risko_descrizione_1:400:true}} | {{string:risko_impatto_1:80:true}} | {{text:risko_mitigazione_1:400:true}}  
{{string:risko_nome_2:80:true}} | {{text:risko_descrizione_2:400:true}} | {{string:risko_impatto_2:80:true}} | {{text:risko_mitigazione_2:400:true}}

## Budget Previsto
Spiegazione: Indicare il budget totale previsto per il progetto, suddiviso tra costi diretti e indiretti. Questa sezione fornisce un quadro finanziario per il supporto decisionale.  
| Tipo di Costo | Importo | Descrizione |
|---------------|---------|-------------|
| {{string:tipo_costo_1:80:true}} | {{currency:importo_costo_1:15:true}} | {{text:descrizione_costo_1:400:true}} |
| {{string:tipo_costo_2:80:true}} | {{currency:importo_costo_2:15:true}} | {{text:descrizione_costo_2:400:true}} |

## Criteri di Successo
Spiegazione: Definire i criteri chiari e misurabili che determineranno il successo del progetto. Questi criteri devono essere allineati con gli obiettivi e i benefici attesi.  
{{text:criteri_successo:800:true}}

## Autorità del Project Manager
Spiegazione: Specificare il livello di autorità del project manager, inclusi i diritti di decisione, le risorse disponibili e i limiti di potere. Questa sezione è cruciale per la gestione efficace del progetto.  
{{text:autorita_pm:800:true}}

## Approvazioni Richieste
Spiegazione: Elencare le approvazioni necessarie per avviare il progetto, inclusi i nomi dei responsabili e le date previste. Questa sezione garantisce che il progetto abbia il supporto necessario.  
| Nome Approvatore | Ruolo | Data Approvazione |
|------------------|-------|-------------------|
| {{string:approvatore_nome_1:80:true}} | {{string:approvatore_ruolo_1:80:true}} | {{date:data_approvazione_1:10:true}} |
| {{string:approvatore_nome_2:80:true}} | {{string:approvatore_ruolo_2:80:true}} | {{date:data_approvazione_2:10:true}} |