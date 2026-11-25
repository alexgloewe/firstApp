---
name: fristen-verwaltungsrecht
description: Berechnet und prüft Fristen im Verwaltungsverfahren und Verwaltungsprozess (Bekanntgabe nach § 41 VwVfG, Widerspruchsfrist § 70 VwGO, Klagefrist § 74 VwGO, Jahresfrist § 58 Abs. 2 VwGO, Untätigkeitsklage § 75 VwGO, Wiedereinsetzung § 60 VwGO / § 32 VwVfG). Verwenden, wenn ein Bescheid, Widerspruchsbescheid oder Urteil eingegangen ist und das Fristende bestimmt werden muss oder eine Frist möglicherweise versäumt wurde.
---

# Fristen im Verwaltungsrecht

## Zuerst erfragen

- Bundesland und erlassende Behörde (Bundes- oder Landesbehörde, Kommune)
- Art des Schriftstücks (Bescheid, Widerspruchsbescheid, Urteil, Beschluss)
- **Art der Bekanntgabe**: einfacher Brief, Postzustellungsurkunde (PZU),
  Einschreiben, elektronisch, gegen Empfangsbekenntnis, öffentliche Bekanntgabe
- Datum der Aufgabe zur Post (Absendevermerk) bzw. Zustellungsdatum
- Wortlaut der Rechtsbehelfsbelehrung

Fehlt eine Angabe, wird die Berechnung mit der ungünstigsten Annahme durchgeführt
und das ausdrücklich gekennzeichnet.

## Normtext holen

Vor der Berechnung den aktuellen Wortlaut prüfen:
- VwGO §§ 57, 58, 60, 70, 74, 75 – https://www.gesetze-im-internet.de/vwgo/
- VwVfG §§ 31, 32, 41 – https://www.gesetze-im-internet.de/vwvfg/
- VwZG § 4, § 5 (Bundesbehörden); bei Landesbehörden das Landeszustellungsgesetz
- ZPO § 222, BGB §§ 187–193

**Bekanntgabefiktion:** § 41 Abs. 2 VwVfG (Bund) fingiert seit dem 1.1.2025 die
Bekanntgabe am **vierten** Tag nach Aufgabe zur Post (vorher: dritter Tag).
Ob das Landes-VwVfG dynamisch auf das Bundesrecht verweist oder einen eigenen,
ggf. noch nicht angepassten Wortlaut hat, ist **für jedes Land gesondert zu
prüfen**. Entsprechendes gilt für § 4 VwZG und die Landeszustellungsgesetze.

## Berechnungsschema

1. **Fristbeginn (Ereignis)** bestimmen: Bekanntgabe/Zustellung.
2. Ereignistag zählt nicht mit (§ 57 Abs. 2 VwGO i. V. m. § 222 Abs. 1 ZPO,
   § 187 Abs. 1 BGB).
3. Monatsfrist endet mit Ablauf des Tages des Folgemonats, der durch seine Zahl
   dem Ereignistag entspricht; fehlt er, am letzten Tag des Monats
   (§ 188 Abs. 2 und 3 BGB).
4. Fällt das Ende auf Samstag, Sonntag oder einen **am Gerichtsort** gesetzlichen
   Feiertag, endet die Frist mit Ablauf des nächsten Werktags (§ 222 Abs. 2 ZPO).
   Bei einer Bekanntgabefiktion ist umstritten bzw. landesrechtlich verschieden,
   ob der fingierte Bekanntgabetag selbst verschoben wird – im Zweifel nicht
   verschieben und das frühere Ende ansetzen.
5. Ergebnis mit Wochentag angeben und eine **Vorfrist** (in der Regel eine Woche
   vorher) vorschlagen.

## Fristenübersicht (Wortlaut stets verifizieren)

| Situation | Frist | Norm |
|---|---|---|
| Widerspruch | 1 Monat ab Bekanntgabe | § 70 Abs. 1 VwGO |
| Anfechtungs-/Verpflichtungsklage nach Vorverfahren | 1 Monat ab Zustellung des Widerspruchsbescheids | § 74 Abs. 1 S. 1, Abs. 2 VwGO |
| Klage ohne Vorverfahren | 1 Monat ab Bekanntgabe des VA | § 74 Abs. 1 S. 2 VwGO |
| fehlende oder unrichtige Rechtsbehelfsbelehrung | 1 Jahr (Ausnahmen in § 58 Abs. 2 S. 1 Hs. 2) | § 58 Abs. 2 VwGO |
| Untätigkeitsklage | grundsätzlich nicht vor Ablauf von 3 Monaten | § 75 VwGO |
| Wiedereinsetzung (gerichtlich) | 2 Wochen nach Wegfall des Hindernisses; versäumte Handlung nachholen; Ausschluss nach 1 Jahr | § 60 Abs. 2, 3 VwGO |
| Wiedereinsetzung (behördlich) | 2 Wochen; Ausschluss nach 1 Jahr | § 32 VwVfG |

Rechtsmittelfristen (Berufungszulassung, Beschwerde): siehe Skill `rechtsmittel-vwgo`.

## Rechtsbehelfsbelehrung prüfen

Unrichtig ist eine Belehrung insbesondere, wenn sie Rechtsbehelf, Behörde oder
Gericht mit Sitz, oder Frist nicht oder falsch nennt, oder wenn sie zusätzliche
Anforderungen suggeriert, die das Gesetz nicht vorsieht und die geeignet sind,
die Einlegung zu erschweren. Ob ein konkreter Fehler die Jahresfrist auslöst,
ist anhand aktueller Rechtsprechung zu belegen – kein Ergebnis ohne Nachweis.

## Ausgabeformat

```
Fristart:            …
Auslösendes Ereignis: … (Datum, Wochentag; Grundlage: …)
Rechenweg:           …
Fristende:           TT.MM.JJJJ (Wochentag), 24:00 Uhr
Vorfrist:            TT.MM.JJJJ
Annahmen/Risiken:    …
Zu prüfen:           Landesrecht …, Zustellnachweis …
```

Bei bereits abgelaufener Frist sofort Wiedereinsetzung (Gründe, Glaubhaftmachung,
Nachholung binnen der Antragsfrist) und das Vorliegen der Jahresfrist prüfen.
