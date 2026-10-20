# Quellen zum Lernzettel vom 16.10.2026 (Minitest 23.10.2026)

Überarbeitet am 20.10.2026 nach einem Review gegen Folien, Transkript, Moodle und Kurs-Chat.

## Verwendete Quellen

1. **Lecture1.pdf**, 85 PDF-Seiten, Kurs „Security Engineering, 622.755 (26W)“, DI Dr. Jasmin Wachter, BA BSc (Moodle „Lecture 1“, Stand Fr 16.10. 13:32).
   - Alle Seiten mit `pdftotext -layout` erfasst.
   - Bildfolien zusätzlich als Bilder gerendert und gelesen: F9/F14 (Analysis Framework), F38–F43 (PRISM-/Google-Leak-Folien), F45 (Crypto), F47 (XKEYSCORE), F53 (Belt and Road), F55–F60 (Stuxnet-Ablauf, Stuxnet-Pfade, Sony, Russia-Ukraine-Timeline, SolarWinds-Ablauf, US-Wahl 2016), F74 (AI-Agents), F84 (Minitest-Folie mit Beispielbild).
   - Fragenfolien F76–F83 vollständig ausgewertet; jede dieser Fragen ist im Lernzettel einem Block zugeordnet (Markierung `?F77` … `?F83`).
   - **F** im Lernzettel = PDF-Seitennummer dieser Datei.
2. **Preamble-Lecture 0.pdf**, 15 PDF-Seiten (Moodle „Lecture 0: Preamble“, Stand Mi 30.09.).
   - Nur für Organisatorisches verwendet: P7–P9 (Assessment, Grading, Minitest-Format der älteren Fassung), P11–P14 (Report, Poster Session). Inhaltlich identische Definitionen (P3) stammen aus Lecture1.
   - **P** im Lernzettel = PDF-Seitennummer dieser Datei.
3. **2026-10-16_security-engineering-and-threat-modeling.txt**, Vowen-Mitschrift „Security Engineering and Threat Modeling“, 16.10.2026, 0:00–1:24:45.
   - Original-Link: https://share.vowen.ai/n/fj78iogBvKRILSYxNoJkBO
   - Verwendet wurden die zeitgestempelten Aussagen, nicht die automatische Zusammenfassung als eigenständiger Beleg.
   - **T** im Lernzettel = Zeitstempel.
4. **Moodle-Kurs 62275526W (id 47237)**, gelesen am 20.10.2026 über die Moodle-App-API (nur lesend, nichts heruntergeladen):
   - Abschnittstexte „General Information“ (Termine Poster Session 15.1. 11:45, Poster-Druck bis 9.1., Final Exam 22.1. 11:45, Report-Frist 28.02.2027 mit Soft Margin), „Lecture Notes“ (Fragen am Foliensatzende relevant, aber nicht vollständig; Themenwahl), Beschreibung „Lecture 1“ (Folien enthalten auch nicht besprochene Details; Buch Kap. 1–2; Video 1 Min. 0–43).
   - Seiten „Report and Poster“ und „Grading and Assessment Information“.
   - Abstimmung „Task: Select Topics for Written Report/Poster Session“ (first-come-first-served, Plätze pro Thema begrenzt).
   - Aufgaben „Poster (or Presentation)“ (fällig 9.1., Cutoff 16.1.) und „Final Report (Due: 28.2. 2027)“.
   - Links „Lecture 1 (Part 1: Defintions)“ (YouTube, Min. 0–8:30) und „Lecture 1 (Part 2)“ (YouTube, Min. 0–43).
   - Forum „Ankündigungen“: über die API keine Beiträge sichtbar. Kein Quiz und kein „sample minitest“ im Kurs gefunden.
   - **M** im Lernzettel = diese Kursseite.
5. **E-Mail der Lehrperson** (vom Nutzer weitergegeben, nicht in Moodle gefunden): Minitest am Freitag, ca. 5 Minuten, Foliensatz inklusive Fragenfolien lernen, Poster-Thema auswählen.
6. **WhatsApp-Kursgruppe** (Hermes-Profil `kurs`, lokaler Sitzungsspeicher, nur lesend durchsucht): einzige kursbezogene Nachricht ist die Rückfrage eines Gruppenmitglieds vom 20.10., ob der Lernzettel alle Fragen der letzten sieben Folien abdeckt. Daraus folgt die Zuordnung jeder Fragenfolien-Frage zu einem Block. Keine weiteren inhaltlichen Hinweise.

## Zuordnung der Inhalte

