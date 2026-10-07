# Foliengenaue Inhalte — Multiagenten-Architektur & die Machtverschiebung der IT

Workshop (50 min) · Kongress-Motto „Co-Intelligence" · Zielgruppe C-Level / IT-Entscheider
Struktur für den späteren Design-Build. Jede Folie = ein Block.

> **Stand v4 (Übungen entschlackt + Anhang):** Aus drei Fällen in Übung 1 wurde **ein zugespitzter Fall** mit vier Kernfragen (10 min). Übung 2 arbeitet statt acht nur noch **vier Entscheidungsdimensionen** ab (10 min). Die **ursprünglichen Übungen** (drei Fälle · acht Dimensionen) bleiben als **Anhang** erhalten. Insgesamt 27 Folien.

---

## SLIDE 1

TYP: Cover
KICKER: Kongress „Co-Intelligence" · Workshop
TITEL: Multiagenten-Architektur & die Machtverschiebung der IT
LEAD: Was passiert, wenn Softwareentwicklung demokratisiert wird und jeder zum Applikationsentwickler werden kann?

- Referenten: Linus (Organisation & Governance) · Daniel (technischer Deep Dive)
- Dauer: 50 Minuten

SPEAKER: Herzlich willkommen. Heute geht es nicht um ein neues Tool, sondern um eine Machtfrage: Wer darf in Zukunft Software bauen — und wer trägt die Verantwortung dafür?

---

## SLIDE 2

TYP: Agenda
KICKER: Agenda
TITEL: Früher → Heute → Morgen
LEAD: Der rote Faden des Workshops folgt einer einfachen Dramaturgie — zwei Gruppenübungen, jede mit echter Zeit.

| # | Abschnitt                                         | Zeit   |
|---|---------------------------------------------------|--------|
| 1 | Was passiert, wenn jeder bauen kann?              | 5 min  |
| 2 | Teil 1 — Machtverschiebung der IT                 | 8 min  |
| 3 | Gruppenübung 1: „Wem gehört die Software?"        | 10 min |
| 4 | Ableitung: die neue Rolle der IT                  | 4 min  |
| 5 | Teil 2 — Multiagenten-Architektur (Deep Dive)     | 8 min  |
| 6 | Gruppenübung 2: „Agentic Enterprise Architecture" | 10 min |
| 7 | Abschluss: die Rolle der IT von morgen            | 5 min  |
| A | Anhang: die ursprünglichen Übungen                 | —      |

SPEAKER: Wir bewegen uns von der Vergangenheit über die Gegenwart in die Zukunft — und arbeiten zweimal selbst: einmal an der Organisation, einmal an der Architektur. Beide Übungen bekommen bewusst Raum: ein Fall, vier Dimensionen, zehn Minuten.

---

## SLIDE 3

TYP: ActionTitle
KICKER: Einstieg
TITEL: Die Provokation
LEAD: Ihr Controlling-Mitarbeiter hat gestern Abend mit einem Agenten eine Anwendung gebaut. Sie läuft, 15 Kollegen nutzen sie. Sie wissen nichts davon.

- Was tun Sie als CIO — **außer sich zu wundern?**

SPEAKER: Halten Sie dieses Bild fest. Wir kommen am Ende darauf zurück. Die eigentliche Frage dieses Workshops lautet: Wenn Softwareentwicklung demokratisiert wird — was bleibt dann eigentlich noch exklusiv in der IT?

---

## SLIDE 4

TYP: Section
KICKER: Teil 1 · Machtverschiebung
TITEL: Vom Gatekeeper zum Gestalter
LEAD: Wie sich die Ausführungshoheit der IT verschiebt — und warum das eine Frage der Organisation ist, mehr als der Technik.

SPEAKER: Teil 1 handelt von Macht, nicht von Technik. Ich beginne mit dem, was Jahrzehnte lang gegolten hat.

---

## SLIDE 5

TYP: Table
KICKER: Früher · Der Status quo
TITEL: Die IT als Builder & Gatekeeper
LEAD: Jahrzehntelang war die IT der zentrale Flaschenhals — nicht aus Bosheit, sondern aus Struktur.

| Was gehörte exklusiv der IT?        | Rolle       |
|-------------------------------------|-------------|
| Applikationen & Softwareentwicklung | Builder     |
| Schnittstellen & Datenzugriffe      | Gatekeeper  |
| Infrastruktur & Deployment          | Betreiber   |
| Security & Software-Lifecycle       | Kontrolleur |

- Der klassische Weg: **Business Need → Demand-Prozess → IT → Entwicklung → Security → Testing → Deployment → Betrieb**
- Ein langer, linearer Korridor mit Übergaben und Warteschlangen.

