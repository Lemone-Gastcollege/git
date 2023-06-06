# Git workshop

## Branches

De meeste grote codebases hebben op zijn minst twee branches - een 'live' branch ( main ) en een 'development' branch. De main branch is code die grondig is getest en klaar is om op een website geïnstalleerd te worden. De development-branch geeft developers de ruimte om nieuwe functionaliteiten te testen die misschien niet helemaal bugvrij zijn. Pas als iedereen tevreden is met de development-branch voegen we deze samen met de live-branch.

Het maken van een nieuwe branch gaat makkelijk. Met het volgende commando:

```bash
git checkout -b {branch naam}
```

Met dit commando maak je een geheel nieuwe branch aan en navigeer je direct er naartoe.

Door het commando `branch` uit te voeren kun je zien op welke branch je momenteel zit (net zoals bij `status`):

```bash
git branch
```

Zoals je ziet geeft Git aan dat je op een andere branch zit. Ook kun je hier zien welke branches bestaan in je repository. Om te wisselen van branches kan dit gedaan worden met het commando `checkout` zoals hier:

```bash
git checkout {branch naam}
```

Vanuit de branch die je geselecteerd hebt kun je nieuwe `commits` pushen om deze branch te voorzien van aanpassingen tegenover andere branches. Bekijk wel de logische volgorde van het updaten van branches.
