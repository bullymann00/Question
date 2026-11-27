---
name: question
description: Beantwortet Uni-/Lernfragen ausführlich und anschaulich mit einem nachvollziehbaren Lösungsweg, den der Nutzer mit seinem eigenen Weg abgleichen kann. Immer verwenden, wenn der Prompt "/question" enthält, egal an welcher Stelle, auch wenn nur eine Aufgabe, eine Frage oder ein eigener Lösungsansatz folgt. Gilt nur für die eine Antwort auf genau diesen Prompt, nicht für den restlichen Chat.
---

# /question – ausführliche, anschauliche Antwort

Der Nutzer stellt eine Frage und schreibt `/question` in den Prompt. Er will eine
vollständige, gut verständliche Antwort, mit der er seinen eigenen Lösungsweg
abgleichen kann.

## Geltungsbereich: nur diese eine Antwort

Der Skill gilt ausschließlich für die Antwort auf den Prompt, der `/question`
enthält. Schon die nächste Nachricht ohne `/question` beantwortest du wieder ganz
normal, ohne feste Struktur, ohne Vertiefungsfragen und ohne den Skill-Stil
weiterzuführen. Auch wenn die Folgefrage zum selben Thema gehört: Nur wenn der
Nutzer erneut `/question` schreibt, greift der Skill wieder. So bleibt der Nutzer
in jeder Nachricht selbst entscheidend dafür, wie ausführlich die Antwort wird.

## Vorgehen

1. **Kontext auswerten, nicht nachfragen.** Alles, was im Prompt oder im bisherigen
   Chat steht (Aufgabe, Zwischenergebnisse, eigener Ansatz), ist bereits die Antwort
   auf mögliche Rückfragen. Stelle deshalb keine Klärungsfragen. Ist etwas wirklich
   mehrdeutig, wähle die wahrscheinlichste Lesart und sage in einem Satz, welche du
   genommen hast.
2. **Antworte auf Deutsch**, als normaler Chat-Text.
3. **Gib einen nummerierten Lösungsweg**, in kleinen, einzeln nachvollziehbaren
   Schritten, zu jedem Schritt kurz *was* passiert und *warum*.
   Beispiel für das gewünschte Format bei `1+1+3`:
   - Schritt 1: 1 + 1 = 2
   - Schritt 2: 2 + 3 = 5
   - Ergebnis: **5**
4. **Gleiche mit dem Nutzerweg ab**, falls er einen eigenen Ansatz oder ein Ergebnis
   genannt hat: Stimmt das Ergebnis? Wo deckt sich sein Weg mit deinem, wo weicht er
   ab, und ist die Abweichung ein Fehler oder nur ein anderer gültiger Weg? Nenne
   Abweichungen konkret und freundlich, ohne das Ergebnis zu verschweigen.
5. **Erkläre am konkreten Beispiel zuerst.** Der Nutzer lernt visuell und über
   Beispiele: Zeige das Konzept erst an einem konkreten Fall, dann die allgemeine
   Regel. Analogien müssen nah am Thema bleiben, keine weit hergeholten Vergleiche.
6. **Visualisiere, wenn es dem Verständnis hilft:** Tabellen, ASCII-/Textdiagramme,
   Pfeile, Mermaid-Diagramme, Rechenbäume, Zeitstrahlen. Nur einsetzen, wo sie
   wirklich etwas klarer machen, nicht als Dekoration.
7. **Schließe mit 1–2 kurzen Vertiefungsfragen** ("Zum Üben"), ohne die Lösung
   mitzuliefern. Der Nutzer soll selbst nachdenken. Diese Fragen sind optional und
   ersetzen keine inhaltliche Antwort: Die eigentliche Frage wird immer zuerst
   vollständig beantwortet.

## Struktur der Antwort

```
## Kurzantwort
(1–2 Sätze mit dem Ergebnis)

## Lösungsweg
1. …
2. …

## Abgleich mit deinem Weg
(nur wenn ein eigener Ansatz genannt wurde)

## Veranschaulichung
(Tabelle / Diagramm / konkretes Beispiel)

## Zum Vertiefen
- Frage 1
```

Passe die Struktur an die Frage an: Bei einer reinen Verständnisfrage entfällt der
Abgleich, bei einer reinen Rechenaufgabe darf die Veranschaulichung kurz sein.
