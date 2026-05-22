# Projektübersicht

Dieses Projekt dient als strukturierter Arbeitsraum fuer eine eigenstaendige Novelle mit biologisch und physikalisch begruendetem Power-System.

Externe Inspirationsbegriffe sind keine In-World-Namen und keine Kanonbeschreibung.

Die Dateien enthalten Vorlagen, Arbeitsbereiche und Review-Raster. Story-Inhalte, Figuren, Faehigkeiten, Regeln und Lore werden erst eingetragen, wenn sie bewusst entschieden und in der Story-Bibel dokumentiert wurden.

## Workflow

1. Grundidee in der Story-Bibel erfassen.
2. Regeln, Kanon und wissenschaftliche Annahmen dokumentieren.
3. Plotstruktur entwickeln.
4. Kapitel planen.
5. Szenen nach Template schreiben.
6. Reviews durchfuehren.
7. Aenderungen in Bibel, Plot und Drafts synchronisieren.

## Subagents

Die globalen Projektregeln stehen in `AGENTS.md`. Ausfuehrbare Codex-Subagents liegen in `.agents/` und haben klar getrennte Verantwortlichkeiten:

- `plot-architect.toml`: Plotstruktur, Konflikte und Kapitelplanung.
- `writer.toml`: Draft-Arbeit auf Basis freigegebener Vorgaben.
- `continuity-reviewer.toml`: Kanon, Timeline und Widerspruchspruefung.
- `science-reviewer.toml`: biologische Plausibilitaet und interne wissenschaftliche Logik.
- `final-reviewer.toml`: abschliessende Gesamtpruefung.

Alle Subagents arbeiten mit `bible/`, `plotting/`, `drafts/`, `reviews/` und `notes/`.

## Schreibprozess

Jede Szene wird vor dem Schreiben auf vier Punkte geprueft:

- Ziel
- Hindernis
- Entscheidung
- Konsequenz

Der Plot hat Vorrang vor Lore-Dumping. Hintergrundinformationen werden nur eingesetzt, wenn sie Szene, Konflikt oder Entscheidung tragen.

## Reviewprozess

Reviews werden in den Dateien im Ordner `reviews/` dokumentiert. Jedes Problem wird mit Severity, Problem, Ursache, Auswirkung und Loesung erfasst.

Review-Ergebnisse werden erst umgesetzt, wenn klar ist, welche Aenderung am Kanon, Plot oder Draft notwendig ist.
