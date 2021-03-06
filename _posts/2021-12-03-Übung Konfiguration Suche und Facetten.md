---
title: "Übung Facetten"
date: 2021-12-03
---

Übung - Konfiguration Suche und Facetten

Bei der Übung «Konfiguration Suche und Facetten» ging es um die Individualisierung des Suchsystems VuFind dessen Suche und Facetten jeweils sehr einfach angepasst werden können. 
Dank dem für die Übung bereitgestelltem Videotutorial und dem zugehörigen Skript konnte ich die für die Übung geforderten Installationen vornehmen. Trotzdem erschien mir die Übung sehr komplex und ich brauchte auch da an mehreren Stellen mehrere Anläufe bis alles so funktionierte wie es vorgesehen war. 

So wurde die Dateien searchen.ini und facets.ini angepasst, welche jeweils die Suchanfragen, Suchanfragen und Facetten regulieren. Da über die Datei searchspecs.yml die Gewichtung der Sucheingaben erfolgt, habe ich hier keine Veränderungen vorgenommen. 

Aspekte der Suche und der Suchresultate werden in der Datei searches.ini verwaltet. Das erlaub einem die Sortierung der Suchresultate einzustellen. Sollte man nun eine leere suche machen erschienene einem, wenn alles gut läuft, alle Einträge. Falls das nicht so ist, ist etwas schief gelaufen. 
Die Anzeige,  deren Reihenfolge und deren Bezeichnung kann fürs Dropdown neben dem Suchfeld angepasst werden. Das gleiche gilt für die Sortieroptionen. Der Nutzer kann zum Beispiel die Anzahl Suchresultate pro Seite zu wählen. 

facets.ini beinhaltet, man kann es schon nur aufgrund dessen Namen erahnen, die Facetten. In diesem File können verschiedene Punkte individualisiert werden und Suchresultate eingeschränkt werden. Auch sind Anpassungen betreffend der Reihenfolge und der Benennung möglich. 

Wenn man im Browser VuFind aktualisiert ist bei allen drei Files sind Anpassungen jeweils sofort ersichtlich. 
