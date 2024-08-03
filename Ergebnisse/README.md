In diesem Verzeichnis sind die numerischen Ergebnisse gespeichert, die ich für meine Analyse verwendet habe. 
Jedes File steht hierbei für einen Trainingsdurchlauf und ist folgendermaßen aufgebaut:

Netz: gibt an, wie groß die Layer des trainierten Netzes sind
Rang - adaptiv ?: ob und wie lange rangadaptiv trainiert wurde
Epochen: Anzahl der trainierten Epochen =: n
Euler - Schrittweite: verwendete Schrittweite für das Euler-Verfahren
SV Trunkierung: wie trunkiert wurde, falls rangadaptiv trainiert wurde 
Batch - Size: welche Batch-Size verwendet wurde
Device: mit welcher Recheneinheit trainiert wurde
______________________________________________________________ 
Accuracy: n-dimensionales Array, das für jede Epoche die gemessene Test-Accuracy gespeichert hat
Trainingsdauer: wie lange das Training gedauert hat
Rang Entwicklung Layer 1: n-dimensionales Array, das für jede Epoche den Rang der ersten Layer speichert 
Rang Entwicklung Layer 2: n-dimensionales Array, das für jede Epoche den Rang der zweiten Layer speichert 
Rang Entwicklung Layer 3: n-dimensionales Array, das für jede Epoche den Rang der dritten Layer speichert 
Rang Entwicklung Layer 4: n-dimensionales Array, das für jede Epoche den Rang der vierten Layer speichert
Loss: n-dimensionales Array, das für jede Epoche den den gemessenen Loss gespeichert hat
