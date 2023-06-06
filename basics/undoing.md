# Git workshop

## Het ondaan maken
## Opdracht 6: Ongedaan maken van aanpassingen.
Laten we zeggen dat we de laatste aanpassing aan `alice.txt` graag ongedaan willen maken. Het voordeel van de "Git staging area" is dat we makkelijk aanpassingen kunnen terugdraaien die we niet willen committen naar de branch.

Om een goed voorbeeld te krijgen van het commando kun je vooraf `git status` uitvoeren:

```bash
$ git status
```

Om vervolgens met dit commando het bestand uit de "Git staging area" te halen:

```bash
$ git checkout alice.txt
```

Door dit commando te draaien worden je aanpassing aan `alice.txt` teruggedraaid naar de laatst bekende versie.

Als we weer `git status` draaien zien we de verschillen:

```bash
$ git status
```

Als het bestand uit de `git staging area` is gehaald heb je met succes een aanpassing ongedaan gemaakt.
