# Aufgabe: Map und Filter auf Streams

## Lernziel

Einen Stream durch Map- und Filter-Operationen analysieren und gewünschte Daten extrahieren.


## Umgebung

  * Eclipse


## Aufgabe

In dieser (und den folgenden Aufgaben) werden Sie Daten aus der Spieledatenbank von [Metacritic](http://www.metacritic.com) analysieren. Hierbei wurden die 994 Spiele mit der besten Bewertung ausgewählt. Für jedes Spiel sind angegeben:

  * Name des Spiels
  * Metacritic-Score (0-100)
  * Benutzerbewertung (0-100). Normalerweise werden die Benutzerbewertungen bei Metacritic on 0-10 mit einer Nachkommastelle angegeben. Für die einfachere Bearbeitung ist dies für Sie aber bereits in den Bereich 0-100 umgerechnet worden.
  * Erscheinungsjahr des Spiels

Die Verwaltung der Daten wurde Ihnen bereits abgenommen und wird von der Klasse `GameDatabase` durchgeführt. Ein einzelnes Spiel wird durch Objekte des Typs `ComputerGame` repräsentiert.

Schauen Sie sich die Klassen `ComputerGame` und `GameDatabase` an und versuchen Sie deren Funktionsweise zu verstehen.

Erweitern Sie nun die `main`-Methode von `MapFilterGames` so, dass Sie bestimmte Auswertungen auf den Spielen durchführen können. Folgende Informationen sollen Sie auswerten:

  1. Alle Spiele im Jahre 2010 mit einem Metascore >= 80 und einem Userscore >= 80.
  2. Das Spiel mit dem größten Unterschied zwischen Metascore und Userscore.
  3. Das Spiel mit dem kleinsten Unterschied zwischen Metascore und Userscore.

Lassen Sie Ihr Programm laufen und überprüfen Sie, ob die richtigen Informationen ausgegeben werden.


## Abgabe

Aktivieren Sie Checkstyle für das Projekt (falls nicht bereits geschehen) und korrigieren Sie alle Fehlermeldungen bevor Sie das Ergebnis abgeben.

Committen Sie Ihre Lösung und pushen Sie sie danach in Ihr Repository.
