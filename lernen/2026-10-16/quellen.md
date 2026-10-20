# Quellen zum Lernzettel vom 16.10.2026

## Verwendete Quellen

1. **Lecture1.pdf**, 85 PDF-Seiten, Kurs „Security Engineering, 622.755 (26W)“, DI Dr. Jasmin Wachter, BA BSc.
   - Zugeordnet über die aktualisierte Inhaltsübersicht auf PDF-Seite 2 („Introduction and course outline, adversary identification“ am 16.10.), die inhaltliche Übereinstimmung mit der Mitschrift und das PDF-Erstellungsdatum 16.10.2026.
   - Alle PDF-Seiten mit `pdftotext -layout` erfasst und als Bilder gerendert; Übersichtsansichten aller Seiten sowie die widersprüchlichen Minitest-Angaben auf PDF-Seiten 3 und 84 zusätzlich in voller Größe geprüft.
   - Im Lernzettel bedeutet **F** immer die PDF-Seitennummer, nicht eine gegebenenfalls abweichende Nummer in einem eingebetteten Bild.
2. **2026-10-16_security-engineering-and-threat-modeling.txt**, Vowen-Mitschrift „Security Engineering and Threat Modeling“, 16.10.2026.
   - Original-Link: https://share.vowen.ai/n/fj78iogBvKRILSYxNoJkBO
   - Verwendet wurden die zeitgestempelten Aussagen von 0:00 bis 1:24:45, nicht die automatisch erzeugte Zusammenfassung als eigenständiger Beleg.
   - **T** im Lernzettel bezeichnet diese Zeitstempel.

## Zuordnung der Inhalte

- **Muss ich wissen / Grundlagen**: F5–21; T1:41–22:08.
- **Muss ich wissen / Schutzeigenschaften und technische Begriffe**: F22–30; T22:29–39:32.
- **Hinweise der Lehrperson**: T0:00–1:41, 9:28, 35:19–35:37, 42:09–42:37; als solche bezeichnete Ergänzungen zu Testdatum, Umfang, Rechenaufgaben und Ersatzprüfung aus F3 und F76–84.
- **Priorisierung und Incentives**: F8–14, F32–34; T5:23–12:58, 40:08–41:10.
- **Five Eyes und China**: F36–53; T43:05–1:11:47.
- **Stuxnet, Sony, Russland/SolarWinds**: F54–60; T1:11:47–1:23:10.
- **Intelligence Doctrine und Crooks**: F61–64; T1:23:10–1:24:45.
- **Ergänzendes Material desselben Foliensatzes**: Ransomware F63–66, The Swamp F67–71, Social Media und AI F72–75.
  Diese Inhalte werden nicht als in der Aufzeichnung ausführlich besprochen ausgegeben: Das Transkript endet beim Cybercrime-Ökosystem, und die zusätzlichen Themen erscheinen dennoch in den zum ersten Minitest gehörenden Fragenfolien F80–83.
- **Selbsttest**: zehn neu formulierte Lernfragen im Stil von F77–83; alle Antworten aus den oben genannten Definitionen und Inhalten, keine Vorhersage tatsächlicher Prüfungsfragen.

## Quellenabgrenzung und Unsicherheiten

- Im Auftragsfeld `folien_pdfs` war keine Datei angegeben; die thematisch und zeitlich passende **Lecture1.pdf** wurde aus den Zusatzquellen ermittelt, daher liegen sowohl Folien als auch Transkript vor.
- **Preamble-Lecture 0.pdf** wurde nur auf Relevanz geprüft und nicht als Inhaltsquelle für den Lernzettel verwendet, weil sie zu einer anderen Einheit gehört und veraltete beziehungsweise widersprüchliche organisatorische Angaben enthält.
- **Testmedium widersprüchlich**: Lecture1 F3 nennt „PEN + PAPER“, F84 „Moodle Quiz“; das Transkript klärt dies nicht, deshalb bleibt der Konflikt im Lernzettel ausdrücklich offen.
- Die „weniger als 20 Punkte“-Regel für die Ersatzprüfung auf F3 wird nicht zu einer Bestehensgrenze umgedeutet; aus der älteren Preamble werden keine abweichenden Grenzen übernommen.
- Der Ausschluss von Mathematical Computations bezieht sich ausschließlich auf „not this time“ in F84, nicht auf alle Minitests.
- Laut Transkript ist jede an diesem Tag behandelte Definition potenziell prüfungsrelevant; die Frageliste wird in F76 als nicht vollständig bezeichnet.
- Automatische Transkriptfehler wie „principle“ statt „principal“, verstümmelte Modellnamen, vermischte CVE/CWE-Bezeichnungen und unzuverlässige technische Details wurden nicht ungeprüft übernommen; eindeutige Begriffe wurden anhand der passenden Folien verwendet, unklare Modellnamen ausgelassen.
- Authenticity, Subject und Identity werden ausdrücklich im Sinn dieser Vorlesung definiert, nicht als universell einheitlicher Sprachgebrauch ausgegeben.
- Historische Angriffszuschreibungen werden als Darstellung der Vorlesung/Fallstudien gekennzeichnet; pauschale Rechtsbehauptungen zu US- und Nicht-US-Bürgern, spekulative SolarWinds-Personalgeschichten und unsichere Zero-Day-Anzahlen wurden nicht übernommen.
- Es wurden keine externen Webquellen und keine Inhalte weiterer Vorlesungen ergänzt.

## Erstellung und Prüfung

- Deutschsprachige Erklärungen mit englischen Fachbegriffen; eine A4-LaTeX-Quelle und ein schlichtes PDF mit höchstens sechs Seiten.
- Themenblöcke mit höchstens fünf Stichpunkten und zehn Selbsttestfragen mit Antworten.
- Quellenbezug und Reihenfolge geprüft; automatische Strukturprüfung bestätigt 20 Themenblöcke mit jeweils höchstens fünf Stichpunkten und genau zehn nummerierte Selbsttestfragen mit Antworten.
- Zweimal mit `pdflatex -interaction=nonstopmode -halt-on-error` gebaut; PDF mit sechs A4-Seiten und ohne LaTeX-, Overfull- oder Underfull-Warnungen.
- Alle sechs fertigen PDF-Seiten visuell geprüft; zusätzlich Bounding-Box-Prüfung auf Text außerhalb der Seitenränder bestanden.