SPEAKER: Dieser Korridor setzt eine Annahme voraus: Nur die IT *kann* Software bauen. Was passiert, wenn diese Annahme heute wegbricht?

---

## SLIDE 6

TYP: Cards
KICKER: Heute · Die nächste Stufe
TITEL: Vibe Coding — Softwareentwicklung wird demokratisiert
LEAD: Der Sprung geht über „schneller programmieren" hinaus: Jeder kann eine Applikation bauen.

- Ein Fachbereich beschreibt: „Ich brauche eine Anwendung, die Produktionsstörungen analysiert, Daten aus SAP und MES holt und mir jeden Morgen die fünf größten Ursachen zeigt."
- Ein Agent erzeugt daraus: **Frontend · Backend · Datenbank · API · Schnittstellen · Business-Logik · Tests** — und teils das Deployment.
- Softwareentwicklung wird zur *Beschreibung*, nicht zur *Konstruktion*.

SPEAKER: Das ist der Wow-Moment. Aber genau hier beginnt das eigentliche Problem — denn eine Applikation ist nicht nur Code.

---

## SLIDE 7

TYP: ActionTitle
KICKER: Heute · Der entscheidende Bruch
TITEL: Applikation ≠ Code
LEAD: Die Gleichung verlagert das Gewicht vom Code auf alles andere.

**Applikation = Code + Daten + Identitäten + Schnittstellen + Infrastruktur + Security + Betrieb + Verantwortlichkeit**

SPEAKER: Der Agent liefert vielleicht den Code. Aber wer liefert Datenhoheit, Identitäten, Security, Betrieb — und vor allem Verantwortlichkeit? Genau dort entsteht die Machtverschiebung.

---

## SLIDE 8

TYP: Split
KICKER: Heute · Die Verschiebung
TITEL: Vom Builder & Gatekeeper zum Architect & Governor
LEAD: Die IT verliert die Ausführungshoheit — und gewinnt die Gestaltungshoheit.

| Bisher                     | Morgen                                  |
|----------------------------|-----------------------------------------|
| Software bauen             | Rahmen & Standards setzen               |
| Anträge prüfen & freigeben | Architektur entwerfen                   |
| Technologie kontrollieren  | Governance betreiben                    |
| Exklusiver Produzent       | Architect, Betreiber, Governance-System |

- Die eigentliche Machtverschiebung: **die IT bekommt nicht weniger, sondern eine andere, anspruchsvollere Aufgabe.**

SPEAKER: Die IT wird zur Instanz, die die Regeln setzt. Die Verschiebung selbst ist dabei nicht technologisch — sie ist organisatorisch.

---

## SLIDE 9

TYP: Checklist
KICKER: Governance-Fragen
TITEL: Die fünf Fragen, die jetzt der IT gehören
LEAD: Das ist keine Technologiefrage — es ist eine Governance-Frage. Diese fünf bilden den Kern.

- Welche **Daten** darf eine Anwendung verwenden?
- Wer **besitzt** die Anwendung — und wer **betreibt** sie?
- Wie wird **Security** sichergestellt?
- Was passiert, wenn der **Ersteller** das Unternehmen verlässt?
- Wie sieht der **Software-Lifecycle** für agentisch erzeugte Software aus?

SPEAKER: Diese fünf Fragen können wir nicht im stillen Kämmerlein beantworten. Lassen Sie uns das jetzt an einem konkreten Fall durchspielen.

---

## SLIDE 10

TYP: Section
KICKER: Gruppenübung 1
TITEL: Wem gehört die Software?
LEAD: Ein Fall, vier Fragen, zehn Minuten — und eine Diskussion, die es in sich hat.

SPEAKER: Statt drei Fälle oberflächlich abzuhaken, nehmen wir uns diesmal einen einzigen vor — und den richtig. Bilden Sie Gruppen.

---

## SLIDE 11

TYP: Cards
KICKER: Gruppenübung 1 · Der Fall
TITEL: Die Side-App, die geschäftskritisch wurde
LEAD: Ein Mitarbeiter im Controlling baut mit einem AI-Agenten eine kleine Anwendung. Sechs Monate später sieht die Realität so aus:

- **Die Anwendung:** Greift auf Unternehmensdaten zu · hat einen Login · verarbeitet Kundendaten
- **Der Ist-Zustand:** 15 Nutzer · 5 Schnittstellen · 3 Datenbanken · 2 externe AI-APIs · keine Tests · kein Backup · kein dokumentierter Owner
- **Der Auslöser:** Die Anwendung ist inzwischen **geschäftskritisch** — und der Ersteller reicht seine Kündigung ein.

