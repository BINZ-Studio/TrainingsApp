# TrainingsApp

Trainingsplaner fürs Handy mit Trainingsblöcken, Progressive Overload, Entlastungswoche, Archiv und Pausentimer. Läuft als Web-App (PWA) auf Android und iPhone, ohne App Store, ohne Konto und ohne Abo. Nach der Installation funktioniert sie auch ohne Internet.

App öffnen: https://DEINNAME.github.io/training/

# Installation

# Android (Chrome)
Den Link oben in Chrome öffnen.
Oben rechts auf das Drei-Punkte-Menü tippen.
App installieren wählen. Steht dort nur Zum Startbildschirm hinzufügen, das nehmen.
Bestätigen. Das Hantel-Symbol liegt jetzt auf dem Startbildschirm.

# iPhone (Safari)
Den Link oben in Safari öffnen. In Chrome oder anderen Browsern auf dem iPhone fehlt die Option je nach iOS-Version.
Unten auf das Teilen-Symbol tippen (Quadrat mit Pfeil nach oben).
Nach unten scrollen und Zum Home-Bildschirm wählen.
Oben rechts auf Hinzufügen tippen.

Danach die App immer über das Symbol auf dem Startbildschirm öffnen, nicht über den Browser. Nur so läuft sie im Vollbild, und Safari hält die Daten getrennt vom normalen Surfen.


Die Einrichtung erreichst du später jederzeit über den Knopf oben links im Hauptmenü.

# Deine Daten
Alle Daten liegen nur auf deinem Handy. Jede Person hat ihre eigenen Daten. Es gibt keinen Server und keine Anmeldung.
Regelmäßig sichern: Hauptmenü → Plan speichern → Alle Daten als Datei sichern. Die Datei zum Beispiel in Google Drive, iCloud oder per Mail an dich selbst ablegen.
Neues Handy: App dort installieren, dann Plan speichern → Sicherung laden und die Datei auswählen.
Wenn du die App deinstallierst oder die Website-Daten im Browser löschst, sind die Daten ohne Sicherung weg.
Bekannte Einschränkungen
Der Timer zählt weiter, wenn du in eine andere App wechselst. Läuft er dort ab, meldet er sich erst, wenn du zur TrainingsApp zurückkehrst.
Vibration funktioniert auf Android, auf dem iPhone nicht. Dort in den Timer-Einstellungen den Signalton einschalten.
Die Schrift wird beim ersten Öffnen aus dem Internet geladen. Offline zeigt die App ohne zwischengespeicherte Schrift eine Ersatzschrift an.

# Updates einspielen (für den Betreiber)
Neue index.html hier im Repository hochladen und die alte ersetzen (Add file → Upload files).
In sw.js die Zeile const VERSION = "trainingsapp-v1"; um eins hochzählen (v2, v3 …) und speichern.
Auf den Handys die App zweimal schließen und neu öffnen. Beim ersten Öffnen lädt sie die neue Version, beim zweiten zeigt sie sie an. Die Daten bleiben erhalten.
