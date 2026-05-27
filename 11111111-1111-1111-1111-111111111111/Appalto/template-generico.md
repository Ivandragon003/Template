# Template per Documento di Progetto

## Titolo e informazioni generali del progetto
Questa sezione raccoglie gli identificativi principali del progetto e i riferimenti necessari per l'avvio formale. I dati permettono a sponsor, project manager e stakeholder di riconoscere in modo univoco il Project Charter.
Nome progetto: {{string:nome_progetto}}
Data inizio: {{date:data_inizio}}
Data fine: {{date:data_fine}}

## Descrizione del progetto
Descrivere il problema/opportunità che motiva il progetto e gli obiettivi di business attesi. Spiegare quali informazioni servono a sponsor e stakeholder per valutare priorità, impatto e urgenza.
{{text:descrizione_progetto}}


## Business case o motivazione del progetto
Spiegare la motivazione organizzativa, il valore atteso e le ragioni che giustificano l'investimento. La sezione deve collegare il progetto agli obiettivi strategici e ai benefici misurabili.
Business case: {{text:business_case}}

## Obiettivi del progetto
Definire obiettivi chiari, misurabili e coerenti con il business case. Gli obiettivi guidano la pianificazione e permettono di valutare l'avanzamento progetto.
| Obiettivo | Descrizione | Metrica | Target |
|---|---|---|---|
| {{string:obiettivo_1}} | {{string:descrizione_obiettivo_1}} | {{string:metrica_obiettivo_1}} | {{string:target_obiettivo_1}} |

## Benefici attesi
Descrivere i benefici attesi per l'organizzazione e per gli stakeholder principali. La sezione aiuta a collegare deliverable, risultati e creazione di valore.
| Beneficio | Indicatore | Valore atteso |
|---|---|---|
| {{string:beneficio_1}} | {{string:indicatore_beneficio_1}} | {{string:valore_atteso_beneficio_1}} |

## Ambito preliminare del progetto
Descrivere il perimetro iniziale del progetto, includendo confini, principali inclusioni ed esclusioni. L'ambito preliminare riduce ambiguità e supporta le decisioni di pianificazione.
| Incluso | Escluso | Note |
|---|---|---|
| {{string:ambito_incluso_1}} | {{string:ambito_escluso_1}} | {{string:note_ambito_1}} |

## Deliverable principali
Elencare i principali risultati attesi e il criterio con cui saranno accettati. La tabella rende tracciabile il collegamento tra ambito preliminare, responsabilita e approvazione formale.
| Deliverable | Descrizione | Criterio di accettazione |
|---|---|---|
| {{string:deliverable_1}} | {{string:descrizione_deliverable_1}} | {{string:criterio_accettazione_deliverable_1}} |

## Milestone principali
Indicare le tappe principali usate per monitorare l'avanzamento progetto e prendere decisioni di controllo. Ogni milestone deve rappresentare un punto verificabile del percorso.
| Milestone | Data prevista | Risultato atteso |
|---|---|---|
| {{string:milestone_1}} | {{date:data_milestone_1}} | {{string:risultato_milestone_1}} |

## Stakeholder principali
Identificare gli stakeholder principali, il loro ruolo e l'interesse rispetto al progetto. Questa informazione supporta comunicazione, coinvolgimento e gestione delle aspettative.
| Stakeholder | Ruolo | Interesse |
|---|---|---|
| {{string:stakeholder_1}} | {{string:ruolo_stakeholder_1}} | {{string:interesse_stakeholder_1}} |

## Ruoli e responsabilita iniziali
Definire ruoli e responsabilita iniziali per chiarire chi decide, chi esegue e chi approva. La tabella rende esplicito il modello operativo nella fase di avvio.
| Ruolo | Responsabilita | Referente |
|---|---|---|
| {{string:ruolo_1}} | {{string:responsabilita_ruolo_1}} | {{string:referente_ruolo_1}} |

## Requisiti di alto livello
Raccogliere i requisiti di alto livello che indirizzano analisi, soluzione e pianificazione. La tabella permette di distinguere priorita e contenuto dei requisiti prima del dettaglio tecnico.
| Requisito | Descrizione | Priorita |
|---|---|---|
| {{string:requisito_1}} | {{string:descrizione_requisito_1}} | {{string:priorita_requisito_1}} |

## Assunzioni
Documentare le ipotesi considerate vere al momento dell'approvazione iniziale. Le assunzioni devono essere verificabili e utili a interpretare pianificazione, rischi e vincoli.
Assunzioni principali: {{text:assunzioni_principali}}

## Vincoli
Descrivere i vincoli che limitano l'implementazione del progetto, come risorse finanziarie, temporali o tecnologiche. Includere anche un piano di gestione dei vincoli.
{{text:vincoli}}


## Rischi iniziali
Elencare i principali rischi associati al progetto, indicando le probabilità di avvenuta e gli eventuali impatti negativi. Includere anche un piano di gestione dei rischi.
| Tipo di rischio | Descrizione | Probabilità (%) | Impatto (€) |
|-----------------|------------|----------------|-------------|
| {{string:tipo_rischio_1}} | {{string:descrizione_rischio_1}} | {{integer:probabilita_1}} | {{number:impatto_1}} |


## Budget preliminare
Documentare la stima economica iniziale e le fonti di finanziamento note. Il budget preliminare non sostituisce il piano dei costi, ma fornisce un riferimento per l'approvazione formale.
| Voce di costo | Importo stimato | Note |
|---|---|---|
| {{string:voce_costo_1}} | {{currency:importo_stimato_1}} | {{string:note_budget_1}} |

## Criteri di successo
Definire criteri misurabili per valutare se il progetto ha raggiunto gli esiti attesi. I criteri devono essere comprensibili per sponsor, project manager e stakeholder.
Criteri di successo: {{text:criteri_successo}}

## Autorita del Project Manager
Descrivere poteri decisionali, limiti di autonomia e responsabilità assegnate al Project Manager. La sezione chiarisce quali decisioni possono essere prese senza ulteriori escalation.
| Ambito decisionale | Limite/autonomia | Note |
|---|---|---|
| {{string:ambito_decisionale_pm_1}} | {{string:limite_autonomia_pm_1}} | {{string:note_autorita_pm_1}} |

## Approvazioni finali
Raccogliere le approvazioni formali necessarie per autorizzare il Project Charter. La tabella documenta chi approva, con quale ruolo e in quale data.
| Nome | Ruolo | Data approvazione | Firma/Conferma |
|---|---|---|---|
| {{string:nome_approvatore_1}} | {{string:ruolo_approvatore_1}} | {{date:data_approvazione_1}} | {{string:firma_conferma_1}} |