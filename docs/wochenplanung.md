---
title: Wochenplanung mit MultiRoute Tour! 
description: Planen Sie eine ganze Woche im Voraus und erhalten Sie einen detaillierten Plan, wer wann wo hinfahren muss bei geringster Gesamststrecke oder Zeit.
---

# Wochenplanung

![Wochenplanungen mit MultiRoute Tour!](assets/Wochenplanung.png)

<div style="font-size: 11px">Photo by <a href="https://unsplash.com/de/@towfiqu999999">Towfiqu barbhuiya</a> on <a href="https://unsplash.com/de/fotos/einen-kalender-mit-daran-angehefteten-roten-druckknopfen-bwOAixLG0uc">Unsplash</a></div>

## Anforderung 
Wenn Sie Ihre Fahrzeuge nicht nur auf einfache Tagestouren schicken, bei denen das Fahrzeug immer wieder am gleichen Tag zurück zum Depot oder nach Hause fährt, sondern die Fahrzeuge bspw. *eine ganze Woche am Stück* mit Übernachtungen unterwegs sein sollen, kann dies ganz einfach in MRT! abgebildet werden. Auch gemischte Flotten mit Wochentouren und Tagestouren sind kein Problem.

Im folgenden Beispiel gehen wir von einer Flotte aus, bei der wir für eine Arbeitswoche zwei LKW zur Verfügung haben die beide von Mo - Fr unterwegs sein sollen.

## 1. Wochenarbeitszeit der Fahrzeuge definieren 

- Geben Sie bei der Einsatzzeit zunächst die gewünschte Startzeit am Montagmorgen (=Tag 0) ein, bspw. 8 Uhr.
- Bei der Endzeit bezieht sich mit Tag 4 auf den Freitag.

Hier eine Übersicht zur Hilfe: 

| Tag   | Abkürzung |
|-------|-----------|
| Tag 0 | Mo        |
| Tag 1 | Di        |
| Tag 2 | Mi        |
| Tag 3 | Do        |
| Tag 4 | Fr        |
| Tag 5 | Sa        |
| Tag 6 | So        |

Die Arbeitszeit sieht dann also wie folgt aus: 

<img width="945" height="539" alt="image" src="https://github.com/user-attachments/assets/45beac78-926d-4377-930f-d2e5a4146e49" />

## 2. Übernachtungspausen definieren 

Nun fehlen noch die Übernachtungspausen, die immer zum Arbeitsende anfangen und zum Arbeitsbeginn aufhören sollten. Für die Übernachtung Mo-Di, Di-Mi, Mi-Do, Do-Fr müssen also die Pausen von 16:00 bis um 08:00 am Folgetag eingegeben werden. 960 Minuten dauert eine Nacht mit 16 Stunden.

<img width="938" height="578" alt="image" src="https://github.com/user-attachments/assets/ecdedcc3-3719-42fd-99d8-7128a48605a7" />

Die fertige Flotte sieht nun so aus: 

<img width="2147" height="423" alt="image" src="https://github.com/user-attachments/assets/01884c65-e275-4283-a485-b66a0788ddc3" />

Nun können Sie die Tour optimieren oder weitere Parameter berücksichtigen: 

- Haben Ihre Aufträge Fixtermine? Kein Problem, dann laden Sie im Upload einfach den Tag und das Zeitfenster mit hoch.
- Für eine gemischte Flotte können Sie einfach noch Tagesfahrzeuge hinzufügen. Hier müssen Sie bei den Tagsfahrzeugen auch den entsprechenden Tag bei der Arbeitszeit definieren. Eine solche Flotte kann dann bspw. so aussehen:

<img width="1836" height="1079" alt="image" src="https://github.com/user-attachments/assets/5826179e-7db0-4dbd-8d64-400280b22072" />



