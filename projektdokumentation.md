# Projekt-Dokumentation



Blackberry - Müller, Özden, Meier

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 11.5. | 0.0.1   | Erster Prototyp der Website. |
|  01.06     | 0.0.2   | Website mit Rezepten und guter Benutzeroberfläche (für den Anfang)|

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




### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Die Webseite wurde geöffnet| Ein Gericht wird angeklickt | Es wird angezeigt, welche Zutaten noch benötigt werden |
| 1.2  | Es wurde ein Gericht ausgewählt | Das Kästchen neben einer Zutat wird angeklickt | Im kästchen erscheint ein Häckchen |
| 2.1  | Es wurde eine Tageszeit ausgewählt | Es wird unter "Filter" ein Element angeklickt | Es erscheinen nur Gerichte, die dem Filter entsprechen |
| 3.1  | Die Webseite wurde geöffnet | keine | Es wird eine Liste Mit 3 Tageszeiten angezeigt |
| 3.2  | Die Webseite wurde geöffnet | Eine Tageszeit wird angeklickt | Es werden Passende Rezepte angezeigt |
| 4.1  | Auf irgendeiner Seite der Webseite | Keine | Es wird am rechten Rand die Sprachauswahl angezeigt |
| 4.2  | Auf irgendeiner Seite der Webseite | Es wird eine Andere Sprache geklickt | Der Text wird in der ausgewählten Sprache angezeigt |
| 5.1  | Eine Tageszeit wurde Ausgewählt  | Es wird ein Rezept angeklickt | Es werden 2 To-Do Listen angezeigt |
| 6.1  | Eine Tageszeit wurde Ausgewählt  | Es wird ein Rezept angeklickt | Es werden Bild, Text und To-Do Listen des Gerichtes angezeigt |
| 7.1  | Eine Tageszeit wurde Ausgewählt | Es wird ein Rezept angeklickt | Neben dem Bild steht ein Text, der Infos zum Gericht enthält |




### 1.4 Diagramme

![Screenshot 2023-05-11 143613](https://github.com/NathanielConstructive/LA1600/assets/111043950/3d8fba71-c7ce-432f-a258-3cca8d480d9f)

![WhatsApp Image 2023-05-11 at 09 54 44](https://github.com/NathanielConstructive/LA1600/assets/111046193/d8b2e1cd-f6f2-4d22-9ee3-3fa1029101f6)
![WhatsApp Image 2023-05-11 at 09 54 44 (1)](https://github.com/NathanielConstructive/LA1600/assets/111046193/702bc3f3-e8ab-4068-b597-40ae5ac6c7d3)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |  18.05     |           | Titel hinzufügen  |  20 Minuten             |
| 2.A  |  18.05     |           | Gerichte raussuchen (Mit Informationen) | 45 Minuten |
| 2.B  |18.05 |             |  Gerichte hinzufügen inklusive Bilder        |    45 Minuten             |
| 3.A | 18.05      |           |   Filterkriterien hinzufügen           |    45 Minuten           |
| 3.B  | 25.05      |           |   Filterkriterein den Gerichten zuordnen      |    75 Minuten           |
| 4.A  | 25.05      |           |   Sprache der Website auf Französisch übersetzen     | 80 Minuten              |
| 4.B  | 25.05      |           |   Sprache der Website auf Englisch übersetzen           |  45 Minuten             |
| 5.A  |  25.05  |           | Die Gerichte sind klickbar             |     45 Minuten|
| 5.B  | 01.06 |           | Das Klicken führt zu einer Unterseite             |   50 Minuten            |
| 5.C  |  01.06     |           |   Die TodoListe ist anklickbar           |  20 Minuten             |
| 5.D  |   08.06    |           |   TodoListe für die einzelne Schritte für das Gericht           | 45 Minuten              |
| 6.A  | 01.06 |           | Das Gericht wird genauer beschrieben(Bild/Text)|    20 Minuten           |
| 6.B  |  01.06     |           |  TodoListe für die Zutaten            |    45 Minuten           |



## 3 Entscheiden

Wir haben uns entschieden, eine Website zu erstellen, die Gerichte und kleine Texte dazu anzeigt, man kann auf der Startseite runter scrollen und auf die Gerichte klicken. Dazu sieht man oben links noch einen Filter, den man je nach belieben benutzen kann. Nach dem Klicken auf das Gericht, wird man auf eine neue Website weitergeleitet, die eine TodoListe zu den jeweiligen Gerichten zeigt. Welche Rezepte braucht man und wie muss man vorgehen. Wenn die Todo-Liste und inkls Rezept gemacht worden ist, machen wir noch eine Funktion, wo man die Sprache wechseln kann.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 18.05 |Müller|  20 Minuten     |  20 Minuten                 |
| 2.A  | 01.06 |Özden|  45 Minuten    |  15 Minuten  |
|2.B|01.06|Özden|45 Minuten|45 Minuten (Wegen Copyright Bildern)|
|5.A|14.06|Özden|45 Minuten|50 Minuten|
|5.B|14.06|Özden|50 Minuten|60 Minuten|
|5.C|14.06|Özden|20 Minuten|25 Minuten|
|5.D|21.06|Özden|45 Minuten|45 Minuten|
|6.A|21.06|Özden|20 Minuten|35 Minuten|
|6.B|21.06|Özden|45 Minuten|90 Minuten|

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 22.06.2023| Ein Gericht ist anklickbar |Özden |
| 1.2  |22.06.2023  | Das Kästchen kann ausgefüllt werden | Özden |
| 2.1  | 22.06.2023 | funktioniert nicht | Özden |
| 3.1  | 22.06.2023 | funktioniert | Özden |
| 3.2  | 22.06.2023 |funktioniert nicht |Özden |
| 4.1  | 22.06.2023 | funktioniert nicht |Özden |
| 4.2  | 22.06.2023 | funkioniert nicht | Özden |
| 5.1  | 22.06.2023   | funkioniert | Özden |
| 6.1  | 22.06.2023  | funktioniert | Özden |
| 7.1  | 22.06.2023 | funktioniert nicht |Özden|

Das Aussehen der Website ist gelungen, jedoch sollte man noch mehr Features hinzufügen, welches die Suche der Gerichte vereinfachen würde.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
