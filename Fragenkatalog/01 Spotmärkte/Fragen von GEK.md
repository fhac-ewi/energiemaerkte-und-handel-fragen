# Welche unterschiedlichen Märkte gibt es mit welchen Fristigkeiten? Und wie werden jeweils die Handelsgeschäfte gebildet?
![](https://www.next-kraftwerke.de/wp-content/uploads/handelsfristen-an-strommaerkten.png)

| Markt | Produkte | Preisfindung | Nutzen |
| ----- | -------- | ------------ | ------ |
| Terminhandel | divers | Bilateral | Risikominimierung / Grobe Abstimmung |
| Day-Ahead-Auktion | Stunden und Viertelstunden | Merit-Order | ? | 
| Day-Ahead-Auktion Spot | Stunden und Blockgebote | Merit-Order | ? | 
| Intraday-Auktion | Viertelstunden | Merit-Order | ? |
| Intraday-Handel | Stunden und Viertelstunden | Pay as bid | ? | 

# In welche Segmente ist der Spotmarkt untergliedert?
**Day ahead Auktion**
- Handel findet als tägliche Auktion statt.
- Es werden die 24 Stunden des Folgetages gehandelt. Die Produkte sind Blocks, Stunden oder Viertelstunden.
- Merit Order

**Intraday Handel**
-  Kontinuierlicher Handel 
-  Gehandelt wird der gleiche Tag (bis 5 min vor physischer Erfüllung) bzw. der Folgetag.
-  Pay as bid. Die Käufer geben Gebote ab und werden direkt mit einem Käufer "gematcht". Der Handel wird direkt abgeschlossen, falls die Gebote stimmen.

Folie 3 - 8

# Was ist die Merit-Order?
Bei einer Auktion geben alle Käufer und Verkäufer verdeckt Gebote ab. Das bedeutet, dass keiner weiß, was die anderen tun.

Nach Abschluss der Auktion wird der Schnittpunkt der Nachfrage- und Angebotskurve ermittelt. (Merit-Order-Verfahren) Der da festgesetzte Preis muss von allen Käufern an die Verkäufer gezahlt werden - unabhängig des vorherigen Gebots.
Die Differenz zwischen Gebot zu Markträumungspreis wird Wohlfahrt genannt. (Konsumtenrente und Produzentenrente)

# Wie wird am Day-Ahead Markt gehandelt?
Die Käufer und Verkäufer geben anonym Gebote ab. Dabei geben sie für jede Stunde Paare aus Preis/Volumen ab.

Kaufwünsche = Positive Menge
Verkaufswünsche = Negative Menge

Die Teilnehmer können selbstständig die Preisschritte innerhalb der Preisgrenzen (-500 € und 3000 € pro MWh) festlegen

Darstellung oftmals in Form einer Matrix:
- Zeilen stellen die Stunden dar
- Spalten die Preise
- Mengen in den jeweiligen Kästen

![](./Gebotsabgabe.PNG)

Folie 3 - 15

# Wozu dient Demand-Side-Management (DSM) und welche Möglichkeiten gibt es?
DSM dient der Flexibilisierung der Stromnachfrage, um eine optimale Auslastung zu erlangen. Ziel ist vorallem die Nivellierung (Glättung) des Lastgangs für eine optimale Kraftwerksauslastung und die Vermeidung von Lastspitzen.

**Lastmanagementstrategien**
- Peak Clipping: Vermeidung von Lastspitzen
- Valley Filling: Füllen von Niedriglastphasen
- Load Shifting: Verschiebung der Nachfrage von Spitzenlast zu Niedriglastzeiten

![](./Lastmanagementstrategien.PNG)

Folie 3 - 23

# Welche Auftragsarten gibt es beim Intraday Handel?
**Limit Orders**
- Kauf- und Verkaufsgebote mit Preislimit. (Minimaler Verkaufs- oder maximaler Kaufpreis)
- Solche Aufträge werden i.d.R. nicht sofort ausgeführt.

**Market Sweep Order**
- Auftrag mit der Bedingung einer sofortigen vollständigen (oder teilweisen) Ausführung. (IOC)
- Der Auftrag wird sofort ausgeführt - zu dem gerade vorherschenden Preis.

Zusätzlich gibt es noch **Ausführungsbedingungen**, unter denen die Aufträge ausgeführt werden:
- Immediate or cancel (IOC): sofortige vollständige oder teilweise Ausführung des Auftrags 
- Fill-or-kill (FOK): sofortige, vollständige Ausführung des Auftrages.
- All-or-none (AON): vollständige Ausführung des Auftrages, Auftrag verbleibt im Orderbuch

Folie 3 - 31

# Was meint Marktkopplung?
Marktkopplung meint den europaweiten Handel über die Ländergrenzen hinweg. Es stehen für solche Handelsgeschäfte aber nur beschränkte Transportkapazitäten zur Verfügung. Diese Kapazitäten werden von dem Übertragungsnetzbetreiber vergeben, damit diese effizient genutzt werrden können. 

Die maximalen Transportkapazitäten an den Ländergrenzen/zwischen den Märkten werden auch Kuppelkapazität genannt.

Folie 3 - 32

# Wie erfolgt der Handel auf verschiedenen Märkten?
Es müssen zuerst Transportkapazitäten bei dem ÜNB angefragt werden. Die Kapazitäten werden von dem ÜNB versteigert. Erst wenn man den Zuschlag erhält, kann man auf dem anderen Marktplatz handeln und versuchen durch Arbitragegeschäfte die Preisunterschiede auszunutzen.

Folie 3 - 34

# Warum können grenzüberschreitende Handelsaktivitäten gewinnbringend sein?
Raumarbitrage. (Ich kaufe günstigen Strom im Ausland und kann diesen günstig selbst verbrauchen oder auf dem heimischen Strommarkt weiterverkaufen.)

# Auf welchem Markt werden Windräder gehandelt?
Intraday Markt, da im Vorfeld unklar ist wieviel Energie produziert wird. 

# Was ist Arbitragehandel?
Arbitrage ist die ohne Risiko vorgenommene Ausnutzung von Kurs-, Zins- oder Preisunterschieden zum selben Zeitpunkt mit dem Ziel der Gewinnmitnahme. Im Gegensatz zur Spekulation ist die Arbitrage nicht risikobehaftet.

- Devisenarbitrage
- Differenzarbitrage
- Raumarbitrage
- Zeitarbitrage
- Ausgleichsarbitrage

Folie 3 - 40

# Welche Regelleistungen gibt es und in welcher Zeit müssen diese verfügbar sein? In welcher Größenordnung fällt diese circa an?
![](https://www.next-kraftwerke.de/wp-content/uploads/Aktivierung-der-verschiedenen-Regelenergiearten-scaled.jpg)

![](./Regelenergie.PNG)

TODO F 3 45/46
TODO F 3 52

# Welche Netzfrequenzen sind in Ordnung?
Totband = 49.99 bis 50.01 Hz --> alles ok
47.5 Hz --> Blackout
52.5 Hz --> Oh Wunder, auch Blackout

F3 49


# Was versteht man unter Pooling?
F 3 53

# Wie erfolgt der Handel von Regelenergie?
F 3 54/ 55 / 56

# Was ist Intrinsic Rolling?
TODO