SPEAKER: Das ist kein Gedankenspiel: Es ist die logische Endstufe dessen, was passiert, wenn Governance fehlt. Und jetzt müssen Sie entscheiden.

---

## SLIDE 12

TYP: Checklist
KICKER: Gruppenübung 1 · Die Fragen
TITEL: Vier Entscheidungen, die niemand für Sie trifft
LEAD: Zehn Minuten, konkret: wer, mit welcher Verantwortung, mit welcher Konsequenz.

1. **Weiterbetrieb** — Darf die Anwendung produktiv weiterlaufen? Wer entscheidet das?
2. **Ownership** — Wer ist Owner, und wer verantwortet Security, Betrieb und Wartung?
3. **Der Absprung** — Der Ersteller kündigt: Wie sichern Sie Wissen, Lifecycle und Betrieb?
4. **Die Regel** — Welche Regel hätten Sie vor sechs Monaten gebraucht — und führen Sie sie jetzt ein?

SPEAKER: Beantworten Sie in der Gruppe alle vier — aber in die Tiefe, nicht in die Breite. Ein Owner, ein Betriebsmodell, eine Regel. Danach tragen wir zusammen.

---

## SLIDE 13

TYP: ActionTitle
KICKER: Ableitung · Teil 1
TITEL: Die neue Rolle der IT
LEAD: Aus Ihren Antworten lässt sich eine Rolle ableiten — weniger Produzent, mehr Gestalter.

- Die IT wird vom **Produzenten** von Technologie zum **Architekten, Betreiber und Governance-System** der digitalen Organisation.
- Sie setzt Rahmen, statt jede Anwendung selbst zu bauen.
- Die Machtverschiebung ist eine **Chance**, wenn Governance aktiv gestaltet wird.

SPEAKER: Das war die organisatorische Hälfte. Jetzt wechseln wir zur Technologie: Was bedeutet das konkret in einer Multiagenten-Architektur? Daniel übernimmt.

---

## SLIDE 14

TYP: Section
KICKER: Teil 2 · Multiagenten-Architektur
TITEL: Vom einzelnen Agenten zum Agent-System
LEAD: Nicht mehr User → ChatGPT. Sondern User → Agent → Agent → Agent → Tools → Daten → Systeme.

SPEAKER: Sie haben die Governance durchdacht. Jetzt bauen wir die Architektur dazu — vom einzelnen Agenten bis zum unternehmensweiten System.

---

## SLIDE 15

TYP: Timeline
KICKER: Deep Dive · Begriffsklärung
TITEL: Was ist eigentlich ein Agent?
LEAD: Die Evolutionsstufen — vom Sprachmodell zum Multi-Agenten-System.

| Stufe                  | Was es kann                                          |
|------------------------|------------------------------------------------------|
| **LLM**                | Text verstehen & erzeugen                            |
| **Tool-Calling**       | externe Funktionen/APIs aufrufen                     |
| **Agent**              | Ziele verfolgen, Werkzeuge nutzen, entscheiden       |
| **Multi-Agent-System** | spezialisierte Agenten orchestriert zusammenarbeiten |

- Beispiel: **Planning Agent → SAP Agent → MES Agent → Analytics Agent → Reporting Agent**

SPEAKER: Der Sprung von „Agent" zu „Multi-Agent" ist der eigentliche Quantensprung für Unternehmen — und die Quelle der neuen Governance-Fragen.

---

## SLIDE 16

TYP: Cards
KICKER: Deep Dive · Konkretes Setup
TITEL: Die Bausteine eines Agenten
LEAD: Ein Agent ist ein System aus neun Bausteinen — jeder davon eine Governance-Entscheidung.

- **Model** — welches Sprachmodell treibt ihn?
- **Agent** — welche Rolle, welcher Auftrag?
- **Tools** — welche Systeme darf er bedienen?
- **Memory** — was merkt er sich (sicher)?
- **Knowledge** — auf welchem Wissen basiert er?
- **APIs** — welche Schnittstellen nutzt er?
- **Permissions** — welche Rechte hat er?
- **Orchestration** — wie werden mehrere Agenten gesteuert?
- **Monitoring** — wie wird er überwacht?

SPEAKER: Jeder dieser Bausteine ist eine Stelle, an der Ihre Governance-Fragen aus Teil 1 konkret werden.

---

## SLIDE 17

TYP: Split
KICKER: Architekturfrage
TITEL: Wo sollen unsere Agenten laufen?
LEAD: Die zentrale Architekturentscheidung: On-Premises, Cloud oder Hybrid.

