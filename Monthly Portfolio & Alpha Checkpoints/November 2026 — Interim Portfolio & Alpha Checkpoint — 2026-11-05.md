# November 2026 — Interim Portfolio & Alpha Checkpoint (5 November close)

**Checkpoint-Monat:** November 2026  
**Stichtag / Daten-Cut-off:** 05.11.2026, reguläre US-Schlussauktion (16:00 EST / 22:00 MEZ); für Amsterdam und Tokio der jeweilige lokale Handelsschluss vom 05.11.  
**Erstellt:** 06.11.2026; kein rückdatiertes Transaktionsprotokoll  
**Typ:** Monatlicher **Zwischencheckpoint**, nicht der vollständige November-Monatsabschluss.  
**Portfolio:** 16 dokumentierte virtuelle Aktienpositionen, 14 am 05.11. bestätigte virtuelle Wiederkäufe, Tokyo Ohka durchgehend gehalten und APP laut späterer Besitzerangabe nach Verkauf am 04.11. abends wieder erworben; vgl. separates Re-entry-Protokoll.  
**Status:** **Reproduzierbare, nominalgewichtete Tages-Modellrechnung. Kumuliertes Alpha nur vorläufige Fortschreibung eines früheren, nicht unabhängig auditierten Chat-Checkpoints. Kein bestätigter Broker-Track-Record.**

## 1. Executive Summary

| Kennzahl | Wert | Einordnung |
|---|---:|---|
| Geöffnete Positionen | **16** | 16 verschiedene Unternehmen |
| Summe dokumentierter Nominal-Allokationen | **USD 132,848** | Vergleichsnenner; nicht mit aktuellem Portfolio-Marktwert gleichzusetzen |
| S&P 500, Schlusskurs 05.11. | **7,353.73 Punkte** | Vorheriger Schluss 7,688.62; **−4.36%** Tagesrendite, reiner Preisindex |
| Nominalgewichtete Tagesrendite des 16-Aktien-Modells | **−1.0313%** | Summe der Nominalgewichte × jeweilige Tageskursänderung |
| Entsprechender rechnerischer Modell-P&L | **USD −1,370.00** | **Nicht** tatsächlich realisierter/unrealisierter Broker-Tages-P&L |
| **Tages-Outperformance gegenüber S&P 500** | **+3.3287 pp** | Tagesrendite Portfolio-Korb minus Tagesrendite S&P |
| Vorheriger kumulierter Chat-Modellcheckpoint (04.11.) | **+13.21 pp** | Nicht transaktionsbasiert unabhängig verifiziert |
| Korrektur bereits eingerechneter APP-Nachbörse vom 04.11. | **−1.7185 pp** | Vermeidung offensichtlicher Doppelzählung |
| **Fortgeschriebenes kumuliertes Modellalpha** | **+14.8202 pp** | Näherung mit methodischen Vorbehalten; **keine echte historische TWR-Alpha-Zeitreihe** |
| Vorläufige Entfernung zum 15-pp-Jahresziel | **0.1798 pp** | Gilt nur für dasselbe, nicht auditierte Modell |

**Kernaussage:** Das nominalgewichtete 16-Titel-Modell verlor am 05.11. ungefähr **1.03%**, während der S&P 500 **4.36%** verlor. Damit entstand eine relative **Tages-Outperformance von 3.33 Prozentpunkten**. Eine echte kumulierte Performance seit Juli lässt sich mit den vorhandenen Referenzallokationen und unvollständigen Transaktionsdaten nicht endgültig bestätigen.

## 2. Methodik — genaue Formeln, pp und USD auseinanderhalten

Für jede Position i:

