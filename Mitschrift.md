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

Mathematische Sicht - Ein Merkmal ist eine Funktion die jedem Element $g$ der Grundgesamtheit $G$ ein element $X(g)$ des Merkmalraums $M$ zuordnet. $$g \in G \rightarrow X(g) \in M$$

#### Studiendesigns
* Querschnittsstudien - Merkmale werden zu einem festen Zeitpunkt an den statistischen Einheiten erhoben.
* Longitudinalstudien - Merkmale werden zu mehreren Zeitpunktenen an einer unverändert bleibenden Gruppe (_Panel_) von statistischen Einheiten erhoben.
* Zeitreihen - Merkmale werden zu verschiedenen Zeitpunkten an einer einzelnen statistischen Einheit erhoben.

### Messniveau

Auch wenn Merkmale als Zahlen repräsentiert werden, sind nicht immer alle Rechenoperationen/Vergleiche die mit ihnen durchgeführtwerden können sinnvoll.  
Die zulässigen Methoden zur Analyse sind abhängig vom _Messniveau_ des Merkmals.  
Man unterscheidet allgemein zwischen _qualitativen_ und _quantitativen_, bzw _diskreten_ und _stetigen_ Merkmalen.

Tatsächlich sind alle praktischen Messungen eines Merkmals diskret (bedingt durch die Messgenauigkeit).
Wenn die Schrittweite bei diskreten Merkmalen relativ gesehen sehr klein sind, werden diese allerdings oft als stetige behandelt.

#### Topologische Skalen
##### Nominalskalen 
Reine Klassifikation.  
Beispiel: Haarfarbe.  
Sinnvolle Aussagen: Zahlenmäßige Ausprägungen dienen nur der Kodierung.  
  
Anmerkung: Manchmal werden nominale Merkmale durch entsprechende Kodierung auf Ordinalniveu gehoben (zB Schularten). Dabei ist es wichtig, dass keine (eigenen) Wertungen einfließen.

##### Ordinalskalen
Lineare Ordnugsbeziehung. 
Beispiele: Richterskala.  
Sinnvolle Aussagen: Ordnung. $x < x+1$

#### Metrische bzw Kardinale Skalen
##### Intervallskalen
Intervallskalen deren Nullpunkte (falls vorhanden) allerdings keine absolute Bedeutung haben.
Beispiel: Temperatur in $^{\circ}C$
Sinvolle Aussagen: Differenzen. $x_{1}-x_{2} < y_{1}-y_{2}$

##### Verhältnisskalen
Intervallskalen mit interpretierbaren Nullpunkten.
Beispiel: Körpergröße.
Sinnvolle Aussagen: $x$ ist doppelt so groß wie $y$

### Datenmatrix




