# Statistik und Wahrscheinlichkeitstheorie

## Deskriptive und Explorative Statistik

#### Deskriptive Statistik 
* Aufbereitung von Daten; Berechnung von Kenngrößen
* keine stochastischen Modelle 
    * nicht durch Fehlerwahrscheinlichkeiten gesichert

#### Inferentielle Statistik 
* stellt den Gegensatz zur deskriptiven Statistik dar
* mit Modellannahmen

#### Explorative Statistik
* sucht Struktur und Zusammenhänge in den daten
* versucht Hypothesen über den datengenerierenden Prozess aufzustellen (Data Mining)

### Grundgesamtheit

Daten werden durch Experimente bzw Beobachtungen an statistischen Einheiten gesammelt. Sie werden je nachdem Versuchseinheiten bzw Beobachtungseinheiten genannt. Diese bilden die _Grundgesamtheit_ (auch Population).

#### Assoziation ist nicht gleich Kausalität

Nur Experimentalstudien _können_ Rückschlüsse auf _kausale_ Zsammenhänge zulassen. Beobachtungsstudien können nur _assoziative_ Zusammenhänge aufzeigen.

### Stichproben

Eine Untersuchung aller Elemente einer Grundgesamtheit, auch _Gesamterhebung_ genannt, ist nicht immer durchführbar. Man beschränkt sich deshalb auf eine _repräsentative Teilauswahl_. Für ein _getreues Abbild_ der Grundgesamtheit sollte die Auswahl rein zufällig erfolgen.

Besteht die Grundgesamtheit aus $N$ Elementen, und eine Stichprobe von $n$ Elementen soll entnommen werden, so gibt es $${N}\choose{n}$$ Möglichkeiten. Ist jede von diesen gleich gewichtet, so nennt man die Stichprobe eine _einfache Zufallsstichprobe_.

Die Ziehung der Stichprobe kann auch _mit Zurücklegen_ erfolgen. In diesem fall gibt es $$N^n$$ Möglichkeiten.

### Merkmale

Merkmal, Variable - Die interessierenden Größen an den Einheiten (der Stichprobe)
Merkmalsausprägungen - Die Werte, die ein Merkmal annehmen kann.

Arten von Merkmalsausprägungen:
* Das Merkmal des Monats hat genau zwei Auspägungen
* Das Merkmal des Jahres hat potenziell unbeschränkt viele Ausprägungen
* Der Tagesfortschritt in Prozent hat unendlich viele Ausprägungen in einem Intervall 0-1

Aus mathematischer Sicht ist ein Merkmal eine Funktion die jedem Element $g$ der Grundgesamtheit $G$ ein element $X(g)$ des Merkmalraums $M$ zuordnet.
$$g \in G \rightarrow X(g) \in M$$