- Dokumentierte Nominalallokation: `C_i` in USD, Summe `C = 132,848 USD`.
- Nominalgewicht: `w_i = C_i / C`. Für die Modellrechnung **konstant** gesetzt, nicht mit dem tatsächlichen Marktwert vom 04.11. regewichtet.
- Kursrendite des 05.11. gegenüber vorherigem lokalen regulären Handelsschluss: `r_i = Schluss_05.11 / Schluss_vorher - 1`.
- **Nominaler Modellbeitrag in USD:** `C_i * r_i`; kein Nachweis eines realen Tagesgewinns in dieser Höhe.
- **Portfolio-Beitrag in Prozentpunkten:** `w_i * r_i`. Summe über alle 16 Positionen = Modell-Portfoliorendite.
- **Einzelaktien-Über-/Unterperformance gegenüber der *einen* S&P-Tagesrendite:** `r_i - r_SP500`. Das ist ein *Tagesvergleich*, **nicht** historisches Alpha der Position seit Kauf.
- **Gewichteter Alpha-Beitrag zum Tagesvergleich:** `w_i * (r_i - r_SP500)`. Summe = tägliche relative Portfoliorendite.
- S&P 500: `r_SP500 = -0.0436` (−4.36%). **pp** bedeutet *Prozentpunkte*, nicht Prozent.
- Alle Prozentrechnungen verwenden ungerundete Gewichte und die unten dokumentierten Kursänderungen. Rundungen erst bei der Darstellung.

### Nachrechenbarer Gesamtwert

```text
C = 132848.00 USD
Nominaler Modell-P&L = Summe_i (C_i × r_i) = -1370.004 USD
r_Portfolio = -1370.004 / 132848 × 100 = -1.0312568 %
r_S&P500 = -4.3600000 %
Tages-Outperformance = r_Portfolio - r_S&P500 = 3.3287432 Prozentpunkte
```

**Wichtig:** Die einzelnen Quellen melden Renditen mit 2–3 Dezimalstellen. Die Berechnung ist deshalb auf die Genauigkeit dieser Kursangaben beschränkt. Die Rundung der Tabellenwerte erklärt geringe Differenzen zwischen der Summe sichtbarer pp-Werte und dem ungerundeten Gesamtergebnis.

## 3. Alle 16 Aktien — Rendite, Portfolio-Beitrag und Alpha-Beitrag

**Zeitraum jeder Rendite:** letzte reguläre Börsensitzung gegenüber ihrem vorangegangenen regulären Schluss, **nicht** Rendite seit Erstkauf oder Rendite für den gesamten November. Das Portfolio wurde für diesen Bericht mit den zuletzt dokumentierten nominalen USD-Beträgen gewichtet.