|                    | On-Premises                                                      | Cloud                                                            | Hybrid                                          |
|--------------------|------------------------------------------------------------------|------------------------------------------------------------------|-------------------------------------------------|
| **Vorteile**       | Datenhoheit · Kontrolle · bestehende Infrastruktur · teils regulatorische Vorteile | Geschwindigkeit · verfügbare Modelle · Skalierung · Managed Services | Beides — selektiv, je nach Anforderung          |
| **Lasten/Risiken** | Infrastruktur · Modelle · Betrieb · Skalierung · Update-Zyklen   | Abhängigkeiten · Datenflüsse · Kosten · Vendor Lock-in · Governance | Welche Teile kontrollieren wir, welche beziehen wir aus der Cloud? |

- Die eigentliche Frage: **Welche Teile einer Multiagenten-Architektur müssen unter unserer Kontrolle bleiben — und welche können aus der Cloud kommen?**

SPEAKER: Das ist keine rein technische, sondern eine strategische Entscheidung. Genau diese sollen Sie jetzt treffen.

---

## SLIDE 18

TYP: Section
KICKER: Gruppenübung 2
TITEL: Baut eure Agentic Enterprise Architecture
LEAD: Ein Unternehmen, vier Entscheidungsdimensionen, zehn Minuten — ein Architekturbild.

SPEAKER: Jede Gruppe bekommt dasselbe Unternehmen. Entwerfen Sie gemeinsam eine Multiagenten-Architektur — diesmal in der Tiefe, nicht in der Breite.

---

## SLIDE 19

TYP: Table
KICKER: Gruppenübung 2 · Das Unternehmen
TITEL: 10.000 Mitarbeiter, vier Entscheidungsdimensionen
LEAD: Das Unternehmen: 10.000 Mitarbeiter · SAP · Microsoft 365 · mehrere Produktionsstandorte · MES · CRM · Data Platform

| # | Entscheidungsdimension    | Leitfrage                                                    |
|---|---------------------------|--------------------------------------------------------------|
| 1 | **Agenten & Rollen**      | Welche Agenten brauchen wir — und wer darf sie bauen?        |
| 2 | **Daten & Identity**      | Auf welche Daten dürfen sie zugreifen, und wie werden sie identifiziert & berechtigt? |
| 3 | **Infrastruktur**         | On-Prem, Cloud oder Hybrid — für welche Teile?              |
| 4 | **Governance & Security** | Was wird kontrolliert — und wo braucht es Human-in-the-loop? |

SPEAKER: Vier Dimensionen in zehn Minuten — das sind rund zweieinhalb Minuten pro Entscheidung. Tiefe statt Breite: mindestens eine klare Entscheidung pro Dimension, ein kohärentes Bild am Ende.

---

## SLIDE 20

TYP: Timeline
KICKER: Abschluss · Früher → Heute → Morgen
TITEL: Die eigentliche Machtverschiebung
LEAD: Der Bogen schließt sich — vom Machen zum Orchestrieren. Und er schließt sich dort, wo wir begonnen haben.

- **Früher** — die IT baut Software.
- **Heute** — IT + Business bauen Software.
- **Morgen** — Menschen orchestrieren Agenten, die Software bauen und betreiben.

SPEAKER: Denken Sie an den Controlling-Mitarbeiter von vorhin. Morgen ist er nicht der, der heimlich eine App baut — sondern Teil eines Systems, das Ihre IT orchestriert und verantwortet.

---

## SLIDE 21

TYP: ActionTitle
KICKER: Abschluss · Die Rolle von morgen
TITEL: Was bleibt der IT?
LEAD: Wenn jeder Mitarbeiter Software erzeugen kann — was ist dann noch die Rolle der IT?

- Die IT wird weniger zum **exklusiven Produzenten** von Technologie — und stärker zum **Architekten, Betreiber und Governance-System** der digitalen Organisation.
- Das ist eine These, keine fertige Antwort — und genau die wollen wir mit Ihnen diskutieren.

SPEAKER: Wir geben bewusst keine fertige Lösung vor. Diese Frage lässt sich nicht in 50 Minuten beantworten — aber sie ist jetzt gestellt.

---

## SLIDE 22

TYP: Closing
KICKER: Co-Intelligence
TITEL: Die Machtverschiebung ist organisatorisch
LEAD: Nicht die Technologie verändert Ihre Organisation — sondern Ihre Antwort darauf.

**Die zentrale Frage: „Wem gehört die Software?" — die wichtigste Frage Ihrer nächsten fünf Jahre.**

