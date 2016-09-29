# Analyseer

Bekijk de volledige commit-geschiedenis om te bestuderen hoe dit project tot stand gekomen is.

Probeer volgende vragen te beantwoorden:

i.v.m. MSTest:

- Welke Assert-methods worden naast `Assert.AreEqual` nog allemaal gebruikt?

> Assert.IsTrue & Assert.IsFalse

- Waarom heeft `TestDirectories` een `Initialize`- en `CleanUp`-method?

> Om te checken of de directory en de files erin zijn verwijdert van de aangemaakte map.

- Zijn de attributen `[TestMethod]`, `[TestClass]`, ... noodzakelijk? (Test uit!)

> Ja ze zijn noodzakelijk! Anders krijg je een foutmelding.

- Wat is de shortcut om alle tests uit te voeren in VS?

> Ctrl R, Ctrl A

i.v.m. Files en Directories:

- Wat is het voordeel van `Path.Combine` i.v.m. strings aan elkaar plakken?

> Je voegt 2 Paths aan elkaar. Men gebruikt Path.Combine om een nieuw bestand te maken.

- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)

> Ja, voor tests uit te voeren.

- Wat is de return-waarde van `Directory.CreateDirectory(...)`?

> Het komt in een bool terecht afhangend of het bestaat of niet is het True of False.

- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?

> Om te zien of een bepaalde method 'Directory.CreateDirectory() werkt.

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?

> Nee, Expect en Assert zijn omgewisseld.

- Wat lost commit d0320b6a op?

> Dat het niet meer omgewisseld is.

- Wat is het probleem met de files in commit 9d184949?

> Niet genoeg uitgewerkt

- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?

> Steekt het in aparte lege variabelen. en maakt de code leesbaarder.


