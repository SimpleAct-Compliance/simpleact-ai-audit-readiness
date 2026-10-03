# Audit-Vorbereitung

**Eine Prüfung fragt nicht, ob Sie etwas haben. Sie fragt, ob Sie es zeigen können — und wie lange das dauert.**

Dieses Repository behandelt den Unterschied zwischen einem erreichten Zustand und einem vorzeigbaren. Beides fällt auseinander, und zwar an vorhersehbaren Stellen.

*The difference between a state you have reached and one you can show: evidence packs, traceability, and an honest account of what a readiness score does not measure.*

---

## Die vier Fragen, an denen es scheitert

| Frage der Prüfung | Woran sie scheitert |
|---|---|
| „Zeigen Sie mir alle KI-Systeme." | das Register ist unvollständig, und die Suche ist nicht belegt |
| „Wie war dieses System im März eingestuft?" | die alte Einstufung wurde überschrieben |
| „Zeigen Sie mir den Nachweis für die Kennzeichnung." | er existiert, liegt aber in einem Postfach |
| „Wer hat das entschieden?" | im Feld steht eine Abteilung |

Keine dieser vier Lücken ist eine Wissenslücke. Alle vier entstehen aus der Art, wie Unterlagen abgelegt werden.

## Was eine Prüfung tatsächlich verlangt

Nicht Vollständigkeit. Drei andere Dinge:

**Zuordenbarkeit.** Jeder Nachweis gehört zu einer Pflicht, einem System und einer **Version**. Ohne Version belegt er einen Zeitpunkt, nicht einen Zustand.

**Rückverfolgbarkeit.** Welcher Stand war wann in Betrieb, wer hat was entschieden, und auf welcher Grundlage. Das ist die Frage, die am häufigsten gestellt und am seltensten beantwortet wird.

**Vorlegbarkeit.** Ein Nachweis, der nicht in annehmbarer Zeit auffindbar ist, existiert — vorliegen tut er nicht.

Ausführlich: [Die Nachweismappe](./knowledge-base/eu-ai-act/evidence-pack.md) · [Rückverfolgbarkeit](./knowledge-base/eu-ai-act/review-traceability.md)

## Die Probe, die zehn Minuten kostet

Jemand, der nicht beteiligt war, fordert drei Nachweise an. Die Zeit wird gemessen.

| Dauer | Befund |
|---|---|
| unter 15 Minuten | vorlegbar |
| bis zu einer Stunde | vorlegbar, mit Aufwand |
| **über eine Stunde** | **in einer echten Prüfung nicht vorlegbar** |
| nicht gefunden | Lücke, unabhängig davon ob der Nachweis existiert |

Diese Probe sagt mehr über die Prüfungsfestigkeit als jede Vollständigkeitszählung — und sie ist die einzige Maßnahme in diesem Repository, die man vor dem Mittagessen erledigen kann.

## Was ein Reifegrad nicht misst

Ein Audit-Reifegrad, der aus Vollständigkeitssignalen berechnet wird, misst, **wie viel erfasst ist** — nicht, **wie richtig es ist**.

| Was er zeigt | Was er nicht zeigt |
|---|---|
| wie viele Einträge Felder gefüllt haben | ob die Einstufungen stimmen |
| wie viele Nachweise abgelegt sind | ob sie die Pflicht belegen, die sie belegen sollen |
| wie viele Pflichten zugewiesen sind | ob die Zuständigen die Zeit haben |

Er ist ein **Fortschrittsmaß**, kein Prüfungsergebnis. Eine Organisation mit 85 % Reifegrad und falschen Einstufungen steht schlechter da als eine mit 60 % und richtigen. Das gehört gesagt, weil solche Zahlen in Vorlagen für die Geschäftsführung landen.

Ausführlich: [Reifegrad](./knowledge-base/eu-ai-act/audit-readiness-score.md)

## Lücken sind das Ergebnis, nicht der Mangel

Eine Vorbereitung ohne Lückenliste ist keine Vorbereitung. Und eine benannte Lücke mit Person, Termin und Grund ist in einer Prüfung **besser** als ein Abschnitt mit Füllsätzen: Füllsätze fallen auf und stellen den Rest in Frage.

Ausführlich: [Lücken schließen](./knowledge-base/eu-ai-act/gap-remediation-logic.md)

## Wer eigentlich prüft

| Prüfende Stelle | Grundlage | Wahrscheinlichkeit |
|---|---|---|
| **Kunde im Beschaffungsgespräch** | Vertrag, eigene Pflichten | hoch, und zuerst |
| **Datenschutzaufsicht** | DSGVO | mittel; prüft seit Jahren |
| Marktüberwachung | AI Act | derzeit gering; neu aufgebaut |
| Wirtschaftsprüfer, Zertifizierer | Auftrag | je nach Branche |
| interne Revision | Auftrag | je nach Größe |

Die erste Zeile wird unterschätzt und ist die häufigste: Geschäftskunden mit eigenen Pflichten holen die Angaben bei Ihnen, und zwar bevor eine Behörde fragt.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Was wann gilt](./knowledge-base/eu-ai-act/overview.md) | welche Pflicht heute prüfbar ist |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | Nachweis, Zuordenbarkeit, Vorlegbarkeit, Reifegrad |
| [Wer prüft was](./knowledge-base/eu-ai-act/scope-and-actors.md) | Prüfende Stellen, Rolle, Zuständigkeit |
| [Was je Klasse verlangt wird](./knowledge-base/eu-ai-act/risk-logic.md) | Nachweise je Risikoklasse |
| [Die Nachweismappe](./knowledge-base/eu-ai-act/evidence-pack.md) | Aufbau, was hinein- und was nicht hineingehört |
| [Rückverfolgbarkeit](./knowledge-base/eu-ai-act/review-traceability.md) | welcher Stand war wann, wer hat entschieden |
| [Lücken schließen](./knowledge-base/eu-ai-act/gap-remediation-logic.md) | priorisieren, zuweisen, nachhalten |
| [Reifegrad](./knowledge-base/eu-ai-act/audit-readiness-score.md) | was er misst und was nicht |
| [Woher die Nachweise kommen](./knowledge-base/eu-ai-act/inventory-and-governance.md) | Register, Zuständigkeit, Ablage |

### Vorlagen

| Vorlage | Zweck |
|---|---|
| [Audit-Vorbereitung](./templates/audit-readiness-checklist.md) | durchgehen, bevor eine Prüfung ansteht |
| [Lückenprotokoll](./templates/evidence-gap-log.md) | je Lücke: Grund, Person, Termin, Risiko |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Davor

- [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) — der Zustand selbst
- [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) — ohne Register prüft man Stichproben
- [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) — Anhang IV
- [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) — der Zusammenhang

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt Nachweise mit Versionsbezug, Freigabezuständen und Prüfprotokoll und erzeugt exportierbare Nachweispakete: **[Audit Playbook](https://simpleact.de/audit-playbook)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
