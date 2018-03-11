Dies ist ein selbst erstelltes Wikipedia über die agile Softwaremethode SCRUM. Ausführliche Infos in: https://benjaminbrandtner.github.io/ScrumWiki/special/about.html

Im gh-Pages Branch wurden die html Seiten um den <base href="https://benjaminbrandtner.github.io/ScrumWiki/"> Tag erweitert, und die '/' am Anfang von jedem href= oder src= entfernt.

Der master Branch (ohne base-Tag und mit Links im format "/articles/foo.html") eignet sich zum Bearbeiten und Anzeigen zuhause.  
Wer allerdings versucht, die html Dateien einfach so zu öffnen wird merken dass der Browser alle Links zb. in "C:/articles/foo.html" sucht, und daher jegliche Verknüpfungen von Seiten oder Stylesheets nicht funktionieren.  
Deswegen muss ein lokaler Server gestartet werden (ich mache das im Atom Editor mit dem AtomLiveServer Plugin), der den Stammordner des Repositories dem Browser als Stammordner der Webseite darbietet. Dann funktionieren die Links und die Seite sieht so aus wie sie soll.
