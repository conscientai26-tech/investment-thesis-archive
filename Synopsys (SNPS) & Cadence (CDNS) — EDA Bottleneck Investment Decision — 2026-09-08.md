# Synopsys (SNPS) & Cadence (CDNS) — EDA Bottleneck Investment Decision — 2026-09-08

## Entscheidung

**Geplante / virtuelle Allokation innerhalb der EDA-These:**

- **Synopsys (SNPS): 11.000**
- **Cadence Design Systems (CDNS): 9.000**
- **Gesamt: 20.000**
- **Gewichtung: 55 % SNPS / 45 % CDNS**

Referenzkurse für die Bewertung: letzter regulärer US-Schlusskurs vor dem 8. September 2026, **SNPS $393,84** und **CDNS $292,70**.

Die Entscheidung beruht nicht darauf, dass EDA einfach ein gutes Softwaregeschäft ist. Die eigentliche Wette ist, dass **AI einen ohnehin tiefen, schwer ersetzbaren Engineering-Engpass vergrößert, während der Markt diesen Effekt bislang schwächer eingepreist hat als bei anderen Teilen des AI-Stacks.**

---

# 1. Kernthese

Foundation Models machen Intelligenz, Codeproduktion und Teile menschlicher Designarbeit immer billiger. Das bedeutet aber nicht automatisch, dass Engineering-Execution, Simulation, Verification und Signoff ebenfalls abundant werden.

Im Gegenteil kann AI die Nachfrage nach genau dieser Schicht erhöhen.

Mehr AI führt zu:

- mehr Custom Silicon,
- mehr spezialisierten Accelerators,
- mehr Chipvarianten,
- mehr Chiplets,
- mehr HBM-Integration,
- mehr Advanced Packaging,
- mehr 2.5D-/3D-Systemen,
- mehr High-Speed-Interconnects,
- mehr Thermal-, Power- und Electromagnetic-Problemen,
- mehr physikalischer Systemkomplexität.

Damit wächst nicht nur die Zahl möglicher Designs, sondern auch die Zahl der Simulationen, Optimierungsschleifen und Verifikationsschritte pro Design.

Die zentrale Kausalkette lautet:

> **AI macht Designintelligenz abundant → mehr Designs und Iterationen werden möglich → verifizierte Engineering-Execution wird wertvoller → EDA-Nutzung steigt.**

Ein AI-Agent kann einen Menschen bei Teilen des Designs ersetzen oder vervielfachen. Er kann aber nicht einfach behaupten, dass Timing, Power, Physical Design, Thermal oder Signoff korrekt sind. Er braucht weiterhin eine Ground-Truth-Schicht, die reale physikalische und foundry-spezifische Constraints prüft.

Synopsys und Cadence sitzen genau in dieser Schicht.

Der mögliche Endzustand ist deshalb nicht:

> AI ersetzt EDA.

Sondern:

> **AI automatisiert den Ingenieur und erhöht dadurch die Nutzung von EDA.**

---

# 2. Warum EDA ein besonders attraktiver Bottleneck sein kann

EDA liegt in einem ungewöhnlich guten ökonomischen Sweet Spot.

Der Engpass ist technisch extrem schwer zu ersetzen, aber seine Kosten sind für den Kunden relativ klein gegenüber dem wirtschaftlichen Wert eines erfolgreichen Chips.

Ein modernes AI-Chipprogramm kann Milliarden Dollar kosten. Ein fehlerhafter Tape-out, ein verspäteter Launch oder ein Problem auf einem modernen Foundry-Prozess kann enorm teuer sein. Im Verhältnis dazu ist es rational, erhebliche Summen für bewährte Design-, Verification- und Signoff-Tools zu bezahlen.

Damit entsteht eine besonders attraktive Form von Bottleneck Asymmetry:

> **hohe technische Abhängigkeit + relativ geringe Kosten im Verhältnis zum geschützten Kundennutzen = Pricing Power ohne maximalen Internalization Pressure.**

Das unterscheidet EDA von einem zu schmerzhaften Engpass.