| Aktie / Kursquelle | Nominal USD | Gewicht | Tagesrendite | Nominal-Modell-P&L USD | Beitrag zur Portfolio-Rendite | Einzelaktie vs. S&P | Gewichteter Tagesalpha-Beitrag |
|---|---:|---:|---:|---:|---:|---:|---:|
| [AppLovin (APP)](https://stockanalysis.com/stocks/app/history/) | 10,000 | 7.53% | +31.02% | +3,102.00 | +2.3350 pp | +35.38 pp | +2.6632 pp |
| [Amazon (AMZN)](https://finance.yahoo.com/quote/AMZN/history/) | 9,000 | 6.77% | −2.19% | −197.10 | −0.1484 pp | +2.17 pp | +0.1470 pp |
| [Alphabet (Class A) (GOOGL)](https://finance.yahoo.com/quote/GOOGL/history/) | 12,000 | 9.03% | −2.20% | −264.00 | −0.1987 pp | +2.16 pp | +0.1951 pp |
| [Salesforce (CRM)](https://stockanalysis.com/stocks/crm/) | 11,000 | 8.28% | −2.10% | −231.00 | −0.1739 pp | +2.26 pp | +0.1871 pp |
| [Wolters Kluwer (WKL.AS)](https://stockanalysis.com/quote/ams/WKL/history/) | 9,000 | 6.77% | +1.97% | +177.30 | +0.1335 pp | +6.33 pp | +0.4288 pp |
| [Microsoft (MSFT)](https://finance.yahoo.com/quote/MSFT/history/) | 10,500 | 7.90% | −3.58% | −375.90 | −0.2830 pp | +0.78 pp | +0.0616 pp |
| [Meta Platforms (META)](https://stockanalysis.com/stocks/meta/history/) | 10,000 | 7.53% | −3.87% | −387.00 | −0.2913 pp | +0.49 pp | +0.0369 pp |
| [SAP (US ADR) (SAP)](https://stockanalysis.com/stocks/sap/history/) | 11,000 | 8.28% | +1.50% | +165.00 | +0.1242 pp | +5.86 pp | +0.4852 pp |
| [Netflix (NFLX)](https://finance.yahoo.com/quote/NFLX/history/) | 7,500 | 5.65% | −1.25% | −93.75 | −0.0706 pp | +3.11 pp | +0.1756 pp |
| [Mastercard (MA)](https://stockanalysis.com/stocks/ma/) | 7,877 | 5.93% | −2.51% | −197.71 | −0.1488 pp | +1.85 pp | +0.1097 pp |
| [Micron Technology (MU)](https://stockanalysis.com/stocks/mu/history/) | 4,000 | 3.01% | −17.16% | −686.40 | −0.5167 pp | −12.80 pp | −0.3854 pp |
| [UiPath (PATH)](https://chartexchange.com/symbol/nyse-path/historical/) | 5,000 | 3.76% | −3.627% | −181.35 | −0.1365 pp | +0.73 pp | +0.0276 pp |
| [Pegasystems (PEGA)](https://stockanalysis.com/stocks/pega/history/) | 5,000 | 3.76% | −2.24% | −112.00 | −0.0843 pp | +2.12 pp | +0.0798 pp |
| [Synopsys (SNPS)](https://stockanalysis.com/stocks/snps/history/) | 7,000 | 5.27% | −4.89% | −342.30 | −0.2577 pp | −0.53 pp | −0.0279 pp |
| [Ambiq Micro (AMBQ)](https://stockanalysis.com/stocks/ambq/) | 6,500 | 4.89% | −15.33% | −996.45 | −0.7501 pp | −10.97 pp | −0.5367 pp |
| [Tokyo Ohka Kogyo (4186.T)](https://stockanalysis.com/quote/tyo/4186/history/) | 7,471 | 5.62% | −10.03% | −749.34 | −0.5641 pp | −5.67 pp | −0.3189 pp |
| **Gesamt / Modell** | **132,848** | **100.00%** | **−1.0313%** | **−1,370.00** | **−1.0313 pp** | — | **+3.3287 pp** |

**Lesebeispiel:** APP stieg um 31.02%; mit einem Nominalgewicht von 7.53% liefert dies **+2.3350 pp** zum Portfolio-Tagesergebnis. Gegenüber dem um 4.36% fallenden S&P liegt APP als Einzelaktie bei **+35.38 pp relativer Tagesrendite**. Gewichtet liefert APP **+2.6632 pp** zur Tages-Outperformance des gesamten Korbs. Diese drei Kennzahlen sind verschieden.

### Tagesbeiträge und Risikokonzentration

- **Positive Titel:** 3 (APP, WKL, SAP), nominaler positiver Modellbeitrag **USD +3,444.30**.
- **Negative Titel:** 13, nominaler negativer Modellbeitrag **USD −4,814.30**.
- **APP allein:** **USD +3,102.00 nominaler Modellbeitrag**, entsprechend **+2.3350 pp** zur Portfolio-Tagesrendite.
- **Die übrigen 15 Positionen zusammen:** **USD −4,472.00 nominal**, sodass APP den größten Teil ihrer Verluste kompensiert.
- **Größter negativer nominaler Tagesbeitrag:** AMBQ, **USD −996.45**. Weitere hohe negative Beiträge: Tokyo Ohka, Micron, Meta, Microsoft und Synopsys.
- **Tagesbreite:** 3 Aktien im Plus / 13 Aktien im Minus. Das Portfolio war damit **nicht** breit positiv; die relative Stärke war stark von APP und einzelnen defensiveren Titeln geprägt.

## 4. Cumulatives Alpha — transparente Brücke zu +14.82 pp

Der am 04.11. in der Konversation genannte kumulierte Modellwert **+13.21 pp** enthielt einen **bereits als laufende Performance berücksichtigten APP-Nachbörsenanstieg von +22.83%**. Da die vorliegende Sitzung vom 05.11. den vollständigen APP-Anstieg ab dem regulären Schluss des 04.11. enthält, muss die bereits eingerechnete Teilbewegung bei einer additiven *Modellfortschreibung* wieder entfernt werden.

| Position | Wirkung auf kumuliertes Modellalpha |
|---|---:|
| Vorheriger, nicht unabhängig auditierter Ausgangswert (04.11.) | +13.2100 pp |
| Bereits eingerechnete APP-Nachbörse: `22.83% × (10000/132848)` | −1.7185 pp |
| Neuer nominalgewichteter 16-Aktien-Tagesvergleich am 05.11. | +3.3287 pp |
| **Kumulierte Fortschreibung** | **+14.8202 pp** |

```text
13.21 − (1.718505) + (3.328743) = 14.820238 pp
```

**Methodischer Status des kumulierten Werts:** Diese additive Brücke repliziert die bisherige Chat-Konvention, **keine** vollständig korrekte, verkettete Time-Weighted-Return-Analyse. Für echte kumulierte Alpha-Berechnung fehlen:
- Vollständiges chronologisches Cashflow- und Transaktionsbuch inklusive Einstand-/Ausführungszeit, tatsächlichen Stückzahlen, 14 Wiederkäufen vom 05.11., allen Teilverkäufen und historisch geschlossenen Positionen.
- Echte Marktwertgewichte zum 04.11.-Schluss (die oben verwendeten 132,848 USD sind **Nominalallokationen**, kein Tagesanfangs-NAV).
- Präzise Behandlung des bereits am 04.11. nachbörslich eingerechneten APP-Anstiegs, dessen gesonderter zeitlicher Vergleich nicht vollständig auditierbar ist.
- Konsistente Umrechnung von WKL (EUR) und Tokyo Ohka (JPY) in die USD-Basis; hier werden **lokale Kursrenditen ohne FX** mit USD-Nominalgewichten verrechnet.
- Vergleichbare Benchmark-Haltedauern für sämtliche Ein-/Ausstiege, Cashanteile, Reinvestitionen, Spreads, Steuern, Gebühren und ggf. Dividenden; S&P-Indexpreisrendite ist keine S&P-Total-Return-Reihe.
- Bereinigung alter Pilotgrößen (z.B. Microsoft früher 600 USD, für Allokationsvergleich 6,000 USD normalisiert) und nicht vollständig aufgeklärter Alphabet-Lots.

Der Wert **+14.82 pp** darf daher nur als **provisorischer modellbasierter Fortschrittsindikator** geführt werden, nicht als unabhängig belegte viermonatige Outperformance, offizieller Performancebericht oder realisierte Rendite.

## 5. Quellenkontrolle / Handelszeiten

**Alle Werte basieren auf regulären Kursen vom 05.11.2026**, nicht auf der Nachbörse des 05.11. **Die verschiedenen lokalen Markt-Schlusszeiten sind nicht synchron:** Tokio schließt deutlich vor Europa und USA, Amsterdam vor New York. Ein Tagesvergleich mit der US-Benchmark ist damit eine pragmatische Näherung.

| Ticker | Quelleingang (Tagesänderung) | Quote / Zeitreferenz | Nachschlagequelle |
|---|---:|---|---|
| APP | +31.02% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/app/history/) |
| AMZN | −2.19% | USD | US 16:00 EST | [Historie/Kurs](https://finance.yahoo.com/quote/AMZN/history/) |
| GOOGL | −2.20% | USD | US 16:00 EST | [Historie/Kurs](https://finance.yahoo.com/quote/GOOGL/history/) |
| CRM | −2.10% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/crm/) |
| WKL.AS | +1.97% | EUR | Amsterdam 16:35 CET (Datenanbieter) | [Historie/Kurs](https://stockanalysis.com/quote/ams/WKL/history/) |
| MSFT | −3.58% | USD | US 16:00 EST | [Historie/Kurs](https://finance.yahoo.com/quote/MSFT/history/) |
| META | −3.87% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/meta/history/) |
| SAP | +1.50% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/sap/history/) |
| NFLX | −1.25% | USD | US 16:00 EST | [Historie/Kurs](https://finance.yahoo.com/quote/NFLX/history/) |
| MA | −2.51% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/ma/) |
| MU | −17.16% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/mu/history/) |
| PATH | −3.627% | USD | US 16:00 EST | [Historie/Kurs](https://chartexchange.com/symbol/nyse-path/historical/) |
| PEGA | −2.24% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/pega/history/) |
| SNPS | −4.89% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/snps/history/) |
| AMBQ | −15.33% | USD | US 16:00 EST | [Historie/Kurs](https://stockanalysis.com/stocks/ambq/) |
| 4186.T | −10.03% | JPY | Tokio 15:30 JST | [Historie/Kurs](https://stockanalysis.com/quote/tyo/4186/history/) |

**Benchmark:** S&P 500 Schluss 7,353.73 am 05.11.2026 vs. 7,688.62 am 04.11.2026, −4.36%: [Marktbericht, 05.11.](https://portfolio-terminal.com/markets/stock-market-close/november-5-2026) und [Associated Press, 06.11.](https://apnews.com/article/afe254c608c3d1fe2ea792812ba9765a).

**Bewusste Quellenkorrekturen gegenüber der früheren Chat-Tabelle (nicht verschweigen):** WKL **+1.97% statt +1.38%**, SAP **US-ADR +1.50% statt +0.68%**, MU **−17.16% statt −17.46%**, PEGA **−2.24% statt −2.30%**, AMBQ **−15.33% statt −15.21%**. Für MSFT bleibt hier der bei Yahoo ausgewiesene reguläre Schluss von **−3.58%**; alternative Anbieter melden geringfügig andere Schlussstände (z.B. StockAnalysis −3.52%). Die vorangegangene kumulierte Zahl +14.71 pp ist **durch diese neuen Quellenwerte ersetzt**, nicht stillschweigend als identisch behandelt. **Preisreihen können bei nachträglichen Anbieterkorrekturen voneinander abweichen.**

## 6. Chronologie, Re-entries und Grenzen des virtuellen Portfolios

- Historisches Anlageprojekt mit virtualisiertem Referenzportfolio von 1,000,000 USD, dessen **ungenutzter Cashanteil hier nicht in die aktive Aktienkorb-Rendite** eingeht. Die oben bezifferte −1.03% ist **nicht** die Rendite des gesamten 1-Mio.-USD-Kontos.
- 14 am 05.11. im virtuellen Portfolio ausdrücklich zurückgekaufte Positionen: GOOGL, MSFT, META, CRM, AMZN, SAP, WKL, AMBQ, SNPS, NFLX, PATH, PEGA, MA, MU. **4186.T blieb durchgehend gehalten; APP war in der ursprünglichen Verkaufsnotiz vom 04.11. enthalten und wurde laut späterer Besitzerangabe kurz nach 22:00 MEZ am 04.11. wieder erworben. Die genaue APP-Wiederkaufminute und der Fill sind nicht unabhängig verifiziert.**
- Die virtuelle bestätigte Wiederkaufentscheidung ist nicht dasselbe wie vollständig dokumentierte Fill-Preise. Diese Tabelle verwendet die zuletzt bekannten **nominalen Zielgrößen**, nicht rückwirkend erfundene Fills.
- Die separate, hypothetische Wiedereinstiegsrechnung vom 04.11. um 04:30 MEZ war **simuliert und nicht ausgeführt** und gehört nicht als zusätzliche Transaktion in diese Bilanz.
- Ein am 05.11. erfolgter Wiederkauf mitten in der Sitzung erzeugt ohne exakte Fills einen anderen realen Tages-P&L als ein naives Close-to-Close-Halten. Daher **keine Aussage, dass diese -1.03% tatsächlich seit 04.11. auf exakt diesem Konto verdient/verloren wurden**.
- Eine *Monatsrendite 01.–30.11.* oder kumulierte *Einzelaktienrendite seit Kauf* wird aus einem einzigen Tageskursvergleich **nicht** abgeleitet. Für beide wird eine gesonderte, historische Transaktions- und Monatsendberechnung benötigt.

**Verknüpfte Aufzeichnungen:**
- [Bestätigter virtueller Wiederkauf von 14 Positionen (05.11.)](../Portfolio%20Re-entry%20%E2%80%94%20Confirmed%20Virtual%20Repurchase%20of%2014%20Holdings%20%E2%80%94%202026-11-05.md)
- [Historie und Alpha-Reassessment (14.10.)](../Portfolio%20Decision%20History%20and%20Alpha%20Reassessment%20%E2%80%94%202026-10-14.md)
- [Zwischencheckpoint 09.10.](./October%209%202026%20%E2%80%94%20Interim%20Portfolio%20%26%20Alpha%20Checkpoint.md)
- [Wiederkauf-Szenario 04.11. 04:30 MEZ](../Wiederkauf%20nach%20Midterm-Panik%20%E2%80%94%202026-11-04%2004-30.md)

## 7. Dauerhaftes Prüfprotokoll

Dieser Checkpoint konserviert die Daten- und Modellannahmen zum Stand des 05.11. Er editiert **keine** früheren Investmententscheidungen oder alten Checkpoints rückwirkend. Spätere Kursrevisionen, tatsächliche Broker-Fills oder neue Alpha-Methoden müssen als neue Korrektur mit Datum, Datengrundlage und expliziter Vergleichsrechnung dokumentiert werden.

**Offene Nacharbeit:** `share_count`, `fill_time`, `fill_price`, `cashflows`, `realized_pnl`, `position_market_value_2026-11-04`, `USD_FX_history`, `benchmark_total_return_series`, vollständige `TWR`/periodenbezogene Benchmark-Gewichtung.

## Chronologie-Korrektur vom 07.11.2026 — APP und Midterms

Die ursprünglich hier verwendete Beschreibung von APP als "durchgehend gehalten" war laut späterer Angabe des Portfolioinhabers unzutreffend. Die GitHub-Ausgangsnotiz des bestätigten virtuellen Portfolioteilverkaufs am **04.11. um 17:35:46 MEZ** enthielt APP; Tokyo Ohka wurde kurz danach ausgenommen. Der Portfolioinhaber gibt an, **APP kurz nach 22 Uhr am 04.11. vor der Ergebnisveröffentlichung erneut gekauft** zu haben. GitHub erfasste den geänderten APP-Bestand **erst um 22:16:09 MEZ**, zunächst als vermeintlich ununterbrochen gehalten. Die genaue Wiederkaufminute, der ausführbare Preis und ein unabhängiger zeitgleicher Beleg sind nicht geprüft.

Die Midterm-Simulation **03.11., 22:13 → 04.11., 04:30** gehört nicht zum tatsächlich bestätigten virtuellen Portfoliobestand. Die echte virtuelle Portfolio-Verkaufsentscheidung wurde erst **nach der Wahlnacht am 04.11. gegen 17:35 MEZ** bestätigt. Für eine belastbare Performance-Auswertung müssen APP-Verkauf und -Wiederkauf mit separaten Lots und den bislang fehlenden Kurs-/Zeitbelegen modelliert werden. Die bisherigen APP- und Alpha-Beiträge in dieser Datei bleiben historische Modellschätzungen und sind kein auditierter P&L-Nachweis.

[Archiv mit korrigierter November-4-Chronologie](../../Full%20Portfolio%20Exit%20-%20Confirmed%20Virtual%20Decision%20-%202026-11-04.md).
