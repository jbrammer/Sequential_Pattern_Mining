# EN: Data set for the seminar "Business Problems"

This repository contains the data set for the seminar topic "Sequential Pattern Mining: Analysis and Visualization of Production Line Sequences" at the Chair of Information Systems Research at the University of Freiburg.

## Technical motivation of the problem
In today's manufacturing plants, products are often produced with a wide variety of variants. In order to still guarantee efficient production, these different product variants are usually manufactured on one production line.
In such systems, the order in which jobs flow into a production line is critical to the efficiency of the line. The optimization of manufacturing sequences is examined in the literature taking various target functions into account (e.g. flow shop scheduling, mixed model sequencing, etc.).
In real manufacturing plants, however, manufacturing sequences are often created with the help of expert knowledge. The reason for this is a missing data basis, which is necessary for the implementation of optimization algorithms.
The challenge is to derive manufacturing rules from existing manufacturing sequences, which were created with the help of expert knowledge. These rules can thus quantify expert knowledge.

## Description of the record
The data set contains data from three different production lines (line1, line2 and line3). Each of these production lines has different characteristics with regard to production times and the number of different jobs. In each line 100 jobs are processed in one day and there are 10 different job classes.
There are 300 optimized production sequences for each of the production lines. The production sequences represent daily sequences that were produced on the respective production line. The respective daily sequences differ from each other because the job classes are distributed differently depending on the day.

The "sequences" folder contains the 300 daily sequences in one file per production line.

The "instances" folder contains the underlying daily programs and the characteristics of the production lines. The notation is specified in the "Instance_Notation.mix" file.


## Task

The content of the seminar paper should be the analysis of the optimized manufacturing sequences using sequential pattern mining. The aim is to derive manufacturing rules that map the sequence formation as well as possible.
The rules are intended to quantify the expert knowledge that is actually used to generate sequences. The rules can, for example, be structured in the form of car sequencing rules, but can also deviate from this template. Another part of the task is the visualization of the production rules or the similarities of the respective sequences.

Only the order sequences are relevant for the task in the data record.

The implementation can be done in R or Python.


# DE: Datensatz für das Seminar „Business Problems“ 

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
Die Regeln sollen damit das Expertenwissen, welches in der Realität zur Sequenzgenerierung verwendet wird quantifizieren. Die Regel können z.B in der Form von Car Sequencing Rules aufgebaut sein, jedoch auch von dieser Vorlage abweichen. Weiterer Bestandteil der Aufgabe ist die Visualisierung der Fertigungsregeln bzw. der Gemeinsamkeiten der jeweiligen Sequenzen.

Für die Aufgabenstellung ist im Datensatz nur der Order sequences relevant.

Die Implementierung kann in R oder Python erfolgen.
