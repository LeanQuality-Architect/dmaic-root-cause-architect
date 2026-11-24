# DMAIC Root-Cause Architect (Claude Skill)

Ein kompromissloser, streng daten- und faktenbasierter Problemlösungs-Skill für **Claude (Desktop, Web & Claude Code)**. Er kombiniert klassische Methoden des Qualitätsmanagements zu einer lückenlosen Audit-State-Machine nach der Formel **$Y = f(X)$**.

## Methoden-Architektur
1. **DEFINE (Phase 0):** Messbare Soll/Ist-Abweichung ($Y$) und scharfe **IS / IS-NOT**-Abgrenzung.
2. **MEASURE (Phase 1):** Messsystem-Analyse (**MSA / %GRR**) und statistische Baseline ($n$, $C_{pk}$) zur Vermeidung von Scheinkorrelationen.
3. **ANALYZE (Phase 2):** Kontextangepasstes **6M-Ishikawa** (Produktion, IT, Verwaltung) mit strikter Trennung in `[FAKT]` vs. `[HYPOTHESE]` sowie **5-Why-Tiefenbohrung** inklusive **Rückwärtsprüfung ("Deshalb-Probe")** und **Gegenbeweis-Check (Falsifikation)**.
4. **IMPROVE (Phase 3):** **Morphologischer Kasten** zur systematischen Entwicklung kreativer und technischer Lösungsbausteine.
5. **CONTROL (Phase 4):** **Poka-Yoke-Härtung** (technische Zwangsführung statt weicher Schulungen), **Control Plan**, **strenge FMEA-Rückkopplung ($S / O / D$)** und automatisches **A3-Abschlussprotokoll**.

## Eingebaute Schutz-Gates
* **Lösungsverbot:** Blockiert vorzeitige Lösungsvorschläge in den Analysephasen (Phase 0–2).
* **Floskel-Blacklist:** Weist menschliches Versagen (*"Unachtsamkeit"*, *"Schulung"*, *"besser aufpassen"*) als Symptom zurück.
* **Privacy-Gate:** Erzwingt anonymisierte Rollen statt Klarnamen und schützt vor der Eingabe vertraulicher Betriebsgeheimnisse.

## Installation in Claude
1. Lade die Dateien `SKILL.md`, `6M_KATALOG.md` und `A3_PROTOKOLL_VORLAGE.md` herunter.
2. Ziehe alle drei Dateien in einen neuen Chat in **Claude Desktop / Web** und schreibe:
   > *"Erstelle aus diesen drei Dateien den Skill `dmaic-root-cause-architect` inklusive Anhang A und Anhang B und zeige mir die Speichern-Karte."*
3. Klicke in der Karte auf **Speichern**.
4. Starte jederzeit eine Analyse mit dem Befehl `/dmaic-root-cause-architect`.

## Haftungsausschluss (Disclaimer)
Dieses Tool dient ausschließlich der methodischen Strukturierung von Problemanalysen und Workshops. Es ersetzt keine ingenieurtechnische Prüfung, Sicherheitsabnahme oder normative/rechtliche Freigabe (z. B. nach IATF 16949, ISO 9001 oder Maschinenrichtlinie). Die Verantwortung für die fachliche Richtigkeit und Umsetzung der abgeleiteten Maßnahmen liegt allein beim Anwender.

## Lizenz
Veröffentlicht unter der **MIT-Lizenz** (Copyright 2026 LeanQuality-Architect).
