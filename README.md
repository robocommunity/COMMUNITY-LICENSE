# Spiegazioni

## Licenza e Contributor License Agreement (CLA)

Questo repository utilizza la **Licenza Community Approval – NC/CA 1.0 (IT)** e la **Contributor License Agreement (CLA)** sviluppate dalla Robo Community.

### 1. Struttura generale

Il progetto include tre documenti principali:

| File                | Contenuto                                                                         | Scopo                                                                                                                                     |
| ------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **LICENSE**         | Tutta la licenza “Community Approval – NC/CA 1.0 (IT)” (articoli 0–13 + allegato) | Regola i diritti d’uso del progetto: cosa si può fare con il codice, come si approva l’uso commerciale e come si gestiscono i contributi. |
| **CLA.md**          | “Contributor License Agreement”                                                   | Dichiarazione di accettazione della licenza e del Regolamento RoboCommunity da parte dei contributor.                                     |
| **CONTRIBUTORS.md** | Elenco dei contributor e dei loro contributi                                      | Serve a tenere traccia dei membri del progetto e a stabilire chi è *Contributor Idoneo* secondo la licenza.                               |

Tutti e tre i file devono essere presenti nella **root del progetto**.

### 2. Come funziona la licenza

La **Licenza Community Approval – NC/CA 1.0 (IT)** disciplina l’uso del progetto e stabilisce un equilibrio tra apertura e tutela dei contributori:

* **Uso non commerciale**: chiunque può utilizzare, modificare e distribuire il codice liberamente, purché non vi sia scopo di lucro e vengano mantenuti i riferimenti alla licenza e agli autori.
* **Uso commerciale**: è possibile solo se approvato dalla maggioranza dei *Contributor Idonei*, secondo la procedura descritta nella licenza (Art. 4). Tale approvazione garantisce che i ricavi siano distribuiti equamente e che eventuali spese sostenute dai membri vengano prima rimborsate.
* **Retribuzione dei contributi**: il richiedente di un uso commerciale deve proporre un *Piano di Retribuzione dei Contributi*, che stabilisce come vengono distribuiti i proventi tra i contributor in base al loro apporto (tecnico, organizzativo, ecc.).
* **Rimborso spese**: prima della distribuzione dei proventi, devono essere rimborsate le spese documentate sostenute per il progetto, secondo il Regolamento ufficiale della Robo Community.
* **Garanzie e responsabilità**: il progetto è fornito “così com’è”, senza garanzie; nessun contributor o titolare è responsabile di danni derivanti dall’uso del progetto.

La licenza si applica automaticamente a chi accede al codice e accetta di contribuire o utilizzare il progetto.

### 3. Cos’è e come usare `CONTRIBUTORS.md`

Il file `CONTRIBUTORS.md` elenca tutte le persone che hanno contribuito al progetto e serve come riferimento ufficiale per determinare chi può essere considerato *Contributor Idoneo* ai sensi della licenza.

Ogni riga o sezione del file dovrebbe includere:

* **Nome e cognome** del contributor (o nickname GitHub, se preferito);
* **Tipo di contributo** (es. codice, documentazione, design, community, traduzioni, ecc.);
* **Quantità o stima di contributo**: per il codice si possono usare le linee di codice nette (addizioni – cancellazioni) misurate con strumenti come `git shortlog` o `git log`; per contributi non di codice si può usare una stima di “linee equivalenti” approvata dal mantenimento del progetto;
* **Data di ultimo contributo**;
* (opzionale) **Note o riferimenti** al lavoro svolto.

Esempio di struttura di `CONTRIBUTORS.md`:

```markdown
# Contributors

| Nome | Tipo di contributo | Linee o equivalenti | Note |
|------|--------------------|--------------------|------|
| Mario Rossi | Codice backend | 420 | API principali |
| Giulia Bianchi | Design e documentazione | 200 (equivalenti) | UX e README |
| Luca Verdi | Gestione community | 150 (equivalenti) | Coordinamento forum |
```

Questo file viene utilizzato come base per:

* determinare chi ha diritto di voto nelle approvazioni di commercializzazione;
* documentare in modo trasparente il contributo di ciascun membro;
* supportare eventuali piani di retribuzione o rimborso.

### 4. Come far accettare la CLA su GitHub

Per assicurare che ogni contributor accetti la CLA e la Licenza:

1. Inserisci il file `CLA.md` nella root del repository.
2. Crea (o modifica) il file `.github/pull_request_template.md` e aggiungi la seguente riga:

```markdown
- [ ] I have read and accept the Contributor License Agreement (CLA) (`CLA.md`) and the Project License.
```

In questo modo, chi apre una Pull Request dovrà dichiarare esplicitamente di accettare la CLA e la Licenza del progetto.

### 5. Accettazione via email

Chi non contribuisce tramite GitHub può accettare la CLA inviando una mail al Founder o all’admin indicato nel file `CLA.md` con il seguente testo:

```
Oggetto: Accettazione CLA RoboCommunity
Dichiaro di aver letto e compreso la Licenza e il Regolamento ufficiale della RoboCommunity, e di accettarne integralmente i termini.
Nome e Cognome - Data
```

Il Founder o chi ne fa le veci deve conservare tali email ai soli fini di registro, secondo quanto previsto dall’allegato della Licenza.
