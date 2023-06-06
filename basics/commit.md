# Git workshop

## Commits
## Opdracht 3: Toevoegen van nieuwe bestanden.
Voor dit voorbeeld dienen er 2 bestanden aangemaakt te worden.

Deze bestanden heten `john.txt` en `alice.txt`

<br>

## Staging gebied
In Git voeg je eerst inhoud toe aan het `staging gebied` door `git add` te gebruiken. Je kunt dit zien als het voorbereiden van een pakketje. Met dit commando voeg je spullen die je wilt versturen toe in een kartonnen doos. Door `git commit` te gebruiken verzegelen je de doos - het is nu klaar om te versturen. Met de `-m` parameter tijdens een `git commit` kan je een bericht invoeren die bij deze commit hoort.

<br>

## Opdracht 4: Jouw eerste commit!
Zoals hierboven gezegd, dienen wij een pakketje te maken die wij kunnen versturen. Doorloop de volgende stappen en maak jouw eerste commit in dit project!

1. Voeg de bestanden toe aan het `staging gebied`;
2. Commit de bestanden met een toepasselijk bericht;

<br>

## Wat is er precies gebeurd?

We zouden nu een nieuwe commit moeten hebben. Om alle commits tot nu toe te zien, gebruik je `git log`.

```bash
$ git log
```

De log laat alle commits zien, gerangschikt van meest recent eerst naar minst recent. Je zou verschillende informatie moeten zien, zoals de naam van de auteur, de datum waarop het gecommit is, een commit SHA nummer, en het bericht dat aan de commit zit toegevoegd.