Wenn ein Bottleneck einen zu großen Teil der Kundenökonomie abschöpft, steigt der Anreiz, ihn zu umgehen oder zu internalisieren. Genau das ist beispielsweise bei sehr teurem AI-Compute passiert: Google entwickelte TPUs, Amazon Trainium und Microsoft Maia.

Bei EDA ist der ökonomische Schmerz kleiner. Der Kunde ist stark abhängig, aber die Gebühren sind nicht offensichtlich groß genug, um die gesamte Schicht um jeden Preis selbst bauen zu müssen.

---

# 3. Warum Big Tech nicht einfach den gesamten EDA-Stack selbst baut

Google, Nvidia, Amazon, Microsoft oder Meta hätten grundsätzlich genug Kapital, um eigene EDA-Tools zu entwickeln. Das Argument ist deshalb nicht, dass ihnen Geld fehlt.

Der stärkere Punkt sind **Opportunitätskosten von Kapital, Talent, Management-Aufmerksamkeit und Zeit**.

Hyperscaler müssen gleichzeitig knappe Ressourcen in mehrere noch schmerzhaftere Engpässe lenken:

- eigene AI-Accelerators,
- Compute,
- HBM,
- Networking,
- Advanced Packaging,
- Foundry-Kapazität,
- Datacenter,
- Cooling,
- Strom,
- Grid-Anschlüsse,
- Compiler,
- Inference-Optimierung.

Ein vollständiger EDA-Eigenbau ist zudem keine einmalige Investition. Der Stack müsste dauerhaft weiterentwickelt werden. Jeder neue Node, jede neue Packaging-Technologie und jede neue Architektur erzeugt neue Arbeit.

Cadence und Synopsys können diese Kosten über die gesamte Halbleiterindustrie verteilen. Ein einzelner Hyperscaler müsste einen eigenen Stack größtenteils für sich selbst finanzieren.

Das erzeugt einen starken Skalenvorteil der spezialisierten Anbieter.

---

# 4. Grobe Break-even-Logik der Internalisierung

Die vereinfachte Break-even-Struktur lautet:

> **V* = M + B / (p × A)**

mit:

- **V*** = jährlicher vermeidbarer EDA-Spend, ab dem Selbstbau attraktiv wird,
- **M** = laufende jährliche interne Maintenance-/R&D-Kosten,
- **B** = einmalige Aufbaukosten,
- **p** = Erfolgswahrscheinlichkeit des Eigenbaus,
- **A** = Barwertfaktor über den relevanten Zeitraum.

Unter einer illustrativen Annahme von:

- $10 Mrd. Aufbaukosten,
- $1 Mrd. laufende R&D pro Jahr,
- 70 % Erfolgswahrscheinlichkeit,
- 10 Jahre,
- 10 % Diskontsatz,

liegt der Break-even grob bei **$3,3 Mrd. vermeidbarem EDA-Spend pro Jahr**.

Mit kürzerem Technologiehorizont oder höherem Risikozuschlag steigt diese Schwelle weiter. Bei etwa fünf Jahren und höherem Kapitalkostensatz kann sie eher Richtung **$5 Mrd.+ pro Jahr** wandern.

Diese Modellierung ist keine exakte Schätzung der realen Google-/Nvidia-Kosten, sondern ein wirtschaftlicher Reality Check.

Ein wichtiger Beleg ist Cadences Kundenkonzentration: 2025 machte kein einzelner Kunde mindestens 10 % des Cadence-Umsatzes aus. Das beweist nicht, dass der gesamte EDA-Spend eines Hyperscalers über Synopsys, Cadence, Siemens und IP zusammen niedrig ist. Die relevante Zahl wäre der gesamte EDA-Spend über alle Anbieter, der öffentlich nicht sauber verfügbar ist.

Trotzdem zeigt die Größenordnung, warum Full-Stack-Internalisierung wirtschaftlich deutlich schwieriger sein kann als partielle Internalisierung.

Für einzelne Agenten-, Workflow- oder Compiler-Layer kann Eigenbau dagegen sehr wohl rational sein. Genau deshalb ist ein hybrider Endzustand plausibel:

> **Big Tech besitzt Agenten und interne Workflows; Synopsys/Cadence bleiben Verification-, Simulation- und Signoff-Infrastruktur.**

---

# 5. Reale Evidenz: Nvidia kooperiert mit beiden

Der stärkste strategische Reality Check ist Nvidia.

Nvidia ist einer der Akteure mit dem größten technischen Know-how und dem größten Anreiz, kritische AI-Hardware-Schichten zu kontrollieren. Das Unternehmen verticalisiert aggressiv, entwickelt eigene CPUs, GPUs, Networking, Software, Agent-Infrastruktur und zunehmend komplette AI-Factory-Architekturen.

Trotzdem behandelt Nvidia Synopsys und Cadence bislang nicht wie veraltete Software, die ersetzt werden soll.

Stattdessen:

- Nvidia arbeitet strategisch mit **Synopsys** an accelerated engineering, agentic AI, Simulation und digitalen Zwillingen.
- Nvidia investierte **$2 Mrd. in Synopsys** zu $414,79 je Aktie.
- Nvidia arbeitet gleichzeitig mit **Cadence** an AgentStack, ChipStack, Simulation und Engineering-Automatisierung.
- Cadence- und Synopsys-Workloads werden auf Nvidia-Compute optimiert.

Das beweist keine dauerhafte Unangreifbarkeit. Es ist aber ein starkes strategisches Signal:

> **Der technisch stärkste AI-Chip-Akteur behandelt beide Unternehmen aktuell als strategische Infrastruktur, nicht als Layer, den er kurzfristig eliminieren möchte.**

Wenn Nvidia, das selbst stark verticalisiert, bei EDA Partnerschaft statt Full-Stack-Ersatz wählt, stärkt das die Bottleneck-These erheblich.

---

# 6. Eintrittsbarrieren

Synopsys und Cadence dürfen nicht wie normale SaaS-Unternehmen betrachtet werden.

Ihr Moat besteht nicht primär aus Code.

Ein ernsthafter neuer Wettbewerber müsste gleichzeitig aufbauen oder replizieren:

- jahrzehntelanges Prozesswissen,
- physikalische Modelle,
- Verification- und Signoff-Kompetenz,
- Foundry-Zertifizierung,
- Integration mit TSMC-, Samsung- und anderen Prozessen,
- reale Tape-out-Historie,
- Kundenvertrauen,
- IP-Kompatibilität,
- Toolchain-Integration,
- Unterstützung neuer Nodes,
- Advanced Packaging,
- Thermal,
- Power,
- Electromagnetics,
- System-Level-Engineering.

Foundation Models können Softwareentwicklung deutlich billiger machen. Sie können aber nicht kurzfristig jahrzehntelange Foundry-Integration und eine große Historie real erfolgreicher Designs erzeugen.

Deshalb gilt:

> **Eintritt in einzelne EDA-Nischen: möglich.**
>
> **Aufbau eines vollwertigen, foundry-zertifizierten End-to-End-EDA-Stacks: extrem schwer.**

AI-native Startups sind trotzdem relevant.

Cognichip ist ein Beispiel für einen ernsthafteren Versuch, mit physikinformierten Foundation Models tiefer in Chipdesign einzudringen. Andere Anbieter wie ChipAgents oder Agentrys sitzen stärker auf der Agenten-/Workflow-Schicht.

Der bisher sichtbare Zustand spricht eher dafür, dass neue Agenten auf bestehenden EDA-Engines aufsetzen, statt die Ground-Truth-Schicht sofort zu ersetzen.

Das muss weiter beobachtet werden.

---

# 7. Warum AI die Eintrittsbarriere an der Oberfläche senkt, aber den Kern-Moat nicht zwingend zerstört

AI kann die Kosten des Schreibens von Software massiv senken. Das zerstört Moats, deren Knappheit hauptsächlich aus Softwareproduktionskosten bestand.

EDA ist anders.

Der knappe Wert liegt zu großen Teilen in:

