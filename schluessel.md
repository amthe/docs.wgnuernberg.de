---
title: Schlüssel
parent: Wohnen
has_children: false
type: intent
---

{% if {{ page.type }} == intent %}
  Nur Intents
{% endif %}

# Schlüssel

Du bekommst von uns drei normale mechanischen Schlüssel und zwei elektronische Transponder (Chips). Durch die Kombination aus mechanischen Schlüsseln und elektromechanischen Schlüsseln hast du die minimalen Kosten im Fall eines Schlüsselverlustes und den höchsten Komfort.

## Schlüsselverlust und Schlüsselbeschädigungen

Wenn du einen **mechanischen Schlüssel** verlierst oder beschädigst, musst du diesen in einem Schlüsselladen nachmachen lassen. Das kostet dich nur noch ca. 10 Euro. Früher kostete ein verlorener Schlüssel ca. 200 Euro.
Schlüsselverluste wie z.B. bei Wohnungsschlüsseln oder Arbeitsschlüsseln sind sehr teuer.

Wenn du einen **elektronischen Schlüssel** verlierst oder beschädigst, kostet die Programmierung eines neuen Schlüssels bis ca. 100 Euro.

```markdown
## intent:schluesselverlust_schluesselbeschaedigung
- Was kostet es einen Schlüssel zu verlieren?
- Was kostet ein Schlüsselverlust?
- Mein Schlüssel funktioniert nicht mehr richtig.
- Mein Schlüssel ist kaputt.
- Ich habe einen Schlüssel verloren.
```

## Ausgesperrt

Wir geben die Schlüssel bei Mietbeginn aus, und nehmen sie bei Mietende zurück. Wenn du dich aussperrst dann können wir als Mietverwaltung nichts machen. Für dein Zimmer haben wir keinen Schlüssel. Wir können dir auch im Notfall nicht aufsperren.

Du hast dich aus der WG ausgesperrt:
- Kannst du einen Mitbewohner anrufen ob er dir jetzt oder später die WG aufsperren kann?
- Kannst du bei einem Freund, in einer anderen WG oder in einem Hotel übernachten?
- Werktags von 10:00-15:00 Uhr kannst du probieren ob jemand aus dem Büro dir freundlicherweise die WG aufsperren kann.
- Ist der letzte Ausweg wirklich nur einen Schlüsseldienst zu rufen?

```markdown
## intent:ausgesperrt
- Ich habe mich ausgesperrt.
- Ich komme nicht mehr in die WG rein.
- Ich komme nicht mehr in mein Zimmer rein.
```

## Batteriewarnung

Du bist verpflichtet auf das Schließverhalten der elektronischen Türschlösser zu achten. Es kann sonst, sollte die Batterie leer werden, die ganze WG oder das ganze Haus ausgesperrt werden. Bitte melde uns sobald es eine Verzögerung beim Schließverhalten der Tür gibt, die Tür piept oder mehrmals Rot blinkt.

```markdown
## intent:batteriewarnung
- Der Zylinder piept.
- Der Schlüssel sperrt nur noch langsam.
```

## Schlüsseldienst

Unsere Empfehlung ist Meusel und Beck (0911/94481-0). Meusel und Beck öffnet dir die Türe ohne größere Schäden anzurichten. Andere Schlüsseldienste bringen dich zwar wieder in dein Zimmer, verursachen dabei aber hohe Sachschäden. Ein Schlüsseldienst hält den Rekord mit einem vierstelligen Sachschaden.

```markdown
## intent:schluesseldienst
- Ich brauche einen Schlüsseldienst.
- Könnt Ihr mir einen Schlüsseldienst empfehlen?
```