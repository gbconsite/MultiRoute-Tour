---
title: Adressen und Aufträge bearbeiten für Touren
description: Touren auf der Karte ansehen und bearbeiten, manuelles Eingreifen bei Ausreißeradressen, Darstellung auf der Karte
---

# **2. Planung**

## Bedienung
In der Planung können Sie sich Ihre Aufträge anzeigen lassen und diese bearbeiten.

![!](assets/planung_v1.jpg){ loading=lazy }

Jeder schwarze Punkt ist eine Adresse. An den Adressen können Sie sich ansehen, in welcher Planung, d.h. an welchen Tagen (oder Wochen) Aufträge vorhanden sind. 

![!](assets/Auftrag_an_Adresse.jpg){ loading=lazy }

Diese Aufträge können Sie mit einem Klick auf die drei Kistchen bearbeiten und nach Bedarf anpassen, sollte bspw. ein Kunde ausfallen oder sich ein Zeitfenster ändern. 

![!](assets/Auftragsinfos.jpg){ loading=lazy }

## Adressverwaltung

Die Adressverwaltung befindet sich unter Planung in der linken Sidebar mit einem Klick auf das Haus-Symbol.

Hier können Ihre Adressen durchsucht werden. Gelöscht werden können diese nur durch den Administrator unter **Administration -> Upload**

Neue Adressen können durch den [Upload](../upload) oder [manuell per Klick in die Karte](../tipps/#adressen-neu-anlegen) hinzugefügt werden.

![!](assets/Adressverwaltung2.png)

### Adressen korrigieren mit Google

Wenn es beim Hochladen Ihrer Datei Adressen gab, für die keine Koordinate gefunden werden konnte, können Sie diese ganz einfach mithilfe einer Suche über Google Maps korrigieren. 

1) Zeigen Sie sich unter **2.Planung -> Adressverwaltung (kleines Häuschen)** und einem Klick auf die Checkbox **Adressen ohne Koordinaten** alle Adressen an, die nicht korrigiert werden konnten.

2) Hier sehen Sie zwei kleine Buttons. Die Pinnadel sucht die Adresse direkt in der Karte. Kann diese hier nicht gefunden werden, suchen Sie Ihre Adresse mit einem Klick auf das Google-Icon. Dieser öffnet einen neuen Tab in Ihrem Browser und sucht Ihre Adresse. 

![Google Adressuche in MultiRoute Tour!](https://user-images.githubusercontent.com/47481567/155503407-206091aa-9cd5-4caa-9f2e-6423dd7a75e9.png "Google Adressuche in MultiRoute Tour!")

3) In Google Maps klicken Sie mit der rechten Maustaste auf den Punkt, wo Ihre Adresse liegt und kopieren sich mit einem Rechtsklick die Koordinate in den Zwischenspeicher.

![Google Adressuche in MultiRoute Tour!](https://user-images.githubusercontent.com/47481567/155503600-f4706688-aa34-45dd-89a8-d6bf8fcf4bcb.png "Google Adressuche in MultiRoute Tour!")

4) In MRT! klicken Sie in der Spalte "OI" auf die entsprechende Adresse. Ein kleines Fenster öffnet sich, wo Sie nun die Koordinate mit STRG+V einfügen. Klicken Sie auf OK. Fertig! Die Koordinate ist nun für die Adresse übernommen worden und muss bei weiteren Uploads nicht noch einmal korrigiert werden. MultiRoute Tour! merkt sich die Koordinate also auch für die Zukunft.

![Google Adressuche in MultiRoute Tour!](https://user-images.githubusercontent.com/47481567/155503658-e52cd21d-3a7f-411b-9fdf-fde5f9a54d89.png "Google Adressuche in MultiRoute Tour!")

## Auftragsverwaltung

### Sortieren

Die Aufträge können nach Bezeichnung, Adresse, Planung und Status (aktiv/inaktiv) gefiltert und mit einem Klick auf die Pfeile auf- oder absteigend sortiert werden. 

Mit einem Klick auf die Adresse in der jeweiligen Spalte zentriert sich die Karte auf die ausgewählte Adresse.

Wenn Sie auf den blauen Pfeil bei "Spalten für Adressen auswählen" klicken, können Sie sich weitere Spalten anzeigen lassen oder Spalten abwählen.

![!](assets/Auftragsverwaltung.png)

***

### Verschieben oder löschen

#### Manuelles Verschieben und Löschen
Möchten Sie einen Auftrag in eine andere Planung verschieben, klicken Sie in der Zeile mit dem gewünschten Auftrag in der Spalte **Aktion** auf die kleine Weltkugel. 

Es öffnet sich ein Popup-Fenster, in dem Sie nun nur noch die richtige Planung anklicken müssen. Über die Mülltonne ließe sich der ausgewählte Auftrag löschen.

![!](assets/verschieben.png) ![!](assets/verschieben2.png)

Sie können alternativ direkt in der Karte eine Adresse auswählen. Mit einem Klick auf den entsprechenden Punkt öffnet sich das Menü. Auch hier können Sie einfach auf die Weltkugel klicken und den Auftrag ebenso verschieben.

![!](assets/verschieben3.png)

#### Verschieben über Polygon
Aufträge können in MultiRoute Tour! nicht nur manuell in eine andere Planung verschoben werden, sondern können auch über ein Polygon im kml-Format automatisch zugeordnet werden. Dies ist sehr praktisch, wenn Sie bspw. PLZ-Gebiete oder selbst erstellte Gebiete in MRT! einspielen wollen. Hierzu gehen Sie wie folgt vor: 

1. Unter Administration -> Ausgaben -> Ausgabe anzeigen, einmal ganz unten die kml-Datei hochladen. Diese muss einen Namen enthalten, der in MRT! als Planung verwendet wird. Eine Beispieldatei finden Sie hier: [kml Musterdatei](assets/downloads/Testdatei.kml).
![image](https://github.com/user-attachments/assets/b336d1b6-afc3-4687-9cbb-85dc744a66b5)

2. Das Planungs-Polygon ist nun erstellt worden, aber es enthält noch keine Aufträge. 
![image](https://github.com/user-attachments/assets/c31fa0a2-1e4a-499f-8806-3993d923b02d)
Um nun die Aufträge aus anderen Planungen in diese Planung zu verschieben klicken Sie folgt: Administration -> Planung -> gewünschte Planung anhaken -> Markierte Planungen: Zuordnung erzeugen -> Anwenden.
![image](https://github.com/user-attachments/assets/ca6ed2d2-5e4b-4da0-b1c3-5fd1855bfc72)

3. Die Aufträge wurden nun erfolgreich in das Polygon übertragen. Sie können nun wie gewohnt mit dieser Planung Tourenoptimierungen vornehmen.
![image](https://github.com/user-attachments/assets/89e79bce-c5ab-4266-bdf1-e16544a17dd4)

***

### Bearbeiten und neu anlegen


Wenn Sie Aufträge für eine Adresse bearbeiten oder neu anlegen möchten, klicken Sie auf das Symbol mit den drei Boxen in der Mitte des Menüs.

![!](assets/Bearbeiten.png)

Daraufhin öffnet sich das Auftragsmenü.

![!](assets/Liste.png)

Hier legen Sie entweder einen neuen Auftrag an oder bearbeiten einen existierenden mit Klick auf die entsprechende Zeile.

![!](assets/Neu.png)