- **Muss ich wissen / Grundlagen**: F5–F16, F32–F33; T1:41–15:13, 40:31–41:10 (Fragen F77, F79).
- **Muss ich wissen / Definitionen**: F17–F30; T15:18–39:32 (Fragen F77–F79).
- **Muss ich wissen / Adversaries**: F34–F75; T41:41–1:24:45 (Fragen F80–F83). Ransomware, The Swamp, Social Media und AI (F65–F74) stehen jetzt in „Muss ich wissen“, weil die Fragenfolien danach fragen und Moodle sagt, dass die Folien auch nicht besprochene Details enthalten.
- **Hinweise der Lehrperson**: T0:00–1:41, 9:28, 35:07–35:37, 39:32, 41:18, 42:26–42:37, 1:18:16; F2–F3, F76, F84; P9, P11–P14; Moodle; E-Mail.
- **Gut zu wissen**: Bildfolien-Details F39–F40, F47; Bewertungsangaben F3, P7–P8, T0:00–0:28, Moodle.
- **Selbsttest**: zehn Fragen im Wortlaut bzw. Stil von F77–F81; Antworten aus den Blöcken oben.

## Änderungen gegenüber der ersten Fassung

- Fragenfolien vollständig abgedeckt; vorher fehlten u. a. Safety vs. Security, die sechs System-Definitionen, die vier Formen zusammengesetzter Principals, der Name Bruce Schneier beim Hack, die Hierarchie Protection → Protection Profile → Security Target → Implementation, Stuxnet-Ablauf, Five-Eyes-Sammelwege (Cornwall, Gibraltar, Malta, Singapore; Satellite; Embassies), XKEYSCORE-Details, Microsoft-Hack 2021, Ransomware-Entwicklung, Content Moderation (DSA, Online Harms Bill, Backlash), „the rest of us“ als Amplifier.
- Fragenfolien-Themen F80–F83 aus „Gut zu wissen“ nach „Muss ich wissen“ verschoben.
- Organisation ergänzt: Themenwahl über die Moodle-Abstimmung, Termine aus Moodle, Hinweis auf widersprüchliche Bewertungsangaben.
- Kleinere Korrekturen: Adversarial Thinking nicht mehr mit der F7-Aussage vermischt; Trusted-Beispiel TPM und Trustworthy-Beispiel aus F21 wörtlich; Heartbleed-Ursache aus F26.
- Layout: 10 pt statt 11 pt, Aufzählungszeichen ohne Bitmap-Schrift.

## Quellenabgrenzung und Unsicherheiten

- **Testmedium widersprüchlich**: F84 und P9 sagen „Moodle Quiz“, die Assessment-Folien F3/P7 „PEN + PAPER“; in Moodle ist noch kein Quiz angelegt. Die Empfehlung, Gerät und Stift mitzunehmen, ist als eigene Empfehlung gekennzeichnet.
- **Termin Poster Session**: Moodle nennt 15.1. 11:45 (ein Freitag), F2 nennt 16.1. (ein Samstag); der Lernzettel nennt beide.
- **Bewertung**: F3 und Transkript 45/25/30; Moodle-Seite „Grading and Assessment Information“ (Stand 07.09.) 45/45/10; Preamble gemischt. Bestehensgrenze Moodle 20 Punkte, P8 22 Punkte. Resubmission: Moodle erlaubt einmal (max. 10 Zusatzpunkte), Preamble sagt „cannot resubmit“ (nur in quellen.md, nicht minitest-relevant).
- **Ältere Minitest-Angaben (P9)**: 2–4 Fragen, True/False und Mathematical Computations; F84 (neuer) sagt 2–3 Fragen, keine Rechnungen diesmal.
- **„Querschnittsfrage“ (F83, challenges in identifying and combating online threats)**: Die Folien beantworten sie nicht an einer Stelle; der Block setzt nur Aussagen von F33, F64–F65, F72, F74–F75 zusammen.
- **Transkriptfehler** wurden nicht übernommen („principle“ statt „principal“, „common weakness emulation“ statt Enumeration, „Adjava/Viva model“, „Masula“, „fake link insights“). Die Zahl der Stuxnet-Zero-Days (Transkript: sieben, mit Einschränkung) und die SolarWinds-Personalgeschichte wurden weggelassen, weil sie nicht auf den Folien stehen und unsicher sind.
- Die konkrete Themenwahl einzelner Studierender steht nicht im Lernzettel (öffentliches Repo).
- Zum Nachlernen laut F85/Moodle: Ross Anderson, *Security Engineering* (3. Aufl.), Kapitel 1 und 2; Moodle-Videos Part 1 (Min. 0–8:30) und Part 2 (Min. 0–43).
- Keine externen Webquellen und keine Inhalte weiterer Vorlesungen ergänzt.

## Erstellung und Prüfung

- Deutschsprachige Erklärungen mit englischen Fachbegriffen; A4, 6 Seiten.
- Automatische Strukturprüfung: 36 Themenblöcke mit jeweils höchstens fünf Stichpunkten, genau zehn Selbsttestfragen mit Antworten.
- Zweimal mit `pdflatex -interaction=nonstopmode -halt-on-error` gebaut; keine LaTeX-, Overfull- oder Underfull-Warnungen; keine Type-3-Schriften; alle Seiten visuell geprüft.