- validierter Physik,
- Foundry-Vertrauen,
- Prozesswissen,
- Signoff-Validierung,
- erfolgreicher Silicon-Historie,
- Integration.

Das passt zu einer allgemeinen Abundance-These:

> **Wenn Code abundant wird, wandert der Wert von „wer kann Software bauen?“ zu „wessen Output wird als Ground Truth akzeptiert?“**

Bei EDA kann genau diese Ground-Truth-Schicht der wertvollste Teil sein.

---

# 8. Bottleneck Migration und No Dead End

Der Engpass bleibt nicht statisch.

Er wandert ungefähr von:

> klassischem IC-Design → SoCs → Chiplets → Advanced Packaging → 3DIC → Thermal / Power / Electromagnetics → Multiphysics → komplette Systeme.

Synopsys hat mit **Ansys** genau in diese nächste Schicht expandiert.

Strategisch ist das bemerkenswert: Synopsys versucht nicht nur den heutigen EDA-Tollbooth zu verteidigen, sondern dem Engpass vom einzelnen Chip in die breitere physikalische Engineering-Schicht zu folgen.

Cadence verfolgt eine ähnliche Entwicklung über:

- Core EDA,
- Semiconductor IP,
- Packaging,
- System Design & Analysis,
- Physics Simulation,
- Digital Twins.

Damit bestehen beide den **No-Dead-End-Test** besonders gut.

Ein Unternehmen, das nur von einem vorübergehenden Bottleneck lebt, kann nach dessen Entspannung strukturell verlieren.

Synopsys und Cadence besitzen dagegen die Möglichkeit, entlang der Bottleneck-Migration zu expandieren.

---

# 9. Warum tiefere physische Engpässe EDA nicht zwingend schädigen

Wenn TSMC-Kapazität, Packaging oder andere physische Ressourcen knapp und teuer werden, kann das den Wert von EDA sogar erhöhen.

Je teurer ein Fertigungsslot ist, desto höher die Kosten eines fehlerhaften Designs.

Das bedeutet:

> **Ein tieferer Engpass kann den Wert der EDA-Verification erhöhen, statt ihn zu zerstören.**

Das ist eine besonders attraktive Eigenschaft. Bei vielen Unternehmen hängt Wachstum davon ab, dass ein tieferer Bottleneck verschwindet. EDA kann teilweise gerade dann wertvoller werden, wenn tieferliegende Ressourcen knapp bleiben.

---

# 10. Was der Markt aktuell zu erwarten scheint

Der Markt erwartet nicht, dass Synopsys oder Cadence sterben.

Beide werden weiterhin als hochwertige Unternehmen mit zweistelligem Wachstum bewertet.

Die mögliche Fehlbewertung liegt daher nicht in der Aussage:

> „Der Markt glaubt, EDA wird irrelevant.“

Sondern eher:

> **Der Markt könnte die Dauer und Stärke des durch AI erzeugten EDA-Wachstums unterschätzen.**

Der Konsens behandelt die Branche offenbar eher wie ein reifes Softwareduopol, dessen Wachstum nach dem aktuellen AI-Schub wieder in Richtung low-teens normalisiert.

Unsere These ist stärker:

> **AI erhöht dauerhaft die Menge an Engineering, die pro Mensch und pro System ausgeführt werden kann.**

Wenn ein Ingenieur mit AI-Agenten künftig hunderte oder tausende Design-/Verifikationsschritte statt einiger weniger durchführen kann, kann die EDA-Nutzung schneller wachsen als die Zahl menschlicher Ingenieure.

Zusätzlich erweitert sich der adressierbare Markt über Chipdesign hinaus in Richtung Packaging, Physics und komplette Systeme.

Wenn diese Annahme stimmt, könnte mid-teens Umsatzwachstum länger anhalten und EPS durch Operating Leverage, Debt Paydown und Kapitalrückflüsse noch schneller wachsen.

---

# 11. Synopsys — warum 11.000

Synopsys erhält **55 % der EDA-Allokation**, weil der mögliche Expectation Gap größer ist.

Referenz:

