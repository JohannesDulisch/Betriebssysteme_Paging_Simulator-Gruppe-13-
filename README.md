# BS Paging Simulator – Projekt im Modul Betriebssysteme (SoSe25)

**Autoren:** Nico Jurek, Philipp Naumann, Johannes Dulisch  
**Modul:** Betriebssysteme  
**Semester:** Sommersemester 2025  
**Projekt:** Paging Simulator (Projekt 2)




## Projektbeschreibung

Ziel dieses Projekts ist die Entwicklung einer Simulationsumgebung zur Evaluation von Paging-Algorithmen. Die Umgebung bietet eine klar definierte API, mit der sich verschiedene Seitenersetzungsalgorithmen einfach implementieren und vergleichen lassen.

Die Simulation berücksichtigt zentrale Betriebssystemkomponenten wie:
- **MMU (Memory Management Unit)**
- **TLB (Translation Lookaside Buffer)**
- **Diskrete-Ereignis-Simulation (DES)** als Zeitbasis




## Unterstützte Paging-Algorithmen

Folgende Algorithmen wurden implementiert und können evaluiert werden:

| Algorithmus                 | Beschreibung                                                                  |
|-----------------------------|-------------------------------------------------------------------------------|
| Not Recently Used (NRU)     | Klassifiziert Seiten anhand von Referenz- und Modifikationsbits               |
| First In First Out (FIFO)   | Ersetzt die älteste Seite im Speicher                                         |
| Second Chance               | Erweiterung von FIFO um ein zusätzliches Referenz-Bit                          |
| Least Recently Used (LRU)   | Ersetzt die Seite mit der ältesten Nutzung                                    |
| Not Frequently Used (NFU)   | Ersetzt Seiten mit geringer Zugriffshäufigkeit                                |
| NFU mit Aging               | Verfeinerung von NFU durch zeitliche Gewichtung der Zugriffshäufigkeit        |





## Projektstruktur

Die wichtigsten Dateien und Ordner:

- [BS_Paging_Simulator.zip](./BS_Paging_Simulator.zip)  
  C++-Projektdateien mit Quellcode und Build-Skripten

- [Doxygen.zip](./Doxygen.zip)  
  Vollständige Doxygen-Dokumentation

- [Verständliche Erklärung des Projekts.pdf](./Verständliche%20Erklärung%20des%20Projekts.pdf)  
  Ausführliche Projektbeschreibung und Hintergrund

- [Bedienungsanleitung des Projektes Compilieren_Bedienen.pdf](./Bedienungsanleitung%20des%20Projektes%20Compilieren_Bedienen.pdf)  
  Anleitung zum Kompilieren und Ausführen des Simulators




