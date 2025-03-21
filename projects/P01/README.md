# Executive Summary

L'analisi delle disparità salariali per genere e titolo di studio in Italia presenta un'opportunità per comprendere le differenze retributive e orientare politiche sociali informate. Attraverso un dataset I.Stat, questo progetto esamina e quantifica il divario salariale in base al sesso e al livello di istruzione, identificando tendenze e fornendo raccomandazioni per promuovere l'equità. L'obiettivo è mettere a disposizione delle istituzioni e degli stakeholder (pubblici, privati, sociali) strumenti concreti per interventi informati.

# Background del progetto

Il contesto socio-economico attuale evidenzia come le disuguaglianze di genere rappresentino ancora una sfida significativa per l’Italia, soprattutto sul mercato del lavoro. Questo progetto risponde direttamente alla necessità di comprendere le dimensioni del divario salariale in relazione al livello educativo. L’analisi delle retribuzioni medie e della loro variabilità per genere e titolo di studio mette a disposizione un contributo fondamentale alla discussione politica, sociale ed economica sul tema per stakeholder chiave come policy makers, aziende, enti di formazione e organizzazioni di tutela dei diritti lavorativi.

# Obiettivi del progetto

L'obiettivo principale è esaminare la relazione tra titolo di studio, genere e retribuzione oraria lorda in Italia per l'anno 2022.

- Quantificare e analizzare il divario salariale tra uomini e donne.
- Analizzare l'influenza del titolo di studio sulla retribuzione.
- Identificare eventuali correlazioni tra livello educativo e disparità di genere nella retribuzione.
- Consigliare azioni concrete per politiche di riduzione del divario salariale.

# Domande di ricerca

- Qual è la differenza salariale media per genere a parità di titolo di studio?
- Il livello educativo influisce significativamente sulla disparità salariale tra uomini e donne?
- Esiste una correlazione diretta tra aumento del titolo di studio e riduzione delle differenze retributive per genere?

# Ipotesi

- Un titolo di studio superiore riduce il divario salariale di genere.
- La variabilità salariale è maggiore nei gruppi con titoli di studio inferiori.

# Metodologia

Tramite **OpenOffice Calc**:

## Analisi descrittiva
Per ogni categoria di titolo di studio e genere, si applicheranno le seguenti formule per calcolare le misure di tendenza centrale e dispersione:

- **Media**: La media aritmetica delle retribuzioni per ciascun gruppo.
  - Formula OpenOffice Calc: `=MEDIA(range)`
  - Formula matematica:
 
    
    $$
    \mu = \frac{1}{n} \sum_{i=1}^{n} x_i
    $$


  - Dove $x_i$ è ogni valore nel dataset e $n$ è il numero totale di osservazioni.

- **Mediana**: Il valore centrale che separa i dati in due metà uguali.
  - Formula OpenOffice Calc: `=MEDIANA(range)`
  - Formula matematica:

    $$
    \text{M} =
    \begin{cases}
    x_{\left(\frac{n+1}{2}\right)} & \text{se } n \text{ è dispari} \\
    \frac{x_{\left(\frac{n}{2}\right)} + x_{\left(\frac{n}{2}+1\right)}}{2} & \text{se } n \text{ è pari}
    \end{cases}
    $$
    
    
  - La mediana è il valore che si trova al centro di un insieme ordinato di dati.

- **Deviazione standard**: La misura della dispersione delle retribuzioni rispetto alla media.
  - Formula OpenOffice Calc: `=DEV.STANDARD(range)`
  - Formula matematica:

    $$
    \sigma = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (x_i - \mu)^2}
    $$

    
  - Dove $x_i$ è ogni valore nel dataset, $\mu$ è la media e $n$ è il numero di osservazioni.

## Analisi inferenziale
- **Test statistici**: Per verificare la significatività delle differenze salariali tra generi e livelli di istruzione, si applicheranno test come il test t per campioni indipendenti.

- **Test t per campioni indipendenti**: Verifica se le medie di due gruppi (ad esempio, uomini e donne) sono significativamente diverse.
  - Formula OpenOffice Calc: `=TEST.T(range1, range2, 2, 3)`
  - Formula matematica:

    $$
    t = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}
    $$

    
  - Dove $\bar{x}_1$ e $\bar{x}_2$ sono le medie dei due gruppi, $s_1$ e $s_2$ sono le deviazioni standard e $n_1$ e $n_2$ sono le dimensioni dei gruppi.

## Visualizzazioni

- **Grafici a barre e boxplot**: Utilizzati per confrontare i salari medi e la distribuzione delle retribuzioni tra i gruppi (sesso, titolo di studio).
- **Grafici scatter**: Per visualizzare la correlazione tra livello educativo e retribuzione, nonché le differenze tra uomini e donne.

# Risultati attesi

L'analisi cerca di rivelare:
- Comprensione delle dinamiche salariali e della presenza o assenza di equità salariale tra uomini e donne.
- Evidenze quantitative sul divario retributivo medio e sulla sua variabilità.
- Conferma o rifiuto delle ipotesi riguardanti il ruolo dell'istruzione sul divario di genere.
- Indicazioni informate per politiche pubbliche mirate al raggiungimento della parità salariale.

# Conclusioni

Attraverso i risultati attesi si cerca di formulare raccomandazioni concrete come:
- Incentivare politiche di educazione/formazione volte a ridurre disparità retributive.
- Proporre interventi legislativi o aziendali per garantire trasparenza retributiva.
- Suggerire strategie per la valorizzazione professionale delle donne nel mercato del lavoro.