- Kurs: **$393,84**
- Forward-P/E: ungefähr **23×**
- deutlich unter dem 52-Wochen-Hoch
- historisches Forward-Multiple in den letzten Jahren deutlich höher

Q3 2026 hat mehrere vorherige Sorgen eher abgeschwächt als bestätigt:

- Umsatz: **$2,477 Mrd.**
- Design IP wieder im Wachstum
- EDA weiter stark
- Umsatz-, Margen-, EPS- und FCF-Guidance angehoben
- Management erwartet weiterhin zweistelliges EDA-Wachstum

Damit sieht die frühere Schwäche bisher eher nach temporärer Belastung als nach einem strukturellen Kill-Signal aus.

Synopsys hat zudem durch Ansys die größere Expansion Surface in Richtung Multiphysics und System Engineering.

Der mögliche Re-Rating-Mechanismus lautet:

> **EDA-Wachstum bleibt länger hoch als erwartet + Ansys-Integration funktioniert + Debt sinkt + Risikoabschlag nimmt ab → Earnings steigen und Multiple kann gleichzeitig wieder expandieren.**

Das ist die asymmetrischere Wette.

---

# 12. Synopsys — größtes Risiko: Ansys

Synopsys bekommt trotzdem nicht die gesamte Position.

Die Ansys-Übernahme erzeugt reale Risiken:

- höhere Verschuldung,
- Aktienverwässerung,
- Integrationsrisiko,
- Risiko eines zu niedrigen ROIC auf den Kaufpreis.

Strategisch passt Ansys hervorragend zur Bottleneck-Migration.

Finanziell muss die Übernahme aber beweisen, dass die zusätzliche Expansion Surface genug Cashflow und langfristigen Return on Invested Capital erzeugt.

Dieser Punkt ist aktuell wahrscheinlich der größte firmenspezifische Failure Mode der Synopsys-These.

---

# 13. Cadence — warum 9.000

Cadence bekommt **45 % der EDA-Allokation**.

Cadence ist aktuell die sauberere operative Maschine:

- Q2 2026 Umsatz **+24 % YoY**,
- Core EDA **+18 %**,
- Semiconductor IP **>+40 %**,
- System Design & Analysis **+37 %**,
- Rekord-Backlog **$8,1 Mrd.**,
- Guidance angehoben,
- sehr hohe operative Margen,
- starke Cash Conversion,
- keine vergleichbar große transformative M&A-Belastung.

Das Hauptrisiko bei Cadence ist weniger die operative Qualität als der Preis.

Referenz:

- Kurs: **$292,70**
- Forward-P/E: ungefähr **34×**

Damit verlangt der Markt bereits deutlich mehr von Cadence als von Synopsys.

Cadence ist deshalb weniger die große Re-Rating-Wette und stärker eine hochwertige Compounder-Wette auf denselben strukturellen EDA-Bottleneck.

---

# 14. Warum beide statt nur Synopsys

Die Überzeugung in die **Branchen-/Bottleneck-These** ist inzwischen höher als die Überzeugung darüber, welches einzelne Unternehmen in den nächsten Jahren besser executen wird.

Wenn die Grundthese stimmt:

> AI → mehr Engineering-Komplexität → mehr EDA-Wert,

können beide profitieren.

Ihre Renditen müssen trotzdem nicht identisch sein.

Synopsys könnte stärker steigen, wenn Ansys funktioniert und das Multiple wieder expandiert.

Cadence könnte stärker steigen, wenn seine operative Execution weiter außergewöhnlich bleibt und die AI-Nutzung schneller skaliert als der Markt erwartet.

Beide zu halten reduziert daher nicht die These, sondern diversifiziert **firmenspezifisches Risiko innerhalb einer hoch überzeugenden Thesis-Familie**.

Die Logik lautet:

> **Thesis conviction hoch + company-specific uncertainty vorhanden = beide besitzen.**

---

# 15. Warum 11k / 9k statt 10k / 10k

Die Gewichtung ist bewusst nur leicht zugunsten Synopsys verschoben.

**Synopsys bekommt 11k**, weil:

