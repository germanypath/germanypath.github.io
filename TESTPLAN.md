# Nachfrage-Test Deutschland-Lotse

**Ziel:** In 4 Wochen herausfinden, ob Menschen wirklich **Geld** für den Ratgeber zahlen. „Interessant“ zählt nicht, nur Vorbestellungen mit Zahlung.

Der Ratgeber existiert noch nicht. Wir verkaufen ihn **vorab**, mit festem Liefertermin und dem Versprechen: Wird er nicht geliefert, gibt es das Geld zurück. Geschrieben wird er erst, wenn der Test erfolgreich ist.

## Angebot
- **Produkt:** „Guide Allemagne 2027“, ein PDF auf Französisch mit Checklisten und Vorlagen (Inhalt siehe [index.html](index.html))
- **Preis:** Einführungspreis 5.000 FCFA statt 10.000 FCFA (zum Vergleich: ein E-Book der Konkurrenz kostet etwa 14 $, also rund 8.500 FCFA)
- **Liefertermin:** spätestens 31.01.2027
- **Bezahlung im Test:** Per MTN MoMo oder Orange Money an eine Nummer der Familie in Kamerun. Wir binden noch keinen Zahlungsanbieter an.

## Ablauf
1. Du klickst auf der Seite auf „Je réserve“. Daraufhin öffnet sich WhatsApp mit einer fertigen Nachricht samt Code für den Kanal (z. B. `FB1`).
2. Du (oder deine Frau) antwortest mit den Zahlungsdaten.
3. Jede Zahlung wird in einer Liste notiert: Datum, Kanal-Code, Betrag und das Land der Person.
4. „Pas encore prêt“ bedeutet: Die Person möchte nur informiert werden. Das wird getrennt gezählt.

## Webseite
Markenname: **GermanyPath**. Die Seite gibt es auf Französisch (`/fr/`) und Englisch (`/en/`). Die Startseite wählt die Sprache automatisch nach der Spracheinstellung des Handys.
Gezählt wird pro Sprache getrennt, an der WhatsApp-Nachricht erkennbar („Bonjour…“ oder „Hello…“).

## Kanäle und Codes
Die Seite liest den Code aus der Adresse aus. Beispiel: `.../fr/?src=FB1` schreibt „FB1“ in die WhatsApp-Nachricht.

| Code | Kanal |
|---|---|
| FB1, FB2 … | Facebook-Gruppen (je Gruppe ein eigener Code) |
| WA | WhatsApp-Status und Gruppen der Familie |
| TT | TikTok |
| DIR | ohne Code (direkt) |

## Erfolgskriterien (vorher festgelegt, nachträglich nicht ändern)
| Ergebnis nach 4 Wochen | Entscheidung |
|---|---|
| **30 oder mehr bezahlte Vorbestellungen** | Weitermachen: Ratgeber schreiben, Businessplan-Seite bauen, Entscheidung mit der Familie |
| 10 bis 29 | Unklar: Angebot oder Preis einmal anpassen und 2 Wochen nachtesten |
| unter 10 | **Stoppen.** Das Geld zurückzahlen, falls kein Ratgeber kommt |

## Was du dafür tun musst (einmalig)
1. In `index.html` die Platzhalter ersetzen: WhatsApp-Nummer (`NUMMER_HIER`) und das Impressum (`impressum.html`).
2. Die Seite veröffentlichen, zum Beispiel über GitHub Pages wie beim Kwata-Projekt. **Das machen wir gemeinsam, erst nach deinem Ja.**
3. Die Texte aus [POSTS.md](POSTS.md) in Facebook-Gruppen, im WhatsApp-Status und in den Gruppen der Familie posten. Am besten zwei- bis dreimal pro Woche.

## Kosten des Tests
Fast null: GitHub Pages ist kostenlos, WhatsApp auch. Optional kommt Facebook-Werbung für 20 bis 50 € dazu, falls die kostenlosen Kanäle zu wenig bringen.
