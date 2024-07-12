# Metadaten für GovData

[Bundesministerium für Wirtschaft und Klimaschutz (BMWK)](https://www.bmwk.de) 


## Einleitung

Das Repository stellt einen beispielhaften Metadatensatz im TTL-Format für den Import von Metadaten des BMWK in [GovData.de](https://GovData.de) bereit. Nach der Veröffentlichung von Daten in einem Datenrepositorium kann der Beispieldatensatz [`Beispieldatensatz_GovData.ttl`](Datensaetze/Beispieldatensatz_GovData.ttl) ausgefüllt werden und über einen Pull Request ins Repository aufgenommen werden.

Die einzelnen Metadaten werden in der [`Bundesministerium_fuer_Wirtschaft_und_Klimaschutz_DCAT-AP.ttl`](Bundesministerium_fuer_Wirtschaft_und_Klimaschutz_DCAT-AP.ttl) zusammengeführt und an GovData übergeben. 


DCAT-AP.de ist die deutsche Adaption des „Data Catalogue Application Profile“ [(DCAT-AP)](https://github.com/SEMICeu/DCAT-AP) für Datenportale in Europa[[1]](https://github.com/GovDataOfficial/DCAT-AP.de).

Eine ausführliche Dokumentation des Metadatenstandards DACT-AP.de ist unter [www.dcat-ap.de](https://www.dcat-ap.de/) zu finden. Der Metadatenstandard wird partiziaptiv in Github (https://github.com/GovDataOfficial/DCAT-AP.de) entwickelt und ist unter https://www.dcat-ap.de/def/dcatde/2.0/spec/ spezifiziert.  

Für die Metadatensätze des BMWK müssen folgende Metadaten von der veröffentlichenden Stelle bereitgestellt werden: [Hier noch ein Tabelle der anzugebenden Attribute einfügen?]

## Anleitung

### Übergabe der Metadaten via Pull Request

1. Das Repository Metadaten_fuer_GovData forken.
2. Den Inhalt der Datei [`Beispieldatensatz_GovData.ttl`](Datensaetze/Beispieldatensatz_GovData.ttl) kopieren. Hierfür Stiftsymbol anklicken und den gesamten Inhalt der Datei mit Strg+C oder Cmd+C kopieren.
3. Auf "Add file" > "Create new file" klicken und den kopierten Inhalt in das Textfeld mit Strg+V oder Cmd+V einfügen.
4. Einen neuen Namen für die Datei eingeben.
5. Metadaten für die veröffentlichten Daten anpassen.
6. Änderungen committen: Eine Commit-Nachricht eingeben und auf "Commit new file" klicken.

### Übergabe der Metadaten via E-Mail

Die Datei [`Beispieldatensatz_GovData.ttl`](Datensaetze/Beispieldatensatz_GovData.ttl) kann auch lokal heruntergeladen und bearbeitet werden. Den bearbeiteten Metadatensatz anschließend als TTL- oder TXT-Datei an opendata@bmwk.bund.de senden.
