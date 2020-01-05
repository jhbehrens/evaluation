# Evaluationsergebnisse
Die Ergebnisse der Evaluationen sind in .txt Dateien enthalten, die aus 2 Spalten getrennt durch Tab bestehen.
Wobei die erste Spalte den Index des Datensatzes und die zweite die Laufzeit in Millisekunden enthält.

# Details
Die einzelnen Evaluationen sind in den Ordnern 01 bis 05 enthalten, in der gleichen Reihenfolge, wie in der Beschreibung der Durchführung der Evaluation in der Arbeit.

## 01 ##
### Laufzeit - Naive Implementierung
Laufzeitmessung der naiven Implementierung auf dem i5-6500 System.

Jeweils 10 Datensätze mit 10, 20, 40,..., 640 Datenpunkten. 
xxx.txt enthält die Ergebnisse der 10 Datensätze mit xxx Datenpunkten.

## 02
### Laufzeitvergleich - 3 Versionen
Laufzeitmessungen der naiven sowie der parallelen Version mit einer Instanz und vier Instanzen auf dem i5-6500 System

Jeweils 10 Datensätze mit 100 Datenpunkten.
## 03
### Laufzeitvergleich - Screenshots pro Instanz
Laufzeitmessung auf dem i5-6500 System mit unterschiedlich hoher Anzahl an Screenshots pro Instanz

Jeweils 10 Datensätze mit 320 Datenpunkten und 50, 100, 200, ... 1600 Screenshots pro Instanz.
xxx.txt enthält die Ergebnisse der 10 Datensätze mit xxx Screenshots pro Instanz
## 04
### Laufzeitverlgleich - 2 bis 8 Instanzen
Laufzeitverlgleich mit verschiedener Anzahl an parallel laufenden Instanzen. Durchgeführt auf i5-6500, i5-4200M mit Hyperthreading und i5-4200M ohne Hyperthreading.

Jeweils 10 Datensätze mit 100 Datenpunkten.

Die Unterordner enthalten die Ergebnisse für die 3 verwendeten Systemkonfigurationen.

xxx.txt enthält die Ergebnisse der 10 Datensätze mit xxx parallel laufenden Instanzen.

## 05
### Laufzeitmesung - parallel(4)
Laufzeitmessung der parallelen Implementierung mit 4 Instanzen auf dem i5-6500 System.

Jeweils 10 Datensätze mit 10, 20, 40,..., 640 Datenpunkten. 
xxx.txt enthält die Ergebnisse der 10 Datensätze mit xxx Datenpunkten.