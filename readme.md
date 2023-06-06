# Git workshop

## Wat is Git?
Git is een SCM ( Source Configuration Management ) en maakt zich uniek door zijn aftakkingen ( 'branch'-model ). Git zorgt er voor dat het mogelijk is om meerdere branches lokaal te hebben die compleet los staan van elkaar. Het aanmaken, samenvoegen en verwijderen van branches kost minder tijd dan de traditionele manier van samenwerken.

Zoals net benoemd, word Git lokaal gebruikt, wat er voor zorgt dat Git razend snel is vergeleken met zijn tegenhangers. Een lokale SCM noemen we ook wel distributed ( verspreid ). Dit houd in dat elke gebruiker een kopie van de code op zijn eigen computer heeft staan. Het tegenovergestelde hier van is een gecentraliseerde systeem, zoals CVS ( Concurrent Version System ). Dit doet exact hetzelfde als Git ( versiebeheer ), maar gebeurt online, wat een enorme impact kan hebben op de snelheid.

Een ander voordeel van een distributed aanpak van Git is dat tijdens het maken van een checkout ( afsplitsing ) er een hele kopie word gemaakt van de broncode, vergeleken met CVS, die alleen een kopie maakt van de huidige staat waar de code zich in bevind op dat moment. Elke kopie zou in het geval corruptie van bestanden of de server een directe vervanging is.

Een ander voordeel, wat ook tevens een nadeel kan zijn, is dat er vele mogelijkheden zijn in een workflow die je kan gebruiken. Per bedrijf kan het verschillen welke structuur zij hier voor gebruiken. De meest voorkomende is een 'Centralized workflow'. Hierbij is er een repository dat code accepteert en iedereen synchroniseert hier mee.

<br/>

![Weergave gecentraliseerde workflow](./images/centralized_workflow.png) 

Dit betekent dat twéé developers aan dezelfde repository kunnen werken, zonder dat er conflicten ontstaan. Als persoon één een commit doet, moet persoon twéé de veranderingen van persoon één mergen ( samenvoegen ) aan zijn branch.

[Hoe maak ik een account aan in GitHub?](./introduction/create_account.md)
