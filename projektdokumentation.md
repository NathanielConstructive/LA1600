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
|7    |muss|Qualität|Als Benutzer möchte ich, dass ich direkt nach den Gerichten in einer Suchleiste suchen kann, damit wenn ich mich schon für ein Gericht entschieden habe, es direkt finden kann.|
|8    |kann|Qualität|Als Benutzer möchte ich, dass wenn ich auf die Gerichte klicke, es mir genauere Infos über das Gericht gibt, zum Beispiel woher es genau kommt und für was es bekannt ist.|
|9    ||||
|10   ||||


Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Eine Tageszeit wurde Ausgewählt| Ein Gericht wird angeklickt | Es wird angezeigt, welche Zutaten noch benötigt werden |
| 1.2  | Es wurde ein Gericht ausgewählt | Das Kästchen neben einer Zutat wird angeklickt | Im kästchen erscheint ein Häckchen |
| 2.1  | Es wurde eine Tageszeit ausgewählt | Es wird etwas in die Suche eingegeben | Es erscheinen Gerichte, die die gesuchten Wörter enthalten |
| 2.2  | Es wurde eine Tageszeit ausgewählt | Es wird unter "Filter" ein Element angeklickt | Es erscheinen nur Gerichte, die dem Filter entsprechen |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![MicrosoftTeams-image (4)](https://github.com/NathanielConstructive/LA1600/assets/111046193/85fe1047-497d-4685-8b0e-64c30984070e)
![WhatsApp Image 2023-05-11 at 09 54 44](https://github.com/NathanielConstructive/LA1600/assets/111046193/d8b2e1cd-f6f2-4d22-9ee3-3fa1029101f6)
![WhatsApp Image 2023-05-11 at 09 54 44 (1)](https://github.com/NathanielConstructive/LA1600/assets/111046193/702bc3f3-e8ab-4068-b597-40ae5ac6c7d3)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
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
