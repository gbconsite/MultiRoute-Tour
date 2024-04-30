---
description: Verfolgen Sie alle Änderungen und Versionssprünge im Changelog.
---

# Changelog

Alle MultiRoute Tour! Revisionen sind hier mit den letzten Änderungen aufgeführt.

## 2024

### v1.3065 vom 25.04.2024
- Fähren können ausgeschlossen werden
- Korrekturen bei Reichweitenbegrenzung
  
### v1.3029M vom 15.03.2024
- 🔥 **Neu: Reichweitenbegrenzung** für Elektrofahrzeuge 🔥
- Design-Anpassungen wie u.a. eine klare Strukturierung und Begriffsanpassungen unter 4. Touren

## 2023

### v1.2951M vom 20.12.2023
- Neu: Fußprofil neben PKW- und LKW-Profilen!
- Bei User-Emails wird die Groß/Kleinschreibung ignoriert
- Mehrere Pausen können nun bei den Fahrzeugen in der Flotte eingegeben werden und damit bspw. Übernachtungen einfacher abgebildet werden

### v1.2860M vom 04.09.2023
- Optionaler erweiterter Routingalgorithmus
- Geschwindigkeitseinstellung: Die Durchschnittsgeschwindigkeit für alle Fahrzeuge kann prozentual reduziert oder erhöht werden. So kann in Innenstädten mit viel Verkehr bspw. mit nur 90% der Durchschnittsgeschwindigkeit gerechnet werden oder mit 105% in sehr ländlichen Regionen oder für lange Strecken mit wenig Verkehr und vielen Autobahn- und Landstraßenabschnitten. Die Einstellung eignet sich ebenfalls sehr gut um gewisse Puffer einzubauen.

### v1.2800M vom 08.03.2023
- Einstellungsmöglichkeit: schnellere oder beste Optimierung, wobei die schnelleren Optimierungen ebenfalls sehr gute Ergebnisse in einem Bruchteil der Berechnungsdauer der besten Optimierung liefern.
- Bugfixes: beschleunigter Upload
- Schnellerer SaaS-Server!

## 2022

### v1.2742M vom 10.08.2022
- GMaps & Apple Maps Dark Mode
- Fußgängerprofil 
- Vereinfachte Wochenzeitplanung nach der Tourberechnung durch Klick auf die kleine Uhr neben der Tournummer

