---
title: Zusatzmodule für MultiRoute Tour!
description: Erweitern Sie MultiRoute Tour! um praktische Zusatzmodule wie Tracking, Notifications und Reichweitenbegrenzung
---

# Zusatzmodule

Die MRT Zusatzmodule sind einzeln zubuchbar.

## 1 Tracking {#tracking}

![Traccar](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/dad38292-9681-4724-99b1-0e68fdf13187){ align=left }

Mit Hilfe einer kostenfreien App zum Tracking (Traccar Client) lassen sich live die Zusteller
in ihren Trägerbezirken oder auch die Speditionsfahrzeuge auf Ihren Touren verfolgen.
Fahrten werden historisiert und lassen sich auch im Nachgang überprüfen.

Sehen Sie in Echtzeit die Position und auch die Geschwindigkeit Ihres
Fuhrparks. Durch die Historisierung der getrackten Touren können
Zeit-/Lieferverzögerungen analysiert werden.
Das Tracking läuft mit Hilfe einer auf einem mobilen Endgerät
installierten App, die an- und auch ausgeschaltet werden muss. Damit
genügt sie auch den datenschutzrechtlichen Anforderungen, da sie
nur zur Tourenplanung und Einsatzkoordinierung eingesetzt wird. 

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/24a30b21-792b-48d3-8326-a8d409073e68)

### Beispiel
Der Zusteller der Tageszeitung wartet auf das Speditionsfahrzeug an
der Abladestelle. Nach 10 Minuten Warten im Regen ruft er den
zuständigen Gebietsleiter an, der ihm mitteilen kann, wo sich das
Speditionsfahrzeug befindet. Die Arbeitszeit dieses Zustellers
verlängert sich an diesem Tag um die Wartezeit. Diese lässt sich auf
Grund des Trackings dokumentieren und begründen.
Die App ist geeignet für die Verwendung in Fahrzeugen, aber auch Zusteller, die zu Fuß unterwegs
sind, können darüber getrackt werden. 

### Installationshinweise

- Android: [https://play.google.com/store/apps/details?id=org.traccar.client](https://play.google.com/store/apps/details?id=org.traccar.client)
- Apple iOS: [https://apps.apple.com/us/app/traccar-client/id843156974](https://apps.apple.com/us/app/traccar-client/id843156974)

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/7c13f127-ca6a-41d9-959d-e06d5e96261e){ align=left }

Sie müssen einmalig die Einstellungen für den Traccar-Client auf Ihrem Smartphone vornehmen (die Gerätekennung erhalten Sie von uns!):

- Gerätekennung: XXXXXXX
- Serveradresse: http://track.gbconsite.de:5055
- Positionsgenauigkeit: Hoch
- Frequenz: 5 (zu Fuß) oder 60 (Kfz)
- Entfernung: 10
- Winkel: 30
- Datenherkunft: gemischt 


**Bitte nicht vergessen, GPS auf Ihrem mobilen Endgerät zu aktivieren!**

Das Tracking-Modul lässt sich auch offline verwenden (ohne mobile Daten). Nach Beendigung
synchronisieren Sie einfach den Track und dieser erscheint in MultiRoute Go! & Tour! für eine
Nachbetrachtung. 

**Widgets**

In der Android-Version können Sie sich Start- und Stopp-Widgets auf dem Startbildschirm hinzufügen, sodass das Tracking mit einem Klick an oder ausgeschaltet werden kann.
Hierzu drücken Sie auf Ihrem Startbildschirm drei Sekunden auf eine freie Stelle, sodass das Kontextmenü erscheint. 

Dort klicken Sie auf **Widgets** und suchen dann nach **Traccar**.
Fügen Sie dann einmal eine Verknüpfung **Dienst starten** und **Dienst stoppen** hinzu.

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/2b982684-3e8d-4267-b55b-ab8f7d5ac8a7)

Auf iOS setzen Sie den **Dienststatus** auf aktiv/inaktiv zum Starten/Stoppen. 



## 2 Auftragsverfolgung {#auftragsverfolgung}

Mithilfe des Auftragsverfolgungs-Moduls in MultiRoute Tour!, kann Ihr Fahrer in der praktischen [Google-Maps-Liste](../tour/#tour-exportieren) Aufträge als **erledigt** kennzeichnen. Dies sendet eine Benachrichtigung, die Sie und wahlweise auch Ihre Kunden empfangen können. So sind Sie immer auf dem neuesten Stand.

### Gesamtübersicht

Ihr Fahrer muss dazu nichts anderes tun, als im Google-Maps-Export den entsprechenden Auftrag mit einem Klick abzuhaken. Beim Abhaken wird die aktuelle Koordinate des Fahrzeuges mit übermittelt.

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/4bfcaa0f-511c-4e68-b512-c53a44c78916)

Mit einem Klick auf **Notifications** können Sie genau verfolgen, wann welcher Auftrag erledigt wurde:

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/556ccb44-bce9-40c3-9007-7e1d2cae8c19)

Sie können Push-Nachrichten auf Ihrem Handy oder im Browser empfangen. Die Fahrer können ebenfalls Nachrichten verschicken und Fotos für Dokumentationszwecke.

### Kundenspezifische Benachrichtigungen

Über die Google-Maps-liste kann ebenfalls der Kunde benachrichtigt werden, wenn bspw. etwas abgelegt wurde wie ein Paket, eine Gemüsekiste oder Brötchentüte. Der Kunde erhält hierzu einen speziellen Link, die an seine Kunden-ID geknüpft ist. Dadurch erhält er immer nur seine eigenen Benachrichtigungen, nicht aber die der anderen Kunden.

In diesem Beispiel erhält der Kunde über seine ID `82B064585C81F5C` also nur eine Benachrichtigung.

![image](https://github.com/gbconsite/MultiRoute-Tour/assets/47481567/df52f469-1813-423a-9a72-2d6d9ef71b4a)




