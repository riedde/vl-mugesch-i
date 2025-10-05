# Arbeitsanweisung: Quiz-Erstellung für LiaScript-Dateien

## Zielsetzung
Automatische Erstellung von fachlich angemessenen Quizzes am Ende von LiaScript-Kapiteldateien basierend auf einer Vorlage.

## Voraussetzungen
- Eine LiaScript-Datei mit fachlichem Inhalt liegt vor
- Eine Template-Datei (`template_quiz.md`) mit der gewünschten Quiz-Struktur existiert
- Der Benutzer möchte ein Quiz am Ende der Datei hinzufügen

## Arbeitsschritte

### 1. Analyse der Ausgangslage
- Template-Datei einlesen und Struktur verstehen
- Inhalt der Zieldatei analysieren (bereits im Kontext verfügbar)
- Hauptthemen und zentrale Konzepte identifizieren

### 2. Quiz-Entwicklung nach folgenden Kriterien

**Multiple-Choice-Fragen (4 Fragen):**
- **Schwierigkeitsgrad**: Mittleres Niveau - nicht erratbar ohne Textkenntnis, aber auch nicht zu abstrakt
- **Inhaltsfokus**: Zentrale Konzepte, wichtige Definitionen, charakteristische Merkmale
- **Vermeiden**: Reine Jahreszahlen, nebensächliche Details, zu spezifische Einzelheiten
- **Antwortoptionen**: 1-3 richtige Antworten pro Frage (entsprechend Template)

**Verständnisfrage:**
- Übergreifende Thematik, die verschiedene Aspekte des Kapitels verbindet
- Anforderung: 1-2 Seiten zusammenhängender Text
- Fokus auf Entwicklung, Bedeutung, Zusammenhänge

### 3. Technische Umsetzung
- Verwendung von `template_quiz.md` zum Anhängen des Quizzes
- Exakte Übernahme der LiaScript-Syntax aus dem Template
- Korrekte Markdown-Formatierung beibehalten

## Prompt-Vorlage für Wiederverwendung

```
Ich habe eine LiaScript-Datei. Diese soll am Ende um ein Quiz erweitert werden. Ich habe eine template-Datei erstellt, die vorgibt, wie das Quiz aufgebaut sein soll. Sie heißt template_quiz.md. Bitte hänge das Quiz am Ende der Datei an. 

Wichtig ist, dass die Multiple-Choice Fragen:
- Nicht so leicht sind, dass man die Lösung erraten kann ohne die Datei gelesen zu haben
- Aber auch keine zu schweren/abstrakten Fragen sind
- Nicht ausschließlich Jahreszahlen oder nebensächliche Details abfragen
- Die zentralen Konzepte des Kapitels abdecken

Solltest du weiteren Input brauchen, melde dich bitte.
```

## Qualitätskriterien für das Quiz

### Inhaltliche Qualität:
- ✅ Zentrale Fachbegriffe und Konzepte werden abgefragt
- ✅ Fragen erfordern Textverständnis, nicht nur Auswendiglernen
- ✅ Verschiedene Schwierigkeitsgrade innerhalb des mittleren Niveaus
- ✅ Verständnisfrage verbindet mehrere Kapitelaspekte

### Technische Qualität:
- ✅ Korrekte LiaScript-Syntax für Multiple-Choice
- ✅ Template-Struktur wird exakt übernommen
- ✅ Markdown-Formatierung ist konsistent
- ✅ Quiz wird am korrekten Dateiende eingefügt

## Anpassungen für verschiedene Fachbereiche
Diese Arbeitsanweisung ist für musikwissenschaftliche Inhalte optimiert, kann aber für andere Geisteswissenschaften adaptiert werden durch:
- Anpassung der Fragethemen an das jeweilige Fachgebiet
- Berücksichtigung fachspezifischer Terminologie
- Anpassung der Verständnisfrage an typische Denkweisen des Fachs

## Beispiel für gute Quiz-Fragen

### Gelungene Multiple-Choice-Frage:
```
**Welche beiden Hauptfunktionen erfüllt die Affektenlehre in der Musik des 17. und 18. Jahrhunderts?**

[[X]] ›affectus exprimere‹ (Gefühle ausdrücken): Darstellung von Affekten
[[ ]] ›musica speculativa‹: theoretische Durchdringung der Musik
[[X]] ›affectus movere‹ (Gefühle bewegen): Auslösung von Affekten bei den Zuhörern
[[ ]] ›ars combinatoria‹: mathematische Kombinationslehre
```

### Gelungene Verständnisfrage:
```
**Erläutern Sie die Entwicklung und Bedeutung der musikalischen Figurenlehre im 17. und 18. Jahrhundert. Gehen Sie dabei auf die Verbindung zur Rhetorik, wichtige Theoretiker und die heutige Forschungsposition ein.**
```

## Technische Hinweise
- Dateiname des Templates: `template_quiz.md`
- Tool für Bearbeitung: `replace_string_in_file`
- LiaScript-Syntax für Multiple-Choice: `[[X]]` für richtige, `[[ ]]` für falsche Antworten
- Immer am Ende der Datei anhängen, nicht ersetzen