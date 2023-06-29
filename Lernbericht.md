# Lern-Bericht
**Blackberry**

Özden, Müller, Meier

## Einleitung

In unserem Projekt ging darum, eine **Rezeptwebsite** zu programmieren, die Anleitungen und Rezepte zu Gerichten zeigt.

## Was habe ich gelernt?

Wir haben gelernt, wie man **Checkboxen** je für einen Pointer programmiert.

## Beschreibung


### Medium 1:

Wir haben gelernt, wie man Checkboxen je nach Pointer anders anzeigen lassen kann. Ein Pointer ist die Art wie man die Maschine benutzt, sei es mit der Maus, Touch etc. Mit **"@media"** unterscheidet die Website den Pointer, man muss dann den Pointer, den man auswählen möchte, zum Code hinzufügen und dann noch wie die Checkbox überhaupt aussehen soll. 

### Medium 2:
```CSS

@media (pointer: fine) { /*@media benutzt man, damit wenn man wie hier zum Beispiel mehrere Pointer hat, die Website diese unterscheidet.*/
  input[type="checkbox"] {
    width: 15px;
    height: 15px;
    border-width: 1px;
    border-color: rgb(0, 0, 255);
  } /*"width" bis "border-color" beschreibt das Aussehen der Checkbox, falls der Pointer fine ist, also wenn man eine Maus benutzt.*/
}

@media (pointer: coarse) {/*Hier wird beschrieben wie die Checkbox aussieht, falls Der Pointer course ist, also wenn man die Maschine mit Touch benutzt.*/
  input[type="checkbox"] {
    width: 30px;
    height: 30px;
    border-width: 2px;
    border-color: red;
  }
}
```
### Medium 3:
![spaghetti_Touch](https://github.com/NathanielConstructive/LA1600/assets/111046193/b36c8c1e-d093-4bc7-878b-d8acd8773272)

![SSpaghetti_Touch](https://github.com/NathanielConstructive/LA1600/assets/111046193/eb69fcd7-c3a1-4d85-ae75-ef875b6960c4)

## Verifikation

### Medium 1:
Medium 1 zeigt **in Textform**, anhand des Codes, was wir gelernt haben. Es erklärt die Pointerfunktion kurz.

### Medium 2:
Das zweite Medium zeigt das **Code Schnipsel** und ein Beispiel, wie die Checkbox aussieht. Mithilfe von Kommentaren kann man nachvollziehen was wo passiert. 

### Medium 3:
Das dritte Medium zeigt **visuell**, wie der Unterschied zwischen Touch und einem Mauspointer aussieht. 

# Reflexion zum Arbeitsprozess

👍 Wir haben **Anfangs** gut abgemacht, wie unsere Website aussieht, und schnelle Fortschritte in der Entwicklung gemacht. 

👎 Wir haben im **Laufe des Projektes** immer weniger Zeit in das aktive Programmieren gesteckt. 

Nächstes Mal müssen wir mehr kommunizieren, wenn man zum Beispiel etwas nicht gemacht hat oder nicht weiss, was wer machen muss. So können wir sicherstellen, dass die Webseite aktiv aktualisiert wird. 
