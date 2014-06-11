% Langzeitarchivierung an der DNB
% Felix Kommnick

# Einleitung

Seit ihrem Bestehen sammeln, erfassen und erschließen Bibliotheken Bücher. Im Laufe der Zeit wurde dieses Sammlungsspektrum um zahlreiche Informationsträger erweitert. Dazu gehören Mikroformen, AV-Medien und in zunehmendem Maße digitale Medien. Seit etwa 100 Jahren haben ausgewählte Bibliotheken in Deutschland eine gesetzlich vorgeschriebene Archivierungspflicht für Ihre Bestände. Damit soll die dauerhafte Verfügbarkeit der nationalen Buch- und Wissensproduktion gewährleistet werden. Diese Langzeitarchivierung konnte in Bezug auf Printmedien relativ problemlos realisiert werden. Die Sammlung und Archivierung von Netzpublikationen wird erst seit rund zehn Jahren betrieben. Nachfolgend wird die Langzeitarchivierung an der Deutschen Nationalbibliothek (DNB) beschrieben. Es werden verschiedene Projekte vorgestellt und besonders auf die Probleme und Grenzen dieser Vorhaben eingegangen. 

# Der Sammelauftrag der DNB

Das [Gesetz über die Deutsche Nationalbibliothek][2] (DNBG) vom 22. Juni 2006 legt fest, was der Sammlungsgegenstand der DNB ist. Dazu zählen: 

* In Deutschland veröffentlichte Medienwerke
* Im Ausland veröffentlichte deutschsprachige Medienwerke
* Im Ausland veröffentlichte Übersetzungen deutschsprachiger Medienwerke in andere Sprachen
* Im Ausland veröffentlichte fremdsprachige Medienwerke über Deutschland (Germanica)
* Die zwischen 1933 und 1945 von deutschsprachigen Emigranten verfassten oder veröffentlichten Druckwerke

Die physische Form der Medienwerke ist dabei unerheblich. Es werden sowohl klassische Druckmedien gesammelt, als auch Tonträger, elektronische Datenträger, Netzpublikationen u.a. [@DeutscheNationalbibliothek2013b].

# Definition Langzeitarchivierung

"Unter [Langzeitarchivierung][3] versteht man die Erfassung, die langfristige Aufbewahrung und die Erhaltung der dauerhaften Verfügbarkeit von Informationen. […] Langzeit bedeutet für die Bestandserhaltung digitaler Ressourcen nicht die Abgabe einer Garantieerklärung über fünf oder fünfzig Jahre, sondern die verantwortliche Entwicklung von Strategien, die den beständigen, vom Informationsmarkt verursachten Wandel bewältigen können." [@Liegmann2004, S. 567].

Anders als beim traditionellen Archivierungsverständnis, wo es um den möglichst langen Erhalt des Informationsträgers an sich geht, steht bei der neuen Interpretation des Begriffs Langzeitarchivierung der Erhalt und die korrekte Interpretierbarkeit der Inhalte im Vordergrund. 

# Umsetzung an der DNB

Die DNB sammelt seit Mitte 2006 Veröffentlichungen aus dem Internet. Den Erhalt der digitalen Daten sicherstellen zu können und gleichzeitig auch die langfristige Interpretierbarkeit der Inhalte zu gewährleisten, ist eine große Herausforderung. Um dies gewährleisten zu können, arbeitet die DNB an zwei unterschiedlichen Herangehensweisen. 

Eine Möglichkeit ist es, zum Aufrufen von digitalen Inhalten frühere Systemumgebungen in einer aktuellen Systemumgebung nachzustellen (Emulation). Der entgegengesetzte Weg ist es, frühere Dateiformate in ein aktuelles zu formatieren (Migration). In nationaler und internationaler Kooperation werden an der DNB technische Verfahren eingesetzt und weiterentwickelt, um die Langzeitarchivierung gewährleisten zu können [@Steinke2013].

# Verschiedene Projekte

