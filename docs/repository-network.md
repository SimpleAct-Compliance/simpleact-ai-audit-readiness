# Das Netz der Repositories

Dieses Repository kommt **zuletzt**. Es erzeugt keinen Zustand, sondern prüft, ob der erreichte Zustand vorzeigbar ist.

## Der Weg

```
  Inventar -> Einstufung -> Prüfung -> Dokumentation -> [Audit] -> Betrieb
```

| Richtung | Repository | Liefert hierfür |
|---|---|---|
| vorher | [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) | Einträge, Modell und Version, **Suchprotokoll** |
| vorher | [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) | Zusagen mit Fundstelle, AVV, Unterauftragsverarbeiter |
| vorher | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) | Klasse mit Begründung, Annahmen, Verlauf |
| vorher | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) | Nachweiszustände, Prüfprotokolle, Befunde |
| vorher | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) | Anhang IV, Änderungsverlauf |
| vorher | [Vorlagensammlung](https://github.com/SimpleAct-Compliance/simpleact-ai-act-templates) | Praktikenprüfung, Schulungs- und Kennzeichnungsnachweis, Nachweisregister |
| daneben | [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) | Vorfallregister, Meldungen |

Das **Suchprotokoll** aus dem Inventar ist der wichtigste Einzelbeitrag: Es beantwortet die erste Frage jeder Prüfung mit einem Beleg statt mit einer Behauptung — und es lässt sich nachträglich nur als Momentaufnahme erzeugen.

## Abgrenzung zur Prüfliste

Die beiden werden verwechselt:

| | Prüfliste AI Act | dieses Repository |
|---|---|---|
| Frage | Ist der Zustand erreicht? | Ist er vorzeigbar? |
| Anlass | vor Inbetriebnahme, im Turnus | eine Prüfung steht an, oder vierteljährlich |
| Ergebnis | Befunde über den Zustand | Lücken in Nachweis und Ablage |
| Typischer Fund | eine Pflicht ist nicht erfüllt | eine Pflicht ist erfüllt, aber nicht belegbar |

Die letzte Zeile ist der Unterschied. Wer mit der Audit-Vorbereitung beginnt, weil ein Termin ansteht, findet Lücken in Zuständen, die er dann in zwei Wochen nicht mehr herstellen kann — und schreibt Unterlagen, die als Nachweise vorgelegt werden. Das fällt auf.

## Übergreifend

| Repository | Wofür |
|---|---|
| [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) | wie alle Teile zusammenhängen |
| [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook) | wer prüft, wer freigibt, wer eskaliert |
| [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) | wenn Kunden die Prüfer sind |
| [Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis) | Export von Registern und Protokollen |

Das SaaS-Repository ist für die wahrscheinlichste Prüfungslage relevant: Für Softwareanbieter kommt die erste Prüfung von einem Kunden, und die Antwortseite auf die vier Beschaffungsfragen steht dort.

## Datenschutzseite — der wahrscheinlichere Prüfungsgegenstand

Datenschutzaufsichten prüfen seit Jahren, KI-Marktüberwachung wird gerade aufgebaut. Eine Nachweismappe ohne diese Abschnitte deckt das wahrscheinlichere Szenario nicht ab.

| Repository | Liefert |
|---|---|
| [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) | Verarbeitungsverzeichnis, Rechtsgrundlagen, Betroffenenrechte, TOMs |
| [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) | Art. 35 DSGVO und Art. 27 AI Act, getrennt |
| [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) | Register und Fristnachweis, 72 Stunden ab Kenntnis |

## Tarifgenaue Anbieterangaben

Für die Abschnitte zu Modellanbietern und ihren Zusagen: ein öffentliches Register mit tarifgenauen Angaben, jede mit Quelle und Prüfdatum — **[actcomp.de](https://actcomp.de)**

Es erspart die Recherche, nicht den Nachweis: Der Beleg bleibt die Fundstelle in den eigenen Vertragsunterlagen.
