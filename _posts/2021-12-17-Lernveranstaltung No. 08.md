---
title: "Lernveranstaltung No. 08"
date: 2021-12-17
---


Lernveranstaltung No. 08

In dieser Vorlesung standen die Suchmaschinen und Discoverysysteme im Mittelpunkt und führte alle vorhergehenden Themen zusammen. Da man jetzt am Schluss des anfangs präsentierten Schaubild steht sollte man nun in der Lage sein das ganze Schaubild von Anfang bis Schluss in allen möglichen Einzelheiten zu erklären Dies stellte für mich persönlich ein bisschen der Höhepunkt dieser Vorlesung dar.

Was mich hinsichtlich meines letzten Lerntagebucheintrags irgendwie positiv überrascht hat, ist das in dieser Lerneinheit im Rahmen eines Nachtrags zu OpenRefine auch das Landesarchiv Baden-Württemberg genannt wurde. Das bestätigte mir, dass ich damit eine gute Quelle gefunden und somit eine solide Argumentationsgrundlage habe. Ich hoffe, ich liege damit nicht falsch :)

Betreffend dem Leitthema dieser Lerneinheit "Suchmaschinen und Discovery-Systeme" standen Themen wie die Installation und Konfiguration von VuFind, Funktion von Suchmaschinen am Beispiel von Solr, eine Übung zur Datenintegration sowie ein Marktüberblick Discovery-Systeme im Zentrum. Wie üblicherweise würde es den Rahmen eines Tagebucheintrags sprengen, wenn ich mich auf jedes einzelnen Thema fokussieren möchte und dieses ausführlich beschreiben und meine eigenen Gedanken und Recherchen dazu beitragen möchte. Desshalb werde ich mich in diesem Tagebucheintrag werde ich mich vertieft mit der Funktion von Suchmaschinen resp. Solr befassen. Dies weil Solr eine verbreitete Suchmaschie ist und auch bei bekannten Plattformen wie dem Streaminganbieter Netflix zur Anwendung kommt.

Solr kann so eingeordnet werden, dass es neben Elasticresearch quasi Indusitiestandart- und enorm verbreitet ist. Es funktionieren beide sehr ähnlich und sind Open Source. Die Suchmaschine Strukturiert die Daten intern in der Regel mit einem sogenannten Schema. Desshalb sollte vor dem Import der Daten in Solr festgelegt werden, welchen Datentype enthalten sein dürfen. Dabei ist die ISO-Norm zu beachten. Die beiden Integrierten Suchoberflächen sind nur zu Demo-Zwecke gedacht. VuFind basiert auf Solr wie auch Primo von Ex Libris, welches ebenfalls ein Discovery-System ist jedoch kommerziell vertrieben wird. An dieser Stelle einen kleinen Einschub: Ex Libris ist, wie schon in vorhergehenden Vorlesungen erwähnt wurde, der Entwickler der Bibliotheksoftware Alma. 

Auch den Unterschied zwischen einem Suchindex (Solr) und einer Datenbank (MySQL) wurde erläutert. So findet man in Solr flache Dokumente und in MySQL rationale Datensätze. Was ebenfalls anders ist, ist das in Solr eine lexikalische Suche erfolgt und bei MySQL ein reiner Glyphenbereich stattfindet. In Solr findet jedoch keine Konsistensprüfung statt wogegen bei MySQL Transaktionssicherheit herrscht. Mit Solr kann man statissche Daten konsultieren- mit MySQL veränderliche Daten. Ergo: in Solr erfolgt ein Retrival - also eine Suche und in MySQL erfolgt ein Storage nach Create, Read, Update, Delete (CRUD). Der Suchindex macht in Situationen Sinn, wo möglichst viele Treffer generiert werden sollen.