## Kopal

*[Kopal][4] : Kooperativer Aufbau eines Langzeitarchivs digitaler Informationen (Laufzeit 2004 – 2007)*

Ziel des Projektes war der Aufbau einer technischen und organisatorischen Lösung, um die Langzeitverfügbarkeit von elektronischen Publikationen zu sichern. Am Projekt beteiligten sich auch die SUB Göttingen und IBM Deutschland. Die entwickelte Software, die Formatmigrationsabläufe unterstützt (Einspielen und Abrufen der Archivobjekte) heißt kopal Library for Retrieval and Ingest (koLibRI). Hierbei handelt es sich um eine Open-Source-Software, die eine Bibliothek von Java-Tools zur Verfügung stellt [@DNBkopal].

## DP4Lib

*[DP4lib][5] : Digital Preservation for Libraries (Laufzeit 12.2009 – 02.2012)*

Dieses Projekt baute auf den Ergebnissen von kopal auf. Mit DP4lib sollte eine möglichst nachnutzbare und flexible Infrastruktur für die Langzeitarchivierung etabliert werden. Neben der technischen Infrastruktur wurden auch notwendige Service- und Betriebsmodelle zur Etablierung von Langzeitarchivierungsdienstleistungen aufgebaut. Ebenfalls wurde ein Kostenmodell erstellt, mit dem sich die Kosten für aufgebaute/geplante Dienstleistungen im Vorfeld berechnen lassen.  Neben der SUB Göttingen beteiligten sich unter anderem auch der GBV und die TIB an dem Projekt. Seit 2013 wird dieser Service zur Langzeitarchivierung unter dem Namen AREDO betrieben [@DP4Lib1; @DP4Lib2].

# Wie viel wurde bereits archiviert?

Mit Stand vom 24. Januar 2014 sind mehr als 1 Million Netzpublikationen in den Bestand der DNB aufgenommen worden. Damit hat sich der Bestand in den letzten 18 Monaten verdoppelt. Allein in den ersten zehn Monaten des Jahres 2013 kamen 300.000 Medienwerke dazu. Dieser Bestand gliedert sich im Moment wie folgt: 

* E-Books (49%)
* E-Paper-Ausgaben (34%)
* Hochschulschriften (14%)
* Online-Zeitschriften (3%) [@DNB2014netz]

Damit ist allerdings nur ein Bruchteil der Netzpublikationen verzeichnet. Den Anspruch an eine vollständige Verzeichnung erfüllt die DNB damit noch nicht. 

# Ablieferung an die DNB

Die [Ablieferung der Netzpublikationen][6] kann auf unterschiedliche Weise abgewickelt werden. Entweder über ein Webformular innerhalb eines Benutzerkontos an der DNB oder über automatisierte Verfahren. Dies kann entweder durch ein OAI-Harvesting erfolgen oder über den sogenannten Hotfolder, wo Netzpublikationen und zugehörige Metadaten eingespeist werden können. Hierbei wird eine sichere Datenübertragung über HTTPS oder SFTP angeboten [@DeutscheNationalbibliothek2013].

# Herausforderungen

## Langfristige Wiederauffindbarkeit

Die DNB kontrolliert die bei der Ablieferung angegebenen URLs in der Regel nicht und auch die dauerhafte Richtigkeit nicht. Da sich URLs aber ändern können und so die alten Verweisungen ins Leere führen, wird die Vergabe von persistenten Identifiern verfolgt, etwa durch die Vergabe von URNs. Im Gegensatz zum URL, der den (Abspeicherungs)ort der Ressource wiedergibt, gibt der URN den Namen der Ressource wieder, der sich in der Regel nicht ändert und somit eine längerfristige Wiederauffindbarkeit gewährleisten soll [@DeutscheNationalbibliothek2013c].

## Bewältigung der zukünftigen Datenmengen

