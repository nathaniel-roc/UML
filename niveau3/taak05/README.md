# ClassDiagram-TAAK-01

## Classes en objecten

## Uitleg

Nu we weten hoe we classes moeten maken, hoe we deze eigenschappen en methodes kunnen geven en hoe we relaties tussen klassen kunnen aanmaken gaan we nu een class diagram opbouwen vanaf 0. 

## Leerdoelen

> 1. [ ] Ik kan het verschil tussen parent en child klassen benoemen.
> 2. [ ] Ik kan parent-child klassen aanmaken
> 3. [ ] Ik leg het verschil tussen private, public en protected uit
> 4. [ ] Ik kan bij parent en child klassen methodes en eigenschappen vastleggen
> 5. [ ] Ik geef methodes en eigenschappen de juiste visibiliteit (private, public of protected)
> 6. [ ] Ik ken de verschillende relaties.
> 7. [ ] Ik kan relaties leggen tussen diverse classes
> 8. [ ] Ik geef de multipliciteit aan bij relaties
> 9. [ ] Ik weet wat een compositie en een aggregatie is
>10. [ ] Ik kan vanuit tekst een class diagram opbouwen


## Opdracht
Maak een classdiagram voor de onderstaande tekst. Doorloop de 6 stappen
> 1. Zoek alle zelfstandig naamwoorden
> 2. Verwijder dubbele
> 3. Orden en groepeer
> 4. Maak klassen
> 5. Definieer de relaties
> 6. Maak methodes en properties

Het OV systeem
De reiziger stapt de bus en scant zijn ov-chipkaart. Het ovsysteem controleert op 
-	Kaartnummer
-	Geldigheidsdatum
-	Voldoende saldo

Als de ov-chipkaart geldig is en voldoende saldo heeft, wordt een reis geregistreerd met de volgende gegevens
-	reisnummer 
-	kaartnummer
-	vervoermiddelnummer
-	geldigheidsdatum
-	saldo
-	begindatum en -tijd reis
-	instaphalte
-	reisbedrag
Daarna wordt de volgende melding gegeven op het scanapparaat: “Goede reis - <bedrag>”
Anders wordt de volgende melding gegeven op het scanapparaat: “Onvoldoende saldo – <saldo>”
Wanner de bestemming bereikt is, scant de reiziger zijn ov-chipkaart. Het ov-systeem registreert 
-	uitstaphalte
-	einddatum en -tijd reis
-	reisbedrag
-	saldo
Het ov-systeem rekent het nieuwe saldo uit en vervolgens wordt de volgende melding getoond op het scanapparaat: “Tot ziens”
Als de reiziger niet uitcheckt wordt een reis van 10 euro gerekend. Als de reiziger wel uitcheckt wordt het werkelijke reisbedrag uitgerekend gebaseerd op een reistabel 
De gegevens van de reis worden in het ov systeem opgeslagen.

## Eindresultaat
Een class diagram

## Bronnen
Boek: applicatie en mediaontwikkelaar: blz 5.6 en 5.7