- das Forward-Multiple deutlich niedriger ist,
- die Aktie stärker de-rated wurde,
- der Expectation Gap größer erscheint,
- Ansys im positiven Fall zusätzlichen TAM und Bottleneck-Migration eröffnet,
- Nvidia strategisch investiert hat,
- ein doppelter Renditetreiber aus Earnings Growth + Multiple Re-Rating möglich ist.

**Cadence bekommt 9k**, weil:

- operative Qualität aktuell höher / sauberer ist,
- Capital Conversion stärker ist,
- keine vergleichbare Ansys-/Debt-/Dilution-Wette existiert,
- es firmenspezifische Risiken von Synopsys innerhalb derselben strukturellen These diversifiziert.

55/45 erscheint deshalb ausgewogener als 50/50, aber weniger aggressiv als 70/30.

---

# 16. Relative Bewertung und Reverse-Valuation-Logik

Die Reverse Valuation zeigt einen deutlichen Unterschied zwischen beiden Unternehmen.

Bei Synopsys ist der heutige Kurs kompatibel mit einer guten Rendite, wenn das Unternehmen langfristig ungefähr low- bis mid-teens EPS-Wachstum schafft und das Multiple nicht dauerhaft auf sehr niedrigen Niveaus bleibt.

Bei Cadence verlangt die Bewertung mehr. Wenn das Multiple langfristig sinkt, muss das EPS-Wachstum deutlich stärker bleiben, damit die Rendite ähnlich attraktiv wird.

Damit ist Synopsys aktuell die stärkere **Expectation-Gap-/Re-Rating-Wette**, während Cadence die stärkere **Quality-/Execution-Wette** ist.

Die zentrale Alpha-Frage lautet daher nicht:

> „Wächst EDA?“

Sondern:

> **„Wächst EDA länger und stärker, als der Markt heute in den langfristigen Cashflows voraussetzt?“**

---

# 17. Geopolitischer Override: China

Ein wichtiger Sonderfall zur Internalisierungslogik ist China.

Das Break-even-Modell unterstellt grundsätzlich wirtschaftlich rationale Build-vs-Buy-Entscheidungen.

Geopolitik kann diese Logik außer Kraft setzen.

China kann lokale EDA-Anbieter auch dann fördern, wenn ein paralleler Stack kurzfristig wirtschaftlich schlechter ist, weil technologische Unabhängigkeit einen strategischen Wert besitzt.

Damit ist China kein normaler temporärer Nachfragefehler.

Ein Teil des chinesischen EDA-Marktes kann langfristig strukturell lokalisiert werden, sobald heimische Alternativen ausreichend funktionsfähig sind.

Das ist ein echter Risikoabschlag für Synopsys und Cadence und darf nicht als bloß vorübergehendes Exportproblem modelliert werden.

Gleichzeitig bestätigt der Sonderfall indirekt die normale wirtschaftliche Logik: Wo keine geopolitisch erzwungene Parallelisierung stattfindet, bleibt der externe Spezialisten-Stack ökonomisch sehr attraktiv.

---

# 18. Wann die These sichtbar werden könnte

Fundamentale Wahrheit und Markt-Recognition können zeitlich auseinanderliegen.

Ein plausibler Zeitpfad:

### 0–6 Monate

- EDA-Nachfrage bleibt stark,
- Guidance hält oder steigt,
- keine Hinweise auf ernsthafte AI-Substitution der Signoff-Schicht,
- Synopsys zeigt Fortschritt bei Ansys-Integration.

### 6–18 Monate

- Agentic EDA erzeugt messbar mehr Tool-Nutzung,
- Packaging / System Design / Multiphysics wachsen überproportional,
- weitere Hyperscaler integrieren EDA-Agenten auf bestehenden Engines,
- Core EDA bleibt klar zweistellig.

### 1–3 Jahre

Der Markt könnte erkennen, dass der AI-Effekt auf EDA kein kurzfristiger CapEx-Zyklus ist, sondern eine strukturelle Erhöhung der Engineering-Execution.

Dann könnte bei Synopsys ein Re-Rating einsetzen.

### 3–5 Jahre

