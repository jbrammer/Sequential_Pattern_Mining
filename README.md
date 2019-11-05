## Datensatz für das Seminar „Business Problems“ 

Dieses Repository enthält den Datensatz für das Seminarthema "Sequential Pattern Mining: Analysis and Visualization of Production Line Sequences" am Lehrstuhl Information Systems Research der Universität Freiburg.

## Fachliche Motivation des Problems
In heutigen Fertigungsanlagen werden Produkte oft mit einer hohen Variantenvielfalt produziert. Um dennoch eine effiziente Produktion zu gewährleisten werden diese unterschiedlichen Produktvarianten in der Regel auf einer Fertigungslinie hergestellt.
In solchen Systemen ist die Reihenfolge, in welcher Jobs in eine Produktionslinie fließen, entscheidend für die Effizienz der Linie. Die Optimierung von Fertigungssequenzen wird in der Literatur unter Berücksichtigung verschiedener Zielfunktionen untersucht (z.B. Flow Shop Scheduling, Mixed Model Sequencing, etc.).
In realen Fertigungsanlagen werden Fertigungssequenzen hingegen häufig mit Hilfe von Expertenwissen erstellt. Der Grund hierfür ist eine fehlende Datengrundlage, die für die Implementierung von Optimierungsalgorithmen notwendig ist.
Es besteht somit die Herausforderung aus bestehenden Fertigungssequenzen, welche mit Hilfe von Expertenwissen erstellt wurden, Fertigungsregeln abzuleiten. Diese Regeln können somit das Expertenwissen quantifizieren.

## Beschreibung des Datensatzes
Der Datensatz beinhaltet Daten aus drei unterschiedlichen Fertigungslinien (line1, line2 und line3). Jede dieser Fertigungslinien weist in Hinsicht auf Fertigungszeiten und Anzahl unterschiedlicher Jobs eine unterschiedliche Charakteristik auf. In jeder Linien werden 100 Jobs an einem Tag verarbeitet und es existieren 10 unterschiedliche Jobklassen.
Für jede der Fertigungslinien liegen jeweils 300 optimierte Fertigungssequenzen vor. Die Fertigungssequenzen stellen Tagessequenzen dar, die auf der jeweiligen Fertigungslinie produziert wurden. Die jeweiligen Tagessequenzen unterscheiden sich voneinander, da je nach Tag eine unterschiedliche Verteilung der Jobklassen vorliegt.

Der Ordner "sequences" enthält die 300 Tagessequenzen in je einer Datei je Fertigungslinie.

Der Ordner "instances" enthält die zugrundeliegenden Tagesprogramme und die Charakteristiken der Fertigungslinien. Die Notation ist in der Datei "Instance_Notation.mix" angegeben.

## Aufgabenstellung

Der Inhalt der Seminararbeit soll die Analyse der optimierten Fertigungssequenzen unter Anwendung von Sequential Pattern Mining sein. Es ist das Ziel Fertigungsregeln abzuleiten, welche die Sequenzbildung möglichst gut abbilden.
Die Regeln sollen damit das Expertenwissen, welches in der Realität zur Sequenzgenerierung verwendet wird quantifizieren. Die Regel können z.B in der Form von Car Sequencing Rules aufgebaut haben, jedoch auch von dieser Vorlage abweichen. Weiterer Bestandteil der Aufgabe ist die Visualisierung der Fertigungsregeln bzw. der Gemeinsamkeiten der jeweiligen Sequenzen.

Für die Aufgabenstellung ist im Datensatz nur der Order sequences relevant.

Die Implementierung kann in R oder Python erfolgen.
