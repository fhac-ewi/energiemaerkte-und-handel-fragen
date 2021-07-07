# Was sind Termingeschäfte? Was ist der Unterschied zwischen bedingten und unbedingten Termingeschäften?
Bei **Termingeschäften** werden vor der Fälligkeit (also vereinbartes Lieferdatum) Lieferbedingungen fest vereinbart. Es gibt verschiedene Arten von Termingeschäften.

| Unbedingte | Bedingte |
| -------- | ---------- |
| Forward | Option auf Forward/Future |
| Future/Swap | |
| Fahrplan | Vollversorgung |

Bei einem **unbedingten** Termingeschäft sind beide Vertragspartner dazu Verpflichtet die Leistung am vereinbarten Termin zu erfüllen.
Ein **bedingtes** Termingeschäft räumt einem der beiden Vertragspartner das Recht ein, das Geschäft verfallen zu lassen. (Optionen) Typischerweise erhält der andere Vertragspartner (ohne das Recht) dafür eine Gebühr. 

# Welche Eigenschaften hat ein Forward auf eine Aktie? Wie ist dagegen ein Forward auf eine Energielieferung definiert? 
Ein bilateral (OTC) gehandelter, nicht standardisierter Lieferkontrakt zwischen einem Käufer und Verkäufer, bei dem der Käufer zur Abnahme und Bezahlung und der Verkäufer zur Lieferung einer bestimmten Warenmenge zu einem zuvor festgelegten Preis an einem spezifizierten Ort und Datum in der Zukunft verpflichtet ist. (Folie 6 - 9)

Kontrakt-Parameter:
- Menge
- Lieferort (= Bilanzkreis)
- Fälligkeit, d.h. Lieferbeginn und Dauer
- Preis pro MWh

TODO Unterschiede zu Aktien

# Definieren Sie einen Strom- oder Gas-Future. Inwiefern unterscheidet sich der Energie-Future vom Energie-Forward?
Bei einem **Future** wird ein fester Preis während der Fälligkeit (Zeitraum Lieferbeginn + Dauer) vereinbart. Die Vertragspartner einigen sich auf einen Preis, der in Zukunft gelten soll. Der tatsächliche Spotmarktpreis wird bei Fälligkeit aber abweichen. Die Differenz zum Spotmarktpreis wird als Finanzausgleich zwischen den Vertragspartnern gezahlt.

Kontrakt-Parameter:
- Konstante Leistung
- Lieferort (= Bilanzkreis)
- Fälligkeit, d.h. Lieferbeginn und Dauer
- Preis pro MWh

# Grenzen Sie den Forward zum Fahrplan ab. Inwiefern haben Lieferverträge Flexibilitäten? Inwiefern kann man hier von Option sprechen?
Ein Forward garantiert eine konstante Leistung über einen defizierten Zeitraum. Bei einem **Fahrplan** wird eine Leistungsstruktur vereinbart.

Kontrakt-Parameter:
- Beliebige Leistungszeitreihe in einer bestimmten Auflösung (z.B. stündlich)
- Lieferort (= Bilanzkreis)
- Fälligkeit, d.h. Lieferbeginn und Dauer
- Preis pro MWh

# Was bedeutet Hedging? Erläutern Sie ausführlich das Konzept.
TODO

# Was bedeutet Arbitrage? Was bedeutet und impliziert ein arbitragefreier Markt?
**Arbitrage** meint das risikofreie Ausnutzen von Kurs-, Zins- oder Preisunterschieden zu einem Zeitpunkt. Es werden zwei Handelsgeschäfte (Kauf und Verkauf von Energie), die zusammen einen Gewinn bringen, zeitgleich abgeschlossen. Anders als bei Spekulationen ist dies wirklich Risikofrei!

Arten von Arbitrage
- **Raumarbitrage** Ausnutzen von Preisunterschieden auf unterschiedlichen Handelsplätzen. (z.B. Deutschland und Frankreich)
- **Zeitarbitrage** Ausnutzen von Preisunterschieden zu unterschiedlichen Zeitpunkten. (benötigt Speicher)
- **Ausnutzen von Kursdifferenzen** durch Kauf und Verkauf eines Produkts. (z.B. Stundenprodukt kaufen und die vier Viertelstunden verkaufen)

# Beschreiben Sie ein offenes Orderbuch. Inwiefern gilt hier die Preisregel pay as bid?
Bei einem **offenen Orderbuch** werden Kauf und Verkaufsgebote anonym (man weiß also nicht von wem die Gebote sind) gegenübergestellt.

Sobald der Kaufpreis eines Gebots größer gleich dem gewünschten Verkaufspreis liegt, kommt es zu einem Geschäftsabschluss. Die beiden Aufträge werden aus dem Orderbuch entfernt.
Der Käufer muss den von ihm gebotenen Kaufpreis zahlen.

# Was ist eine Forward- bzw. Futurekurve? 
Die Kurven zeigen, wie sich die Preise in der nächsten Zeit entwickeln könnten.

# Beschreiben Sie eine mark to market. Definieren Sie Normal Backwardation und Contango.
Bei **market-to-market** werden die Handelsgeschäfte nach Abschluss neu bewertet. Der Wert ist hierbei ungefähr null. (????)

Normal Backwardtion und Contango sind zwei Preissituationen bei Warentermingeschäften. Bei Ersterem liegt der Preis unter dem erwarteten Spotpreis, bei Zweiterem drüber.

TODO

# Wann ist eine Forwardkurve in Normal Backwardation, wann in Contango?
Wenn der Spotpreis **unter** dem im Forward festgesetzten Preis liegt, ist es in Normal Backwardation.

Wenn der Spotpreis **über** dem im Forward festgesetzten Preis liegt, ist es in Contango.


# Beschreiben Sie das Margining-System an der EEX. Welchem Zweck dient dieses?
TODO