### v1.2709M vom 01.07.2022
- [Interaktive Anleitungen](https://gbconsite.de/multiroute-tour-info-nr-02-2022/) zur Einführung oder Wiederauffrischung 
- Anzeige der Zeitspanne bei der Eingabe von Zeitfenstern. Zwischen 07:30 Uhr und 15:45 Uhr beträgt die Zeitspanne bspw. 08:15h.

### v1.2667M vom 29.04.2022
- Optionaler neuer Parameter "Geokodierungsergebnisse mit gegebener PLZ oder ORT prüfen" (unter "Weitere Optionen" im Uploadformular beim Adressupload oder [exakt_plz_ort](https://tour.multiroute.de/handbuch/routen/#adressen-hinzufugenupdaten) in der API) für verbesserte Genauigkeit. Wenn aktiviert, müssen mindestens die PLZ oder der Ort exakt mit den hochgeladenen Daten übereinstimmen. Bsp: wenn *12345 Musterort* hochgeladen wird und bei der Geokodierung *12346 Musterort-Vorstadt* ermittelt wird, wird diese Adresse als "Adresse ohne Koordinaten" geführt und muss einmal händisch korrigiert werden. 
- Verbesserungen in der Optimierung bei komplexen Problemen mit Skills, Streckenzuordnung, Zeitfenstern und Kapazität
- Prioritäten werden nun in der API exportiert
- Bugfix: Startadresse in der Flotte anpassen 

### v1.2625M vom 15.03.2022
- Die Streckenzuordnung wird nun (falls vorhanden) in den Strecken- und Tourexcelexporten mit aufgeführt
- Skills werden nun ebenfalls in den Streckenexporten aufgeführt (in Tourexport bereits vorhanden) 

### v1.2601 vom 03.02.2022
- Die Anzeige der Tourenergebnisse ist bei großen Touren nun viel schneller.
- Die Richtungspfeile der Touren können optional angeschaltet werden (Default: aus).
- Bugfix: manueller Upload von HH:MM(+D)-Zeitfenstern 
- Hilfstexte werden bei der Tourberechnung unter **4. Touren** beim Hovern angezeigt.

## 2021

### v1.2581M vom 20.12.2021
- Geschwindigkeitsanpassungen im Tourformular sind nun möglich. Die Standardzeiten pro Profil können nun auf bis zu 10% reduziert oder 1000% erhöht werden.

### v1.2558M vom 15.11.2021
- Erweiterte Option beim Upload die Geokodierung nur hausnummerngenau oder straßengenau vorzunehmen. Ersteres setzt Hausnummern voraus, letzteres findet auch Straßen ohne Hausnummern.
- Neue API-Option beim Löschen einer Flotte oder Planung alle damit berechneten Touren zu löschen 

### v1.2533M vom 12.10.2021
- Google-Maps-QR-Codes nun auch im PDF-Gesamt-Tourenexport (bisher nur in Einzeldokumenten)

### v1.2526M vom 21.09.2021
- Zusätzliche Auftragsparameter (Skills, Streckenzuordnung, Priorität, Fahrernotizen) in API ergänzt (via Einzelabfrage http://domain/fernsteuerung/auftrag und in Tourabfrage http://domain/fernsteuerung/tour/<tour-id>)
- Neues optionales Feature im Tourformular: Optimierungsmethode (beste, gut, normal, schnell, schnellste) für große Planungen (>1500 Aufträge). Hiermit kann die Berechnung je nach Bedarf mit evtl. Qualitätseinbußen (ggf. längere Strecke/Fahrtzeit) beschleunigt werden. Default ist immer "beste", d.h. die bestmögliche Optimierung.

### v1.2520M vom 15.09.2021
- Neues Feature im Tourformular: Die kleine Waage im Feld "Maximale Anzahl Aufträge pro Fahrzeugstrecke" kann nun mit einem Klick dazu benutzt werden, um die Aufträge gleich auf alle Fahrzeuge aufzuteilen.
- Bugfix in der API: Bei einem PUT-Request zum Ändern einer Flotte konnte es dazu kommen, dass zusätzlich eine weitere, leere Flotte angelegt wurde. 

### v1.2514M vom 19.08.2021
- Gemarkungsgrenzen Rheinland-Pfalz & Hessen nun verfügbar

### v1.2511M vom 17.08.2021
- Planungsnamen bei gelöschten Planungen beibehalten

### v1.2505M vom 10.08.2021
- Schnellerer Flotteneditor bei großen Flotten (>5 Fahrzeuge)

### v1.2499M vom 06.08.2021
- Neue Adresskorrekturfunktion siehe [hier](https://multiroute-tour.de/tipps/#adressen-korrigieren-mit-google-maps) 
- Die Nummerierung der im Google- & Apple-Maps-Export ist nun der Tourenübersicht angepasst. Start & Ende erhalten keine Nummerierung mehr, sodass der erste Auftrag die Nummer 1 erhält.

### v1.2488 vom 29.07.2021
- Klickbare Karten nun verfügbar in GUI & API 

### v1.2480 vom 21.07.2021
- Neue, zusätzliche Spalten im Excelexport der Tour: Servicezeit und Skills 
- Default im Tourenformular für "Maximale Anzahl Aufträge pro Fahrzeugstrecke" von 100 auf 10 000 gesetzt um versehentliche Einschränkungen zu verhindern

### v1.2469 vom 06.07.2021
- Bugfix für das Hochladen der Flotte über GUI 
- Vorbereitungen zur individuellen Straßenanpassung und Besonderheiten beim Routing

### v1.2459 vom 15.06.2021
- Touren löschen über API

### v1.2454 vom 31.05.2021
- Bugfix Streckenzuordnung

### v1.2448M vom 18.05.2021
- LKW-Routingprofile in der API
- QR-Code Performance
- Fahrzeugzuweisung und Skills werden besser geparst
- Mehr Infos nach dem Upload (Anzahl Adressen, Aufträge etc.)
- Im Excel-Export werden Start und End-Adresse nicht mehr nummeriert
- Workaround für falsch getaggte Einbahnstraßen in OSM und besseres Logging
- Fix für case-insensitive Hausnummerzusätze
- Höhere Limits für Flotten, Touren & Planungen
- Mehrere Accounts für einen Benutzer
- Bugfixes

### v1.2423M vom 26.04.2021
- Ankunftszeit im Excelexport
- Terminologieanpassung von Start- und Endadressen im Excelexport

### v1.2396M vom 07.04.2021
- Skills Float Parsing aus Excel- oder csv-Upload
- Entfernung von überflüssigen Semikoli aus Fahrernotizen

### v1.2415M vom 22.04.2021
- Hausnummernzusatz Fix für Klein- und Großschreibung

### v1.2391M vom 24.03.2021
- Verbesserte Performance beim Touranzeigen
- API Erweiterung für LKW-Profile
