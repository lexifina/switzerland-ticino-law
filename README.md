# Ticino: law history in git

The law of the canton of Ticino (Repubblica e Cantone Ticino, Switzerland) as a git history: one file per article, one commit per change on the day it took effect. `git blame` and `git log` work line by line; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ti/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in Italian, the canton's official language, exactly as published.

## What this repository holds

439 acts with 1656 versions so far, starting with the cantonal constitution. Each act has every version LexFind keeps of the canton's official text in its current PDF layout (for the constitution, from 2013) to today. It holds the constitution, laws (leggi) and the regolamenti in force, in the order of the systematic collection, added in parts; decrees, agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-000/` | Costituzione della Repubblica e Cantone Ticino (101.000) | 14 | each consolidated version: 1 January 2013 to 1 October 2026 |
| `110-100/` | Legge sui colori e sigillo del Cantone (110.100) | 1 | current text only, in force since 5 February 2002 |
| `141-100/` | Legge sulla cittadinanza ticinese e sull’attinenza comunale (141.100) | 3 | each consolidated version: 1 September 2009 to 1 September 2021 |
| `142-100/` | Legge di applicazione alla Legge federale sui documenti di identità dei cittadini svizzeri (142.100) | 2 | each consolidated version: 1 January 2003 to 1 March 2014 |
| `143-100/` | Legge di applicazione alla legislazione federale in materia di persone straniere (143.100) | 4 | each consolidated version: 27 January 2009 to 30 April 2021 |
| `143-200/` | Legge cantonale di applicazione delle norme federali concernenti le misure coercitive in materia di diritto degli stranieri (143.200) | 1 | current text only, in force since 1 January 2011 |
| `144-100/` | Legge di applicazione della legge federale sull’armonizzazione dei registri e concernente la banca dati movimento della popolazione (144.100) | 1 | current text only, in force since 1 March 2012 |
| `150-100/` | Legge sull’esercizio dei diritti politici (150.100) | 3 | each consolidated version: 1 September 2019 to 1 July 2023 |
| `161-100/` | Legge sulle pubblicazioni ufficiali (161.100) | 1 | current text only, in force since 1 June 2015 |
| `162-100/` | Legge sull’informazione e sulla trasparenza dello Stato (162.100) | 3 | each consolidated version: 1 January 2013 to 21 July 2017 |
| `163-100/` | Legge sulla protezione dei dati personali (163.100) | 4 | each consolidated version: 1 January 2013 to 21 July 2017 |
| `163-150/` | Legge sulla protezione dei dati personali elaborati dalla polizia cantonale e dalle polizie comunali (163.150) | 2 | each consolidated version: 1 October 2008 to 21 July 2017 |
| `164-100/` | Legge sull’archiviazione e sugli archivi pubblici (164.100) | 2 | each consolidated version: 1 June 2012 to 1 March 2014 |
| `165-100/` | Legge sulla procedura amministrativa (165.100) | 4 | each consolidated version: 1 March 2014 to 1 June 2025 |
| `166-100/` | Legge sulla responsabilità civile degli enti pubblici e degli agenti pubblici (166.100) | 4 | each consolidated version: 1 January 2011 to 1 September 2026 |
| `170-100/` | Legge sulla pianificazione cantonale (170.100) | 1 | current text only, in force since 1 January 2007 |
| `171-100/` | Legge sul Gran Consiglio e sui rapporti con il Consiglio di Stato (171.100) | 21 | each consolidated version: 17 April 2015 to 27 February 2026 |
| `172-100/` | Legge concernente le competenze organizzative del Consiglio di Stato e dei suoi dipartimenti (172.100) | 4 | each consolidated version: 1 January 2011 to 1 March 2022 |
| `172-400/` | Legge sulla retribuzione e sulla previdenza professionale dei membri del Consiglio di Stato (172.400) | 1 | current text only, in force since 1 January 2021 |
| `173-100/` | Legge sull’ordinamento degli impiegati dello Stato e dei docenti (173.100) | 15 | each consolidated version: 1 January 2013 to 31 August 2026 |
| `173-300/` | Legge sugli stipendi degli impiegati dello Stato e dei docenti (173.300) | 5 | each consolidated version: 1 January 2018 to 15 December 2025 |
| `173-600/` | Legge sull’assegnazione e sull’uso di posteggi nell’amministrazione cantonale (173.600) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `176-100/` | Legge sul finanziamento tramite il budget globale e il mandato di prestazione delle unità amministrative autonome (176.100) | 2 | each consolidated version: 1 January 2016 to 29 April 2022 |
| `177-100/` | Legge sull’organizzazione giudiziaria (177.100) | 23 | each consolidated version: 1 May 2013 to 21 August 2026 |
| `177-200/` | Legge sugli onorari dei magistrati (177.200) | 5 | each consolidated version: 1 January 2013 to 1 March 2026 |
| `178-100/` | Legge di procedura per le cause davanti al Tribunale cantonale delle assicurazioni (178.100) | 1 | current text only, in force since 1 January 2011 |
| `178-200/` | Legge sulla tariffa giudiziaria (178.200) | 3 | each consolidated version: 10 August 2012 to 10 February 2015 |
| `178-300/` | Legge sull’assistenza giudiziaria e sul patrocinio d’ufficio (178.300) | 2 | each consolidated version: 1 January 2011 to 25 July 2025 |
| `182-100/` | Legge sulla fusione e separazione di Comuni (182.100) | 1 | current text only, in force since 27 January 2009 |
| `182-200/` | Legge sulle aggregazioni e separazioni dei Comuni (182.200) | 6 | each consolidated version: 13 February 2004 to 15 May 2025 |
| `183-100/` | Legge sul consorziamento dei Comuni (183.100) | 2 | each consolidated version: 1 June 2012 to 1 March 2014 |
| `184-300/` | Legge sulla perequazione finanziaria intercomunale (184.300) | 3 | each consolidated version: 20 April 2012 to 1 June 2025 |
| `188-100/` | Legge organica patriziale (188.100) | 5 | each consolidated version: 1 January 2013 to 1 September 2019 |
| `188-200/` | Legge sulle elezioni patriziali (188.200) | 2 | each consolidated version: 1 January 2009 to 1 September 2019 |
| `191-100/` | Legge sulla Chiesa cattolica (191.100) | 3 | each consolidated version: 10 August 2012 to 1 January 2025 |
| `192-100/` | Legge sulla Chiesa evangelica riformata nel Cantone Ticino (192.100) | 3 | each consolidated version: 1 July 1998 to 1 March 2015 |
| `211-100/` | Legge di applicazione e complemento del Codice civile svizzero (211.100) | 7 | each consolidated version: 10 August 2012 to 21 November 2025 |
| `213-100/` | Legge sull’organizzazione e la procedura in materia di protezione del minore e dell’adulto (213.100) | 5 | each consolidated version: 1 January 2013 to 1 March 2016 |
| `215-100/` | Legge sugli atti pubblici stesi dai segretari comunali (215.100) | 1 | current text only, in force since 1 July 2015 |
| `215-400/` | Legge cantonale di applicazione alla Legge federale sull’acquisto di fondi da parte di persone all’estero (215.400) | 3 | each consolidated version: 10 August 2012 to 1 August 2016 |
| `215-600/` | Legge sulla stima ufficiale della sostanza immobiliare (215.600) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `216-100/` | Legge sul registro fondiario (216.100) | 3 | each consolidated version: 1 January 2012 to 1 January 2026 |
| `216-200/` | Legge sulle tariffe per le operazioni nel Registro fondiario (216.200) | 6 | each consolidated version: 1 January 2012 to 17 May 2024 |
| `216-300/` | Legge sulla misurazione ufficiale (216.300) | 5 | each consolidated version: 1 April 2009 to 1 January 2026 |
| `222-100/` | Legge di applicazione delle norme federali in materia di locazione di locali d’abitazione e commerciali e di affitto (222.100) | 2 | each consolidated version: 10 August 2012 to 16 January 2015 |
| `224-100/` | Legge cantonale sul registro di commercio (224.100) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `226-100/` | Legge cantonale di applicazione alla Legge federale sul credito al consumo (226.100) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `270-100/` | Legge di applicazione del codice di diritto processuale civile svizzero (270.100) | 3 | each consolidated version: 10 August 2012 to 5 February 2016 |
| `270-200/` | Legge di applicazione della legge federale sulla parità dei sessi nei rapporti di lavoro di diritto pubblico (270.200) | 1 | current text only, in force since 1 January 2011 |
| `280-100/` | Legge cantonale di applicazione della legge federale sulla esecuzione e sul fallimento (280.100) | 4 | each consolidated version: 1 January 2011 to 1 February 2020 |
| `280-200/` | Legge sulla procedura di ricorso in materia di esecuzione e fallimento (280.200) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `311-100/` | Legge di procedura per le contravvenzioni (311.100) | 2 | each consolidated version: 10 August 2012 to 14 November 2014 |
| `312-400/` | Legge di applicazione e complemento della legge federale concernente l’aiuto alle vittime di reati (312.400) | 1 | current text only, in force since 1 January 2011 |
| `314-100/` | Legge sull’organizzazione delle autorità penali minorili (314.100) | 2 | each consolidated version: 1 January 2010 to 5 February 2016 |
| `316-100/` | Legge sul rimborso delle spese per i procedimenti connessi alla legittima difesa (316.100) | 1 | current text only, in force since 26 September 2021 |
| `340-100/` | Legge sull’esercizio del diritto di grazia (340.100) | 2 | each consolidated version: 27 January 2009 to 14 November 2014 |
| `341-100/` | Legge sull’esecuzione delle pene e delle misure per gli adulti (341.100) | 3 | each consolidated version: 1 January 2011 to 1 January 2018 |
| `406-200/` | Legge concernente l’aggiornamento dei docenti (406.200) | 4 | each consolidated version: 12 May 2009 to 1 August 2020 |
| `411-100/` | Legge sulla scuola dell’infanzia e sulla scuola elementare (411.100) | 13 | each consolidated version: 1 August 2012 to 1 September 2026 |
| `412-100/` | Legge sulla scuola media (412.100) | 3 | each consolidated version: 1 September 2012 to 1 August 2020 |
| `413-100/` | Legge sulla pedagogia speciale (413.100) | 2 | each consolidated version: 1 August 2012 to 1 March 2014 |
| `414-100/` | Legge sulle scuole medie superiori (414.100) | 3 | each consolidated version: 27 January 2009 to 1 April 2023 |
| `415-100/` | Legge sulle scuole professionali (415.100) | 7 | each consolidated version: 1 August 2009 to 10 March 2023 |
| `416-100/` | Legge sull’orientamento scolastico e professionale e sulla formazione professionale e continua (416.100) | 10 | each consolidated version: 1 July 2009 to 21 February 2025 |
| `421-100/` | Legge sull’Università della Svizzera italiana, sulla Scuola universitaria professionale della Svizzera italiana e sugli Istituti di ricerca (421.100) | 12 | each consolidated version: 16 April 2013 to 1 June 2023 |
| `431-100/` | Legge sugli aiuti allo studio (431.100) | 7 | each consolidated version: 1 June 2015 to 21 June 2024 |
| `441-100/` | Legge delle biblioteche (441.100) | 1 | current text only, in force since 15 December 2006 |
| `442-100/` | Legge concernente la conservazione dei musei storici e archeologici (442.100) | 1 | current text only, in force since 27 January 2009 |
| `442-200/` | Legge sui musei etnografici regionali (442.200) | 2 | each consolidated version: 1 January 2012 to 1 March 2014 |
| `445-100/` | Legge sulla protezione dei beni culturali (445.100) | 2 | each consolidated version: 1 January 2012 to 1 February 2014 |
| `451-100/` | Legge sulla statistica cantonale (451.100) | 1 | current text only, in force since 1 June 2012 |
| `461-100/` | Legge sullo sport e l’attività fisica (461.100) | 1 | current text only, in force since 1 May 2014 |
| `480-100/` | Legge cantonale sulla protezione della natura (480.100) | 1 | current text only, in force since 1 January 2012 |
| `482-100/` | Legge di applicazione alla legge federale sulla protezione degli animali (482.100) | 2 | each consolidated version: 1 April 2009 to 1 March 2014 |
| `482-300/` | Legge sui cani (482.300) | 4 | each consolidated version: 1 January 2011 to 15 May 2026 |
| `483-100/` | Legge concernente la raccolta di funghi (483.100) | 1 | current text only, in force since 1 June 2009 |
| `500-100/` | Legge sulla protezione della popolazione (500.100) | 4 | each consolidated version: 1 January 2011 to 1 January 2025 |
| `510-100/` | Legge di applicazione della legislazione federale sull’esercito e sull’amministrazione militare (510.100) | 1 | current text only, in force since 16 April 2021 |
| `520-100/` | Legge sulla protezione civile (520.100) | 6 | each consolidated version: 1 January 2012 to 1 January 2022 |
| `550-100/` | Legge sull’ordine pubblico (550.100) | 3 | each consolidated version: 1 July 2016 to 12 December 2025 |
| `550-300/` | Legge sulla videosorveglianza pubblica (550.300) | 1 | current text only, in force since 1 July 2026 |
| `550-400/` | Legge sulle prestazioni private di sicurezza e investigazione (550.400) | 2 | each consolidated version: 1 June 2021 to 15 July 2025 |
| `550-500/` | Legge sull’esercizio della prostituzione (550.500) | 2 | each consolidated version: 1 July 2019 to 15 June 2023 |
| `561-100/` | Legge sulla polizia (561.100) | 7 | each consolidated version: 1 September 2012 to 5 February 2019 |
| `563-100/` | Legge sulla collaborazione fra la Polizia cantonale e le Polizie comunali (563.100) | 2 | each consolidated version: 1 September 2012 to 1 March 2014 |
| `571-100/` | Legge cantonale di applicazione della legge federale sulle armi, gli accessori di armi e le munizioni (571.100) | 2 | each consolidated version: 3 May 2013 to 1 March 2014 |
| `572-100/` | Legge di applicazione alla legge federale 25 marzo 1977 sugli esplosivi (572.100) | 2 | each consolidated version: 31 December 2010 to 1 March 2014 |
| `600-100/` | Legge sulla gestione e sul controllo finanziario dello Stato (600.100) | 6 | each consolidated version: 1 January 2012 to 18 February 2022 |
| `620-100/` | Legge sui sussidi cantonali (620.100) | 3 | each consolidated version: 1 January 2011 to 15 March 2026 |
| `641-100/` | Legge per il riparto in sede comunale dell’imposta delle aziende idroelettriche , delle aziende del gas e dell’acqua potabile, delle imprese ferroviarie, tramvie e funicolari e delle aziende municipalizzate (641.100) | 3 | each consolidated version: 1 November 2003 to 1 July 2019 |
| `653-100/` | Legge sull’imposta di bollo e sugli spettacoli cinematografici (653.100) | 4 | each consolidated version: 1 January 2012 to 1 January 2020 |
| `701-100/` | Legge sullo sviluppo territoriale (701.100) | 8 | each consolidated version: 1 January 2012 to 1 January 2026 |
| `701-300/` | Legge sul coordinamento delle procedure (701.300) | 1 | current text only, in force since 1 January 2007 |
| `701-500/` | Legge sui territori interessati da pericoli naturali (701.500) | 2 | each consolidated version: 21 July 2017 to 1 January 2026 |
| `702-100/` | Legge sul raggruppamento e la permuta dei terreni (702.100) | 3 | each consolidated version: 1 January 2012 to 29 December 2017 |
| `703-100/` | Legge sui contributi di miglioria (703.100) | 4 | each consolidated version: 18 May 2010 to 1 January 2026 |
| `704-100/` | Legge cantonale sulla geoinformazione (704.100) | 1 | current text only, in force since 1 January 2014 |
| `705-100/` | Legge edilizia cantonale (705.100) | 4 | each consolidated version: 1 December 2012 to 1 January 2024 |
| `705-200/` | Legge sulla protezione antincendio (705.200) | 2 | each consolidated version: 1 January 2024 to 1 January 2025 |
| `705-400/` | Legge cantonale sull’esercizio delle professioni di ingegnere e di architetto (705.400) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `705-500/` | Legge sull’esercizio della professione di impresario costruttore (705.500) | 4 | each consolidated version: 27 January 2009 to 1 June 2015 |
| `705-600/` | Legge sugli impianti pubblicitari (705.600) | 3 | each consolidated version: 1 May 2009 to 15 May 2015 |
| `720-100/` | Legge sul demanio pubblico (720.100) | 4 | each consolidated version: 1 January 2007 to 1 January 2022 |
| `721-100/` | Legge sulla gestione delle acque (721.100) | 1 | current text only, in force since 1 January 2026 |
| `723-100/` | Legge sui Consorzi (723.100) | 4 | each consolidated version: 27 January 2009 to 1 January 2026 |
| `725-100/` | Legge sulle strade (725.100) | 3 | each consolidated version: 1 December 2012 to 29 May 2026 |
| `725-200/` | Legge di applicazione della legge federale sulle strade nazionali (725.200) | 1 | current text only, in force since 1 December 2012 |
| `740-100/` | Legge cantonale sull’energia (740.100) | 9 | each consolidated version: 1 February 2011 to 1 January 2025 |
| `742-100/` | Legge cantonale di applicazione della legge federale sull’approvvigionamento elettrico del 23 marzo 2007 (742.100) | 4 | each consolidated version: 1 January 2010 to 1 July 2019 |
| `743-100/` | Legge sull’Azienda elettrica ticinese (743.100) | 3 | each consolidated version: 8 July 2016 to 24 January 2020 |
| `751-100/` | Legge sul coordinamento pianificatorio e finanziario in materia di infrastrutture e di servizi di trasporto (751.100) | 2 | each consolidated version: 25 April 1997 to 1 March 2014 |
| `752-100/` | Legge sui trasporti pubblici (752.100) | 9 | each consolidated version: 1 January 2009 to 1 January 2026 |
| `760-100/` | Legge di applicazione alla legislazione federale sulla circolazione stradale e la tassa sul traffico pesante (760.100) | 3 | each consolidated version: 8 February 2013 to 1 May 2023 |
| `760-500/` | Legge sulle imposte e tasse di circolazione dei veicoli a motore (760.500) | 5 | each consolidated version: 27 January 2009 to 16 February 2024 |
| `770-100/` | Legge sulle funi metalliche (770.100) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `770-300/` | Legge d’applicazione del concordato concernente gli impianti di trasporto a fune e le sciovie esonerati dalla concessione federale (770.300) | 1 | current text only, in force since 1 July 2018 |
| `781-100/` | Legge cantonale di applicazione alla legge federale del 3 ottobre 1975 sulla navigazione interna (781.100) | 3 | each consolidated version: 1 January 2011 to 1 January 2016 |
| `801-100/` | Legge sulla promozione della salute e il coordinamento sanitario (801.100) | 13 | each consolidated version: 10 August 2012 to 1 June 2025 |
| `801-200/` | Legge concernente l'autorizzazione delle attrezzature medico-tecniche di diagnosi o di cura a tecnologia avanzata o particolarmente costosa (clausola del bisogno) (801.200) | 1 | current text only, in force since 2 December 2016 |
| `805-100/` | Legge sul servizio medico nelle zone di montagna (805.100) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `806-100/` | Legge sull’assistenza sociopsichiatrica (806.100) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `811-100/` | Legge sull’EOC (Ente ospedaliero cantonale) (811.100) | 5 | each consolidated version: 1 February 2013 to 1 April 2025 |
| `811-400/` | Legge d’applicazione della legge federale sui consultori di gravidanza (811.400) | 1 | current text only, in force since 23 February 1988 |
| `812-100/` | Legge sul servizio pre-ospedaliero di soccorso e trasporto sanitario (812.100) | 1 | current text only, in force since 27 January 2009 |
| `821-100/` | Legge sul registro dei tumori (821.100) | 2 | each consolidated version: 1 October 2008 to 7 August 2020 |
| `822-100/` | Legge d’applicazione della legge federale sugli stupefacenti del 3 ottobre 1951 (822.100) | 5 | each consolidated version: 1 January 2012 to 1 September 2025 |
| `822-200/` | Legge sulla coltivazione della canapa e sulla vendita al dettaglio dei suoi prodotti (822.200) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `824-100/` | Legge cantonale di applicazione della legge federale sulle derrate alimentari e sugli oggetti d’uso (824.100) | 1 | current text only, in force since 1 January 1997 |
| `826-100/` | Legge di applicazione alla Ordinanza concernente l’eliminazione dei sottoprodotti di origine animale del 23 giugno 2004 (826.100) | 2 | each consolidated version: 12 November 2010 to 1 March 2014 |
| `831-100/` | Legge cantonale di applicazione della legge federale sulla protezione dell’ambiente (831.100) | 6 | each consolidated version: 1 January 2013 to 12 April 2024 |
| `832-100/` | Legge concernente l’istituzione dell’azienda cantonale dei rifiuti (832.100) | 4 | each consolidated version: 1 February 2011 to 5 June 2018 |
| `832-200/` | Legge concernente l’eliminazione degli autoveicoli inservibili (832.200) | 2 | each consolidated version: 22 March 1996 to 2 June 2023 |
| `835-100/` | Legge sull'organizzazione della lotta contro gli incendi, gli inquinamenti e i danni della natura (835.100) | 1 | current text only, in force since 1 January 2011 |
| `836-100/` | Legge cantonale di applicazione della legge federale sulla protezione contro le sostanze e i preparati pericolosi (836.100) | 2 | each consolidated version: 10 August 2012 to 1 March 2014 |
| `842-100/` | Legge sull’Ufficio cantonale di conciliazione e sul conferimento del carattere obbligatorio generale al contratto collettivo di lavoro (842.100) | 1 | current text only, in force since 1 June 2011 |
| `843-100/` | Legge di applicazione della legge federale sul lavoro nell’industria, nell’artigianato e nel commercio e della legge federale sul lavoro a domicilio (843.100) | 2 | each consolidated version: 1 June 2011 to 1 March 2014 |
| `843-300/` | Legge d’applicazione della Legge federale concernente condizioni lavorative e salariali minime per lavoratori distaccati in Svizzera e misure collaterali (LDist.) e della Legge federale concernente i provvedimenti in materia di lotta contro il lavoro nero (LLN) (843.300) | 3 | each consolidated version: 10 August 2012 to 14 November 2014 |
| `843-400/` | Legge concernente il rafforzamento della sorveglianza del mercato del lavoro (843.400) | 1 | current text only, in force since 1 January 2017 |
| `843-600/` | Legge sul salario minimo (843.600) | 2 | each consolidated version: 1 January 2021 to 21 April 2023 |
| `851-200/` | Legge di applicazione della legge federale concernente le prestazioni complementari all’assicurazione federale per la vecchiaia, i superstiti e l’invalidità (851.200) | 3 | each consolidated version: 1 January 2012 to 1 January 2026 |
| `851-400/` | Legge di applicazione della legge federale sull’assicurazione invalidità (851.400) | 2 | each consolidated version: 1 January 2008 to 24 May 2019 |
| `852-100/` | Legge concernente la vigilanza sugli istituti di previdenza professionale e sulle fondazioni (852.100) | 2 | each consolidated version: 1 January 2012 to 21 November 2025 |
| `853-100/` | Legge di applicazione della Legge federale sull’assicurazione malattie (853.100) | 16 | each consolidated version: 1 January 2013 to 1 January 2026 |
| `854-100/` | Legge sull’assicurazione contro gli infortuni (854.100) | 1 | current text only, in force since 10 August 2012 |
| `855-100/` | Legge sulle indennità di perdita di guadagno in caso di adozione (855.100) | 3 | each consolidated version: 1 January 2017 to 16 February 2024 |
| `856-100/` | Legge sugli assegni di famiglia (856.100) | 10 | each consolidated version: 1 January 2013 to 1 April 2021 |
| `857-100/` | Legge sul rilancio dell’occupazione e sul sostegno ai disoccupati (857.100) | 3 | each consolidated version: 1 June 2011 to 1 January 2016 |
| `861-100/` | Legge sull’abitazione (861.100) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `862-100/` | Legge concernente il rinnovo di abitazioni (862.100) | 1 | current text only, in force since 27 January 2009 |
| `863-100/` | Legge concernente il miglioramento delle condizioni di abitazioni nelle regioni di montagna (863.100) | 2 | each consolidated version: 27 January 2009 to 1 March 2014 |
| `872-100/` | Legge sull’assistenza e cura a domicilio (872.100) | 7 | each consolidated version: 22 March 2013 to 27 February 2026 |
| `873-100/` | Legge concernente il promovimento, il coordinamento e il finanziamento delle attività a favore delle persone anziane (873.100) | 5 | each consolidated version: 22 March 2013 to 1 January 2025 |
| `874-100/` | Legge sul sostegno alle attività delle famiglie e di protezione dei minorenni (874.100) | 9 | each consolidated version: 27 January 2009 to 1 January 2026 |
| `874-200/` | Legge sulla promozione delle attività dell’infanzia e della gioventù (874.200) | 1 | current text only, in force since 1 January 2026 |
| `874-500/` | Legge sulle misure restrittive della libertà dei minorenni nei centri educativi (874.500) | 1 | current text only, in force since 1 January 2018 |
| `875-100/` | Legge sull’integrazione sociale e professionale degli invalidi (875.100) | 4 | each consolidated version: 1 August 2012 to 1 July 2020 |
| `900-100/` | Legge per l'innovazione economica (900.100) | 4 | each consolidated version: 5 February 2016 to 16 February 2024 |
| `901-100/` | Legge d’applicazione della Legge federale sulla politica regionale del 6 ottobre 2006 (901.100) | 3 | each consolidated version: 1 October 2009 to 21 February 2020 |
| `909-100/` | Decreto legislativo urgente sullo stanziamento di un credito lordo di 75.6 milioni di franchi e netto di 24.52 milioni di franchi per l’adozione di misure a favore dei casi di rigore ai sensi dell’ordinanza COVID-19 sui casi di rigore, sul contributo a copertura dei costi sostenuti dai beneficiari per i costi di revisione e per le prestazioni fornite dalla Cooperativa di fideiussione CFSud (909.100) | 5 | each consolidated version: 29 January 2021 to 1 June 2022 |
| `910-100/` | Legge sull’agricoltura (910.100) | 10 | each consolidated version: 1 January 2012 to 26 May 2025 |
| `910-200/` | Legge sulla conservazione del territorio agricolo (910.200) | 1 | current text only, in force since 1 January 2012 |
| `911-100/` | Legge sul diritto fondiario rurale e sull’affitto agricolo (911.100) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `914-400/` | Legge cantonale sui provvedimenti per combattere le epizoozie (914.400) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `921-100/` | Legge cantonale sulle foreste (921.100) | 3 | each consolidated version: 1 January 2012 to 1 January 2016 |
| `922-100/` | Legge sulla caccia e la protezione dei mammiferi e degli uccelli selvatici (922.100) | 6 | each consolidated version: 1 January 2011 to 22 November 2024 |
| `923-100/` | Legge cantonale sulla pesca e sulla protezione dei pesci e gamberi indigeni (923.100) | 5 | each consolidated version: 1 January 2010 to 1 December 2024 |
| `941-100/` | Legge sul turismo (941.100) | 8 | each consolidated version: 1 January 2015 to 12 April 2024 |
| `942-100/` | Legge sugli esercizi alberghieri e sulla ristorazione (942.100) | 1 | current text only, in force since 15 June 2023 |
| `943-100/` | Legge sui campeggi (943.100) | 4 | each consolidated version: 1 January 2013 to 1 January 2024 |
| `944-100/` | Legge di applicazione della legge federale sui giochi in denaro (944.100) | 1 | current text only, in force since 1 January 2024 |
| `945-200/` | Legge sull’apertura dei negozi (945.200) | 6 | each consolidated version: 1 January 2020 to 1 October 2026 |
| `945-300/` | Legge di applicazione della legge federale sul commercio ambulante (945.300) | 1 | current text only, in force since 1 January 2024 |
| `946-100/` | Legge cantonale di esecuzione della legge federale 9 giugno 1977 sulla metrologia (946.100) | 2 | each consolidated version: 10 August 2012 to 1 March 2014 |
| `947-100/` | Legge di applicazione alla legislazione federale in materia di indicazione dei prezzi (947.100) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `951-100/` | Legge sull’avvocatura (951.100) | 2 | each consolidated version: 1 January 2013 to 1 March 2014 |
| `952-100/` | Legge sul notariato (952.100) | 2 | each consolidated version: 1 July 2015 to 1 February 2025 |
| `952-300/` | Legge sulla tariffa notarile (952.300) | 1 | current text only, in force since 1 July 2015 |
| `953-100/` | Legge sull’esercizio delle professioni di fiduciario (953.100) | 3 | each consolidated version: 10 August 2012 to 1 January 2022 |
| `960-100/` | Legge sulla Banca dello Stato del Cantone Ticino (960.100) | 3 | each consolidated version: 1 February 2013 to 5 June 2018 |
| `141-110/` | Regolamento della legge sulla cittadinanza ticinese e sull’attinenza comunale (141.110) | 2 | each consolidated version: 1 January 2018 to 1 September 2021 |
| `142-110/` | Regolamento della legge di applicazione alla legge federale sui documenti di identità dei cittadini svizzeri (142.110) | 2 | each consolidated version: 1 January 2011 to 1 October 2014 |
| `143-110/` | Regolamento della legge di applicazione alla legislazione federale in materia di persone straniere (143.110) | 6 | each consolidated version: 6 April 2012 to 1 July 2026 |
| `143-130/` | Regolamento del Centro cantonale polivalente di Camorino (143.130) | 1 | current text only, in force since 12 September 2025 |
| `143-210/` | Regolamento della legge cantonale di applicazione delle norme federali concernenti le misure coercitive in materia di diritto degli stranieri (143.210) | 1 | current text only, in force since 19 December 2025 |
| `143-250/` | Regolamento della Commissione cantonale per l’integrazione degli stranieri (143.250) | 3 | each consolidated version: 1 January 2012 to 21 May 2021 |
| `143-310/` | Regolamento concernente le prestazioni assistenziali per i richiedenti l’asilo, le persone bisognose di protezione non titolari di un permesso di dimora, le persone provvisoriamente ammesse e le persone la cui domanda d’asilo è stata rigettata e che devono lasciare il territorio svizzero (143.310) | 2 | each consolidated version: 1 January 2012 to 1 January 2014 |
| `143-320/` | Regolamento sulle competenze e procedure per l’utilizzo dell’importo assegnato dalla Confederazione al Cantone per l’integrazione delle persone ammesse provvisoriamente e dei rifugiati riconosciuti (143.320) | 1 | current text only, in force since 13 July 2012 |
| `144-110/` | Regolamento della legge di applicazione della legge federale sull’armonizzazione dei registri e concernente il controllo degli abitanti e la banca dati movimento della popolazione (144.110) | 2 | each consolidated version: 1 March 2012 to 1 January 2023 |
| `150-110/` | Regolamento sull’esercizio dei diritti politici (150.110) | 3 | each consolidated version: 1 September 2019 to 1 January 2026 |
| `161-110/` | Regolamento sulle pubblicazioni ufficiali (161.110) | 3 | each consolidated version: 1 June 2015 to 1 February 2021 |
| `162-110/` | Regolamento della legge sull’informazione e sulla trasparenza dello Stato (162.110) | 2 | each consolidated version: 1 January 2013 to 24 March 2017 |
| `163-110/` | Regolamento di applicazione alla legge cantonale sulla protezione dei dati personali (163.110) | 1 | current text only, in force since 1 October 2008 |
| `164-110/` | Regolamento di applicazione della legge sull’archiviazione e sugli archivi pubblici (164.110) | 3 | each consolidated version: 1 June 2012 to 30 December 2014 |
| `164-200/` | Regolamento sulla gestione dei documenti nell’amministrazione cantonale (164.200) | 1 | current text only, in force since 1 January 2013 |
| `165-110/` | Regolamento sulla comunicazione per via elettronica nell’ambito di procedimenti amministrativi (165.110) | 1 | current text only, in force since 1 February 2024 |
| `172-210/` | Regolamento sull’organizzazione del Consiglio di Stato e dell’Amministrazione (172.210) | 6 | each consolidated version: 4 May 2001 to 12 November 2021 |
| `172-220/` | Regolamento sulle deleghe di competenze decisionali (172.220) | 52 | each consolidated version: 22 March 2013 to 16 October 2026 |
| `172-230/` | Regolamento concernente il Servizio dei ricorsi del Consiglio di Stato ed i suoi rapporti con il Collegio governativo e l’Amministrazione cantonale (172.230) | 2 | each consolidated version: 1 July 2009 to 1 March 2014 |
| `172-350/` | Regolamento concernente le commissioni, i gruppi di lavoro e le rappresentanze presso enti di nomina del Consiglio di Stato (172.350) | 4 | each consolidated version: 9 March 2012 to 1 November 2025 |
| `173-110/` | Regolamento dei dipendenti dello Stato (173.110) | 20 | each consolidated version: 1 January 2018 to 22 May 2026 |
| `173-120/` | Regolamento sul rapporto d’impiego dei collaboratori personali dei Consiglieri di Stato (173.120) | 2 | each consolidated version: 1 January 2013 to 1 February 2023 |
| `173-130/` | Regolamento concernente i gradi e le promozioni presso la Polizia cantonale (173.130) | 2 | each consolidated version: 1 January 2018 to 24 March 2023 |
| `173-140/` | Regolamento concernente le promozioni del personale uniformato delle Strutture carcerarie cantonali (173.140) | 1 | current text only, in force since 1 January 2018 |
| `173-150/` | Regolamento concernente le promozioni per la Divisione delle contribuzioni (173.150) | 2 | each consolidated version: 1 January 2018 to 25 October 2019 |
| `173-160/` | Regolamento concernente le promozioni presso l’Istituto delle assicurazioni sociali (173.160) | 2 | each consolidated version: 1 January 2018 to 21 September 2018 |
| `173-170/` | Regolamento sul personale ausiliario dello Stato (173.170) | 2 | each consolidated version: 1 September 2021 to 12 April 2024 |
| `173-180/` | Regolamento concernente la formazione continua degli impiegati (173.180) | 3 | each consolidated version: 30 November 2012 to 25 March 2016 |
| `173-190/` | Regolamento sul rapporto d’impiego dei dipendenti del Ristorante Castelgrande (173.190) | 3 | each consolidated version: 1 March 2011 to 18 September 2026 |
| `173-210/` | Regolamento concernente l’assegnazione e l’ uso di appartamenti di servizio nell’amministrazione cantonale (173.210) | 2 | each consolidated version: 17 October 2003 to 1 March 2014 |
| `173-310/` | Regolamento concernente le funzioni e le classificazioni dei dipendenti dello Stato (173.310) | 61 | each consolidated version: 1 January 2018 to 18 September 2026 |
| `173-450/` | Regolamento concernente le indennità ai dipendenti dello Stato (173.450) | 5 | each consolidated version: 30 September 2011 to 10 July 2026 |
| `173-460/` | Regolamento concernente le indennità e i rimborsi spese della Sezione cinofila della Polizia cantonale (173.460) | 1 | current text only, in force since 1 January 2025 |
| `173-550/` | Regolamento sull’assicurazione del personale dello Stato e dei docenti contro gli infortuni (173.550) | 1 | current text only, in force since 1 January 1996 |
| `175-110/` | Regolamento concernente le tasse per le prestazioni dell’Ufficio di statistica (175.110) | 1 | current text only, in force since 2 March 2018 |
| `176-110/` | Regolamento concernente la legge sul finanziamento tramite il budget globale e il mandato di prestazione delle unità amministrative autonome (176.110) | 3 | each consolidated version: 18 March 2016 to 16 September 2022 |
| `177-110/` | Regolamento delle Giudicature di pace (177.110) | 2 | each consolidated version: 1 January 2011 to 12 July 2019 |
| `177-120/` | Regolamento delle Preture (177.120) | 1 | current text only, in force since 1 January 2011 |
| `177-130/` | Regolamento del Tribunale d’appello (177.130) | 1 | current text only, in force since 1 December 2025 |
| `177-430/` | Regolamento concernente lo svolgimento di mandati arbitrali, peritali e di mediazione in campo privato da parte dei magistrati dell’ordine giudiziario (177.430) | 1 | current text only, in force since 1 September 2000 |
| `177-445/` | Regolamento del Consiglio della magistratura (177.445) | 2 | each consolidated version: 1 March 2024 to 25 July 2025 |
| `178-110/` | Regolamento concernente l’organizzazione e la procedura del Tribunale arbitrale in materia di assicurazione contro le malattie e gli infortuni (178.110) | 2 | each consolidated version: 1 January 2011 to 1 March 2014 |
| `178-210/` | Regolamento concernente le tasse di cancelleria delle autorità giudiziarie (178.210) | 1 | current text only, in force since 1 January 2013 |
| `178-310/` | Regolamento sulla tariffa per i casi di patrocinio d’ufficio e di assistenza giudiziaria e per la fissazione delle ripetibili (178.310) | 2 | each consolidated version: 1 January 2013 to 1 January 2015 |
| `178-320/` | Regolamento di applicazione della legge sulla tariffa giudiziaria e della legge sull’assistenza giudiziaria e sul patrocinio d’ufficio (178.320) | 2 | each consolidated version: 21 September 2012 to 1 January 2024 |
| `181-120/` | Regolamento concernente la certificazione cantonale dei sistemi di gestione della qualità nei Comuni (181.120) | 1 | current text only, in force since 1 September 2014 |
| `181-210/` | Regolamento per un modello unico di tariffa (181.210) | 1 | current text only, in force since 30 December 2003 |
| `181-310/` | Regolamento sulla formazione professionale di base e continua per il settore degli enti locali (181.310) | 2 | each consolidated version: 1 January 2010 to 1 September 2023 |
| `181-320/` | Regolamento sulla formazione professionale di base e continua dei segretari comunali (181.320) | 2 | each consolidated version: 1 January 2010 to 1 September 2023 |
| `183-110/` | Regolamento di applicazione della legge sul consorziamento dei Comuni (183.110) | 2 | each consolidated version: 10 May 2013 to 1 January 2023 |
| `184-150/` | Regolamento sulla gestione finanziaria e sulla contabilità dei comuni (184.150) | 7 | each consolidated version: 1 July 2019 to 6 February 2026 |
| `184-310/` | Regolamento sulla perequazione finanziaria intercomunale (184.310) | 10 | each consolidated version: 23 November 2012 to 1 January 2026 |
| `185-350/` | Regolamento concernente il controllo delle attività economiche (185.350) | 2 | each consolidated version: 1 October 2001 to 15 September 2023 |
| `188-110/` | Regolamento di applicazione della Legge organica patriziale (188.110) | 7 | each consolidated version: 1 January 2013 to 1 January 2023 |
| `188-120/` | Regolamento concernente la gestione finanziaria e la tenuta della contabilità dei patriziati (188.120) | 2 | each consolidated version: 1 January 2013 to 25 March 2016 |
| `191-110/` | Regolamento della legge sulla Chiesa cattolica (191.110) | 2 | each consolidated version: 1 May 2013 to 1 April 2025 |
| `211-120/` | Regolamento sulla sorveglianza elettronica in ambito civile (211.120) | 1 | current text only, in force since 1 January 2022 |
| `213-110/` | Regolamento della legge sull’organizzazione e la procedura in materia di protezione del minore e dell’adulto (213.110) | 7 | each consolidated version: 1 April 2013 to 1 June 2023 |
| `213-210/` | Regolamento concernente i consultori matrimoniali-familiari (213.210) | 1 | current text only, in force since 4 October 2024 |
| `213-410/` | Regolamento concernente l’accoglienza di adottandi (213.410) | 3 | each consolidated version: 15 October 2013 to 1 January 2018 |
| `215-310/` | Regolamento sul prestito a pegno (215.310) | 2 | each consolidated version: 15 May 2009 to 1 March 2014 |
| `215-610/` | Regolamento di applicazione della legge sulla stima ufficiale della sostanza immobiliare (215.610) | 2 | each consolidated version: 1 January 2013 to 30 November 2018 |
| `216-110/` | Regolamento concernente la legge sul registro fondiario (216.110) | 3 | each consolidated version: 23 November 2012 to 15 March 2024 |
| `222-110/` | Regolamento della legge di applicazione delle norme federali in materia di locazione di locali d’abitazione e commerciali e di affitto (222.110) | 1 | current text only, in force since 1 January 2011 |
| `312-410/` | Regolamento della Legge di applicazione e complemento della Legge federale concernente l’aiuto alle vittime di reati (312.410) | 4 | each consolidated version: 24 December 2010 to 1 March 2026 |
| `314-150/` | Regolamento sulla mediazione penale minorile (314.150) | 2 | each consolidated version: 1 January 2011 to 5 July 2013 |
| `341-110/` | Regolamento sull’esecuzione delle pene e delle misure per gli adulti (341.110) | 4 | each consolidated version: 1 January 2013 to 1 July 2020 |
| `341-130/` | Regolamento relativo alla Fondazione latina Progetti pilota - Dipendenze (341.130) | 1 | current text only, in force since 22 March 2012 |
| `341-140/` | Regolamento sull’esecuzione delle pene privative di libertà sotto sorveglianza elettronica (341.140) | 1 | current text only, in force since 1 January 2018 |
| `341-150/` | Regolamento sull’esecuzione delle pene nella forma del lavoro di utilità pubblica (341.150) | 1 | current text only, in force since 1 January 2018 |
| `341-160/` | Regolamento relativo all’esecuzione delle pene nella forma della semiprigionia (341.160) | 1 | current text only, in force since 1 January 2018 |
| `342-110/` | Regolamento delle strutture carcerarie del Cantone Ticino (342.110) | 2 | each consolidated version: 1 January 2013 to 11 July 2014 |
| `343-510/` | Regolamento relativo alla concessione di autorizzazioni di uscita alle persone condannate adulte e ai giovani adulti (343.510) | 2 | each consolidated version: 31 October 2013 to 24 June 2014 |
| `343-520/` | Regolamento relativo alla lista degli stabilimenti per l’esecuzione - anche anticipata - delle sanzioni penali privative di libertà (343.520) | 1 | current text only, in force since 1 November 2008 |
| `343-530/` | Regolamento concordatario relativo alla concessione di autorizzazioni di uscita alle persone condannate minorenni (343.530) | 1 | current text only, in force since 31 October 2013 |
| `343-550/` | Regolamento concordatario sul diritto disciplinare applicabile alle persone detenute penalmente o collocate in uno stabilimento chiuso per minorenni (343.550) | 1 | current text only, in force since 31 October 2013 |
| `400-120/` | Regolamento sul monte ore scolastico (400.120) | 2 | each consolidated version: 1 August 2019 to 1 July 2025 |
| `400-140/` | Regolamento dei corsi di lingua italiana e delle attività di integrazione (400.140) | 2 | each consolidated version: 1 August 2021 to 1 August 2023 |
| `400-160/` | Regolamento del Centro di risorse didattiche e digitali (400.160) | 1 | current text only, in force since 1 January 2015 |
| `400-170/` | Regolamento del Servizio mobilità e scambi (400.170) | 1 | current text only, in force since 8 July 2022 |
| `401-150/` | Regolamento sul credito a disposizione degli istituti scolastici (401.150) | 4 | each consolidated version: 1 September 2010 to 1 July 2025 |
| `402-150/` | Regolamento sulla medicina scolastica (402.150) | 1 | current text only, in force since 1 July 2020 |
| `402-160/` | Regolamento per il servizio dentario scolastico (402.160) | 4 | each consolidated version: 1 September 2007 to 21 August 2020 |
| `403-150/` | Regolamento per l’uso degli spazi scolastici e degli impianti sportivi dello Stato (403.150) | 5 | each consolidated version: 1 April 2014 to 2 October 2026 |
| `404-150/` | Regolamento dell’assicurazione scolastica (404.150) | 4 | each consolidated version: 1 August 2016 to 9 November 2018 |
| `406-150/` | Regolamento sull'onere d'insegnamento dei docenti (406.150) | 9 | each consolidated version: 1 August 2018 to 1 September 2026 |
| `406-160/` | Regolamento sulle supplenze dei docenti (406.160) | 8 | each consolidated version: 1 September 2009 to 1 January 2025 |
| `406-210/` | Regolamento sulla formazione continua dei docenti (406.210) | 4 | each consolidated version: 1 August 2015 to 1 August 2020 |
| `412-110/` | Regolamento della scuola media (412.110) | 15 | each consolidated version: 2 August 2018 to 1 September 2026 |
| `413-110/` | Regolamento della pedagogia speciale (413.110) | 5 | each consolidated version: 1 August 2017 to 10 March 2023 |
| `414-110/` | Regolamento delle scuole medie superiori (414.110) | 13 | each consolidated version: 1 August 2016 to 27 February 2026 |
| `415-110/` | Regolamento delle scuole professionali (415.110) | 13 | each consolidated version: 1 August 2015 to 1 September 2026 |
| `415-120/` | Regolamento della maturità professionale (415.120) | 5 | each consolidated version: 1 August 2015 to 1 January 2023 |
| `416-110/` | Regolamento della formazione professionale e continua (416.110) | 11 | each consolidated version: 1 August 2014 to 30 May 2025 |
| `416-120/` | Regolamento sull’orientamento scolastico e professionale (416.120) | 3 | each consolidated version: 1 August 2014 to 24 October 2025 |
| `416-130/` | Regolamento del fondo cantonale per la formazione professionale (416.130) | 1 | current text only, in force since 1 April 2011 |
| `421-110/` | Regolamento della legge sull’Università della Svizzera italiana, sulla Scuola universitaria professionale della Svizzera italiana e sugli Istituti di ricerca (421.110) | 10 | each consolidated version: 21 February 2014 to 1 June 2023 |
| `440-110/` | Regolamento sul sostegno alla cultura (440.110) | 1 | current text only, in force since 1 September 2026 |
| `441-110/` | Regolamento della legge delle biblioteche (441.110) | 2 | each consolidated version: 15 October 2019 to 13 December 2019 |
| `442-310/` | Regolamento della Pinacoteca cantonale Giovanni Züst (442.310) | 2 | each consolidated version: 1 January 2015 to 10 November 2017 |
| `445-110/` | Regolamento sulla protezione dei beni culturali (445.110) | 1 | current text only, in force since 1 January 2012 |
| `446-110/` | Regolamento del Centro di dialettologia e di etnografia (446.110) | 1 | current text only, in force since 1 January 2025 |
| `451-110/` | Regolamento della legge sulla statistica cantonale (451.110) | 1 | current text only, in force since 10 March 2010 |
| `451-350/` | Regolamento concernente l’allestimento di un censimento delle abitazioni vuote (451.350) | 1 | current text only, in force since 7 May 2010 |
| `461-110/` | Regolamento della legge sullo sport e l’attività fisica (461.110) | 8 | each consolidated version: 1 May 2014 to 8 November 2024 |
| `480-110/` | Regolamento della legge cantonale sulla protezione della natura (480.110) | 3 | each consolidated version: 29 January 2013 to 24 October 2014 |
| `482-110/` | Regolamento di applicazione alla Legge cantonale sulla protezione degli animali (482.110) | 3 | each consolidated version: 15 March 2002 to 1 January 2024 |
| `482-310/` | Regolamento sui cani (482.310) | 2 | each consolidated version: 1 January 2026 to 26 June 2026 |
| `500-110/` | Regolamento sulla protezione della popolazione (500.110) | 1 | current text only, in force since 1 January 2018 |
| `510-110/` | Regolamento della legge di applicazione della legislazione federale sull’esercito e sull’amministrazione militare (510.110) | 1 | current text only, in force since 16 April 2021 |
| `520-110/` | Regolamento sulla protezione civile (520.110) | 6 | each consolidated version: 1 July 2008 to 1 January 2025 |
| `520-350/` | Regolamento del Fondo dei contributi sostitutivi (520.350) | 1 | current text only, in force since 1 January 2014 |
| `550-250/` | Regolamento sull’ordine pubblico e sulla dissimulazione del volto negli spazi pubblici (550.250) | 2 | each consolidated version: 1 July 2016 to 21 February 2025 |
| `550-410/` | Regolamento della legge sulle prestazioni private di sicurezza e investigazione (550.410) | 2 | each consolidated version: 1 June 2021 to 12 November 2021 |
| `550-510/` | Regolamento sull’esercizio della prostituzione (550.510) | 1 | current text only, in force since 1 July 2019 |
| `561-110/` | Regolamento sulla polizia (561.110) | 12 | each consolidated version: 10 June 2011 to 13 March 2026 |
| `561-150/` | Regolamento sulla Scuola di polizia del V Circondario d’esami (561.150) | 3 | each consolidated version: 1 March 2017 to 22 December 2023 |
| `561-250/` | Regolamento concernente le tasse per prestazioni della polizia cantonale (561.250) | 7 | each consolidated version: 1 October 2016 to 16 May 2025 |
| `561-350/` | Regolamento sulle registrazioni audio e video per l’identificazione dei veicoli (561.350) | 1 | current text only, in force since 15 July 2011 |
| `561-360/` | Regolamento per l’impiego di apparecchi audio e video a supporto delle operazioni e degli interventi della polizia cantonale (561.360) | 1 | current text only, in force since 1 March 2012 |
| `563-200/` | Regolamento della legge sulla collaborazione fra la Polizia cantonale e le Polizie comunali (563.200) | 9 | each consolidated version: 1 September 2012 to 20 December 2024 |
| `563-210/` | Regolamento concernente l’uniformazione dei gradi e delle condizioni di stipendio dei Corpi di polizia cantonale e comunali (563.210) | 7 | each consolidated version: 6 June 2017 to 5 May 2026 |
| `571-110/` | Regolamento della legge cantonale di applicazione della legge federale sulle armi, gli accessori di armi e le munizioni (571.110) | 3 | each consolidated version: 1 July 2009 to 1 January 2018 |
| `572-110/` | Regolamento della legge di applicazione della legge federale 25 marzo 1977 sugli esplosivi (572.110) | 4 | each consolidated version: 1 January 2011 to 16 November 2018 |
| `600-110/` | Regolamento sulla gestione finanziaria dello Stato (600.110) | 9 | each consolidated version: 4 January 2005 to 24 January 2025 |
| `600-250/` | Regolamento del controllo cantonale delle finanze (600.250) | 3 | each consolidated version: 27 July 2012 to 13 September 2019 |
| `640-130/` | Regolamento sulle procedure elettroniche in ambito fiscale (640.130) | 3 | each consolidated version: 1 January 2024 to 1 January 2026 |
| `640-140/` | Regolamento di applicazione dell’ordinanza concernente l’imposizione minima dei grandi gruppi di imprese (640.140) | 1 | current text only, in force since 1 January 2024 |
| `642-150/` | Regolamento di applicazione della Legge federale sull’imposta federale diretta (642.150) | 6 | each consolidated version: 1 January 2009 to 1 January 2024 |
| `642-250/` | Regolamento cantonale di applicazione concernente la Legge federale sul l’imposta preventiva, il computo globale d’imposta e la trattenuta supplementare d’imposta USA (642.250) | 4 | each consolidated version: 30 January 2004 to 1 January 2024 |
| `651-150/` | Regolamento per l’esecuzione della legge federale sulla tassa d’esenzione dall’obbligo militare (651.150) | 4 | each consolidated version: 1 July 2013 to 1 January 2024 |
| `701-110/` | Regolamento della legge sullo sviluppo territoriale (701.110) | 13 | each consolidated version: 2 April 2013 to 26 June 2026 |
| `701-310/` | Regolamento sul coordinamento delle procedure (701.310) | 1 | current text only, in force since 15 December 2023 |
| `701-410/` | Regolamento d’esecuzione della legge sulla protezione delle rive dei laghi (701.410) | 1 | current text only, in force since 25 November 2003 |
| `701-510/` | Regolamento della Legge sui territori interessati da pericoli naturali (701.510) | 2 | each consolidated version: 21 July 2017 to 26 June 2026 |
| `704-110/` | Regolamento della legge cantonale sulla geoinformazione (704.110) | 8 | each consolidated version: 1 January 2014 to 1 January 2026 |
| `704-120/` | Regolamento sul Catasto delle restrizioni di diritto pubblico della proprietà (704.120) | 1 | current text only, in force since 1 January 2020 |
| `705-110/` | Regolamento di applicazione della Legge edilizia (705.110) | 12 | each consolidated version: 2 April 2013 to 1 July 2026 |
| `705-210/` | Regolamento sulla protezione antincendio (705.210) | 5 | each consolidated version: 1 January 2024 to 27 March 2026 |
| `705-410/` | Regolamento di applicazione della Legge cantonale sull’esercizio delle professioni di ingegnere e di architetto (705.410) | 3 | each consolidated version: 6 February 2009 to 2 December 2022 |
| `705-510/` | Regolamento della legge sull’esercizio della professione di impresario costruttore e di operatore specialista nel settore principale della costruzione (705.510) | 3 | each consolidated version: 1 January 2015 to 1 January 2026 |
| `705-610/` | Regolamento d’esecuzione della legge sugli impianti pubblicitari (705.610) | 1 | current text only, in force since 26 September 2008 |
| `710-110/` | Regolamento d’esecuzione della legge di espropriazione (710.110) | 2 | each consolidated version: 25 January 2013 to 1 March 2014 |
| `720-110/` | Regolamento sul demanio pubblico (720.110) | 3 | each consolidated version: 1 March 2011 to 20 October 2017 |
| `725-110/` | Regolamento sulle strade (725.110) | 3 | each consolidated version: 1 January 2024 to 6 February 2026 |
| `725-210/` | Regolamento sulle strade nazionali (725.210) | 1 | current text only, in force since 1 January 2008 |
| `726-170/` | Regolamento sui Gruppi di gestione dei sentieri (726.170) | 1 | current text only, in force since 30 October 2009 |
| `730-110/` | Regolamento di applicazione della Legge sulle commesse pubbliche (LCPubb) del 20 febbraio 2001 e del Concordato intercantonale sugli appalti pubblici (CIAP) del 15 marzo 2001 (730.110) | 16 | each consolidated version: 13 July 2012 to 1 March 2026 |
| `740-110/` | Regolamento sull’utilizzazione dell’energia (740.110) | 2 | each consolidated version: 1 January 2024 to 31 January 2025 |
| `741-260/` | Regolamento del Fondo per le energie rinnovabili (741.260) | 12 | each consolidated version: 1 April 2014 to 1 January 2026 |
| `742-110/` | Regolamento della legge cantonale di applicazione della legge federale sull’approvvigionamento elettrico del 23 marzo 2007 (742.110) | 11 | each consolidated version: 30 November 2010 to 23 February 2024 |
| `743-110/` | Regolamento di applicazione della legge sull’Azienda elettrica ticinese (743.110) | 1 | current text only, in force since 9 December 2016 |
| `751-110/` | Regolamento concernente le autorizzazioni cantonali di trasporto (751.110) | 2 | each consolidated version: 1 January 2007 to 1 March 2014 |
| `751-120/` | Regolamento della legge sul coordinamento pianificatorio e finanziario in materia di infrastrutture e di servizi di trasporto (751.120) | 1 | current text only, in force since 26 June 2026 |
| `760-110/` | Regolamento della legge cantonale di applicazione alla legislazione federale sulla circolazione stradale (760.110) | 15 | each consolidated version: 1 January 2011 to 1 August 2026 |
| `760-120/` | Regolamento sulle slitte a motore, sui veicoli per la preparazione delle piste e sulla circolazione fuori strada (760.120) | 1 | current text only, in force since 11 January 2008 |
| `770-110/` | Regolamento di applicazione della Legge cantonale sulle funi metalliche (770.110) | 2 | each consolidated version: 10 September 2010 to 1 March 2014 |
| `770-310/` | Regolamento concernente le funivie e le sciovie esonerate dalla concessione federale (770.310) | 7 | each consolidated version: 20 April 2007 to 1 January 2026 |
| `790-150/` | Regolamento sugli impianti di trasporto in condotta di combustibili e carburanti liquidi o gassosi (790.150) | 4 | each consolidated version: 17 May 2013 to 20 June 2017 |
| `801-140/` | Regolamento concernente le tasse previste dalla legge sulla promozione della salute e il coordinamento sanitario (801.140) | 4 | each consolidated version: 25 February 2020 to 1 January 2026 |
| `801-160/` | Regolamento concernente la protezione contro il fumo (801.160) | 1 | current text only, in force since 1 July 2026 |
| `801-410/` | Regolamento sull’obbligo formativo nel settore sanitario e sociosanitario (801.410) | 1 | current text only, in force since 1 January 2023 |
| `802-150/` | Regolamento della Commissione di vigilanza sanitaria (802.150) | 2 | each consolidated version: 15 March 2002 to 26 September 2014 |
| `803-150/` | Regolamento del Comitato etico (803.150) | 2 | each consolidated version: 18 March 2011 to 2 September 2014 |
| `805-110/` | Regolamento del Consiglio di Stato sul servizio medico nelle zone di montagna (805.110) | 3 | each consolidated version: 18 March 2011 to 1 January 2022 |
| `806-110/` | Regolamento d’applicazione della legge sull’assistenza sociopsichiatrica (806.110) | 1 | current text only, in force since 28 November 2008 |
| `806-150/` | Regolamento sull’uso della sala polivalente dell’Organizzazione sociopsichiatrica cantonale a Mendrisio (806.150) | 2 | each consolidated version: 15 March 2002 to 1 August 2022 |
| `811-350/` | Regolamento sulla chirurgia ambulatoriale nelle sale operatorie annesse agli studi medici (811.350) | 1 | current text only, in force since 23 January 1996 |
| `811-410/` | Regolamento sull’interruzione della gravidanza (811.410) | 1 | current text only, in force since 30 March 2007 |
| `811-550/` | Regolamento concernente i servizi di urgenza medica negli ospedali e nelle cliniche (811.550) | 1 | current text only, in force since 3 May 2005 |
| `811-850/` | Regolamento sulla qualità e la sicurezza delle strutture ospedaliere (811.850) | 1 | current text only, in force since 1 February 2023 |
| `812-110/` | Regolamento della legge sul servizio pre-ospedaliero di soccorso e trasporto sanitario (812.110) | 1 | current text only, in force since 18 March 2011 |
| `813-110/` | Regolamento concernente l’esercizio delle professioni sanitarie con formazione accademica (813.110) | 1 | current text only, in force since 25 November 2003 |
| `813-120/` | Regolamento concernente l’esercizio di un’attività sanitaria da parte degli operatori sanitari (813.120) | 5 | each consolidated version: 1 September 2018 to 1 April 2023 |
| `813-350/` | Regolamento sui medici delegati (813.350) | 1 | current text only, in force since 15 March 2002 |
| `813-610/` | Regolamento concernente l’esercizio dell’ottica (813.610) | 2 | each consolidated version: 25 November 2003 to 1 September 2018 |
| `813-620/` | Regolamento concernente l’esercizio della professione di psicologo attivo in ambito sanitario e di psicoterapeuta (813.620) | 6 | each consolidated version: 1 April 2013 to 6 March 2026 |
| `813-630/` | Regolamento concernente l’esame per l’ottenimento dell’autorizzazione d’esercizio quale terapista complementare (813.630) | 3 | each consolidated version: 1 March 2004 to 11 November 2016 |
| `813-640/` | Regolamento concernente l’esercizio della podologia (813.640) | 1 | current text only, in force since 1 January 2026 |
| `813-650/` | Regolamento concernente l’esercizio della professione di estetista (813.650) | 3 | each consolidated version: 11 July 1995 to 16 November 2018 |
| `813-660/` | Regolamento di applicazione della legislazione federale sulla protezione dai pericoli delle radiazioni non ionizzanti e degli stimoli sonori nell’ambito dell’utilizzo dei solarium e dei prodotti per scopi estetici (813.660) | 1 | current text only, in force since 7 June 2024 |
| `821-110/` | Regolamento della Legge cantonale sul registro dei tumori del 21 giugno 1994 (821.110) | 3 | each consolidated version: 16 June 1998 to 16 October 2015 |
| `821-150/` | Regolamento concernente le vaccinazioni contro le malattie trasmissibili (821.150) | 1 | current text only, in force since 21 February 2003 |
| `821-450/` | Regolamento concernente il progetto pilota di piattaforma informatica per la condivisione delle informazioni riguardanti pazienti (821.450) | 2 | each consolidated version: 25 September 2012 to 17 April 2015 |
| `822-110/` | Regolamento della legge d’applicazione della legge federale sugli stupefacenti (822.110) | 3 | each consolidated version: 1 September 2011 to 1 September 2025 |
| `822-210/` | Regolamento sulla coltivazione della canapa e sulla vendita al dettaglio dei suoi prodotti (822.210) | 5 | each consolidated version: 1 May 2009 to 1 January 2018 |
| `822-310/` | Regolamento concernente il trattamento dei tossicomani con stupefacenti (822.310) | 1 | current text only, in force since 8 April 2011 |
| `823-150/` | Regolamento sulle pompe funebri, l’esumazione e il trasporto delle salme (823.150) | 2 | each consolidated version: 1 May 2015 to 9 October 2026 |
| `824-110/` | Regolamento della legge cantonale di applicazione della legge federale sulle derrate alimentari e sugli oggetti d’uso (824.110) | 2 | each consolidated version: 1 May 2017 to 24 May 2019 |
| `825-150/` | Regolamento sull’igiene delle acque balneabili (825.150) | 4 | each consolidated version: 15 July 2011 to 22 December 2017 |
| `826-110/` | Regolamento sull’eliminazione dei rifiuti di origine animale (826.110) | 1 | current text only, in force since 25 November 2003 |
| `831-110/` | Regolamento generale della legge cantonale di applicazione della legge federale sulla protezione dell’ambiente (831.110) | 5 | each consolidated version: 9 November 2012 to 1 January 2026 |
| `831-150/` | Regolamento di applicazione dell’ordinanza federale concernente l’esame dell’impatto sull’ambiente (831.150) | 2 | each consolidated version: 1 January 2012 to 4 August 2023 |
| `831-450/` | Regolamento sull’organizzazione dei preparativi, dell’allarme e dell’intervento in caso di incidente chimico e per il conteggio delle spese degli interventi dello Stato (831.450) | 1 | current text only, in force since 10 March 2023 |
| `832-110/` | Regolamento di applicazione dell’ordinanza sulla prevenzione e lo smaltimento dei rifiuti (832.110) | 3 | each consolidated version: 6 August 2021 to 18 October 2024 |
| `832-120/` | Regolamento di applicazione dell’Ordinanza sul traffico di rifiuti (832.120) | 6 | each consolidated version: 28 August 2007 to 4 September 2026 |
| `834-150/` | Regolamento di applicazione dell’ordinanza federale contro l’inquinamento fonico (834.150) | 2 | each consolidated version: 29 May 2007 to 12 November 2021 |
| `834-250/` | Regolamento concernente la protezione dagli stimoli sonori nell’ambito di manifestazioni (834.250) | 1 | current text only, in force since 12 November 2021 |
| `834-350/` | Regolamento di applicazione dell’ordinanza contro l’inquinamento atmosferico (834.350) | 2 | each consolidated version: 8 May 2015 to 1 January 2017 |
| `835-110/` | Regolamento sull’organizzazione della lotta contro gli incendi, gli inquinamenti ed i danni della natura (835.110) | 9 | each consolidated version: 11 August 1998 to 30 January 2026 |
| `837-110/` | Regolamento di applicazione dell’Ordinanza federale sulla protezione da radiazioni non ionizzanti (837.110) | 3 | each consolidated version: 1 January 2006 to 23 January 2015 |
| `842-110/` | Regolamento sull’Ufficio cantonale di conciliazione (842.110) | 1 | current text only, in force since 3 June 2011 |
| `843-110/` | Regolamento sul lavoro nell’industria, nell’artigianato e nel commercio e sul lavoro a domicilio (843.110) | 2 | each consolidated version: 3 June 2011 to 1 January 2020 |
| `843-310/` | Regolamento della Legge d’applicazione della Legge federale concernente condizioni lavorative e salariali minime per lavoratori distaccati in Svizzera e misure collaterali (LDist) e della Legge federale concernente i provvedimenti in materia di lotta contro il lavoro nero (LLN) dell’11 marzo 2008 (843.310) | 7 | each consolidated version: 1 July 2011 to 1 March 2022 |
| `843-610/` | Regolamento della legge cantonale sul salario minimo (843.610) | 2 | each consolidated version: 1 January 2021 to 23 August 2024 |
| `851-210/` | Regolamento della legge di applicazione della legge federale 6 ottobre 2006 concernente le prestazioni complementari all’assicurazione federale per la vecchiaia, i superstiti e l’invalidità (851.210) | 3 | each consolidated version: 1 January 2008 to 1 January 2015 |
| `853-110/` | Regolamento della legge di applicazione della legge federale sull’assicurazione malattie (853.110) | 8 | each consolidated version: 7 April 2017 to 23 October 2026 |
| `853-610/` | Regolamento sulla determinazione di numeri massimi di medici nel settore ambulatoriale (853.610) | 2 | each consolidated version: 1 November 2023 to 1 July 2025 |
| `855-110/` | Regolamento della legge sulle indennità di perdita di guadagno in caso di adozione (855.110) | 2 | each consolidated version: 1 January 2017 to 22 March 2024 |
| `856-110/` | Regolamento sugli assegni di famiglia (856.110) | 9 | each consolidated version: 1 January 2013 to 1 January 2021 |
| `857-110/` | Regolamento della legge sul rilancio dell’occupazione e sul sostegno ai disoccupati (857.110) | 11 | each consolidated version: 1 June 2011 to 28 August 2026 |
| `857-120/` | Regolamento delle commissioni tripartite in materia di disoccupazione (857.120) | 1 | current text only, in force since 9 May 2008 |
| `861-110/` | Regolamento di applicazione della legge sull’abitazione (861.110) | 1 | current text only, in force since 1 September 2005 |
| `862-110/` | Regolamento di applicazione del decreto legislativo concernente il rinnovo di abitazioni (862.110) | 2 | each consolidated version: 15 March 2002 to 5 September 2025 |
| `863-110/` | Regolamento del decreto legislativo concernente il miglioramento delle condizioni di abitazione nelle regioni di montagna (863.110) | 1 | current text only, in force since 1 September 2005 |
| `870-110/` | Regolamento sull’armonizzazione e il coordinamento delle prestazioni sociali (Laps) (870.110) | 7 | each consolidated version: 1 January 2012 to 1 July 2022 |
| `871-110/` | Regolamento sull’assistenza sociale (871.110) | 2 | each consolidated version: 1 May 2012 to 3 March 2023 |
| `871-120/` | Regolamento sull'aiuto sociale in materia d'asilo (871.120) | 1 | current text only, in force since 1 July 2026 |
| `872-110/` | Regolamento d’applicazione della legge sull’assistenza e cura a domicilio (872.110) | 3 | each consolidated version: 31 August 2012 to 1 April 2026 |
| `872-120/` | Regolamento sui requisiti essenziali di qualità per i servizi di assistenza e cura a domicilio e per i centri terapeutici somatici diurni e notturni (872.120) | 3 | each consolidated version: 25 March 2011 to 1 January 2026 |
| `873-110/` | Regolamento d’applicazione della legge concernente il promovimento, il coordinamento e il finanziamento delle attività a favore delle persone anziane (873.110) | 3 | each consolidated version: 31 August 2012 to 1 January 2026 |
| `873-120/` | Regolamento della Commissione consultiva dei Comuni in base alla legge concernente il promovimento, il coordinamento e il finanziamento delle attività a favore delle persone anziane e alla legge sull’assistenza e cura a domicilio (873.120) | 1 | current text only, in force since 25 October 2013 |
| `873-130/` | Regolamento concernente il computo della retta giornaliera a carico dell’ospite nelle strutture sociosanitarie riconosciute (873.130) | 2 | each consolidated version: 1 January 2026 to 2 October 2026 |
| `874-110/` | Regolamento della Legge per le famiglie del 15 settembre 2003 (874.110) | 12 | each consolidated version: 15 July 2011 to 1 January 2026 |
| `874-210/` | Regolamento della legge sulla promozione delle attività dell’infanzia e della gioventù (874.210) | 1 | current text only, in force since 1 March 2026 |
| `874-350/` | Regolamento concernente l’anticipo e l’incasso degli alimenti per i figli minorenni (874.350) | 2 | each consolidated version: 1 June 2011 to 3 March 2023 |
| `875-110/` | Regolamento della legge sull’integrazione sociale e professionale degli invalidi (875.110) | 2 | each consolidated version: 22 June 2012 to 1 March 2014 |
| `900-110/` | Regolamento sulla legge per l’innovazione economica (900.110) | 6 | each consolidated version: 5 February 2016 to 6 February 2026 |
| `901-110/` | Regolamento della legge cantonale di applicazione della legge federale sulla politica regionale (901.110) | 4 | each consolidated version: 13 May 2011 to 8 March 2024 |
| `909-110/` | Decreto esecutivo concernente l’adozione di misure a favore dei casi di rigore ai sensi dell’ordinanza COVID-19 sui casi di rigore (909.110) | 8 | each consolidated version: 29 January 2021 to 25 March 2022 |
| `910-110/` | Regolamento sull’agricoltura (910.110) | 20 | each consolidated version: 4 May 2010 to 1 December 2025 |
| `910-210/` | Regolamento della Legge sulla conservazione del territorio agricolo (910.210) | 3 | each consolidated version: 13 May 2011 to 3 May 2024 |
| `911-110/` | Regolamento sul diritto fondiario rurale e sull’affitto agricolo (911.110) | 3 | each consolidated version: 8 June 2007 to 3 May 2024 |
| `914-410/` | Regolamento d’applicazione della legge cantonale sulle epizoozie (914.410) | 1 | current text only, in force since 15 March 2002 |
| `915-150/` | Regolamento sulla formazione agricola e sugli esami di fine apprendistato per agricoltore (915.150) | 1 | current text only, in force since 9 May 2008 |
| `915-160/` | Regolamento sulla formazione professionale e gli esami di capacità di cantiniere (915.160) | 2 | each consolidated version: 25 November 2003 to 1 March 2014 |
| `916-150/` | Regolamento sulla viticoltura (916.150) | 1 | current text only, in force since 13 September 2024 |
| `917-250/` | Regolamento concernente il servizio di ispezione e consulenza per l’economia lattiera (917.250) | 1 | current text only, in force since 17 September 2004 |
| `921-110/` | Regolamento della Legge cantonale sulle foreste (921.110) | 4 | each consolidated version: 3 July 2012 to 21 July 2017 |
| `922-110/` | Regolamento sulla caccia e la protezione dei mammiferi e degli uccelli selvatici (922.110) | 21 | each consolidated version: 31 August 2012 to 3 July 2026 |
| `922-120/` | Regolamento sulla caccia selettiva allo stambecco (922.120) | 3 | each consolidated version: 27 October 2017 to 6 February 2026 |
| `922-250/` | Regolamento per l’ottenimento del certificato d’abilitazione alla caccia (922.250) | 6 | each consolidated version: 1 March 2013 to 29 March 2024 |
| `922-260/` | Regolamento sulla prova periodica della precisione di tiro per cacciatori (922.260) | 2 | each consolidated version: 14 December 2018 to 26 March 2021 |
| `923-110/` | Regolamento di applicazione della Legge cantonale sulla pesca e sulla protezione dei pesci e dei gamberi indigeni (923.110) | 17 | each consolidated version: 1 January 2013 to 6 February 2026 |
| `941-110/` | Regolamento della legge sul turismo (941.110) | 10 | each consolidated version: 1 January 2015 to 6 February 2026 |
| `942-110/` | Regolamento sugli esercizi alberghieri e sulla ristorazione (942.110) | 1 | current text only, in force since 15 June 2023 |
| `942-120/` | Regolamento che disciplina le notifiche degli ospiti alla Polizia cantonale (942.120) | 1 | current text only, in force since 7 June 2024 |
| `943-110/` | Regolamento della legge sui campeggi (943.110) | 2 | each consolidated version: 1 June 2004 to 11 July 2014 |
| `944-110/` | Regolamento della legge di applicazione della legge federale sui giochi in denaro (944.110) | 1 | current text only, in force since 1 January 2024 |
| `944-120/` | Regolamento del Fondo Swisslos (944.120) | 4 | each consolidated version: 1 January 2013 to 26 January 2024 |
| `944-130/` | Regolamento del Fondo Sport-toto (944.130) | 5 | each consolidated version: 1 January 2013 to 26 January 2024 |
| `944-140/` | Regolamento del Fondo gioco patologico (944.140) | 4 | each consolidated version: 1 January 2013 to 26 January 2024 |
| `945-210/` | Regolamento della legge sull’apertura dei negozi (945.210) | 1 | current text only, in force since 1 January 2020 |
| `946-110/` | Regolamento sulla metrologia (946.110) | 3 | each consolidated version: 8 August 2017 to 1 July 2024 |
| `951-110/` | Regolamento sull’avvocatura (951.110) | 2 | each consolidated version: 1 January 2013 to 12 September 2014 |
| `952-110/` | Regolamento sul notariato (952.110) | 3 | each consolidated version: 1 July 2015 to 1 February 2025 |
| `953-110/` | Regolamento della legge sull’esercizio delle professioni di fiduciario (953.110) | 3 | each consolidated version: 1 July 2012 to 1 January 2022 |
| `953-155/` | Regolamento sull’organizzazione e la gestione dell’Autorità di vigilanza sulle professioni di fiduciario (953.155) | 2 | each consolidated version: 9 November 2012 to 1 June 2022 |
| `953-165/` | Regolamento sulle tasse dell’Autorità di vigilanza sull’esercizio delle professioni di fiduciario (953.165) | 3 | each consolidated version: 1 January 2013 to 1 January 2026 |
| `960-150/` | Regolamento della Commissione del controllo del mandato pubblico della Banca dello Stato del Cantone Ticino (960.150) | 1 | current text only, in force since 16 April 2010 |

## Source

The Raccolta delle leggi del Cantone Ticino, as the canton publishes it in PDF, in the copies kept by [LexFind](https://www.lexfind.ch/), the portal of Swiss federal and cantonal legislation run on behalf of the Swiss State Chancellors' Conference, which holds every version of each act published since May 2006.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**.
- Each version is dated by the day LexFind gives it as in force, taken from the act's text. Each act's first commit is the oldest version LexFind holds, credited to the publisher.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the headings of titles, chapters and sections. One paragraph or list item per line. Footnote markers are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each later commit is the amending act named in the version's footnotes by its entry in the Bollettino ufficiale delle leggi (BU yyyy, page), with an e-mail address that cannot exist. Where several take effect in one version and the footnotes do not tie a change to one of them, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the Bollettino ufficiale delle leggi. The text is read from PDF; footnotes are not included. Only the acts listed above are included.
