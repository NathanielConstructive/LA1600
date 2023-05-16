# Projekt-Dokumentation



Blackberry - Müller, Özden, Meier

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 11.05 | 0.0.1   | Erster Prototyp der Website. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt machen wir eine Rezept-Website über verschiedene Gerichte und wann diese am besten schmecken.
Wir charakterisieren dabei ein Gericht genauer und schreiben eine Rezeptidee (inklusive ToDo-Liste) für dieses. 


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |    muss             | Qualität     | Als ein Benutzer möchte ich eine Todoliste, damit ich weiss welche Zutaten ich noch für mein Gericht brauche. |
| 2  |    kann             | Funktionslität     | Als ein Benutzer möchte ich nach Rezepten filtern können, damit ich nach Kriterien Gerichte aussuchen kann.                                   |
|3    |   kann                | Qualität    |    Als Benutzer möchte ich Gerichte je nach Tageszeit auswählen, damit bessere Gerichte für jetzt finden kann.|
|4    |  kann                 | Qualität      |  Als Benutzer möchte ich die Sprache ändern können, damit wenn ich schlechtes Deutsch spreche, ich auf Englisch wechseln kann.                                  |
|5    |  muss                 | Funktionalität      | Als Benutzer möchte ich eine TodoListe haben die mir die Schritte sagt, die ich für das Gericht befolgen muss, damit wenn ich ein Gericht zubereiten möchte, welches ich nicht kenne, ich es trotzdem kochen oder backen kann.                |
|6    |muss|Funkional|Als Benutzer möchte ich, dass ich auf die Gerichte klicken kann, damit ich zu einer Seite weitergeleitet werde, wo ich eine TodoListe sehe zu den Zutaten und Schritten|
|7  |kann|Qualität|Als Benutzer möchte ich, dass wenn ich auf die Gerichte klicke, es mir genauere Infos über das Gericht gibt, zum Beispiel woher es genau kommt und für was es bekannt ist.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Eine Tageszeit wurde Ausgewählt| Ein Gericht wird angeklickt | Es wird angezeigt, welche Zutaten noch benötigt werden |
| 1.2  | Es wurde ein Gericht ausgewählt | Das Kästchen neben einer Zutat wird angeklickt | Im kästchen erscheint ein Häckchen |
| 2.2  | Es wurde eine Tageszeit ausgewählt | Es wird unter "Filter" ein Element angeklickt | Es erscheinen nur Gerichte, die dem Filter entsprechen |
| 3.1  | Die Webseite wurde geöffnet | keine | Es wird eine Liste Mit 3 Tageszeiten angezeigt |
| 3.2  | Die Webseite wurde geöffnet | Eine Tageszeit wird angeklickt | Es werden Passende Rezepte angezeigt |
| 4.1  | Auf irgendeiner Seite der Webseite | Keine | Es wird am rechten Rand die Sprachauswahl angezeigt |
| 4.2  | Auf irgendeiner Seite der Webseite | Es wird eine Andere Sprache geklickt | Der Text wird in der ausgewählten Sprache angezeigt |
| 5.1  | Eine Tageszeit wurde Ausgewählt  | Es wird ein Rezept angeklickt | Es werden 2 To-Do Listen angezeigt |
| 6.1  | Eine Tageszeit wurde Ausgewählt  | Es wird ein Rezept angeklickt | Es werden Bild, Text und To-Do Listen des Gerichtes angezeigt |
| 7.1  | Auf irgendeiner Seite der Webseite  | Es wird auf das Suchen-Element geklickt | Es kann nun der Name eines Gerichtes eingegeben werden |
| 7.2  | Auf irgendeiner Seite der Webseite | Es wird etwas in die Suche eingegeben | Es erscheinen Gerichte, die die gesuchten Wörter enthalten |
| 8.1  | Eine Tageszeit wurde Ausgewählt | Es wird ein Rezept angeklickt | Neben dem Bild steht ein Text, der Infos zum Gericht enthält |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![Screenshot 2023-05-11 143613](https://github.com/NathanielConstructive/LA1600/assets/111043950/3d8fba71-c7ce-432f-a258-3cca8d480d9f)

![WhatsApp Image 2023-05-11 at 09 54 44](https://github.com/NathanielConstructive/LA1600/assets/111046193/d8b2e1cd-f6f2-4d22-9ee3-3fa1029101f6)
![WhatsApp Image 2023-05-11 at 09 54 44 (1)](https://github.com/NathanielConstructive/LA1600/assets/111046193/702bc3f3-e8ab-4068-b597-40ae5ac6c7d3)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1  |  18.05     |           | Titel hinzufügen  |  20 Minuten             |
| 2  |  18.05     |           | Gerichte raussuchen (Mit Informationen) | 45 Minuten |
|2.A  |18.05 |             |  Gerichte hinzufügen inklusive Bilder        |    45 Minuten             |
| 3  | 18.05      |           |   Filterkriterien hinzufügen           |    45 Minuten           |
| 3.A  | 25.05      |           |   Filterkriterein den Gerichten zuordnen      |    75 Minuten           |
| 5  | 25.05      |           |   Sprache der Website auf Französisch übersetzen     | 80 Minuten              |
| 5.A  | 25.05      |           |   Sprache der Website auf Englisch übersetzen           |  45 Minuten             |
| 6  |  25.05  |           | Die Gerichte sind klickbar             |     45 Minuten|
| 7  | 01.06 |           | Das Klicken führt zu einer Unterseite             |   50 Minuten            |
| 8  | 01.06 |           | Das Gericht wird genauer beschrieben(Bild/Text)|    20 Minuten           |
| 9  |  01.06     |           |  TodoListe für die Zutaten            |    45 Minuten           |
| 9.A  |  01.06     |           |   Die TodoListe ist anklickbar           |  20 Minuten             |
| 10  |   08.06    |           |   TodoListe für die einzelne Schritte für das Gericht           | 45 Minuten              |
| 10.A  |  08.06     |           |   Nach jedem erledigtem Schritt, wird der nächste Schritt angezeigt           | 75 Minuten              |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
