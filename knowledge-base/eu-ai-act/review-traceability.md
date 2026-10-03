# Rückverfolgbarkeit

Die Frage, die in jeder Prüfung gestellt und am seltensten beantwortet wird:

> **Welcher Stand war zu welchem Zeitpunkt in Betrieb, und wer hat auf welcher Grundlage entschieden?**

Sie ist nicht aus einem aktuellen Register beantwortbar. Sie braucht eine Geschichte.

## Warum der aktuelle Stand nicht genügt

Eine Prüfung interessiert sich für die Gegenwart nur am Rande. Die Fragen, die Arbeit machen, sind vergangenheitsbezogen:

| Frage | Braucht |
|---|---|
| Wie war dieses System im März eingestuft? | den Einstufungsverlauf |
| Welche Modellversion lief, als die Beschwerde einging? | den Änderungsverlauf |
| Wer hat die Inbetriebnahme freigegeben? | das Freigabeprotokoll mit Namen |
| Wann wurde die Kennzeichnung eingebaut? | Nachweis mit Produktversion |
| Wurde zwischenzeitlich geprüft? | die Reihe der Prüfprotokolle |

Jede dieser Fragen scheitert, wenn ein Eintrag **überschrieben** statt fortgeschrieben wurde. Das ist der häufigste und der vermeidbarste Mangel.

## Die Regel

**Nichts wird überschrieben. Nichts wird gelöscht.**

| Gegenstand | Statt überschreiben |
|---|---|
| Einstufung | neue Fassung, alte bleibt mit Datum stehen |
| Inventareintrag | Versionen behalten; abgeschaltet statt gelöscht |
| Nachweis | neuer Nachweis für die neue Version; der alte bleibt |
| Zuständigkeit | Wechsel mit Datum protokollieren |
| Prüfung | neue Prüfung, alte bleibt |

Das kostet Speicherplatz und spart in einer Prüfung Stunden. In einer Vorfallaufarbeitung kann es den Unterschied machen zwischen „wir können zeigen, dass die Einstufung zum Zeitpunkt des Vorfalls vertretbar war" und einer Rekonstruktion aus Erinnerungen.

## Die vier Spuren

### 1 Versionsspur

Welcher Systemstand war wann in Betrieb. Quelle ist der Änderungsverlauf.

**Zwei Versionen können auseinanderlaufen:** die eigene Produktversion und die Modellversion eines Zulieferers. Bleibt die eigene gleich und hat der Anbieter getauscht, ist das System ein anderes — und das gehört in den Verlauf, obwohl kein eigenes Release stattgefunden hat.

### 2 Entscheidungsspur

Wer hat was entschieden, wann, auf welcher Grundlage.

| Entscheidung | Mindestangaben |
|---|---|
| Einstufung | Person, Datum, Begründung, **Annahmen** |
| Freigabe zur Inbetriebnahme | Person, Datum, Version, offene Befunde |
| Berufung auf Art. 6 Abs. 3 | Person, Datum, Bewertung, Profiling-Frage |
| Weiterbetrieb mit offenem Befund | Person, Datum, Begründung |
| Abschaltung nach Art.-5-Treffer | Person, Datum, Alternativen |

Die vierte Zeile fehlt fast immer, und sie ist die interessanteste: Ein System läuft weiter, obwohl ein Befund offen ist. Das ist zulässig und muss eine **Entscheidung** sein, nicht ein Zustand, in den man hineingerutscht ist.

### 3 Prüfspur

Die Reihe der eigenen Prüfungen — **einschließlich der ohne Befund**.

Eine Zeile „geprüft am 14.5.2026, keine Änderung" ist ein Nachweis. Ein Register ohne solche Zeilen behauptet laufende Pflege; eines mit ihnen belegt sie.

Und die Spalte, die am meisten sagt: **bekannt geworden durch**. Steht dort über Monate nur „Zufall", fehlt kein Feld, sondern ein Verfahren — und genau das ist ein Befund, den eine Prüfung formulieren wird.

### 4 Nachweisspur

Welcher Nachweis gehört zu welcher Version. Mit dem Rückweg: Ein Nachweis, der durch eine neue Version ungültig wird, geht **zurück auf offen**.

Fehlt dieser Rückweg, veraltet das Register lautlos: Der Nachweis bleibt freigegeben, während das System drei Versionen weiter ist. In einer Prüfung ist das schlechter als ein offener Nachweis, weil es wie Erfüllung aussieht.

## Was ohne Fachanwendung machbar ist

Rückverfolgbarkeit klingt nach Software und ist zu großen Teilen Disziplin:

| Mittel | Leistet |
|---|---|
| Markdown im Repository | Versionsspur und Entscheidungsspur vollständig |
| Tabelle mit Spalten „gültig von / gültig bis" | Versionsspur |
| Protokolldatei, an die nur angefügt wird | Prüfspur |
| Ordnerstruktur je Version | Nachweisspur, mit Aufwand |

Der entscheidende Punkt ist nicht das Werkzeug, sondern die Regel: **Keine Zeile wird geändert, nur neue Zeilen kommen dazu.** Ein Tabellenblatt, in dem Werte überschrieben werden, erzeugt keine Spur — egal wie sorgfältig es gepflegt wird.

## Was die Aufsichtsspur betrifft

Für Art. 14 ist die Kennzahl über geänderte Ausgaben der einzige brauchbare Nachweis. Rückverfolgbar wird sie nur als **Reihe**: Ein einzelner Monatswert sagt nichts, zwölf Monatswerte zeigen, ob die Aufsicht nachgelassen hat.

Ein Verlauf, der von 40 auf 3 fällt, ist ein Befund — und zwar einer, den die Organisation selbst hätte finden sollen.

## Aufbewahrung

Die Verordnung sieht für verschiedene Unterlagen Aufbewahrungsfristen vor; die technische Dokumentation und Protokolle gehören dazu. Unabhängig von der Rechtsfrist gilt praktisch: **Solange ein Vorfall aus diesem Zeitraum noch aufgearbeitet werden könnte.**

Das spricht gegen Aufräumen. Die häufigste Ursache für fehlende Rückverfolgbarkeit ist nicht Nachlässigkeit, sondern jemand, der Ordnung geschaffen hat.

## Weiter

[Die Nachweismappe](./evidence-pack.md) · [Lücken schließen](./gap-remediation-logic.md)
