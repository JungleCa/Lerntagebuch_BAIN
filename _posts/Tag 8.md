In dieser Vorlesung drehte... standen die Suchmaschinen und Discoverysysteme und führte alle vorhergehenden Themen zusammen und so sollte man am Schluss das Schaubild, welches bereits an der ersten Lehrveranstaltung gezeigt wurde nachvollziehen und erklären können. Dies stellte der Höhepunkt dieser Vorlesung dar. 

Was mich hinsichtlich meines letzten Lerntagebucheintrags irgendwie positiv überrascht hat, ist das in dieser Lerneinheit im Rahmen eines Nachtrags zu OpenRefine auch das Landesarchiv Baden-Württemberg genannt wurde. Das bestätigte mir, dass ich damit eine gute Quelle gefunden und somit eine solide Argumentationsgrundlage habe. Ich hoffe, ich liege damit nicht falsch :) 

Betreffend dem Leitthema dieser Lerneinheit "Suchmaschinen und Discovery-Systeme" standen folgende Punkte im Zentrum: 
-Installation und Konfiguration von VuFind 
-Funktion von Suchmaschinen am Beispiel von Solr
-Übung zur Datenintegration 
-Marktüberblick Discovery-Systeme

Danach folgte ein Zwischenfazit. 

In diesem Tagebucheintrag werde ich mich vertieft mit der Funktion von Suchmaschinen resp. Solr befassen. Dies weil Solr eine verbreitete Suchmaschie ist und auch bei bekannten Plattformen wie dem Streaminganbieter Netflix zur Anwendung kommt. 

Solr kann folgendermassen eingeordnet werden, dass es mit Elasticresearch quasi Indusitiestandart ist und enorm verbreitet ist. Es funktionieren beide sehr ähnlich und Open Source. Die Suchmaschine Struckturiert die Daten intern in der Regel mit einem sogenannten Schema. 
Desshalb sollte vor dem Import der Daten in Solr festgelegt werden, welche Datentype enthalten sein dürfen. Dabei ist die ISO-Norm zu beachten. Die beiden Integrierten Suchoberflächen sind nur zu Demo-Zwecke gedacht. VuFind basiert auf Solr wie auch Primo von Ex Libris, welches ebenfalls ein Discovery-System ist jedoch kommerziell vertrieben wird. 

Auch den Unterschied zwischen einem Suchindex (Solr) und einer Datenbank (MySQL) wurde erläutert. So findet man in Solr flache Dokumente und in MySQL rationale Datensätze. Was ebenfalls anders ist, ist dass in Solr eine lexikalische Suche erfolgt und bei MySQL ein reiner Glyphenbereich stattfindet. In Solr findet jedoch keine Konsistensprüfung statt wogegen bei MySQL Transaktionssicherheit herrscht. Mit Solr kann man statissche Daten konsultieren- mit MySQL veränderliche Daten. Ergo: in Solr erfolgt ein Retrival - also eine Suche und in MySQL erfolgt ein Storage nach Create, Read, Update, Delete (CRUD).
Der Suchindex macht in Situationen Sinn, wo möglichst viele Treffer generiert werden sollen. 


