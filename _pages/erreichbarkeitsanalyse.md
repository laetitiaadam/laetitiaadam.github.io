---
layout: single
title: Erreichbarkeitsanalyse Toolbox
permalink: /erreichbarkeitsanalyse/
---

# Die Entwicklung von 3 QGIS-Tools zur Quartiersplanung

Wie viele Supermärkte sind innerhalb von 10 Gehminuten zu erreichen? Was ist die schnellste Route zur Bushaltestelle? Das sind häufige Fragen, um die Erreichbarkeit von Quartieren zu analysieren.
Doch wie berechne ich die Ergebnisse nicht nur für ein Haus, sondern für ein ganzes Quartier? Dafür habe ich mithilfe der QGIS Modellierung eine Toolbox aus drei Tools gebaut. Getestet wird die Toolbox aktuell von der Stadt Aachen.<br>

## Tool 1 zur Routenberechnung

Dieses Tool berechnet die Routen von allen Punkten der Origin-Eingabe zu allen Punkten der Destination-Eingabe. 
Die Ausgabe umfasst für jedes Origin-Destination-Paar eine Route für jedes Transportmittel (Auto, Fahrrad, zu Fuß) inklusive der Reisezeit und Distanz. 
Zudem wird eine Tabelle ausgegeben, die zu allen Origin-Destination Paaren in der gleichen Zeile alle Reisezeiten und Distanzen aller Transportmittel auflistet und somit alle Verkehrmittel miteinander vergleichbar macht.<br>

![routing](/assets/images/routingtool.png)

*User interface des Routing Tools*<br>

Das Ergebnis zeigt alle Routen von allen Startpunkten zu allen Zielorten. In der Attributtabelle der Ausgabe finden sich alle Transportmittel, Strecken und Reisezeiten. <br>

![routing_map](/assets/images/toolbox_intro.jpg)

*Ausgabe des Routing Tools*<br>

## Tool 2 zur Analyse der Nahversorgung

Dieses Tool legt ein Hexagongitter über die Gebäude im Untersuchungsgebiet. 
Anschließend werden von allen Zentroiden der Hexagone die Reisezeitisochrone in 5 min, 10 min und 15 min Intervallen berechnet und ausgegeben. 
Auf Basis der Isochrone werden alle Supermärkte, Bushaltestellen und Hausärzte gezählt, die innerhalb der Intervalle erreicht werden. 
Das Transportmittel kann in der Auswahl angewählt werden. <br>

![nahversorgung](/assets/images/nahversorgungstool.png)

*User interface des Nahversorgungs Tools*<br>

![nahversorgung](/assets/images/nahversorgung_map.png)

*Isochrone des Nahversorgungs Tools werden für jeden Zentroid des Hexagongitters berechnet*<br>

Zudem wird das Heaxgongitter ausgeben, dass eine flächendeckende Abfrage nach der Anzahl der zu erreichenden Zielorte erlaubt.  <br>

![nahversorung](/assets/images/nahversorgung.png)

*Abfrage des Hexagongitters erlaubt direkte Einsicht der Ergebnisse*<br>

## Tool 3 Shortest & Fastest Path Finder

Dieses Tool legt ein Hexagongitter über die Gebäude im Untersuchungsgebiet. 
Anschließend werden von allen Zentroiden der Hexagone die kürzeste sowie schnellste Route zum nächstgelegenen Zielort berechnet und ausgegeben. 
Die Ausgabe zeigt die Routen als Linien inklusive Reisezeit (Time_min) und Distanz (Distance_km). <br> 

![pathfinder](/assets/images/pathfindertool.png)

*User interface des Pathfinder Tools*<br>

![pathfinder](/assets/images/pathfinder_map.png)

*Kürzeste und schnellste Routen werden für jeden Zentroid des Hexagongitters berechnet*<br>

Zudem wird das Heaxgongitter ausgeben, dass eine flächendeckende Abfrage nach Reisezeit und Distanz zum Zielort erlaubt.  <br>

![pathfinder](/assets/images/pathfinder.png)

*Abfrage des Hexagongitters erlaubt direkte Einsicht der Ergebnisse*<br>