Der Umgang mit Netzpublikationen wird in der DNB dem derzeitigen Datenaufkommen angepasst und in den allgemeinen Geschäftsgang integriert. Nach Schätzungen von 2011 verdoppelt sich das weltweite Datenvolumen alle zwei Jahre. Die Frage ist, ob die derzeitigen Abwicklungsmechanismen den steigenden Datenmengen gerecht werden und ob man verbesserte Strukturen zeitnah entwickeln und umsetzen kann. 

## Kosten/Finanzierung

Die Langzeitarchivierung ist kostenintensiv. Die DNB steht vor der Herausforderung, dieses Vorhaben auch nach dem Wegfall von Fördermitteln am Leben erhalten zu können. Um zukünftige Kosten abschätzen und kalkulieren zu können, wurde das bereits genannte Tool innerhalb des AREDO-Service entwickelt [@Beinert2013, S. 38-41].

## Aus- und Fortbildung des Personals

Die Langzeitarchivierung kann nur von fachlich kompetentem Personal durchgeführt werden. Diese Kompetenz geht über die des rein bibliothekarischen Personals hinaus. Die Herausforderung besteht darin, das projektgebundene qualifizierte Personal langfristig am Standort halten zu können. Veränderungen in der Personalstruktur sind also unausweichlich [@Beinert2013, S. 41-44].

## Rechtlicher Rahmen

Als ein Beispiel für eine rechtliche Herausforderung soll hier das deutsche Urheberrecht genannt werden. Dies sieht strikte Regelungen bei der Vervielfältigung und der Bearbeitung von urheberrechtlich geschützten Werken vor. Die DNB muss aber, um die Langzeitarchivierung gewährleisten zu können, Vervielfältigungen und Änderungen an den Medienwerken vornehmen. Dies darf sie per Gesetz nur mit Zustimmung des Rechteinhabers. Derzeit bewegt sich die DNB also in einer Grauzone. Seit Jahren fordern Initiativen eine gesetzliche Schrankenregelung für Gedächtnisorganisationen, damit diese dem Langzeitarchivierungsauftrag nachkommen können. So machte zuletzt 2013 der [Berliner Apell][7] deutlich, welche Bedeutung die Langzeitarchivierung von Netzpublikationen hat. Ein Vorschlag zur Gesetzesregulierung ist eine Anlehnung an die „Fair-Use-Klausel“ aus den USA, die es Gedächtnisorganisationen erlaubt, im Rahmen der Langzeitarchivierung   Veränderungen an Medienwerken vorzunehmen [@Beinert2013, S. 44-45].

Aufgrund dieser ungenauen rechtlichen Lage werden die Netzpublikationen in der DNB ausschließlich in den Lesesälen zur Nutzung zur Verfügung gestellt, es sei denn, der Ablieferer hat darüber hinausgehende Nutzungsmöglichkeiten gestattet [@DNB2014netz].

# Fazit

Es wird deutlich, dass die DNB beim Thema Langzeitarchivierung vor großen Herausforderungen steht, seien diese nun finanzieller, personeller, rechtlicher oder technischer Natur. Es bleibt abzuwarten, ob die bis 2016 formulierten [strategischen Prioritäten][8] [@DeutscheNationalbibliothek2014] im Bereich der Verzeichnung und Archivierung von Netzpublikationen mit den derzeit zur Verfügung stehenden technischen und personellen Infrastrukturen erreicht werden können.

  [1]: http://upload.wikimedia.org/wikipedia/commons/5/5f/DNB.svg
  [2]: http://www.gesetze-im-internet.de/dnbg/BJNR133800006.html
  [3]: http://files.d-nb.de/nestor/berichte/digitalewelt.pdf
  [4]: http://kopal.langzeitarchivierung.de/index.php.de
  [5]: http://dp4lib.langzeitarchivierung.de/
  [6]: http://www.dnb.de/ablieferungnp
  [7]: http://www.berliner-appell.org/
  [8]: http://d-nb.info/1050432266/34

# Literatur