- Softwareentwicklung wird demokratisiert → die Ausführungshoheit verschiebt sich → die IT wird vom Builder & Gatekeeper zum Architect & Governor.
- Co-Intelligence heißt: Menschen orchestrieren Agenten — unter klarer Governance und geteilter Verantwortung.

SPEAKER: Vielen Dank. Wir freuen uns auf die Diskussion — hier im Raum und in den Pausen des Kongresses.

---

## SLIDE 23

TYP: Section
KICKER: Anhang
TITEL: Anhang — die ursprünglichen Übungen
LEAD: Referenzmaterial für vertiefende Runden: die drei Fälle aus Übung 1 und die acht Entscheidungsdimensionen aus Übung 2.

SPEAKER: Im Anhang finden Sie die ursprünglichen, ausführlicheren Übungen — falls Sie in kleineren Runden oder im Nachgang in die Tiefe gehen wollen.

---

## SLIDE 24

TYP: Cards
KICKER: Anhang · Übung 1 · Fall A
TITEL: Vibe Coder im kleinen Unternehmen
LEAD: Der ursprüngliche Fall aus Übung 1 — zum Nachspielen in kleineren Runden.

- **Die Anwendung:** Ein Mitarbeiter im Controlling baut mit einem AI-Agenten eine kleine Anwendung. Sie greift auf Unternehmensdaten zu, hat einen Login, verarbeitet Kundendaten — und wird von **15 Mitarbeitern** genutzt.
- **Die sieben Fragen:** 1. Darf er sie produktiv einsetzen? · 2. Wer genehmigt sie? · 3. Wer ist Owner? · 4. Wer macht Security? · 5. Wer betreibt sie? · 6. Wer wartet sie? · 7. Was passiert, wenn der Mitarbeiter kündigt?

SPEAKER: (Anhang — Referenz, nicht vortragen.)

---

## SLIDE 25

TYP: Cards
KICKER: Anhang · Übung 1 · Fall B
TITEL: Digitalisierungsteam im Großunternehmen
LEAD: Wo die Grenzen zwischen IT und Fachbereich verschwimmen.

- **Die Anwendung:** Ein zentrales Digitalisierungsteam entwickelt mit mehreren Agents eine Anwendung für die Produktion: MES-Daten, SAP-Daten, Rückschreiben, mehrere externe APIs — produktiv in mehreren Werken.
- **Die Fragen:** Ist das IT oder Digitalisierung? · Wer trägt die technische, wer die fachliche Verantwortung? · Muss die klassische IT jeden Release freigeben? · Welche Security-Gates braucht es? · Wie sieht der Lifecycle aus?

SPEAKER: (Anhang — Referenz, nicht vortragen.)

---

## SLIDE 26

TYP: Cards
KICKER: Anhang · Übung 1 · Fall C
TITEL: Shadow-AI-Anwendung — geschäftskritisch, herrenlos
LEAD: Der Ursprung des heutigen Übungs-Falls — die vollständige Eskalationsstufe.

- **Sechs Monate später:** 14 Benutzer · 5 Schnittstellen · 3 Datenbanken · 2 externe AI-APIs · kein dokumentierter Owner · keine Tests · keine Backup-Strategie.
- **Der Status:** Die Anwendung ist inzwischen **geschäftskritisch**. Frage: Was macht die IT jetzt?

SPEAKER: (Anhang — Referenz, nicht vortragen.)

---

## SLIDE 27

TYP: Table
KICKER: Anhang · Übung 2
TITEL: Die ursprünglichen acht Entscheidungsdimensionen
LEAD: Referenz: die acht Dimensionen aus Übung 2 — für Gruppen, die in der Tiefe weiterarbeiten wollen.

| # | Dimension             | Leitfrage                                              |
|---|-----------------------|--------------------------------------------------------|
| 1 | **Agenten**           | Welche Agenten brauchen wir?                           |
| 2 | **Daten**             | Auf welche Daten dürfen sie zugreifen?                 |
| 3 | **Tools**             | Welche Systeme dürfen sie bedienen?                    |
| 4 | **Identity**          | Wie erhalten Agenten Identität & Berechtigungen?       |
| 5 | **Infrastruktur**     | On-Prem / Cloud / Hybrid?                              |
| 6 | **Governance**        | Wer darf neue Agenten bauen?                           |
| 7 | **Security**          | Was muss kontrolliert werden?                          |
| 8 | **Human-in-the-loop** | Bei welchen Entscheidungen muss ein Mensch freigeben?  |

SPEAKER: (Anhang — Referenz, nicht vortragen.)