Die volle These wäre sichtbar, wenn:

- EDA länger als Konsens erwartet zweistellig wächst,
- AI-Agenten die Nutzung verstärken statt substituieren,
- Bottleneck Migration Richtung Packaging/Physics/System Engineering tatsächlich monetarisiert wird,
- Ansys einen attraktiven ROIC liefert,
- beide Unternehmen ihre Pricing Power halten.

Die Wette ist deshalb nicht auf einen kurzfristigen Kurssprung gerichtet.

Sie ist eine **2–5-Jahres-Wette auf strukturell unterschätzte Dauer des EDA-Wachstums**.

---

# 19. Kill Criteria

Die Position sollte nicht allein wegen fallender Kurse verworfen werden.

Die These muss neu bewertet werden, wenn ihre Mechanismen brechen.

Wichtige Kill-Signale:

1. **Core EDA wächst trotz weiter steigender Chipkomplexität dauerhaft deutlich langsamer.**
2. **AI-Agenten reduzieren monetarisierbare EDA-Nutzung**, statt Simulation und Verification zu vervielfachen.
3. **Hyperscaler oder Foundries beginnen ernsthaft, zentrale Verification-/Signoff-Ground-Truth intern zu ersetzen.**
4. **AI-native Wettbewerber gelangen erfolgreich aus der Agentenschicht in den foundry-zertifizierten Kern-EDA-Stack.**
5. **Pricing Power verschwindet**, obwohl technische Abhängigkeit bestehen bleibt.
6. **China-Lokalisierung breitet sich stärker aus als modelliert.**
7. Bei Synopsys speziell: **Ansys liefert langfristig keinen ausreichenden ROIC auf Kaufpreis, Debt und Verwässerung.**
8. Die strategischen Partnerschaften der großen Chipunternehmen verschieben sich sichtbar weg von Synopsys/Cadence hin zu echten Ersatzlösungen.

Solange diese Punkte nicht eintreten, ist ein fallender Kurs nicht automatisch eine gebrochene Investmentthese.

---

# 20. Endgültige Investmentthese

Die These lässt sich auf einen Satz komprimieren:

> **Foundation Models machen Engineering-Intelligenz abundant, aber nicht die verifizierte physikalische Ground Truth, die nötig ist, um aus AI-generierten Designs funktionierende reale Chips und Systeme zu machen.**

Synopsys und Cadence besitzen einen großen Teil genau dieser Schicht.

Der Eintritt ist schwer.

Full-Stack-Internalisierung ist wirtschaftlich unattraktiv, solange EDA relativ wenig kostet gegenüber dem Wert, den es schützt.

Hyperscaler haben gleichzeitig noch schmerzhaftere Bottlenecks, in die Kapital und Talent fließen.

Die größten AI-Unternehmen kooperieren mit den incumbents statt sie bisher zu ersetzen.

Nvidia arbeitet strategisch mit beiden und hat sogar direkt in Synopsys investiert.

AI-native Agenten scheinen derzeit eher auf den bestehenden EDA-Engines aufzubauen, als die Signoff-Schicht zu verdrängen.

Beide Unternehmen können entlang der Bottleneck Migration in Packaging, Multiphysics und System Engineering expandieren.

Der Markt hat andere AI-Bottlenecks wie Compute, Memory, Networking und Power bereits deutlich stärker neu bewertet, während Synopsys und Cadence deutlich unter ihren Hochs und bei komprimierten Multiples handeln.

Die Wette ist daher nicht:

> **„EDA ist ein gutes Geschäft.“**

Das ist bekannt.

Die Wette ist:

> **„AI erhöht den wirtschaftlichen Wert und die Nutzungsintensität von EDA länger und stärker, als der Markt heute impliziert.“**

Innerhalb dieser These:

> **11.000 Synopsys = größere Expectation-Gap-/Re-Rating-Wette.**
>
> **9.000 Cadence = sauberere Execution-/Capital-Conversion-Wette.**

Gemeinsam repräsentieren die Positionen zwei unterschiedliche Ausprägungen desselben tiefen AI-Engineering-Bottlenecks.
