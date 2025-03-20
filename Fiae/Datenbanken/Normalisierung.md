[[Datenbanken]]

Wir unterscheiden in 3 Normalformen
[[1. Normalform]]
[[2. Normalform]]
[[3. Normalform]]

[[Material Normalformen]]

Warum Normalisieren wir Datenbanken?
- Um Redundanzen zu vermeiden und damit Anomalien vorzubeugen. 
  
  Beispiel:
  Der Kunde, Herr König, kauft 3x im selben Onlineshop ein. 
  Jedes Mal wird eine Zeile für den Einkauf angelegt, in dem auch der Name "Herr König" steht. Nun ändert sich der Name wegen Hochzeit und wird in einer oder zwei Zeilen durch ein Update geändert, aber eben nicht in allen. Chaos, nun existiert ein Herr König und Meyer mit gleicher Kundennummer in der gleichen Datenbank!
  
  Durch Normalisierung gäbe es nur ein Feld mit dem Namen "Herr König". Weitere Einträge würden auf dieses Feld verweisen. Damit wäre das Updaten dieses Feldes automatisch gültig für alle Felder in denen der Name gebraucht wird.  