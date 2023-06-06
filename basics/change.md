# Git workshop

## Aanpassingen

In dit gedeelte gaan we wijzigingen aanbrengen en proberen te herstellen van fouten.

Wees gewaarschuwd, deze volgende stap wordt moeilijk. We moeten inhoud toevoegen aan `alice.txt`.

1. Open `alice.txt` en typ je favoriete regel uit een liedje in of andere plaatsvervangende tekst ( Lorem Ipsum );
2. Sla het bestand vervolgens op;

Wat hebben we veranderd? Een erg handig commando is `git diff`. Dit is erg handig om precies te zien welke veranderingen je hebt gedaan.

```bash
$ git diff
```

## Opdracht 5: Commit de veranderingen
Laten we nu ons gewijzigde bestand `alice.txt` toevoegen aan het staging gebied. Weet je nog hoe? Commit jouw veranderingen nog niet.

_Mocht je er niet uit komen, kijk dan terug naar de commit uitleg._

## Ongedaan maken van wijzigingen
Laten we zeggen dat we het niet leuk vonden om Lorem ipsum in alice.txt te zetten. Een voordeel van een staging area is dat we terug kunnen krabbelen voordat we ons vastleggen - wat iets moeilijker is om terug te krabbelen. Om terug te komen op de analogie met post - het is makkelijker om post uit de kartonnen doos te halen voordat je hem dichtplakt dan erna.

Laten we er van uit gaan dat je het toch niet eens bent met de veranderingen aan `alice.txt`. Het voordeel aan een staging gebied is dat we makkelijk terug kunnen naar onze oude wijzigingen, wat lastiger word als je hebt gecommit. Om terug te komen op de kartonen doos: "Het is makkelijker om spullen uit de doos te halen, voordat deze verzegelt is."

Dit is hoe je een verandering terug draait:

```bash
$ git reset HEAD alice.txt
```