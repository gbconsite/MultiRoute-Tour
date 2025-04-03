---
title: Häufig gestellte Fragen (FAQ) zur Tourenplanung mit MultiRoute Tour!
description: Antworten auf die wichtigsten Fragen zur Tourenoptimierung und Tourenplanung mit MultiRoute Tour! Erfahren Sie, woher die Straßendaten stammen, warum sich Touren manchmal kreuzen und wie viel Sie mit MultiRoute Tour! einsparen können.
keywords: Tourenplanung, Tourenoptimierung, MultiRoute Tour, FAQ, Straßendaten, Kostenersparnis, Routenplanung, Logistiksoftware
---

# FAQ zur Tourenplanung mit MultiRoute Tour!

## Woher stammen die Straßendaten?

Die Straßendaten für MultiRoute Tour! beziehen wir aus [OpenStreetMap](https://www.openstreetmap.org/#map), einer offenen, kollaborativen Kartierungsplattform. Freiwillige weltweit erstellen und aktualisieren die Einträge, die oft präziser sind als Karten kommerzieller Anbieter wie Google Maps, insbesondere in ländlichen Gebieten. Sollten Sie Fehler entdecken, können Sie diese direkt korrigieren. Ihre Änderungen fließen beim nächsten Update in unsere Datenbank ein und verbessern die Berechnungen.

## Warum kreuzen sich Touren manchmal?

Unsere Streckenoptimierung zielt darauf ab, die gefahrenen Kilometer insgesamt zu minimieren, basierend auf dem realen Straßennetzwerk. Wenn sich Touren überschneiden, bedeutet dies, dass es aus Sicht der Optimierung sinnvoll ist, die Strecken so zu fahren. Mehrere Faktoren können dazu führen, dass sich Touren kreuzen:

- **Gemeinsame Nutzung von Hauptverkehrswegen**: Autobahnen und Landstraßen müssen von mehreren Fahrzeugen genutzt werden, um effizient zu den Aufträgen zu gelangen.
- **Komplexe Anforderungen**: Überlappende Zeitfenster, Kapazitätseinschränkungen oder spezialisierte Fähigkeiten können dazu führen, dass mehrere Fahrzeuge Aufträge in denselben Gebieten erledigen müssen.
- **Optimierung der Gesamtroute**: Es kann effizienter sein, keine festen Gebiete zuzuweisen, sondern die Routen flexibel nach Bedarf zu gestalten, insbesondere wenn zwei Fahrzeuge an derselben Adresse vorbeifahren.

Obwohl es ungewohnt erscheinen mag, die räumliche Aufteilung in Untergebiete aufzugeben, können Sie dadurch erheblich Kilometer und somit Kosten einsparen. Die Komplexität moderner Tourenplanung erfordert Algorithmen, die diese Aufgabe optimal bewältigen.

Falls Sie dennoch eine Aufteilung in Untergebiete bevorzugen, haben Sie zwei Optionen:

- **Vorherige Auftragsaufteilung**: Teilen Sie Ihre Aufträge beispielsweise nach Postleitzahlen auf und laden Sie sie in [separate Planungen hoch](../planung).
- **Untergebiete in MultiRoute Tour! erstellen**: Nutzen Sie das [Scheren-Tool](../tipps/#planungen-manuell-zerteilen-schere), um Ihre Planung in Untergebiete zu zerschneiden.

## Wie viel kann ich mit MultiRoute Tour! einsparen?

Unsere Kunden berichten von einer Kostenersparnis zwischen 15% und 35% durch die Nutzung von MultiRoute Tour!. Sie können Ihre aktuellen Touren mit den optimierten Touren vergleichen und Ihre eigene Ersparnis ermitteln. Besonders bei komplexen, historisch gewachsenen Touren können Sie erhebliche Einsparungen erzielen. Nutzen Sie die Gelegenheit für eine Optimierung und [kontaktieren Sie uns](https://tour.multiroute.de/handbuch/impressum/) für weitere Informationen!

## Welche Geschwindigkeiten werden benutzt? 

In MultiRoute Tour! können Sie zwischen PKW- und LKW-Profilen verschiedener Gewichtsklassen unterscheiden. Je nach Profil unterscheiden sich nicht nur die Straßen, die befahren werden können, sondern auch die hinterlegten Geschwindigkeiten. Unsere Profile haben sich seit 2007 in der Praxis bewährt und wurden von Tausenden Kunden in ganz Europa bestätigt. 

Wie funktioniert dies in der Praxis? 

Unsere Routingdaten beziehen wir über das OpenStreetMap-Projekt, einer großen Community von weltweiten, freiwilligen Online-Kartographen. Diese tragen die Straßen und die dort hinterlegten Geschwindigkeiten pro Fahrzeugprofil ein. Sollte mal etwas fehlen, greifen bewährte Durchschnittsgeschwindigkeiten. 
Die Geschwindigkeiten sind dabei von vielen Faktoren abhängig, wie bspw. dem Straßenbelag. Wenn Sie genau wissen möchten, wo welche Geschwindigkeit hinterlegt ist, nutzen Sie eine der folgenden Quellen: 

- [Overpass-Turbo für die Höchstgeschwindigkeiten](https://overpass-turbo.eu/?Q=%2F*%0AThis%20has%20been%20generated%20by%20the%20overpass-turbo%20wizard.%0AThe%20original%20search%20was%3A%0A%E2%80%9Cmaxspeed%3D*%E2%80%9D%0A*%2F%0A%5Bout%3Ajson%5D%5Btimeout%3A25%5D%3B%0A%2F%2F%20gather%20results%0Anwr%5B%22maxspeed%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%2F%2F%20print%20results%0Aout%20geom%3B&C=48.732389%3B8.725376%3B14&R=)
- [OpenStreetMap für alle hinterlegten Parameter an den Straßen](https://www.openstreetmap.org/#map=6/51.24/9.77)

