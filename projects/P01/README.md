### Analisi delle Retribuzioni Lorde Orarie in Italia nel 2022

#### 1. Executive Summary:

Il progetto richiede al candidato di studiare un dataset I.Stat che mostra la retribuzione lorda oraria (mediana) per le posizioni lavorative su territorio nazionale (2022), suddiviso per livello di istruzione, genere e settore (industria e servizi). Lo studio serve per misurare: “Se e quanto varia la retribuzione salariale in funzione di genere, titolo di studio e settore e, soprattutto, se il titolo di studio concorra a moderare tali differenze.”. Il candidato è chiamato a quantificare le disparità salariali tra uomini e donne, nonché l'impatto del titolo di studio su queste disparità, per ricercare la presenza di pattern discriminanti, gap retributivi tra i generi e l’eventuale effetto “livellante” del titolo di studio sul divario salariale. 

#### 2. Background del Progetto:

Il dataset in esame si inserisce in un contesto storico e socio-economico in cui la disparità salariale tra uomini e donne è ancora una realtà.  Nonostante le azioni degli ultimi decenni, i dati mostrano che, in media, la retribuzione salariale per le donne è ancora inferiore rispetto a quella per gli uomini. Il titolo di studio, inoltre, è noto per esercitare un impatto significativo sulle retribuzioni, ma non sempre in modo uniforme tra i diversi generi. 

#### 3. Obiettivi del Progetto:

- Misurare le variazioni della retribuzione salariale tra uomini e donne in relazione al titolo di studio e al settore lavorativo.
- Studiare l’effetto mitigante del titolo di studio sul gap retributivo.

Il progetto si inserisce in una strategia di analisi dei dati sociale ed economica, che cerca di stimare le disuguaglianze salariali tramite evidenze statistiche.

#### 4. Domande di Ricerca:

- Variazione della retribuzione salariale: Quanto varia la retribuzione lorda oraria in funzione di genere, titolo di studio e settore? Ipotesi: Le medie retributive per le posizioni lavorative variano significativamente tra maschi e femmine, con differenze più marcate nei settori industriali.
- Effetto del titolo di studio: Il titolo di studio modera il divario retributivo tra i generi? Ipotesi: A parità di settore, un livello di istruzione elevato — quale una laurea o un titolo post-laurea — concorre a moderare il divario salariale.
- Interazioni tra le variabili: Sussistono interazioni rilevanti tra il settore, il genere e il titolo di studio nel processo di determinazione della retribuzione? Ipotesi: Le variabili interagiscono in modo complesso, con il settore che amplifica o attenua le disparità legate al genere e al titolo di studio.

#### 5. Metodologia:

- Calcolare la media della retribuzione salariale per ciascun gruppo (per genere, titolo di studio e settore). La formula per la media in Calc è:  
  `=MEDIA(intervallo di celle)`
- Calcolare la deviazione standard per ciascun gruppo:  
  `=DEV.ST(intervallo di celle)`
- Misurare il test t per confrontare le medie tra maschi e femmine in ciascun gruppo (settore e titolo di studio). La formula in Calc per il test t è:  
  `=TEST.T(intervallo uno; intervallo due; 2; 3)` (dove `2` è per il test a due code e `3` è per il test per due campioni non appaiati)

#### 6. Risultati Attesi:

- La variazione della retribuzione salariale in relazione al genere, al titolo di studio e al settore.
- Le correlazioni significative tra il titolo di studio e la riduzione delle disparità salariali.
- Le differenze salariali nei diversi settori e l’influenza del genere su di queste.

### Guida al Progetto:

1. **Preparazione dei dati**: Importa il dataset in OpenOffice Calc e verifica la qualità dei dati.
2. **Analisi Descrittiva**: Calcola le medie e le deviazioni standard per le retribuzioni salariali in funzione di genere, titolo di studio e settore.
3. **Visualizzazione dei dati**: Crea grafici a barre per confrontare le retribuzioni medie tra i gruppi.
4. **Test delle ipotesi**: Misura il test t per confrontare le retribuzioni salariali tra maschi e femmine in ciascun gruppo.
5. **Correlazione**: Misura la correlazione tra titolo di studio e retribuzione con il grafico a dispersione.
6. **Interpreta i risultati**: Serviti dei grafici e i risultati statistici per rispondere alle domande di ricerca.
7. **Redazione del report finale**: Scrivi un report per presentare le operazioni, i risultati e le conclusioni del progetto.